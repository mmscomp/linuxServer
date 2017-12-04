# Linux Server Configuration to run Catalog App

# IP address
public: 18.216.183.144


# URL address #
        18.216.183.144:5000         lypple.com:5000 
#http://ec2-13-59-85-31.us-east-2.compute.amazonaws.com

# Installation
Install python 2.7 and other necesary modules including postgreSQL database
server on the ubuntu server hosted by amazon aws.
A grader user is created.
Install and configure Apache to serve a Python mod_wsgi application.
A wsgi script file (catalog.wsgi) is congigured in the root directory.
A database user 'catalog' is created with limited permissions.

# Firewall
Configure the Uncomplicated Firewall (ufw) to allow incoming connections
to SSH (port 2200), HTTP (port 80), and NTP (port 123).

# UTC timezone
UTC timezone is configured by selecting UTC-4.

# Third-party resources
Amazon aws lightsail instance is used to ssh into ubuntu server.
Authentication is established thru third-party (Google and Facebook)
login. 
