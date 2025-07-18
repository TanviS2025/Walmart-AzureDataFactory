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

### Storage Blob 
#### Storage account
<img width="1920" height="850" alt="{8C937C03-BA12-4B4C-BAEA-5388FF9FCFCA}" src="https://github.com/user-attachments/assets/b958e263-46d2-4ef7-adf0-ac9bd6c4ba61" />

#### Storage Account | Container
<img width="1920" height="846" alt="{387357E6-0226-4677-A6B9-E49FE5B9A699}" src="https://github.com/user-attachments/assets/0130079d-e1e0-48c2-a8db-23d9462c8669" />

#### Storage Account | Container | File
<img width="1920" height="864" alt="{8D0B6C7B-AE10-484F-8A9D-DFD9EBCE6CA4}" src="https://github.com/user-attachments/assets/0774e0fb-dbd4-4c3e-addb-a2e206f6589d" />


### ADF
<img width="1920" height="858" alt="{05373F5F-8F47-4081-AF1D-9474962C9BEC}" src="https://github.com/user-attachments/assets/8a376f7b-a2a1-4c74-b015-69db29009b06" />
<img width="1920" height="855" alt="{540BC6E8-6B5A-48BD-9F2D-B8964AB261CE}" src="https://github.com/user-attachments/assets/39d88f1a-f774-4dee-b46d-3dd2b101c3d2" />

### SQL Server > Database >Table (Actual Destination)
#### SQL Server
<img width="1920" height="856" alt="{9774DF92-87C6-4AB2-A3B2-E80B6FF1083E}" src="https://github.com/user-attachments/assets/4e3a242c-1077-4889-9610-b15f55818225" />

#### SQL Database
<img width="1920" height="853" alt="{9864ADF3-1262-4C2D-A58A-CF3ADC24F196}" src="https://github.com/user-attachments/assets/162a3b22-c907-439a-941e-6aa45cfeb617" />

#### Destination | Table
<img width="1920" height="859" alt="{82DCBA2E-AB72-4547-8E45-99DDBE3AAA28}" src="https://github.com/user-attachments/assets/edb93f16-8edc-48d3-a761-6406a0e6839d" />

