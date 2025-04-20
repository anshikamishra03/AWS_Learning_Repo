 AWS Load Balancer- Helps with the problem of large traffic management on ec2 instance

for example- . There are three ec2 instance and all are having the same characterstics ( They will handle the request in round robin format)

. B'coz of this slowness and downtime problem will be solved.

. and we have highly available application.

Different types of load balancer
1. Nginx

2. F5

3. Envoy

4. Traffic etc.

Seven Layers of OSI

User ---> Linkedin.com ---> Server ---> Response back to user

This traffic flows in seven different layers
1. Application Layer- When user requests an http request (Layer 7) what type of protocol required like ftp or something else.

2. Presentation Layer- Layer 6 (Secure requests ssl/tls based requests) ssl depricated now everything is tls. ( encoding / encrypting our requests).

3. Session Layer- Layer 5 ( creating session of our requests , session objects will created with the details like when the request is created, what kind od client has requested)

4. Transportation Layer- Layer 4 ( requests is spilt into multiple packets or small chunks , it make sure that information is transmitting to client in a secure way and in small small packets

5. Network Layer- Layer 3 ( Requests goes through the multiple routers)

6. Data Link Layer- Layer 2 ( request will go to a switch and will go to the data center from there it will go to physical layer)

7. Physical Layer (layer 1 ) All the cables after that reach to the server.


Types of Load Balancer
1. Application Load Balancing - . If we want to perform traffic load balancing on layer 7. (http/ ftp traffic) {host,path,domain} also called as L7 load balancer.

. It can also perform ssl offloading. { even if you send plain http requests to load balancer this load balancer can initiate a secure connection to your servers}

. It can also perform reencrpyt

. Passthrough

. Costly load balancer

. Slow

2. Network Load Balancing- If we want to perform traffic load balancing on layer 4. { cannot intercept http requests}

. Game servers,  Youtube, Streaming platforms require layer 4 load balancing.

. No loss of data.

. Low latency

. High transmission of data.

. Less Costly

. Routing at tcp and udp packets.

. Can create sticky sessions.

3. Gate way load balancer ( gwlb)-  VPN, Firewall applications.

. 
