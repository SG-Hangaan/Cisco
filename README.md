# Information Assurance and Security

# Simple LAN Connection

A Simple LAN (Local Area Network) Connection is a basic setup where multiple devices, such as computers, printers, and servers, are connected within a limited geographical area, like an office, home, or school, using Ethernet cables or wireless technology. This connection allows devices to communicate and share resources like files, printers, and internet access efficiently. It typically involves a router or switch to manage the network traffic and assign IP addresses to devices.
____________________________________________________________________

Using Cisco packet tracer application (any version), Kindly construct the following scenarios:

IT Department: 5 PC, 2 Laptops and 1 printer
Sales Department: 3 PC, 2 laptops
Purchasing Department: 5 PC

 A. Construct a network topology for the following:
- IT: Bus
- Sales: Ring
- Purchasing: Star
  
 B. Interconnect each department and a construct a Simple LAN Connection. Kindly configure each
end devices, you may use IP Addresses such as 192.168.1.1 or 10.0.0.10, etc.

 C. Submit a proof that the connections are working by using PING Command. You can do it
randomly.

 D. Screenshot the Network Topology, and PING Status

<p align="center">
  <img src="https://github.com/SG-Hangaan/Cisco/assets/127215110/6e862b87-d36b-4f82-8d26-a56e8e9c3263"/>
</p>

# Basic Server Management Configuration
Basic Server Management Configuration for a network involves setting up and maintaining servers within a network infrastructure to ensure optimal performance, security, and connectivity. This typically includes:

<ul>
<li>Network Topology Design: Planning the layout of the network, including the placement of servers, switches, routers, and other networking equipment.

<li>IP Addressing: Assigning static or dynamic IP addresses to servers, ensuring each server has a unique identifier within the network.

<li>Subnetting: Dividing the network into smaller subnets to improve performance, security, and manageability.

<li>DNS Configuration: Setting up Domain Name System (DNS) servers to translate domain names into IP addresses and vice versa, facilitating network communication.

<li>DHCP Configuration: Configuring Dynamic Host Configuration Protocol (DHCP) servers to automatically assign IP addresses and other network configuration parameters to client devices.

<li>Firewall Configuration: Configuring firewalls to filter network traffic, block unauthorized access, and protect servers from malicious activity.

<li>Routing Configuration: Configuring routing protocols to enable communication between servers and other devices on different subnets or networks.

<li>Load Balancing: Implementing load balancers to distribute incoming network traffic across multiple servers, ensuring high availability and scalability.

<li>VPN Configuration: Setting up Virtual Private Network (VPN) connections to securely extend the network and provide remote access to servers for authorized users.

<li>Monitoring and Management: Installing monitoring tools to track network performance, analyze traffic patterns, and detect potential security threats. Implementing network management protocols like SNMP (Simple Network Management Protocol) for centralized management of network devices.

By implementing these basic configurations, administrators can effectively manage servers within a network infrastructure, ensuring reliable connectivity, security, and performance for users and applications.
____________________________________________________________________
Problem Scenario:

Create 2 web servers with webpages of any topic, that should be constructed using: 
- 4 PC (Static) – Manual set of IPv4 Address
-  Web Server 1: www.neu.edu.ph
- Web Server 2: www.cssociety.org
-  1 switch

2. Block Web Server 1 and allow Server 2 to be browsed in PC1 and PC2. Screenshot all of the Web
Pages that have been allowed or blocked. PC3 and PC4 should access all web servers.

3. Block Web Server 2 and allow Server 1 to be browsed in PC3 and PC4. Screenshot all of the Web
Pages that have been allowed or blocked. PC1 and PC2 should access all web servers.

<p align="center">
  <img src="https://github.com/SG-Hangaan/Cisco/assets/127215110/273ea5dc-47a6-4a13-891b-e1470585399d"/>
</p>



# Web Design and Simulation of the Client/Server Interaction

Web Design and Simulation of the Client/Server Interaction involves creating the visual layout and functionality of a website while simulating how it interacts with a server. By carefully designing and simulating the client/server interaction, web designers and developers can create functional and visually appealing websites that effectively meet the needs of users while ensuring reliability, security, and performance.

____________________________________________________________________
Problem Scenario:

- Simulate how does the electronic mail (E-mail) transfers from one point to another
- Configure E-mail Servers
- Determine the function of the e-mail Server in Networks
- Identify how the server responses at the client’s request

<p align="center">
  <img src="https://github.com/SG-Hangaan/Cisco/assets/127215110/1ebcdd35-25b2-44f1-bb51-40bc93638b6f"/>
</p>

Procedure
1. Open the Packet Tracer. Drag 2 PCs, 1 switch, 1 server to the Platform area.
2. Change the label of PC0 and PC1 as Static 1 and Static 2 respectively
3. In PC0, since it is named as Static 1, Set the Fast Ethernet ‘s IP address to 172.16.0.90 and its
subnet mask to 255.255.0.0 while the gateway is 172.16.0.1
4. In PC1, since it is named as Static 2, Set the Fast Ethernet ‘s IP address to 172.16.0.80 and its
subnet mask to 255.255.0.0 while the gateway is still 172.16.0.1
5. Configure the E-mail Server




















# E-Mail Configuration using Cisco Packet Tracer
<p align="center">
  <img src="https://github.com/SG-Hangaan/Cisco/assets/127215110/86f4f6fb-f04d-47ec-a251-d11bc308e5c2"/>
</p>

# Securing the Network using Firewall
<p align="center">
  <img src="https://github.com/SG-Hangaan/Cisco/assets/127215110/56e94709-217a-413d-b43f-87fd1d8cc5ee"/>
</p>

# Secured communication and establish a VLAN connection
<p align="center">
  <img src="https://github.com/SG-Hangaan/Cisco/assets/127215110/717749da-ef67-4ce7-8e0e-523b66898f68"/>
</p>
