# Steinhaus Filtration and Stable Paths in the Mapper

This repository contains Jupyter notebooks related to our paper *Steinhaus Filtration and Stable Paths in the Mapper*.
There are three notebooks of notes.

The packages required to run all three notebooks can be installed via
```
pip install -r requirements.txt
```

## ComparisonofCechandCoverFiltrations.ipynb

Computational exploration of an isomorphism of 1-skeletons between the two filtrations. 
We construct Vietoris-Rips and Steinhaus filtrations of a data set consisting of 20,000 points centered about 50 landmark points.
We then compare the persistence diagrams of their 1-skeletons.

##### Required Packages
- matplotlib
- numpy
- dionysis
- ripser
- persim
- cechmate

## MapperonFashion.ipynb

TODO: Describe this notebook

##### Required Packages
- hdbscan
- matplotlib
- python-mnist
- networkx
- numpy
- seaborn
- scikit-learn
- umap
- kmapper

## PathsonRecSys.ipynb

TODO: Describe this notebook

##### Required Packages
- pandas
- numpy
- networkx
- scipy
- matplotlib
- seaborn
- umap

