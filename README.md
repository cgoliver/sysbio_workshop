# SysBio Graph Workshop

Welcome to the SysBio Graph Analysis workshop!

[slides](https://docs.google.com/presentation/d/1SFsJAx5wKGWFRqPclAezGJSOsRRjeGgHQtQxOw1ixec/edit?usp=sharing)

## Setup and Installations

Download [data here](https://mega.nz/file/JXZ1GCTI#TJ7gZpgKpxT_GRHAz8riwtd8IZvaFhYjdIHImlqRoTI)

To follow along in this workshop please follow these steps:

```
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements.txt
```

Go to [this](https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html#quick-start) link and select the download that matches your computer's specs.

Since I am on a mac with no GPUs I should run this:

```
pip install torch-scatter torch-sparse torch-cluster torch-spline-conv torch-geometric -f https://data.pyg.org/whl/torch-1.12.0+cpu.html
```	

## Exercises

Solved exercises are in the `solutions/` folder.

Partially filled scripts for each exercise are in the `exercises/` where you can fill in the missing code.

**Note**: To re-use code across exercises we will rely on python imports so make sure that you `cd` into the `exercises/` or `exercises/` directory while you work to make importing easy.

