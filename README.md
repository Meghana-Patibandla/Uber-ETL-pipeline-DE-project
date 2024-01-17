# Uber-ETL-pipeline-DE-project

## Introduction

The mission is to harness the power of modern technology to analyze Uber trip data, providing insights that could transform the way urban transportation is understood and organized. By leveraging cutting-edge tools and platforms such as Google Cloud Storage, Python, and Looker Studio, we aim to dive deep into the nuances of urban mobility.

## Technology Stack

- **Programming Language**: Python
- **Google Cloud Platform (GCP) Services**:
  - Google Storage: Securely store our raw Uber trip data.
  - Compute Instance: Run our powerful data processing jobs.
  - BigQuery: Perform SQL-like analysis on large datasets.
  - Looker Studio: Visualize our findings and create interactive dashboards.

- **Modern Data Pipeline Tool**:
  - Mage AI: Streamline our ETL processes and make data transformation efficient and manageable. Learn more about this tool [here](https://www.mage.ai/).

## Dataset Overview

Our analysis is based on the **TLC Trip Record Data** which encompasses comprehensive details of yellow and green taxi trips in New York City. This rich dataset includes:

- Pick-up and drop-off dates/times
- Locations
- Trip distances
- Itemized fares
- Rate types
- Payment types
- Driver-reported passenger counts

For a detailed understanding of the data structure, visit the following resources:

- Dataset Info: [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- Data Dictionary: [Trip Records Data Dictionary](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

## Project Structure

The following diagrams illustrate the architecture of our data analytics pipeline:

1. **Data Schema/Model Diagram**: Outlines the relational structure of the trip data, showing the dimensional breakdown of key metrics like passenger count, trip distance, rate code, and payment type.
<img src="data_model_uber.jpeg">

3. **Architecture Diagram**: Displays the flow of data from raw storage in GCP to processing via Mage ETL, followed by analysis in BigQuery and visualization in Looker.
<img src="architecture_uber.jpeg">

These diagrams guide the understanding of how each component interacts within our data ecosystem, ensuring a smooth and efficient analytical process.

## Conclusion

This project is more than just code and datasets; it's about unlocking the stories hidden within the numbers. 
