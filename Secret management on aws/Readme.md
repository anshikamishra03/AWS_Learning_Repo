
CI/CD - Using Docker 

a. Username / Password
b. Registry urls

(if this information is leaked anyone will be able to access docker and change the image)

Using Interact with database

a. delete the entries from database

Using ansible/ terraform

AWS credentials will be secured

Secret management solutions

a. system manager- parameter store anything which is stored is very easy to retierve (grant the iam role using this they can access the information stored in IAM role.

b. secrets manager- rotate the sensititive information( certificates will be expired in 180 days automatically rotated)/ Passwords also/ API Tokens.

Mangage between System manager/ secrets manager according to the requirement

c. Hashicorp vault (mostly used)- When using Hybrid cloud ( AWS/ Azure)/ Open source platform/ Many features (encryption )/ Community driven project (many features keep on adding )


