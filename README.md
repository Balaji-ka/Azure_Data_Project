# Azure_Data_Project_1

https://github.com/Balaji-ka/Azure_Data_Project/assets/73286859/7fa1c56b-e16f-40eb-a9ae-9226cf423868

This project leverages the capabilities of Azure Data Factory to orchestrate and manage the process of transforming datasets from their original format into a new desired format. The primary objective of this endeavor is to enable seamless conversion and manipulation of data to facilitate various downstream applications and analyses.

The foundation of this project lies in the systematic conversion of datasets. These datasets, which could be sourced from various origins, often come in diverse formats that might not be optimal for the intended analytical or operational purposes. Azure Data Factory steps in to bridge this gap by providing a robust framework to perform these transformations efficiently and at scale.

The initial step involves sourcing the datasets and storing them in a designated storage area referred to as the "raw container." Within this container, the datasets are stored in their original, unaltered forms. This raw data serves as the starting point for the subsequent transformation process.

To ensure the quality and reliability of the transformed data, a checking system is implemented. This system evaluates each dataset to determine its validity according to predefined criteria. Valid datasets are then stored in a container labeled "validdata," while any invalid files are segregated into an "errordata" container. This system helps streamline dataset formatting and organization while enabling efficient validation and segregation of data based on its quality and validity.
