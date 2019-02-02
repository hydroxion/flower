### Vida

> Flower classification using Convolutional Neural Networks and Autoencoders through PyTorch

[Colab notebook](https://drive.google.com/file/d/1zRGpOIh03G_d82MnEYGQ1MrUd6v4x--f/view?usp=sharing).

#### Dependencies

Install the [Pyenv](https://github.com/pyenv/pyenv) and [Pyenv Virtualenv](https://github.com/pyenv/pyenv-virtualenv).

Install Anaconda image:

```shell
pyenv install anaconda3-2018.12
```

Create a virtual environment:

```shell
pyenv virtualenv anaconda3-2018.12 vida
```

Activate the virtual environment:

```shell
pyenv activate vida
```

Install the dependencies:

```shell
conda install --yes --file requirements.txt
```

List installed modules:

```shell
conda list
```

Update conda:

```shell
conda update -n base -c defaults conda
```

#### Run

Start Jupyter Lab:

```shell
jupyter lab
```

#### Credits

[Github.com/Sphinxs](https://github.com/Sphinxs)

[Robots.ox.ac.uk/~vgg/data/flowers/102](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/)