## GMIT H.DIP in Data Analytics
### Project for Machine Learning and Statistics Module

This repository contains all of the files pertaining to my project submission for the Machine Learning and Statistics module of the GMIT H.DIP in Data Analysis program. The main body of work is in the `boston-housing.ipynb` Jupyter notebook file. This README.md file is a guide to set up and run the notebook.

### Repository contents

The repository contains:
* `boston-housing.ipynb` - the notebook with all the project details
* this `README.md` file
* an `img` folder containing images for the notebook
* a `data` folder containing the data set for the project

### Dependancies

The dependencies for project are:
* Python 3
* matplotlib.pyplot
* numpy
* pandas
* scipy.stats
* tensorflow
* keras
* [Jupyter Notebooks](https://jupyter.org/)

If you are unsure whether ot not you have these dependant libraries, it is recommended that the latest version of [Anaconda](https://www.anaconda.com/) is installed to ensure that all dependant software is installed and up to date.

Note that tensorflow and keras are not part of the standard anaconda library. Once you have Anaconda installed and up to date, you can install these with the following commands:

Tensorflow
```
conda install -c conda-forge tensorflow 
```
Keras
```
conda install -c conda-forge keras
```
### Instructions for running the software

The software can be downloaded and run on a machine as follows:

* Clone the repository with the following command
```
git clone https://github.com/shkyler/gmit-mls-project.git
```
* Run Jupyter Notebooks from the repository with the following command:
```
jupyter notebook
```
* Jupyter Notebooks should open in your default web browser
* Open the `boston-housing.ipynb` notebook

There is a good tutorial on Jupyter Notebooks available [here](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)