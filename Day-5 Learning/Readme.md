Security Groups – It operates at the instance level. AWS assigns a default Security Group while creating an EC2 instance. Security Group is only for allowing traffic, not for denying it.

a. Default Security Group – It allows all outbound traffic except for port 25. It does not allow traffic on port 25 because it is used for mailing services, and AWS wants to prevent any kind of spam activity. They also want to avoid recording the IP address of the EC2 instance, so they block outbound traffic on port 25 by default.

b. AWS denies all inbound traffic coming into the instance by default.

1. Inbound traffic – Traffic coming into the EC2 instance.
For example: A user trying to access an application inside the EC2 instance.

2. Outbound traffic – Traffic going out of the EC2 instance.
For example: An application inside the EC2 instance trying to access something outside the EC2 instance.

NACL (Network Access Control List) – 
1. It is applied at the subnet level. Acts as an additional layer of security. We can deny and allow the traffic we want to give access to.

2. Using NACL, a DevOps engineer can define their organization's network traffic.

3. If something is applied at the subnet level, then it is applied to all the instances within the subnet.

For example –
a. There are 50 EC2 instances inside the subnet, so using NACL we can define the NACL configuration for all the EC2 instances.
b. Using this, we can automate the work of assigning the rules at each EC2 instance. Instead, we can use NACLs.


Practical Implementation
Using this command:
python3 -m http.server 8000

We can run Python on port 8000.

If we want to run it on port 8080, we use:
python3 -m http.server 8080

For this, we will create inbound and outbound traffic rules in the Security Group to allow traffic on port 8000 or 8080.






