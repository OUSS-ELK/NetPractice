NetPractice
This project has been created as part of the 42 curriculum by OUSS-ELK.

📖 Description
NetPractice is a practical networking exercise designed to introduce the fundamentals of computer networking. The project consists of 10 progressive levels where students configure small-scale network topologies to ensure proper communication between devices.
Goal: Learn how to configure IP addresses, subnet masks, and routing tables to connect devices through routers and understand the role of gateways within a network.
Overview: Through hands-on practice with a browser-based training interface, this project teaches essential networking concepts including TCP/IP addressing, subnetting, CIDR notation, and packet routing. Each level presents a non-functioning network diagram that must be corrected by filling in the appropriate network configuration values.

🚀 Instructions
Running the Training Interface

Download the NetPractice files from the project page
Extract the archive to your preferred location
Open the index.html file in your web browser

Recommended browser: Google Chrome or Chromium-based browsers
Note: Firefox may have compatibility issues due to security constraints


Enter your login in the training interface to save your progress with your personal configuration

Alternatively, use the "evaluation" tab for random configurations



Completing Levels

Each level displays a non-functioning network diagram
Read the goals at the top of the screen (what needs to communicate)
Modify the unshaded/white fields to fix the network configuration
Click "Check again" to verify your solution
Review the logs at the bottom for error messages and hints
Once successful, click "Get my config" to download your configuration file
Save the exported .json file before proceeding to the next level

Exporting Configurations

Use the "Get my config" button after completing each level
Save each file with its level number (e.g., level1.json, level2.json, etc.)
Important: Export your configuration before moving to the next level to avoid losing your work

Submission Requirements
What to submit:

Place 10 configuration files (one per level) at the root of your Git repository
Files should be named: level1.json, level2.json, ..., level10.json
Include this README.md file


📚 Resources
Networking Concepts Studied
This project covers the following fundamental networking concepts:
TCP/IP Addressing

IPv4 addresses: 32-bit identifiers written as four octets (e.g., 192.168.1.10)
Network vs Host portions: Understanding how IPs are divided
Private IP ranges (RFC 1918): 10.0.0.0/8, 172.16.0.0/12, 192.168.0.0/16

Subnet Mask

Determines which portion of an IP address represents the network
Common masks: 255.255.255.0 (/24), 255.255.255.192 (/26), 255.255.255.252 (/30)
Subnet calculation using the "magic number" method: 256 - last octet

CIDR Notation

Classless Inter-Domain Routing format: IP/prefix (e.g., 192.168.1.0/24)
More flexible than traditional class-based addressing
Allows efficient IP address allocation

Default Gateway

The router's IP address used by devices to reach other networks
Must be in the same subnet as the device
Acts as the "exit point" from the local network

Routers and Switches

Routers: Forward packets between different networks using routing tables
Switches: Connect devices within the same network (Layer 2)
Routing table components: Destination, Mask, Next Hop, Interface

OSI Layers (Focus on Network Layer)

Understanding Layer 3 (Network Layer) where IP routing occurs
How different layers work together in the TCP/IP model
Packet forwarding and routing decisions

Reference Materials
Books:

Computer Networks by Andrew Tanenbaum - Chapter 5 (Network Layer)
TCP/IP Illustrated, Volume 1 by W. Richard Stevens

Online Resources:

RFC 1918 - Address Allocation for Private Internets
Subnet calculators for verification and practice
Visual subnet calculator tools
Cisco Networking Basics documentation

Practice Tools:

NetPractice training interface (provided with project)
Online subnetting practice websites
Network diagram visualization tools

Use of AI in This Project
AI was used for the following tasks:

Concept Clarification

Understanding complex networking concepts (subnetting, CIDR, routing tables)
Getting explanations of how default gateways work
Learning the relationship between subnet masks and network ranges


Calculation Methods

Learning the "magic number" method for quick subnet calculations
Understanding binary-to-decimal conversions (though ultimately used decimal methods)
Verifying subnet range calculations


Documentation

Structuring this README file according to project requirements
Organizing technical information clearly
Formatting examples and explanations


Problem-Solving Assistance

Debugging network configuration issues
Understanding error messages from the training interface
Learning systematic approaches to network troubleshooting



Parts of the project completed with AI assistance:

Initial learning of networking fundamentals
README structure and formatting
Understanding the relationship between different networking concepts

Parts completed independently:

All 10 level configurations (hands-on practice)
Troubleshooting and fixing network issues
Applying concepts to solve specific network problems
Final verification and testing of all configurations

Note: All AI-generated explanations were verified through practice, peer discussions, and testing in the NetPractice interface. The actual network configurations were solved through personal understanding and problem-solving.


🧠 Key Concepts Learned
Same Network Communication

Two devices can communicate directly only if they're on the same network.
Example:
  PC1: 192.168.1.10/24  }  Same network → Direct ✓
  PC2: 192.168.1.20/24  }

Different Network Communication
Devices on different networks need a router.
Example:
  PC1: 192.168.1.10/24  }  Different networks → Router needed
  PC2: 192.168.2.10/24  }
Reserved Addresses
Cannot assign to hosts:
  - Network address (first): e.g., 192.168.1.0
  - Broadcast address (last): e.g., 192.168.1.255
  
Usable range: 192.168.1.1 - 192.168.1.254

Subnetting Quick Reference
CIDR        Subnet Mask         Usable Hosts            Magic Number
/24       255.255.255.0             254                     256
/25       255.255.255.128           126                     128
/26       255.255.255.192            62                      64
/27       255.255.255.224            30                      32
/28       255.255.255.240            14                      16
/29       255.255.255.248             6                       8
/30       255.255.255.252             2                       4

🎯 Skills Developed

IP addressing and subnetting proficiency
Network topology analysis
Routing table configuration
Gateway and interface management
Network troubleshooting and debugging
Systematic problem-solving approach

👤 Author
Elkharraf Oussama

GitHub: @OUSS-ELK


📝 Project Information

School: 42 Network
Project: NetPractice
Level: Fundamentals of Computer Networking
Completion Date: [02/01/2026]