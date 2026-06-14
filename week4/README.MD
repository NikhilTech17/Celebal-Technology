# Azure Cloud Fundamentals and Data Pipeline Implementation using Azure Data Factory

## Objective

To understand Azure cloud concepts and build an end-to-end data pipeline using Azure Storage Account and Azure Data Factory (ADF).

## Project Overview

This project demonstrates the creation of a complete data integration workflow in Microsoft Azure. A CSV dataset was uploaded to Azure Blob Storage and processed through Azure Data Factory. The pipeline validates file metadata and copies the data from a source container to a destination container.

## Services Used

* Azure Resource Group
* Azure Storage Account
* Azure Blob Storage
* Azure Data Factory (ADF)
* Azure IAM (Reader and Contributor Roles)

## Implementation Steps

1. Created a Resource Group in Azure.
2. Created a Storage Account and Blob Containers.
3. Uploaded the CSV dataset to the source container.
4. Created Azure Data Factory and explored Author, Monitor, and Manage modules.
5. Configured a Linked Service to connect ADF with Azure Blob Storage.
6. Created Source and Destination Datasets.
7. Used the Get Metadata activity to retrieve file details.
8. Built a pipeline using the Copy Data activity.
9. Executed the pipeline using Debug/Trigger.
10. Monitored pipeline execution in ADF Monitor.
11. Assigned IAM roles (Reader and Contributor) to ensure secure access.
12. Validated metadata and successfully copied the file to the destination container.

## Pipeline Flow

Source Blob Storage
↓
Get Metadata
↓
Copy Data Activity
↓
Destination Blob Storage

## Results

* Successfully connected Azure Data Factory to Azure Blob Storage.
* Retrieved file metadata including file name, size, and last modified date.
* Successfully copied the dataset from the source container to the destination container.
* Verified pipeline execution through ADF Monitor.
* Implemented secure access using Azure IAM roles.

## Conclusion

This project provided hands-on experience with Azure cloud services and Azure Data Factory. An end-to-end data pipeline was successfully implemented, demonstrating data movement, metadata validation, monitoring, and access management within the Azure ecosystem.
