DHCP Configuration – Cisco Packet Tracer

This project demonstrates the design and configuration of a Star Topology network in Cisco Packet Tracer, implementing DHCP (Dynamic Host Configuration Protocol) to automatically assign IP addresses to client devices.

📘 Project Overview

In this network, a central switch connects all devices in a star configuration. A dedicated DHCP server automatically provides IP addresses, subnet masks, and gateway information to the connected PCs. This reduces manual configuration effort and ensures consistent addressing.

Key Advantages:

Centralized IP address management

Reduces configuration errors

Easy to scale and maintain

🖥️ Network Topology

Components Used:

Switches: 1 × Cisco 2960-24TT

PCs: 4 × End devices (DHCP clients)

Servers: 1 × Server (DHCP-enabled)

Cables: Copper straight-through for all connections

IP Address Plan
Device	IP Address Type	Connected To
Server0	Static (DHCP Server)	Switch0
PC0	DHCP (Assigned by server)	Switch0
PC1	DHCP (Assigned by server)	Switch0
PC2	DHCP (Assigned by server)	Switch0
PC3	DHCP (Assigned by server)	Switch0
📂 Files
File Name	Description
dhcp_configuration.pkt	Cisco Packet Tracer project file
README.md	Project documentation
topology_screenshot.png	Network diagram image
⚙️ Configuration Steps

1️⃣ Connect Devices

Connect all PCs and the server to the switch using copper straight-through cables.

2️⃣ Configure DHCP Server

Assign a static IP to the server.

Enable the DHCP service and configure a pool with IP range, subnet mask, and default gateway.

3️⃣ Configure PCs

Set each PC to obtain IP configuration automatically (DHCP mode).

4️⃣ Test Connectivity

Use the ipconfig command on PCs to verify IP assignment.

Ping between PCs to check full connectivity.

🎯 Learning Objectives

Understand DHCP and its role in IP management

Learn how to configure DHCP in Cisco Packet Tracer

Verify automatic IP address assignment and network communication

🧠 Key Notes

DHCP makes network management easier, especially for large networks

A DHCP server must be reachable for IP assignments to work

Always reserve static IPs for servers and network devices that need fixed addresses

💡 Author

Kishore Anand M
🎓 B.Tech IT | 🧠 Pre-final Year
🔧 Aspiring Network Engineer | 💡 AI & No-Code Tools Explorer

🛡️ DHCP automates IP address allocation, making networks easier to configure, maintain, and expand.
