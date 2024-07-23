
# Forecasting Carbon Intensity and Solar Generation in the Building Sector

This repository contains code for the bachelor's thesis on the topic of forecasting carnon intensity and solar generation. The data for this project was taken from an [NeurIPS 2023 Citylearn Challenge](https://www.aicrowd.com/challenges/neurips-2023-citylearn-challenge).

The project consist of three directories:

1. **Data** - This directory contains all the required datasets. The files provided in the competition can be found in the *original* sub-directory. The sub-directories *results* and *train-test-split* contain the outpu files from the models and preprocessing, respectively. 

2. **Data_preprocessing** - This directory contains the ipynb files with data visualization and preprocessing. 

3. **Models** - This directory contains the three main ipynb files, one for for each of the models (MLP, LSTM, and GRU). Additioanlly, one more file that combines the results is included. Note that running these files will rewrite the only acquired results in the *Data* directory.

To run the code, make sure all the requirements are installed. All files can be run independently of each other since all the preprocessing steps were already done and the results were obtained.

