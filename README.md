# Develop Azure Compute Solutions
## Virtual Machine
Gives full conbtrol of servers but we have to maintain them
## Containers
The microservices approach normally requires the use of containers, such as Docker, Kubernetes

User needs to provision, schedule , manage the container orchestration.

Both `Virtual Machine` and  `Containers` are Infrastructure as a Service `Iaas`
## PaaS Solutions
### Azure App Service
Azure App Service allows to host web and mobile applications without worrying about underlying web servers.
### Azure FUnctions
known as serverless solution as servers are hidden and takes care of the task without actually showing their use in doing the tasks.
# Develop for Azure Storage
Azure storage include `blob storage` which is for storing unstructured data and `Cosmos DB` which is a `NoSQl` datastore
# Implement Azure Security
Managed Identity are the best way to authenticate applications so they can use azure Services

`Azure Key Vault` helps to manage keys, secrets, certificates.
# Monitor, troubleshoot, and optimize Azure solutions
## Autoscaling
instead of provisioning manually we can automate it by using autoscale by metrics
## Cache
Caching can be done usinf azure cache for redis and azure CDN.
# Connect to and consume Azure services and third-party services
## Logic Apps 
can create woekflows without having to write code.

For complex situations azure has messaging services, including `Service Bus` and `Storage Queues`, event handling services including `EVent Grid`, `Event Hub` and `Notification Hub` and API service called `Azure API Management`
