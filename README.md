### [Vida](http://yakusokunoneverland.wikia.com/wiki/Vida)

![Vida](./vida.jpg)

> A Vida is a vampiric plant used to extend the shelf life of a meat which functions by absorbing the blood. This also doubles as a main subject of ritual for demon descents as their way of dedicating the meal to their god.

This project goal is to classify a flower dataset ([102 Category Flower Dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/)) compound by one hundred and twelve species of flower, each class consists of between 40 and 258 images, using two different techniques based on convolution. To achieve a good accuracy the architectures Res Net and Conv Net are considered for the classification.

#### Dependencies

It's recommended to create a virtual environment using the Pyenv Virtualenv tool, see how to install [Pyenv](https://github.com/pyenv/pyenv) and [Pyenv Virtualenv](https://github.com/pyenv/pyenv-virtualenv).

Install Anaconda image:

```shell
pyenv install anaconda3-2018.12
```

Create a virtual environment based on Anaconda iamge:

```shell
pyenv virtualenv anaconda3-2018.12 vida
```

Activate the virtual environment:

```shell
pyenv activate vida
```

Install dependencies:

```shell
conda install --yes --file requirements.txt
```

See installed modules:

```shell
conda list
```

#### Run

The available code is writen in a Jupyter Lab notebook, to start the notebook server:

```shell
jupyter lab
```

Open the browser at [localhost:8888/lab](http://localhost:8888/lab) and execute the cells `ctrl` + `enter`.

#### Credits

[Github.com/Sphinxs](https://github.com/Sphinxs)

[Linkedin.com/in/walter-hr](https://www.linkedin.com/in/walter-hr/)

#### References

Below are the references of study to create this project:

[Intro to Deep Learning with PyTorch](https://www.udacity.com/course/deep-learning-pytorch--ud188)

[MIT 6.S191: Introduction to Deep Learning](https://www.youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI)

[MIT Deep Learn](https://www.youtube.com/playlist?list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf)

[Deep Learn book](http://www.deeplearningbook.org/)

[PyTorch documentation](https://pytorch.org/docs/stable/index.html)

[Math as code](https://github.com/Jam3/math-as-code)

[Deep Learning cheatsheets for Stanford's CS 230](https://github.com/afshinea/stanford-cs-230-deep-learning)

[PyTorch cheatsheet](https://github.com/Tgaaly/pytorch-cheatsheet)