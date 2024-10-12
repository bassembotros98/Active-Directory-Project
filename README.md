# Active-Directory-Project
![AD-Project](https://github.com/user-attachments/assets/255c4451-f6c7-4cd0-88f6-1c77fa85abf1)

## Introduction 

This project demonstrates the setup of an Active Directory environment using Oracle VirtualBox, including the installation of monitoring tools and security testing. The goal is to create a secure environment and monitor it using Splunk.
## Table Of Contents 

Part 1: VM Setup

Part 2: Installation of Monitoring Tools

Part 3: Active Directory Configuration

Part 4: Security Testing and Telemetry Collection

Conclusion

## Part 1: VM Setup

  Steps:

- Create VMs in Oracle VirtualBox:

- Windows 10 (Target Machine)

- Windows Server 2022 (Active Directory)

- Splunk Server (Ubuntu)

- Kali Linux

![Virtual Machines Screenshot ](https://github.com/user-attachments/assets/21887c31-a495-41d1-8988-2dbb15acebfd)

## Part 2: Installation of Monitoring Tools
  Steps:

- Install Splunk Universal Forwarder on:

  - Windows 10 (Target Machine)

  - Windows Server (Active Directory)

- Install Sysmon and Olaf Sysmon Config on both Windows machines.

- Install Splunk on Ubuntu (Splunk Server).

## Part 3: Active Directory Configuration
Steps:
- Install & Configure Active Directory on Windows Server.
- Promote the server to a domain controller.
- Create Groups and Users:
 
   Groups: IT, HR
  
   Users: Jenny Smith, Terry Smith
 - Join Windows 10 to the Domain.

- ![It Group User](https://github.com/user-attachments/assets/45053a8c-a686-4214-a6e4-d6bfff482a3c)

![HR Group User](https://github.com/user-attachments/assets/dd93e934-c357-4f4b-a560-d4e020a0739a)

## Part 4: Security Testing and Telemetry Collection
Steps:
- Use Crowbar Tool on Kali Linux for brute force attack on Windows PC.
  
- Install Atomic Red Team for threat emulation.
 
- Collect Telemetry on Splunk for analysis.

- 
