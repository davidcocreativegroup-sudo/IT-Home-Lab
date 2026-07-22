# Linux user Management Lab

## Objective 

This project demonstrates Linux system administration skills by creating and managing user accounts, groups,passwords, and file permissions, in an ubuntu virtual machine.

## Skills demonstrated
-user account creation
-group management
-password adminsitration
Linux file permissions
-Ownership changes
-principle of least privilege
-command-line administration

## Environment
-oracle VirtualBox
-Ubunutu desktop 26.04 LTS
bash Shell

## Commands used
```bash
sudo adduser manager
sudo adduser technician
sudo groupadd managers
sudo groupadd techcnicans
sudo usermod -aG managers manager
sudo usermod -aG technicians technician
chmod
chown
ls -l
```

## What I learned
-creating local users
-managing Linux groups
-Assinging folder ownership
-restricitin access using ownership
-restricing access sing permissions
-Verfying security controls

## Outcome
Successfully configured seperate user accounts with different permission levels and verfified that access restricitions worked as intended.o

