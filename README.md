# Reinforcement Learning Tutorial

## Installing the dependencies

To install the dependencies to run these notebooks, you should first install [Anaconda](https://www.anaconda.com/products/individual#Downloads). 

Once you have installed Anaconda, run:

    conda env create -f environment.yml

to install all the dependencies into an isolated environment.

Activate the environment by running:

    conda activate rl_lab

Update the environment with a new package by adding it in the YAML file and while in the same directory as environment.yml, activate the environment, and run:

    conda env update -f environment.yml