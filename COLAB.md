### [Google Colab](https://colab.research.google.com/)

The models require a huge amount of computational power, if you don't have this power, you can use the Google Colab. Create a notebook and import the notebook from `./notebooks/vida`. To download the dataset:

```shell
!wget -cq https://github.com/udacity/pytorch_challenge/raw/master/cat_to_name.json

!wget -cq https://s3.amazonaws.com/content.udacity-data.com/courses/nd188/flower_data.zip

!rm -r flower_data || true

!unzip -qq flower_data.zip
```