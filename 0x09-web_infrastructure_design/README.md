# Web infrastructure design

This is a collaborative Project done during Full Stack Software Engineering Program at ALX. Our objective is to learn how to design a Web Infrastructure.

# Key concepts

* Network basics
* Server
* Web server
* Application server
* DNS & DNS record types
* Load Balancer
* Monitoring
* Database
* Single point of failure
* HTTP & HTTPS
* Firewall

# File Descriptions

Each file contains a link to an image hosted on Imgbox. These images are based on the following requirements:

# 0-simple_web_stack

On a whiteboard, design a one server web infrastructure that hosts the website that is reachable via www.foobar.com. Start your explanation by having a user wanting to access your website.

Use the following:

* 1 physical server

* 1 web server (Nginx)

* 1 application server

* 1 application files (your code base)

* 1 database (MySQL)

* 1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8

# 1-distributed_web_infrastructure

On a whiteboard, design a three servers web infrastructure that host the website www.foobar.com.

You must add to 0-simple_web_stack:

* 2 physical servers

* 1 web server (Nginx)

* 1 application server

* 1 load-balancer (HAproxy)

* 1 application files (your code base)

* 1 database (MySQL)

# 2-secured_and_monitored_web_infrastructure

On a whiteboard, design a three servers web infrastructure that host the website www.foobar.com, it must be secured, serve encrypted traffic and be monitored.

You must add to 1-distributed_web_infrastructure:

* 3 firewalls

* 1 SSL certificate to serve www.foobar.com over HTTPS

* 3 monitoring clients (data collector for Sumologic or other monitoring services)

# 3-scale_up

You must add to 2-secured_and_monitored_web_infrastructure:

* 1 physical server

* 1 load-balancer (HAproxy) configured as cluster with the other one

* Split components (web server, application server, database) with their own server
