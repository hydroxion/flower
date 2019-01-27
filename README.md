### Vida

The goal of this project is to classify the [102 category flower dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/), compound by one hundred and twelve species of flowers. Using different techniques based on convolution the classification is made.

#### Dependencies

Create a virtual environment using Pyenv Virtualenv, see how to install [Pyenv](https://github.com/pyenv/pyenv) and [Pyenv Virtualenv](https://github.com/pyenv/pyenv-virtualenv).

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

Install dependencies:

```shell
conda install --yes --file requirements.txt
```

See installed modules:

```shell
conda list
```

Update conda:

```shell
conda update -n base -c defaults conda
```

#### Run

Start the notebook server:

```shell
jupyter lab
```

Open [localhost:8888/lab](http://localhost:8888/lab) at the browser.

#### References

[Intro to Deep Learning with PyTorch](https://www.udacity.com/course/deep-learning-pytorch--ud188)

[MIT 6.S191: Introduction to Deep Learning](https://www.youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI)

[MIT Deep Learn](https://www.youtube.com/playlist?list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf)

[Deep Learn book](http://www.deeplearningbook.org/)

[PyTorch documentation](https://pytorch.org/docs/stable/index.html)

[Deep Learning cheatsheets for Stanford's CS 230](https://github.com/afshinea/stanford-cs-230-deep-learning)

[Computer Vision Foundation](https://www.youtube.com/channel/UC0n76gicaarsN_Y9YShWwhw/videos)

#### Credits

[Github.com/Sphinxs](https://github.com/Sphinxs)