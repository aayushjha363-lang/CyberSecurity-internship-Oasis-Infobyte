Basic Firewall Setup Using UFW
Objective

The purpose of this project was to implement a fundamental network security layer on a Linux system using the Uncomplicated Firewall (UFW).

Configuration Steps

Installation: Installed UFW through the system's package manager (apt).

Default Policy: Configured the default policy for incoming connections to deny, establishing a “secure by default” stance.

Rule Configuration:

Permitted SSH (Port 22) to allow remote administrative access.

Blocked HTTP (Port 80) to prevent unauthorized web requests.

Enabling Firewall: Activated the UFW service and ensured it starts automatically on system boot.

Verification

Used the command sudo ufw status verbose to check:

Firewall State: Active

Port 22: ALLOW IN

Port 80: DENY IN
