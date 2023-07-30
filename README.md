[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://python.org)
[![Pytorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)](https://pytorch.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![scipy](https://img.shields.io/badge/scipy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)](https://www.scipy.org)
[![heilo](https://img.shields.io/badge/helio-119EFF?style=for-the-badge&logo=helio&logoColor=white)](https://observethesun.github.io/helio/)
## Sunspot groups

This repository contains the dataset of sunspot groups, sunspot parametrization model and latent vectors. With these data one can reproduce the results presented in the paper [Parametrization of sunspot groups based on machine learning approach](https://link.springer.com/article/10.1007/s11207-022-01955-0).

### Demo

Online demo with the sunspot parametrization model is available at
[https://sun.njit.edu/sunspots](https://sun.njit.edu/sunspots)

### Installation

Clone the repository with its submodules
```
git clone --recursive https://github.com/observethesun/sunspot_groups.git
```

### Content

Folder [dataset](./dataset) contains 
* sunspot_dataset - a dataset of sunspot groups observed at the [Kislovodsk Mountain Astronomical Station](http://en.solarstation.ru/) for the period 2010--2020;
* sunspot_group_properties.csv - a table with position, area and other properties of sunspot groups.

Read more about the dataset [here](./dataset/README.md).

Folder [notebooks](./notebooks) contains 
* [Model_training.ipynb](./notebooks/1.Model_training.ipynb) - description of the sunspot parametrization model and model training process;
* [Latent_space_exploration.ipynb](./notebooks/2.Latent_space_exploration.ipynb) - demonstration of latent features and its relation to physical properties of sunspot groups.

Finally, the folder [latent_vectors](./latent_vectors) contains latent vectors obtained with the sunspot parametrization model for all sunspot groups in the dataset.

To save disk space, some files are archived in `zip` format.
