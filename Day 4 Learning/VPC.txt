VPC (Virtual Private Cloud)

1. To address the issue of security breaches, AWS came up with the solution of VPC.

2. Defining the size of a VPC involves specifying its IP address range.

3. When a DevOps engineer splits the IP address range into smaller ranges for multiple projects, it is called a subnet.

4. The DevOps engineer will create a gateway. A gateway is a pass that allows access to the VPC.

5. A public subnet is the one that users can access inside the VPC.

6. A public subnet connects to the user through an Internet Gateway.

7. From the Internet Gateway, a public subnet request goes to the Load Balancer. The Load Balancer creates a target group for the application.

8. A Route Table is created and configured to direct the Load Balancer to the correct path to reach the subnet.

9. A Security Group can block or allow a request based on whether the IP address is authorized to access the subnet.

10. NACLs (Network Access Control Lists) are an automation layer for Security Groups. Instead of defining security rules repeatedly, they can be defined once using NACLs.

NAT Gateway:

1. A NAT Gateway helps private subnets download data from the internet by masking their IP address, so they are not exposed to the external world.

2. It masks the IP address with a public IP, either from a Load Balancer or a Router.

3. If done using a Load Balancer, it is called SNAT (Source Network Address Translation).

4. If done using a Router, it is called a NAT Gateway.

5. VPC Flow Logs: They record the flow of traffic within the above process. Sometimes these logs are chargeable, and sometimes they are not.
