# Azure ETL Project: IMDB Movies

ETL Project of IMDB Movies using Azure Data Factory,Synapse Analytics, Datalake Storage and Azure SQL db. 

### Architecture 

![architecture](https://drive.google.com/uc?id=1rG4AkjeGjXMjNHFDmMyMFyletJ33ZoiN)

### Azure Data Factory Pipeline

![linked services](https://drive.google.com/uc?id=1zJKSMLm9XxvFmH7TbXNzgRmggPYTG9Br)

![ETL](https://drive.google.com/uc?id=1vBauQqB060s_4CrU14kpCDzidDWWXcic)

## Pyspark Azure Synapse Transformation

 Writing transformed data to Refined Container
 We are using Datalake as Refined layer
 Storing data in parquet format
 This helps to copy the data into Azure Database using ADF

### Result: Transformed data loaded in Azure SQL

![linked services](https://drive.google.com/uc?id=1RCXWlDVLwLMgWVdBcovCUUzBtNfhaLZl)
