<div align="center"> 
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/Iam4lex/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Iam4lex">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/Iam4lex?style=social"> 
  </a> 
</div>

## How to Connect Your Hack The Box (HTB) Account with Kali Linux

Hack The Box (HTB) is a popular platform for cybersecurity enthusiasts to practice penetration testing and ethical hacking. In this guide, we’ll walk through the process of connecting your HTB account to Kali Linux to start solving challenges.

### Prerequisites

Before starting, ensure you have the following:
- An active Hack The Box account.
- Kali Linux installed and updated.
- Basic knowledge of using the terminal in Kali Linux.

### Step 1: Create or Log into Your Hack The Box Account

1. Visit [Hack The Box](https://www.hackthebox.eu) and sign up for an account if you don’t have one.
2. Once signed in, you will need to locate your HTB VPN connection details. These are required to connect Kali Linux to the HTB network.
   - Click on your username on the top right conner.
   - Click on VPN settings
![image](https://github.com/user-attachments/assets/6e14c4d6-9212-4c79-8220-6dece62f3f8a)

   - Scroll down to VPN servers.
   - Select TCP and download the VPN connection file
![image](https://github.com/user-attachments/assets/6242c925-6427-4804-8d43-af6aa1954b5a)

## Step 2: Install OpenVPN on Kali Linux

You will need OpenVPN to connect to HTB. Most versions of Kali Linux come with OpenVPN pre-installed. If it’s not already installed, run the following commands to install it:

- Update kai linux
```bash
sudo apt update
```

- Install openvpn
```bash
sudo apt install openvpn
