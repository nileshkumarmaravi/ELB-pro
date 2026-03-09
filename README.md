# AWS Elastic Load Balancer overview

This project demonstrates how to configure and use AWS Elastic Load Balancing (ELB) to distribute incoming traffic across multiple **Amazon EC2 instances.
The goal of this project is to ensure high availability, scalability, and fault tolerance for a web application.

How

In this project:

Two or more EC2 instances are launched.

A simple web server (like **Apache HTTP Server or **Nginx) is installed on each instance.

An Elastic Load Balancer is created.

EC2 instances are registered as targets in the Load Balancer.

The Load Balancer distributes incoming HTTP requests across all instances.

This ensures that if one instance fails, the traffic is automatically routed to the remaining healthy instances.

Why

Using a Load Balancer provides several advantages:

Improves application availability

Distributes traffic evenly across servers

Prevents server overload

Supports automatic scaling

Provides fault tolerance

Load balancing is a key concept used in cloud computing and DevOps architectures.
