# CS 7641 - Assignment 2: Randomized Optimization

This repository contains the experiments made to analyze and complete assignment 2 of the CS7641 - Machine Learning 
course from the Georgia Institute of Technology.

The main purpose of this assignment is to analyze 4 randomized optimizations algorithms:
* Randomized Hill Climbing
* Simulated Annealing
* Genetic Algorithm
* Mutual-Information-Maximum Input Clustering (MIMIC)

with 3 optimization problems:
* One Max
* Flip Flop
* Knapsack

as well as finding weights for a neural network using RO algorithms to replace back propagation from gradient descent.

We use the `mlrose-hiive` module to execute these experiments.

----

### Setup Virtual Environment

In the root directory of the project, do one of the following two

#### Conda

```shell
$ conda create --name myenv python=3.8
$ conda activate myenv
$ pip install -r requirements.txt
```

#### PipEnv

```shell
$ python -m venv /venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```

#### mlrose-hiive
If `mlrose-hiive` does not install automatically with the `requirements.txt`, then run
```shell
$ cd mlrose
$ pip install -e .
```

### Run Scripts

#### Optimization Problems using Randomized Optimization Algorithms

Open up `randomized_optimiztion.ipynb` in VS Code (or your preferred editor/jupyter server), select your virtual environment (in this example `myenv`) as your kernel and run the code cells one by one. 

Note that the problems may take a long time to finish computing sometimes (from 30 mins to 2 hours) depending on hardware specs.
This is due to the number of experiments we do on each problem (~180 per problem).


#### Finding Optimal Weights to train a Neural Network using Randomized Optimization Algorithms

Open up `neural_network_weight_optimization.ipynb` in VS Code (or your preferred editor/jupyter server), select your virtual environment (in this example `myenv`) as your kernel and run the code cells one by one. 

Note that the problems may take a long time to finish computing sometimes (~20 mins max) depending on hardware specs.

----

## Note: If you are a GT Student taking CS7641 **_DO NOT_** proceed looking at this repository in order to not violate the GT Academic Honor Code