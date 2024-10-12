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
