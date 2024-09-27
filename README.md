
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

![Architecture](https://lh3.googleusercontent.com/u/4/drive-viewer/AEYmBYTYWirxazSB6RGbdv13PkvHnPjsYa_4XevMJD1gWe1QjF0H7R6Cn-7C2QKso3lHva31QHIFrDN2AJ0OoVqtidWZLjAc9g=w1317-h942)

## Dataset Used
All data downloaded from TCL Trip Record Yellow and Grenn taxi trip records
Link: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Fields: capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.


## Looker Studio Analytic Report

Preview link: https://lookerstudio.google.com/u/0/reporting/ea7a5e81-2e53-4be8-96c9-59b4680aa6f2/page/zOYoD

![Architecture](https://lh3.googleusercontent.com/u/4/drive-viewer/AEYmBYSHjD7IfFZFQ8ix4XwXTGn-50uAoQXomBWXeVlBXWAoz9-dEgF48yX16u1_drCYcxxz49mvjW3YoxQ7zOJbz133zT7S5A=w1317-h942)


## Data Architecture

![Architecture](https://lh3.googleusercontent.com/u/4/drive-viewer/AEYmBYSL2Xmp8TCU53WpnvKeW8-koyQIshmA28aZYHhtHNqySTWTng9AsSLRduWQMBRlKFVYb4RoQ1sHAa1roOJY3rORoJnNBw=w1872-h942)

Link to the main dataset: https://github.com/ssmqd/Uber-data-pipeline/blob/main/data/uber_data.csv

### Analytic table created using sql query in bigquerry tool
![table data](https://lh3.googleusercontent.com/u/4/drive-viewer/AEYmBYRCWXXFSur7k12gENSBJFOE55vB3uoKDpTWcAsPsAL_wfD3_ABQh4rhOD9FU_yMoKMvCsGH6QshqpHhfrFVUXFK-ZplEA=w1872-h942)
### Powered by Darshil Parmar


[link to channel](https://www.youtube.com/@DarshilParmar)

