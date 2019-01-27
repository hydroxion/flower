### [Google Colab](https://colab.research.google.com/)

Google Colab is a Jupyter Notebook application hosted online, that offers 11GB of GPU memory to use per session.

Register an account on Google and access the [Google Colab](https://colab.research.google.com/) application, import the notebook present on [./notebooks/vida.ipynb](./notebooks/vida.ipynb) and install the dependencies:

```shell
# Pytorch
from os.path import exists

from wheel.pep425tags import get_abbr_impl, get_impl_ver, get_abi_tag

platform = '{}{}-{}'.format(get_abbr_impl(), get_impl_ver(), get_abi_tag())

cuda_output = !ldconfig -p|grep cudart.so|sed -e 's/.*\.\([0-9]*\)\.\([0-9]*\)$/cu\1\2/'

accelerator = cuda_output[0] if exists('/dev/nvidia0') else 'cpu'

!pip install -q http://download.pytorch.org/whl/{accelerator}/torch-0.4.1-{platform}-linux_x86_64.whl torchvision

import torch

# Pillow
!pip install --no-cache-dir -I pillow
```

Download the dataset:

```shell
!wget -cq https://github.com/udacity/pytorch_challenge/raw/master/cat_to_name.json

!wget -cq https://s3.amazonaws.com/content.udacity-data.com/courses/nd188/flower_data.zip

!rm -r flower_data || true

!unzip -qq flower_data.zip
```

Read [github.com/pytorch/pytorch/issues/958#issuecomment-309752126](github.com/pytorch/pytorch/issues/958#issuecomment-309752126) to calculate the computational power required by the model.