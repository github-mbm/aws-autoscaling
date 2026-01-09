AWS Auto Scaling:

Simple project shows how AWS Horizontal  Auto Scaling works using a simple Nginx web server.

When traffic increases, AWS automatically adds servers.
When traffic decreases, AWS removes servers.

What This Project Does

Runs a web page on EC2

Uses Auto Scaling Group

Uses Application Load Balancer

Shows(Webpage):

Date & Time

Server IP / Hostname

Helps understand scaling behavior visually

Architecture (Simple)
User(Load) > Load Balancer > Auto Scaling Group > EC2 (Nginx)

Services Used:

EC2

Auto Scaling Group

Application Load Balancer

CloudWatch

Nginx

