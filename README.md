
# Midas_datasampling Repo

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lemkova/midas_datasampling/blob/master/Use_Monthly_IP_and_LEI_to_Predict_Quarterly_GDP.ipynb)

This repository is a forked version of [https://github.com/sapphire921/midas_pro](https://github.com/sapphire921/midas_pro). Although it still uses a function that is "soon to be deprecated", I have fixed the original version to replace the "already deprecated" function so that it works with the recent version of pandas.

# midas_pro
Python version of Mixed Data Sampling (MIDAS) regression (allow for multivariate MIDAS)

This package is developed based on midaspy. This version can be used for MIDAS regression and multivariate MIDAS regression.

**A brief introduction to MIDAS model:**

Mixed-data sampling (MIDAS) model is a direct forecasting tool which can relate future low-frequency data with current and lagged high-frequency indicators, and yield different forecasting models for each forecast horizon. It can flexibly deal with data sampled at different frequencies and provide a direct forecast of the low-frequency variable. It incorporates each individual high-frequency data in the regression, which solves the problems of losing potentially useful information and including mis-specification.

MIDAS model can have more than one high-frequency indicator at the same time which lead to the Multivariate-MIDAS (Multi-MIDAS) model. The high-frequency indicators considered can have different theta parameters, different sampling frequencies and different lag length.
