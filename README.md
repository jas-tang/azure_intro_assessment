# Azure Exploration

Storage: Object Storage Archive, Amazon Elastic Block Storage

Compute: Azure VMware Solution, Google App Engine

Database services: Azure Cache for Redis, Oracle Lift Services


## Storage:

### Object Storage Archive

Brief Summary: Object Storage Archive or Object Storage Services (OSS), by Alibaba Cloud, is a secure cloud-based storage and data intelligence provider. It allows its consumers to store a vast amount of unstructured data, including images, videos, etc., in a secure and durable fashion. The purpose of this storage type is for its longevity and durability. Data stored in the OSS is stored as objects within buckets. Data is organized in this bucket-based architecture, which provides a way to organize and manage the data stored in the cloud. It is more flexible and scalable than traditional methods that store a large amount of unstructured data. In terms of billing, they support three methods: pay-as-you-go, subscription, and storage capacity unit. 

Python Application: Using a Python API called OPENIO SDS, you can manipulate containers where you store objects using Python. You will be able to gain the function of managing accounts, creating containers, showing the description of containers, storing objects, retrieving objects, deleting objects, retrieving container and object metadata, listing containers, and deleting containers. 

### Amazon Elastic Block Storage

Brief Summary: Amazon Elastic Block Store or EBS is a block-level cloud storage service to store persistent data. It allows consumers to manage storage volumes, making it easy to build and run applications on the cloud. A general storage use case is to store virtual machine disk storage. EBS provides persistent storage, meaning that the data stored remains even when the virtual machine instance ends. There is also a snapshot and backup capability, which allows copies of a point in time in case of disaster recovery. 

Python Application: Using a Python API called Boto3, you gain the option to directly manipulate snapshots. You can write directly into it and identify the changes or differences within two snapshots. This is a solution for a more efficient and cost-effective way to track incremental changes within Amazon EBS. 

## Compute:

### Azure VMWare Solution

Brief Summary: Azure VMWare Solution is a virtual machine adapter that allows organizations to run their VMware programs on the Microsoft Azure network. It allows users to migrate, extend, and operate their VMware environments while maintaining a seamless process. Azure VMWare Solution offers security, consistency, and has recovery capabilities. 

Python Application: Microsoft Azure SDK for Python has 180 Python libraries that relate to Azure services. Using this SDK or Software Development Kit, you can communicate with Azure services using Python code. 

### Google App Engine

Brief Summary: Google App Engine is a platform that allows users to host their web applications. Developers can build and manage their web services without needing to manage server and networking infrastructure. Google App Engine offers support for a variety of languages, including Python, Java, Node.js, Ruby, and more. Google App Engine also offers affordability and automatic scaling, meaning it adjusts resources based on traffic. 

Python Application: Google App Engine offers support for Python as a language to build environments You can use Python on Google App Engine to build, deploy and monitor Python applications. 

## Database services

### Azure Cache for Redis

Brief Summary: Azure Cache for Redis is a database program that allows data to be stored based on Redis, which is a software that improves the performance and scalability of an application. It helps enhance application performance by providing fast and efficient data storage and retrieval. Azure Cache for Redis allows for full compatibility with the Redis API, and hosts secure Redis server instances. In conjunction, they can store data caches, which contain a massive amount of data. 

Python Application: You can use Azure Cache for Redis in Python by installing a package called Redis-py. 

### Oracle Lift Services

Brief Summary: Oracle Lift Services is a cloud-based migration solution that allows a seamless transfer of applications or data. They help migrate both on-premise environments as well as other cloud environments onto Oracle Cloud. They aim to simplify and expedite the migration process with minimal disruption to the business. They also offer support throughout the planning and go-live stage of a data migration. 

Python Application: There is no Python application involved in Oracle Lift Services, however, you can manage an Oracle database using Python. 


