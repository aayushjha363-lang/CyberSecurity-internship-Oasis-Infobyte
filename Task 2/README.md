Basic Firewall Configuration with UFW

Objective

The aim of this project was to establish a simple security barrier on a Linux system using the Uncomplicated Firewall (UFW).


Configuration Steps

Installation: UFW was installed through the Linux package management tool (apt).

Policy Setup: Incoming connections were blocked by default by setting the policy to deny for better security.


Rule Application:

Enabled SSH (Port 22) to allow remote system management.

Disabled HTTP (Port 80) to stop unauthorized web traffic.

Activation: The firewall was turned on and set to remain enabled after every system restart.


Verification

The sudo ufw status verbose command was used to confirm:

Firewall Status: Active

Port 22: ALLOW IN

Port 80: DENY IN
