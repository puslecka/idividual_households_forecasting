# idividual_households_forecasting
This repository contains the preprocessing scripts for the popular datasets with a large amount of individual households energy consumption data:
- CER - Customer Behavior Trials (CBT) dataset
- Low Carbon London (LCL) dataset
- Smart Grid Smart City (SGSC) dataset

The aim of each script is to transform the data to have the consumption data for each household id in hourly resolution as follows:
|    id    |       datetime       | consumption |
|----------|----------------------|-------------|
| 8144689  | 2012-08-17 13:00:00  |    0.359    |
| 8144689  | 2012-08-17 14:00:00  |    2.329    |
| 8144689  | 2012-08-17 15:00:0   |    1.942    |
|   ...    |          ...         |     ...     |

The scripts assume that the data was downloaded from the respective sources specified in the first cell of each notebook. 
