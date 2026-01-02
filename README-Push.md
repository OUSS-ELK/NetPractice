# NetPractice

*This project has been created as part of the 42 curriculum by OUSS-ELK.*

---

## Description

NetPractice is a networking exercise to learn the basics of TCP/IP. The project has 10 levels where you configure small networks to make them work correctly.

**Goal**: Learn how to set up IP addresses, subnet masks, and routing tables so devices can communicate through routers.

---

## Resources

### Networking Concepts

This project teaches:

- **TCP/IP addressing**: How devices get IP addresses (e.g., `192.168.1.10`)
- **Subnet mask**: Defines network size (e.g., `255.255.255.0` or `/24`)
- **CIDR notation**: Short way to write subnets (e.g., `/24`, `/26`, `/30`)
- **Default gateway**: Router's IP that devices use to reach other networks
- **Routers and switches**: Routers connect different networks, switches connect devices in same network
- **OSI layers**: Understanding Layer 3 (Network Layer) where routing happens

### AI Usage

**I used AI for:**
- Understanding networking concepts (subnetting, routing, CIDR)
- Learning calculation methods (magic number for subnets)
- Getting help with this README structure

**I did myself:**
- Solved all 10 levels by hand
- Tested and fixed configurations
- Applied what I learned to actual problems

---

## Quick Reference

### Common Subnet Masks
```
/24 = 255.255.255.0   → 254 hosts
/26 = 255.255.255.192 → 62 hosts
/30 = 255.255.255.252 → 2 hosts (for routers)
```

### Key Rules
- Devices must be in same network to communicate directly
- Network address (first IP) and Broadcast (last IP) cannot be used
- Gateway must be in same network as your device

---

## Author

Elkharraf Oussama - [GitHub](https://github.com/OUSS-ELK)