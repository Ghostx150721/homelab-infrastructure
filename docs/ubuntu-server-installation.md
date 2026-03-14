# Ubuntu Server Installation

This document records the initial setup of the homelab server.

## Hardware

* CPU: Intel i5
* RAM: 8GB
* Storage: SSD + HDD

## OS Installation

Installed Ubuntu Server LTS on the dedicated homelab machine.

Steps:

1. Created bootable USB with Ubuntu Server ISO
2. Installed OS on SSD
3. Created main user account
4. Configured network
5. Installed OpenSSH server

## SSH Verification

Tested remote access from another machine:

ssh username@server-ip

SSH connection was successful.

## Next Steps

* Install Docker
* Install Docker Compose
* Configure static IP
* Prepare directories for containers

