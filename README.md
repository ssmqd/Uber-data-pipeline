
# Uber Data Engineering GCP Project

## Technology

- Python
- SQL
- GCP
    - Cloud Storage
    - Compute Instance
    - BigQuery
    - IAM
- Looker Studio 
- Mage.ai

Contibute: https://github.com/mage-ai/mage-ai

## Architecture

![Architecture](https://i.imgur.com/HQsOVxj.jpeg)

## Mage pipeline
All script files can be found in repository main folder. The pipeline was made using the mage ETL tool. A short intro into each one.
 - *load_data_from_bucket* - download dataset from GCP cloud bucket to ETL script
 - *transform_data_into_tables* - used to create dim and fact tables, convert data types, and add additional values
 - *uber_bq_load* - upload all tables created in the previous step into google bigquerry 

![Architecture](https://imgur.com/J0iCVYV.jpeg)

## Dataset Used
All data downloaded from TCL Trip Record Yellow and Grenn taxi trip records
Link: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Fields: capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.


## Looker Studio Analytic Report

Preview link: https://lookerstudio.google.com/u/0/reporting/ea7a5e81-2e53-4be8-96c9-59b4680aa6f2/page/zOYoD

![Architecture](https://imgur.com/ueEZPgu.jpeg)


## Data Architecture

![Architecture](https://imgur.com/dDrgECt.jpeg)

Link to the main dataset: https://github.com/ssmqd/Uber-data-pipeline/blob/main/data/uber_data.csv

### Analytic table created using sql query in bigquerry tool
![table data](https://imgur.com/L6QnIA6.jpeg)
### Powered by Darshil Parmar


[link to channel](https://www.youtube.com/@DarshilParmar)

