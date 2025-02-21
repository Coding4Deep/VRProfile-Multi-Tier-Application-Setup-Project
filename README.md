<h1>Aim of the Project </h1>
The goal of this project is to set up a multi-tier architecture for the VRProfile application in a 
local environment using Vagrant and VirtualBox. This setup simulates a production-like 
environment where different services work together to ensure scalability, reliability, and 
performance. 

<h1>Scenario & Use Case </h1>
● The VRProfile application is a web-based system that requires multiple services to 
function properly. <br>
● Each service is deployed on a separate virtual machine (VM) to mirror real-world 
deployments. <br>
● This multi-tier architecture ensures modularity, scalability, and fault isolation. <br>


<h1>Why Are We Setting Up This Project? </h1>
● To create a local development & testing environment before deploying to production. <br>
● To learn and practice infrastructure automation using Vagrant. <br>
● To test and optimize application performance by setting up a distributed service 
architecture. <br>
● To simulate a production environment for DevOps CI/CD pipeline testing.<br>

<h1>Multi-Tier Architecture Breakdown </h1>
The application is structured into five key services, each running on separate VMs: <br><br>
1. Database Tier: MySQL (MariaDB) → Stores user and application data. <br>
2. Cache Tier: Memcached → Caches database queries for better performance. <br>
3. Message Queue Tier: RabbitMQ → Handles asynchronous messaging. <br>
4. Application Tier: Tomcat → Runs the Java-based backend application. <br>
5. Web Tier: Nginx → Acts as a reverse proxy and serves web requests. 
