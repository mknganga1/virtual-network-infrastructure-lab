# Virtual Network Infrastructure Lab

## Project Overview

This project demonstrates how to build and configure a basic network infrastructure using virtualization.  
The lab simulates a small network environment with a server and client machines.

The server (godfather) provides core network services including:
the private network is called "godfather.youngbuck.local"
- DHCP Server
- DNS Server
- Web Server
- Firewall
- NAT networking

The infrastructure was deployed using **Ubuntu Server** and **Oracle VirtualBox**.

---

## Objectives

The goal of this project was to:

- Learn how to deploy core network services
- Understand client-server communication
- Practice Linux server administration
- Simulate enterprise infrastructure in a virtual lab environment

---

## Technologies Used

- Ubuntu Server
- Oracle VirtualBox
- Linux networking tools
- Apache Web Server
- ISC DHCP Server
- Bind DNS Server

---

## Network Architecture
Internet
   |
NAT Network
   |
Server VM (godfather)
(DHCP, DNS, Web)
   |
Client VM (spoiltbrat)
