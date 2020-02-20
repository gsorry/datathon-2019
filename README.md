# Raiffeisen Recommender System

Raiffeisen dataset is not a provided here because it is too big.
Need to be extracted in this folder: 'Datathon_sample_final1.csv'

## Clean Data

The first step is to clean the raw data from dataset.
Therefore, the notebook 'RFB - Data Cleaning.ipynb' should be started first.
It will generate a new dataset: 'RFB - Clean Data.csv'

## Load External Data

Another step is to load external data obtained from The Statistical Office of the Republic of Serbia and Open data portal of Republic of Serbia:

- 'RFB - Potrosacke Cene Indeksi.txt'
- 'RFB - Strukturna Imovina.txt'

and Synthetic label from:

- 'RFB - Prvi Zajam.txt'

NOTE: Change txt extension to csv (due to version controll isues).

It will generate a new dataset: 'RFB - Merged Data.csv'

## EDA

A simple EDA is described in Notebook 'RFB - EDA.ipynb'.

## Machine Learning Algorithms

To run, train, and test ML models, run the following notebooks:

- RFB - Classification Random Forest.ipynb
- RFB - Classification Random LightGBM.ipynb
