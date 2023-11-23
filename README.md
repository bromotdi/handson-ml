Machine Learning Notebooks
==========================

It is my personal notebooks that contain the example code and solutions to the exercises in the third edition of O'Reilly book [Hands-on Machine Learning with Scikit-Learn, Keras and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/):

<img src="https://images-na.ssl-images-amazon.com/images/I/51aqYc1QyrL._SX379_BO1,204,203,200_.jpg" title="book" width="150" />

## Quick Start

### Want to play with these notebooks online without having to install anything?
Use any of the following services (I recommended Colab or Kaggle, since they offer free GPUs and TPUs).

**WARNING**: _Please be aware that these services provide temporary environments: anything you do will be deleted after a while, so make sure you download any data you care about._

* <a href="https://colab.research.google.com/github/ageron/handson-ml2/blob/master/" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

* <a href="https://homl.info/kaggle/"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open in Kaggle" /></a>

* <a href="https://mybinder.org/v2/gh/ageron/handson-ml2/HEAD?filepath=%2Findex.ipynb"><img src="https://mybinder.org/badge_logo.svg" alt="Launch binder" /></a>

* <a href="https://homl.info/deepnote/"><img src="https://deepnote.com/buttons/launch-in-deepnote-small.svg" alt="Launch in Deepnote" /></a>

### Just want to quickly look at some notebooks, without executing any code?

* <a href="https://nbviewer.jupyter.org/github/ageron/handson-ml2/blob/master/index.ipynb"><img src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg" alt="Render nbviewer" /></a>

* [github.com's notebook viewer](https://github.com/ageron/handson-ml2/blob/master/index.ipynb) also works but it's not ideal: it's slower, the math equations are not always displayed correctly, and large notebooks often fail to open.

### Want to run this project using a Docker image?
Read the [Docker instructions](https://github.com/ageron/handson-ml2/tree/master/docker).

### Want to install this project on your own machine?

Start by installing [Anaconda](https://www.anaconda.com/distribution/) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)), [git](https://git-scm.com/downloads), and if you have a TensorFlow-compatible GPU, install the [GPU driver](https://www.nvidia.com/Download/index.aspx), as well as the appropriate version of CUDA and cuDNN (see TensorFlow's documentation for more details).

Next, clone this project by opening a terminal and typing the following commands (do not type the first `$` signs on each line, they just indicate that these are terminal commands):

    $ git clone https://github.com/ageron/handson-ml2.git
    $ cd handson-ml2

Next, run the following commands:

    $ conda env create -f environment.yml
    $ conda activate tf2
    $ python -m ipykernel install --user --name=python3

Finally, start Jupyter:

    $ jupyter notebook

If you need further instructions, read the [detailed installation instructions](INSTALL.md).

