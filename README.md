# Sales Insight Navigator Project
A data analysis solution using Azure Data Lake Storage, Azure Data Factory, and Power BI to integrate, process, and visualize supermarket sales and revenue data for actionable insights.

## Project Overview:
This repository contains the documents showing the implementation of a ADLS gen2, data analysis pipeline for a supermarket store, Azure synapse, and Power Bi dashboard designed to provide insights into sales and revenue. The project showcases end-to-end data processing, integration, and visualization using Azure and Power BI.

## Key Components:

### Data Files: 
Contains sample datasets representing sales transactions and revenue records.
### Azure Data Factory (ADF) Data Flow: 
Includes configurations for combining and transforming data from the ADLS Gen2 container.
### Synapse SQL Pool Integration: 
Scripts and configurations for sinking transformed data into a Synapse SQL pool.
### Power BI Reports: 
Power BI report files demonstrating data visualization and analysis based on the processed data.

## Technologies Used:
Azure Data Lake Storage (ADLS) Gen2, Azure Data Factory (ADF), Azure Synapse Analytics, Power BI, DAX.

## Process:
1) Upload datasets to ADLS Gen2 container SOURCE.
2) Configure ADF data flow to combine and process data.
3) Set up Synapse SQL pool to sink/receive processed data.
4) Connect Synapse SQL pool to Power BI for visualization.
5) Use DAX to clean data.
6) Visualised data using interactive charts and graphs.
