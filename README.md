# aws-ec2-web-server-project

# AWS EC2 Web Server Hosting Project

## Overview

This project demonstrates how to launch an Amazon EC2 instance, connect using SSH, install Apache HTTP Server, and host a static website on AWS.

## Technologies Used

* AWS EC2
* Amazon Linux 2023
* Apache HTTP Server (httpd)
* Linux Commands
* SSH
* Security Groups

## Project Steps

1. Created an EC2 instance using Amazon Linux 2023.
2. Generated and used an SSH key pair.
3. Connected to the server using SSH.
4. Updated system packages using DNF.
5. Installed Apache HTTP Server.
6. Started and enabled the Apache service.
7. Created a static HTML webpage.
8. Configured Security Group rules to allow HTTP traffic.
9. Verified website accessibility through a browser.

## Commands Used

sudo dnf update -y
➡️ Updates all installed packages on the Amazon Linux server to their latest versions

sudo dnf install httpd -y
➡️ Installs the Apache HTTP web server (httpd) on the EC2 instance.

sudo systemctl start httpd
➡️ Starts the Apache web server service immediately.

sudo systemctl enable httpd
➡️ Configures Apache to start automatically whenever the server reboots.

# echo'<h1>Hello from Payal's AWS Server</h1>' | sudo tee /var/www/html/index.html

Updated the Amazon Linux server, installed and configured Apache HTTP Server (httpd), started the service, and enabled automatic startup on system boot. 🚀☁️

## Outcome

Successfully hosted a static webpage on an AWS EC2 instance and accessed it through a public IP address.
