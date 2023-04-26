# A Multi-Cloud Application

Architecture Diagram - [multicloud.pdf](./multicloud.pdf)

## AWS DYNAMO DB
### Requirements: Global availability and highly scalable pricing
- It offers compatibility with S3-api
- Dynamo DB allows us to split the services equally providing high availability
- Dynamo DB also provides 25 GB of data storage, 2.5 million streams read requests, and 100 GB of data transfer outs under AWS free tier which can enable cheap testing under dev.


### Images
- Destroying terraform on aws 
![Destroying terraform on aws](images/Aws-destroy.png)

- Destroying terraform on azure 
![Destroying terraform on azure](images/Azure-destroy.png)

- App service render on azure 
![App service render on azure](images/Azure.png)

- App service render on aws 
![App service render on aws](images/load-balancer.png)

