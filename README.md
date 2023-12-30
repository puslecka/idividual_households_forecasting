# idividual_households_forecasting
This repository contains the preprocessing scripts for the popular datasets with a large amount of individual households energy consumption data:
- CER - Customer Behavior Trials (CBT) dataset
- Low Carbon London (LCL) dataset
- Smart Grid Smart City (SGSC) dataset

The aim of each script is to transform the data to have the consumption data in kWh for each household id in hourly datetime resolution as follows:
|    id    |       datetime       | consumption |
|----------|----------------------|-------------|
| 8144689  | 2012-08-17 13:00:00  |    0.359    |
| 8144689  | 2012-08-17 14:00:00  |    2.329    |
| 8144689  | 2012-08-17 15:00:00  |    1.942    |
|   ...    |          ...         |     ...     |

The scripts assume that the data was downloaded from the respective sources specified in the first cell of each notebook. 
The data preprocessing scripts require only pandas and numpy and were tested with pandas==2.1.1 and numpy==1.26.0. 

In addition there is included a script containing comparison of performance of LSTM-based model for each dataset on different forecasting horizons. The script assumes that the datasets were previously preprocessed with the abovementioned scripts. 


