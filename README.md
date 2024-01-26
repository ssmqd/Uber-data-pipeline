
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

![Architecture](https://lh3.googleusercontent.com/u/4/drive-viewer/AEYmBYSUdPtKV8EIbXsIu9K_3kH42ipIDOwR3J4GCGSQsYjeh-i_9GUMtJPw-lXAwtC1i917bEGlHKbBSZR9KSMuetTuHOqmqQ=w1872-h942)

## Mage pipeline
All script files can be found in repository main folder. Pipeline was made using mage ETL tool. Short intro into each one.
 - *load_data_from_bucket* - download dataset from GCP cloud bucket to ETL script
 - *transform_data_into_tables* - used to create dim and fact tables, convert data types and add additional values
 - *uber_bq_load* - upload all tables created in previous step into google bigquerry 

![Architecture](https://lh3.googleusercontent.com/u/4/drive-viewer/AEYmBYTYWirxazSB6RGbdv13PkvHnPjsYa_4XevMJD1gWe1QjF0H7R6Cn-7C2QKso3lHva31QHIFrDN2AJ0OoVqtidWZLjAc9g=w1317-h942)

## Dataset Used
All data downloaded from TCL Trip Record Yellow and grenn taxi trip records
Link: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Fields: capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

## Data Architecture

![Architecture](https://lh3.googleusercontent.com/u/4/drive-viewer/AEYmBYSL2Xmp8TCU53WpnvKeW8-koyQIshmA28aZYHhtHNqySTWTng9AsSLRduWQMBRlKFVYb4RoQ1sHAa1roOJY3rORoJnNBw=w1872-h942)

Link to main dataset: https://github.com/ssmqd/Uber-data-pipeline/blob/main/data/uber_data.csv

### Analytic table created using sql query in bigquerry tool
![table data](https://lh3.googleusercontent.com/u/4/drive-viewer/AEYmBYRCWXXFSur7k12gENSBJFOE55vB3uoKDpTWcAsPsAL_wfD3_ABQh4rhOD9FU_yMoKMvCsGH6QshqpHhfrFVUXFK-ZplEA=w1872-h942)
### Povered by Darshil Parmar


[link to channel](https://www.youtube.com/@DarshilParmar)

