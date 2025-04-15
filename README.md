# Statistical Pattern Recognition exercises 

This code repository contains the exercises for the
[Statistical Pattern recognition Course](https://lmb.informatik.uni-freiburg.de/lectures/spr/).

Exercise and solutions will be in jupyter notebook format and will be made available
in a delayed basis.
The `data` directory contains small datasets that your will need for different excercies.

## Setup

Follow [setup.pdf](setup.pdf).
Afterwards you should have a working miniconda installation,
a python environment with the installed requirements and a clone of this exercise repository.
All commands assume you run them from the root of the repository folder unless otherwise stated.

Get familiar with [jupyter notebooks](https://jupyter-notebook.readthedocs.io/en/stable/),
start a local jupyter lab server with the `jupyter lab` command 
and open the exercise notebooks to start coding.
You can also use `jupyter notebook` for a simpler interface.

## Other information

All exercises should be runnable on your own computer. In case you want to use the computer pools,
these links might be helpful:

[Computer vision exercises - frequently asked questions](https://github.com/lmb-freiburg/cv-exercises/blob/master/FAQ.md)
[TFPool FAQ](https://poolmgr.informatik.uni-freiburg.de/?id=103)

## Troubleshooting


- Errors installing libsvm: Try to upgrade the dependencies (clang, gnuplot, ...)
  you can also ignore the package for now since you only need it for exercise 8.
  To do this, comment it out with a `#` in the `requirements.txt` file.
- Other python errors: Check if your conda setup is correct by running
  `which python` (linux) or `where python` (windows).
  This should show you the path to the python executable in the \code{cvenv} environment.
  If it shows you something else, your conda setup is not correct.
  In case it shows something related to e.g. `pyenv`, check your config files 
  (`~/.bashrc` or `~/.zshrc`) and comment out everything related to `pyenv`.
    