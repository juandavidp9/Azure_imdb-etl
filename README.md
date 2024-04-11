# Azure ETL Project: IMDB Movies

ETL Project of IMDB Movies using Azure Data Factory, Synapse Analytics, Datalake Storage, and Azure SQL DB.

In this project, I use a “Self Hosted Integration Runtime” feature to access on-premise environment data sources.
It will allow us to copy the data to the Datalake Storage.
The data is transformed in Azure Synpase using Pyspark. Finally, it is loaded into an Azure SQL database.


### Architecture 

![architecture](https://drive.google.com/uc?id=1rG4AkjeGjXMjNHFDmMyMFyletJ33ZoiN)

### Azure Data Factory Pipeline

![linked services](https://drive.google.com/uc?id=1zJKSMLm9XxvFmH7TbXNzgRmggPYTG9Br)

![ETL](https://drive.google.com/uc?id=1vBauQqB060s_4CrU14kpCDzidDWWXcic)

### Result: Transformed data loaded in Azure SQL

![linked services](https://drive.google.com/uc?id=1RCXWlDVLwLMgWVdBcovCUUzBtNfhaLZl)
