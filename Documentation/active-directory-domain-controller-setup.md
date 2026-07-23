# Active Directory Domain Controller Setup

## project Overview

Built a windows Server virtualizated lab environment to simulate an enterprise Active Directory infrastructer. the goal of this project was to deploy a Domain Controller, configure DNS, and prepare the environment for user, group, and policy managnement.

---
# Lab Environemnt

## Virtualization Platform

- Oracle VirtualBox

## Server Operating System

- Windows Server Evaluation edition

## Sever Role
- Active Directory Domain Servces (AD DS)
- DNS

## Sever name
-DC01

## Domain Created
-davidlab.local


## Implementation Steps Completed 

## 1. Created Windows Server Virtual Machine
- Installed Windows Server Evaluation Edition in VirtualBox.
- COnfigured administrator credentials.
- Completed initial operating system setup.

---

## 2. Configured Server identity

renamed the server:

SERVER - DC01


restarted the system to apply changes.

---

## 3. Configured Static IP Address

Configured a static IPv4 address fgor the future Domain Controller.

Network Configuration:

Ip Address:
10.0.2.10

Subnet mask:
255.255.255.0

Default gateway: 
10.0.2.2

DNS:
10.0.2.10


---
 
## 4. Installed Active Directory Domain Services

installed the following windows server role:

Active Directory Domain Services (AD DS)
 verified successful installation through Server Manager

---

## 5. Promoted Server to Domain Controller

Configured the server as the first Domain Controller in a new forest.

Created domain:
davidlab.local

Configured:
- Domian Controller
- DNS Server-
- Global Catalog

---
# Validation

Successful domain login confirmed:
DAVIDLAB?Administrator

This verified that:
- Active Directory was succesfully installed
- The server was promoted to Domain Controller
- Authentication through the new domain was working
---

# Skills Demontrated
- Windows Server Administration
- Active Directory Domain Services
- DNS Configuration
- Domain Controller Deployment
- Virtual Machine Management
- Network Configuration
- enterprise identity Management
- Infrastructure Documentation

