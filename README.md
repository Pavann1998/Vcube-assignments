# Vcube-assignments
**Deploy Two-Tier Architecture on AWS
Creating a Two-Tier architecture on AWS We’ll explore the essential services involved, ensuring high availability, security, and scalability for hosting a static website
Also, we are adopting a modular approach with enhanced security measures The infrastructure is organized into dedicated modules, ensuring a scalable, maintainable, and secure deployment

Create an isolated network with the following components:
VPC
Subnets
Route Tables
Internet Gateway
NAT gateway
Security Groups
Create VPC with CIDR Block range (10000/16)

Create 4 subnet (2 Public subnets, 2 Private subnet

Create Internet gateway and attach to VPC

Create Two route tables one for Public and Private subnets and add internet gateway to Public route table

Create Security Group, edit inbound rules with SSH and HTTP Port

Launch 2 Ec2 Web server and configure with Nginx

Create an sample Web Page in indexhtml
Webserver-1 :
Webserver-2 :

Create Application Load Balancer and add 2 ec2 instances in Target Group

Test Load Balancer with Load balancer DNS Name

For Creation of Autoscaling we required Launch template

Create RDS and attach 2 Ec2 instances to the RDS for database access

Tested writer instance in Public server

Now connected to Reader instance and tried create database but it shows “—read-only” Option

Create Hostedzone in Route 53

Configure Nameservers in Domain purchased website

I have purched domain in Godaddy

So editing my own Nameservers in Godaddy website

In order to secure a webpage we required SSL/TLS Certificates in ACM

Create Amazon Certificate Manager(ACM) and attach to Cloud Front

Creating Cloud Front and configuring

Create a record in Route 53 add Cloud front in record

Test the out with our own DNS Name

My Domain name is rajeshwebonline
**
