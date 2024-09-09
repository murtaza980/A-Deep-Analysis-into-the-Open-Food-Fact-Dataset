# A Deep Analysis into the Open Food Fact Dataset

This repository is deep exploratory data analisys of the Open Food Facts dataset. It is a very long notebook with lots of code, explanation and insights.

The dataset is relatively huge with about 3'361'648 record and 206 colume and a size of about 10 GB. For this reason, it is not provided in this repository but can be downloaded at this URL: https://static.openfoodfacts.org/data/en.openfoodfacts.org.products.csv.gz

The following packages are required to execute the notebook :
* `python`
* `numpy`
* `pandas`
* `matplotlib`

If using `conda`, a ready to use environment can be created with the commands :
```bash
# Create the conda environment
> conda create -f environment.yml

# Activate the environment
> conda activate eda-openfoodfacts

# Launch Jupyter notebook server
> jupyter notebook
```

Here is the notebook outline :

## A. Importing and Cleaning the data

The goal of this part is to get a very high level understanding of the data :

The goal of this part is to get a very high level understanding of the data :

1. Importing the data from a csv file
2. Basic and safe cleaning
3. Data summary and variables identification 
4. Missing values analysis
5. Time-series convert
6. Manipulating the data
7. Text data and manipulation
8. Finding correlations
