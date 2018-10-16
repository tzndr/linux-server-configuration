# linux_server_configuration
Udacity curriculum project. Configuration and deployment of an AWS linux server that hosts 
a previously completed catalog application. This application is hosted using Amazon Web Services 
and Lightsail an Apache2 web server running on Linux. Linux server is configured through firewall 
configuration and user permissions to prevent any attacks. 

## Viewing Details
1. Public IP: 18.205.1.143
1. SSH Port: 2200
1. Application URL: www.18.205.1.143.xip.io

## Project Details
  ### Configuration Summary
  1. File and directory permissions set using octal permission values
  1. Firewall configured to only allow specific connection types and ports
  1. Uses key-based authentication through kay pairs and a passphrase with user password-based 
  login disabled
  1. Required installation of Apache2/mod_wsgi and PostgreSQL along with various Python3 modules 
  to run the application
