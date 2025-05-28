Bigdata refers to data sets that are too large or complex to be dealt with by traditional data managemnet software

# [big-data-analytics](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-big-data-analytics)

#[big-data-architecture-styles](https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/big-data)


...The 5 Vs of big data, which are key characteristics, are Volume, Velocity, Variety, Veracity, and Value. These characteristics help define what makes big data different and why it's so valuable for analytics. 

3 vs **__Volume, Velocity, Variety__**
==============================

Volume:
This refers to the sheer quantity of data generated and stored. It highlights the massive scale of big data, often measured in terabytes, petabytes, and even exabytes. 
**1 Terabyte = 1000 Gigabytes**
**1 Petabyte = 1000 Terabyte**
**1 Exabyte  = 1000 Petabyte**

it can be generated from various sources such as social media, IoT devices, and transactional systems.

Velocity:

This is the speed at which data is generated and collected, and the ability to process and analyze
	* real-time
	* near real-time
	* Periodic
	* Bath


Variety:
This refers to the diverse types of data that big data encompasses, including **structured, semi-structured, and unstructured ** formats. This diversity can __include text, images, videos, audio, and more__. 


Azure Data Lake Storage Gen2 to store data in a distributed manner across multiple servers. scalable to the point where it can handle exabytes of data.


Azure Data Factory to move and process big data using parallel processing via big
data technologies such as Hadoop and Spark. it's equipped to deal with large amounts of data in parallel across a cluster of computers,making it well suited for big data workloads.

Microsoft Fabric that serves as a unified workspace for data ingestion, data 
engineering, data warehousing, real time and advanced analytics. 

# [organize-resources](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/organize-resources)

#[resource-naming](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming)

[resource-abbreviations](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations)


----------------------------------------
[data-factory-introduction](https://learn.microsoft.com/en-us/azure/data-factory/introduction)

What is Data factory

Data Factory is an Azure service which is used for Data movement and Transformation Activities.
You can setup rules for data movement, transformation 
You can setup triggers when the activity should execute.
You can monitor the data once the activities are performed. 
You can view the failure logs under this datafactory incase of activity failure

[concepts-linked-services](https://learn.microsoft.com/en-us/azure/data-factory/concepts-linked-services?tabs=data-factory)

[concepts-datasets-linked](https://learn.microsoft.com/en-us/azure/data-factory/concepts-datasets-linked-services?tabs=data-factory)

[concepts-pipelines-activities](https://learn.microsoft.com/en-us/azure/data-factory/concepts-pipelines-activities?tabs=data-factory)

[concepts-integration-runtime
](https://learn.microsoft.com/en-us/azure/data-factory/concepts-integration-runtime)

# [copy-activity](https://learn.microsoft.com/en-us/azure/data-factory/copy-activity-overview)

------------------------------------
What are the components of Data Factory

1. Integration Runtimes
2. Linked Service
3. Datasets
4. Pipelines
5. Activities
6. Data Flows
7. Triggers
8. Parameters
9. Variables
10. Git Repository


INTEGRATION RUNTIME
IT CREATES A GATEWAY CONNECTION BETWEEN THE INPUT AND OUTPUT DATABASES, BLOBSTORAGE ETC.. IN AZURE PORTAL

IT CAN ALSO CONNECTION BETWEEN ON PREMISES SERVER TO AZURE CLOUD AND VICEVERSA

IT CAN ALSO CREATE CONNECTION BETWEEN SSIS TO CLOUD

AZURE HAS 3 TYPES OF INTEGRATION SERVICES
1. AZURE OR AUTORESOLVE INTEGRATION RUNTIME
2. AZURE SELFHOSTED INTEGRATION RUNTIME
3. AZURE SSIS INTEGRATION RUNTIME


