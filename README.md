
🌐 Apex University Enterprise Network Design (CSE 405 Mini Project)
This repository contains the complete design and configuration for a complex, multi-campus enterprise network for Apex University, created as a mini-project for the Computer Networks (CSE 405) course. The project demonstrates the successful implementation of a scalable, full-fledged network with multiple subnets, centralized services, and dynamic routing.


Project Goal
To design a complete network model that reflects Apex University's infrastructure, ensuring reliable, scalable, and secure connectivity across eight campuses.


Key Features and Configurations
Feature	Details
Topology & Scale	
Interconnects eight campuses using a router-based, multi-subnet architecture[cite: 110, 111].

Routing Protocol	
Implemented Dynamic Routing (OSPF) to ensure efficient path discovery and seamless communication between all subnets[cite: 87, 145].

Addressing	
Uses a Class B IP scheme starting at 172.10.0.0[cite: 98, 100].

Centralized Services	
All servers are located in a designated Server Room (Campus 7 acts as the service hub)[cite: 113, 119].

DHCP Server	
Configured as a single DHCP server to automatically assign IP addresses to hosts across all campus subnets (e.g., Campus 1, 2, 3, 4, 6, 7 pools)[cite: 87, 117, 120].

DNS/Web Server	
A DNS Server is configured to resolve www.apex.edu.bd to the Web Server's IP address (172.60.0.3)[cite: 116, 124, 125].

Physical Connections	
Utilizes serial DCE cables for all router-to-router WAN connections.

Wireless Access	
Wireless Access Points are implemented in each network, secured with WEP protection[cite: 128, 129].

Tools Used
The entire network model and its functionalities were designed and simulated using:


Cisco Packet Tracer 


Networking Devices: Routers, Switches, Wireless Access Points 


Servers: DNS Server, DHCP Server, Web Server 


Cables: Straight-through and Serial DCE cables 

Project Deliverables
Packet Tracer File (.pkt): The live simulation file with all device configurations.

Technical Report (.pdf): Comprehensive documentation including:

Logical Diagram & Network Summary.


Purpose and Limitations of the Network.


Testing and Verification (DHCP request, Ping tests).


Full Router Configuration Codes and OSPF Routing Table.
