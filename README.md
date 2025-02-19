# Steinhaus Filtration and Stable Paths in the Mapper

This repository contains Jupyter notebooks related to our paper *Steinhaus Filtration and Stable Paths in the Mapper*.
There are three notebooks touching on three aspects.

## ComparisonofCechandCoverFiltrations.ipynb

Computational exploration of an isomorphism of 1-skeletons between the two filtrations. 
We construct Vietoris-Rips and Steinhaus filtrations of a data set consisting of 20,000 points centered about 50 landmark points.
We then compare the persistence diagrams of their 1-skeletons.

##### Required Packages
- matplotlib
- numpy
- dionysus
- ripser
- persim
- cechmate (see InstallingCechmate.md)

## MapperonFashion.ipynb

In this application we make use of the Steinhaus filtration to provide explanations for supervised machine learning.
We build a Mapper from the predicated probability space of a logistic regression model.
We then analyze stable paths on the resulting Steinhaus filtration.

The notebook demonstrates this process on the [Fashion-MNIST](https://www.kaggle.com/datasets/zalando-research/fashionmnist) data set consisting of 70,000 images of clothing items from 10 classes.

To make use of this notebook, one must extract the [Fashion-MNIST](https://www.kaggle.com/datasets/zalando-research/fashionmnist) data set to ``data/``.

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

In this application we apply the Steinhaus filtration to answer the following question: what sequence of movies should one watch to gently transition from the movie *Mulan* to *Moulin Rouge*.
We make use of the [MovieLens-20m](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset) data set and represent each movie as a cover element consisting of users who rated said movie.
We then apply the Steinhaus filtration to build a filtration on the Mapper graph.
Using our theory on stable paths we can find a stable order of movies to watch.

To make use of this notebook, one must extract the [MovieLens-20m](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset) data set to ``data/ml-20m/``.

##### Required Packages
- pandas
- numpy
- networkx
- scipy
- matplotlib
- seaborn
- umap

