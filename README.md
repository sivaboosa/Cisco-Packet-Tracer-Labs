DHCP Server Configuration & Network Automation
This project showcases a centralized DHCP service implementation across multiple routed network segments. It demonstrates how to automate IP addressing in a structured network environment using Cisco Packet Tracer.

Lab Overview
Objective: Automate IP, Subnet Mask, and Default Gateway assignment across different network subnets.

Core Command: ip helper-address configured on router interfaces to bridge DHCP broadcast traffic to a centralized server.

Network Topology: A routed architecture featuring a central DHCP server supporting multiple client subnets.

Verification & Results
DHCP Provisioning: Successfully automated client IP assignment using the ip helper-address relay agent.

Connectivity: Full end-to-end connectivity was verified via ICMP. A successful ping from PC1 to PC3 (on a different switch network) confirmed that routing and DHCP relay are functioning correctly.

How to use this Lab
Download the .pkz file from this repository.

Open the file in Cisco Packet Tracer.

Use the Simulation Mode to observe the DHCP request packets traveling from the client, through the router, and reaching the server.
