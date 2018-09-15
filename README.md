# Machine Learning Nanodegree
## Capstone Project
### Kaggle - TGS Salt Identification Challenge
This repository contains the final project for Udacity's Machine Learning Engineer Nanodegree.


# Description
This project aims to provide a solution to Kaggle’s TGS Salt Challenge. The Challenge consists in predicting if a target surface is salt or not. 

The theoretical workflow for approaching a solution consists of using Inception v3 as backbone with ImageNet pre-trained weights and U-net as the segmentation algorithm. IoU metric was used to evaluate the results. The model will be trained on a p2.xlarge instance of Amazon EC2 (AMI).

# Dependencies

This project was developed using **Python 3.6.4** with the following packages:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](http://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [keras](https://keras.io/)
- [tensorflow](https://www.tensorflow.org/)

Is highly recommended to use [Anaconda](http://continuum.io/downloads) to handle the packages.

# Code
`capstone_project.ipynb` contains all code used for this project. The data in this repository is just a sample of original data. Full data can be found on [Kaggle](https://www.kaggle.com/c/tgs-salt-identification-challenge/data)

# Documentation
`Propostal.pdf` contains this project's original proposal
`Final Report.pdf` contains the documentation for all steps of this project