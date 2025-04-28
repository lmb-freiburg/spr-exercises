# Environment Setup for Statistical Pattern Recognition
For this course you will need a working python environment. There are many ways to setup a python environment, you may choose the one you prefer, here we will show you how to use [Conda](https://docs.conda.io/en/latest/), since it is a painless and scalable way.

## Installation
We recommend using the **Miniforge** installer. Follow the installation instructions for your operating system at [https://conda-forge.org/download/](https://conda-forge.org/download/).

### Installation Check
#### On Linux and Mac:
* Close and reopen your terminal window to make sure the changes take effect.
* Test your installation by running `conda --version`.

#### On Windows:
* Open the Miniforge Command Prompt you just installed
* Run the command `python -V`. It should output `Python (version number)` or similar.

## Environment Setup
To setup a new Conda environment for the course exercises, run the following commands in your Miniconda prompt (Windows) or terminal (macOS, Linux):
```
conda --version
conda update conda -y
conda create --name cvenv python=3.11 -y
conda activate cvenv
conda env list
```

The last command should show you all installed environments (including `base` and the activated `cvenv` environment). This way, you have a separate environment to install everything for this course and avoid possible interference with/from other python projects.

**Important**: Whenever you start the miniconda prompt/terminal for this course, run `conda activate cvenv` to
switch to the correct environment.


## Installation of the Required Packages
The course exercises require a few packages for scientific computing, plotting results, etc. Follow these steps to install them in your `cvenv` environment:
* Clone the exercise repository (https://github.com/lmb-freiburg/spr-exercises) using `git`.
* Open the Miniconda prompt (Windows) or terminal (macOS, Linux) and `cd` into the repository.
* Run `pip install -U -r requirements.txt` to install the required package.
* `cd` into folder `ex01_intro`
* Run `python hello.py` and check the output.

## IDE and Code Editors
In this course we will be using jupyter notebooks to run our code so we do not necessarily need an IDE. If you
want to use one, both VSCode and PyCharm offer notebook support.