# Apache

# How To Install Linux, Apache, MySQL, PHP (LAMP) Stack on Ubuntu 22.04

## Project Overview

This project aims to develop a web-based application using the LAMP stack. The LAMP (Linux, Apache, MySQL, PHP/Perl/Python) stack is a popular open-source web development platform used for building dynamic websites and web applications.

## Prerequisites

- AWS EC2 Instance: An EC2 instance will be used as the hosting environment for the LAMP stack. It provides scalability and flexibility for web development projects.

- AWS Security Group Configuration: Ensure that all traffic is allowed in the AWS Security Group associated with your EC2 instance. However, this is not a recommended practice for production environments, and security configurations should be adjusted accordingly.

- Choose Ubuntu OS: Select Ubuntu as the operating system when configuring your EC2 instance. Ubuntu is widely used and well-supported, making it a suitable choice for hosting web applications.

## Step-by-Step Implementation

### Step 1 - Installing Apache

- Update package manager

```
sudo apt update
```

- Install Apache2 webserver

```
 sudo apt install apache2
```

You’ll be prompted to confirm Apache’s installation. Confirm by pressing Y, then ENTER

- After installation, verify the status of Apache

```
sudo apt install apache2
```

![sudo-systemctl-status-apache2](image1/domi-name.jpg)