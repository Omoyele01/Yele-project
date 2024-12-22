# Omoyele Oluwaseyi Ewaregbemi Project Landing Page  

**IP Address**: [18.175.197.67](18.175.197.67)

---

## **Project Overview**  

The **Omoyele Oluwaseyi Ewaregbemi Landing Page** demonstrates deploying a static web page on an Nginx web server hosted on an AWS EC2 instance. This project highlights the following key skills and configurations:  
- Setting up a Linux server environment.  
- Installing and configuring the apache2 web server.  
- Deploying a custom HTML page.  
    

The deployed landing page introduces the project creator and provides relevant project details.  


## **Setup Instructions**  

The step-by-step guide is to documentation installation for a web server **Omoyele Oluwaseyi EwaregbemiProject Landing Page**.  

### **1. Provision an AWS EC2 Instance**  
- Log in to your AWS account and launch an EC2 instance.  
- Choose an Ubuntu 24.04 AMI for the server.  
- Select an appropriate instance type (e.g., `t2.micro`).  
- Configure the security group to allow the following traffic:  
  - HTTP (Port 80) for web traffic.  
  - HTTPS (Port 443) for secure web traffic.  
  - SSH (Port 22) for remote server access.  

### **2. Install the apache2 Web Server**  
Run the following commands on the server to install and start apache2  

sudo apt update
sudo apt install apache2 -y


### **3. Deploy the HTML Create the HTML File Landing Page**  
1. Navigate to the default web root directory of apache2:  
   
   cd /var/www/html

 Create the HTML File:
  sudo vi index.html

 
Add the following content:
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Welcome to [Your Name] Landing Page</title>
<style>
body {
font-family: Arial, sans-serif;
line-height: 1.6;
margin: 0;
padding: 0;
background-color: #f4f4f4;
color: #333;
}
header { 
  background: #0078d7;
  color: #fff;
  padding: 10px 20px;
  text-align: center;
  }
  main {
  max-width: 800px;
  margin: 20px auto;
  padding: 20px;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0
0 10px rgba(0, 0, 0, 0.1);
}
h1, h2 {
  color: #0078d7;
  }
  
# Yele-project
