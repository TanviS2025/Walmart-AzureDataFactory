# Walmart-AzureDataFactory

## Data Factory
works as the brain of this whole process with it's pipeline acting as a intermediatory who extracts the data from source and loads it in the destination.

## Source: 
Storage Account (Blob Storage) > Container > CSV file uploaded
This CSV file gets extracted by the Azure Data Factory (ADF)

## Destination: 
SQL Server > SQL DB > Table 
data gets added when ADF extracts it from source and loads it in this table.


<img width="1512" height="703" alt="{84524958-E230-4492-8EC2-9A98333ADE3F}" src="https://github.com/user-attachments/assets/9285001b-2170-45a8-b7bf-3e333983e5a1" />
