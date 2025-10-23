# azure-data-pipeline
Front to End Data Pipeline

 Used Azure to peform the extraction and tranformation of an ETL pipline.

 Tech Stack:

 SQL - tables, dtabases, formatting
 Bashr
 Azure Data Factory - ingest data from raw dataset, used sql to extract specific data and formatted it to be transformed
 Azure Data Bricks - Used bronze -> silver -> gold transformation pipeline to clean data to be usable
 Self Integrated Runtime Host
 Powershell

 Problems Encountered:

 Setting up Java JDK proved troublesome as the most recent version of Microsoft SHIR isn't compatible with the most recent Oracle Sourced Java JDK
 Solution: Trial and error multiple older versions of Java JDK packages, then rewrote registry keys for SHIR to access the proper Java versions

 Databricks runs in a separate container that you specify on a certain Microsoft Facility. The prices for these services were overpriced and outside my budget.
 Solution: The minimum specs to run Azure DataBricks for my purposes was 16gb ram and 4 cores, computationally light enough for my local device to handle so I rerouted databricks to run on a container on my local devices rather than pay for services on a offsite Microsoft Facility.
 
