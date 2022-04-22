# Cryptocurrencies

## Overview

This repository contains an  unsupervised learning jupyter noetbook project that cleans a cryptocurrency trading dataset and groups statistically similar currencies through principle component analysis, and KMeans clustering.  

## Resources

### Data
  * **Resource/crypto_data.csv** - dataset holding 1252 Cryptocurrencis with metrics Algorithm type, Trading Status, Prooftype, TotalCoinsMIne, TotalCoinSupply

### Software
  * **crypto_clustering.ipynb** - jupyter notebook coding for claening, clustering and visualizing dataset
  * **Python Libraries**
    * Pandas
    * hvplot
    * plotly
    * SKlearn
      * preprocessing: Standard Scaler, MinMAxScaler
      * Decomosition: PCA
      * cluster: KMeans
