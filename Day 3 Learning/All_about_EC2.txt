EC2 – Elastic Cloud Compute (Virtual server/machine on AWS):
AWS has multiple data centers (physical servers) across the world. On those physical servers, AWS uses a hypervisor to create a virtual machine based on user requests. 
It then provides an IP address and key pair to the users who requested the service. The term “Elastic” is prefixed to many AWS services, meaning these resources can 
scale up or scale down based on our needs—we can increase or decrease the resources at any time.

Why EC2?
Creating EC2 instances using the public cloud platform is easy. As DevOps engineers, we do not need to worry about manually upgrading physical servers. 
There are minimal security concerns, and it saves costs for management. On AWS, you only pay for what you use—following the pay-as-you-go model.

Types of EC2 Instances:
Depending on the type of application—whether it is a machine learning application, data analytics application, or gaming application—we choose the appropriate 
instance type. The process of creating EC2 instances is the same; the only difference is that while creating the instance using the UI or CLI, we need to select 
the correct instance type, and AWS will charge accordingly. The main types of EC2 instances are:

1. General Purpose EC2 Instances

2. Compute Optimized EC2 Instances

3. Memory Optimized EC2 Instances

4. Storage Optimized EC2 Instances

5. Accelerated Compute EC2 Instances

Regions on AWS:
AWS has data centers in multiple geographic locations. Depending on your location or your client's location, you can request to create EC2 instances in that specific
region. This helps reduce latency, as the request will take more time to travel if the servers are located far away.

Availability Zones:
An Availability Zone (AZ) is like a data center—a place where AWS stores its servers, applications, and your data. However, it’s more than just one building; 
it's a group of data centers in a specific region that work together to provide high availability, fault tolerance, and disaster recovery.
