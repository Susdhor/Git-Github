# Conda cheat sheet

## Setup a conda environment
 
``conda create --name ds python=3.11 numpy pandas scikit-learn matplotlib seaborn jupyter plotly``

## Activate the environment

``activate ds``

## Install a package

``conda install plotly``

## Update a package

``conda update pandas``

## Remove a package

``conda remove pandas``

## List all packages and versions installed in active environment

``conda list``

## Get a list of all my environments

``conda env list``

## Deactivate the current environment 

``deactivate``

## Remove an environment

``conda remove --name myenv --all``

## Environment YAML file

Example:

```
name: my_env
channels:
  - defaults
  - anaconda
  - conda-forge
dependencies:
  - ipykernel
  - jupyter_contrib_nbextensions
  - matplotlib
  - mlflow
  - notebook
  - numpy
  - pandas
  - pyarrow
  - python=3.6
  - scikit-learn
  - seaborn
  - pip:
    - mlflow
    - cloudpickle
    - azureml-mlflow
    - azureml-defaults
    - azureml-dataprep[pandas,fuse]
    - shap
    - xgboost==1.0.0
```

## Create environment from a YAML file

```conda env create --file environment.yml```

## Export environment to a YAML file

To export the active environment: ```conda env export > environment.yml```

To export an environment called my_env: ```conda env export --name my_env > environment.yml```
