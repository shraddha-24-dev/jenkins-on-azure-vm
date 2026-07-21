# Jenkins Deployment on Azure Virtual Machine

## Overview

This project demonstrates how to install and configure Jenkins on an Azure Virtual Machine (Ubuntu). The goal was to set up Jenkins successfully and access it through a web browser for continuous integration tasks.

## Technologies Used

- Microsoft Azure
- Azure Virtual Machine (Ubuntu)
- Jenkins
- Java (OpenJDK)
- Linux
- Git

## Project Steps

1. Created an Azure Virtual Machine.
2. Connected to the VM using SSH.
3. Installed Java.
4. Installed Jenkins.
5. Started the Jenkins service.
6. Configured the Network Security Group (NSG) to allow port **8080**.
7. Accessed Jenkins through the browser.
8. Completed the initial Jenkins setup.

## Architecture

```
Browser
   │
Azure Public IP
   │
Azure Network Security Group (Port 8080)
   │
Azure Virtual Machine (Ubuntu)
   │
Jenkins
```

## Result

Jenkins was successfully deployed on an Azure Virtual Machine and is accessible through the web interface.

## Learning Outcomes

- Provisioned an Azure Virtual Machine.
- Installed Jenkins on Linux.
- Configured Azure networking.
- Managed Linux services using systemctl.
- Learned the basics of deploying Jenkins on Azure.

## Future Improvements

- Connect Jenkins with GitHub.
- Create CI/CD pipelines.
- Build and deploy a sample Java application.
- Integrate Docker.

