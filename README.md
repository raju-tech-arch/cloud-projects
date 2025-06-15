# Duo AWS EC2 2FA Setup

Secure your AWS EC2 Windows instance remote access using Duo Two-Factor Authentication (2FA) with RDP.

---

## Overview

This project demonstrates how to implement Duo Security’s Two-Factor Authentication (2FA) for Remote Desktop Protocol (RDP) access on an AWS EC2 Windows Server instance. Adding 2FA enhances security by requiring an additional verification step beyond just username and password, protecting your cloud infrastructure from unauthorized access.

---

## Features

- Step-by-step guide to integrate Duo 2FA with Windows RDP
- Configuration of AWS EC2 instance for secure access
- Screenshots and demo walkthroughs included
- Best practices for securing Windows Server on AWS

---

## Technologies Used

- AWS EC2 (Windows Server)
- Duo Security 2FA
- Remote Desktop Protocol (RDP)
- PowerShell (for automation/scripts)
- Windows Server Configuration

---

## Prerequisites

- AWS Account with permissions to launch and manage EC2 Windows instances
- Duo Security account with API credentials
- Basic knowledge of AWS EC2 and Windows Server administration
- Remote Desktop Client

---

## Setup Steps

1. **Launch an EC2 Windows Instance**
   - Select Windows Server AMI
   - Configure security groups to allow RDP (TCP 3389)

2. **Install Duo Authentication for Windows Logon**
   - Download the Duo installer on the EC2 instance
   - Run the installer and configure with Duo API credentials

3. **Configure RDP with Duo 2FA**
   - Enable RDP access for your user accounts
   - Test login flow requiring 2FA approval via Duo app

4. **Verify and Troubleshoot**
   - Confirm Duo prompts during RDP login
   - Check logs if authentication fails

---


## Challenges & Solutions

- Handling network firewall rules to allow Duo communication  
- Ensuring minimal downtime during 2FA integration  
- Testing multiple user scenarios for 2FA prompts  

---

## How to Use This Project

- Follow the setup steps in order on your own AWS account  
- Customize Duo settings for your organizational needs  
- Use the provided screenshots and tips to troubleshoot  

---
## Contact

For questions or feedback, reach out at jbhagyaraju0304@gmail.com

---

## Acknowledgments

Thanks to Duo Security and AWS for providing robust security and cloud services.

