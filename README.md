- 👋 Hi, I’m @DigitalSupportServices
- 👀 I’m interested in IT, Networking, Project management, ITIL
- 🌱 I’m currently learning T Level Infrastructure
- 💞️ I’m looking to collaborate on most.
- 📫 How to reach me ...
- 😄 Pronouns: US
- ⚡ Fun fact: 

<!---
DigitalSupportServices/DigitalSupportServices is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

## Networking Projects
Design and Implementation of a Campus/University System Network Design (Project #1)

__Project #1__  

- Case Study and Requirements
- Albion University is a large university which has two campuses situated 20 miles apart. The university’s students and staff are distributed in 4 faculties; 
these include the faculties of Health and Sciences; 
Business; 
Engineering/Computing and Art/Design. 

Each member of staff has a PC and students have access to PCs in the labs. Create a network topology with the main components to support the following:
University location.

__Main Campus__
- __Building A__: Administrative staff in the departments of management, HR and finance. The admin staff PCs are distributed in the building offices and it is expected that they will share some networking equipment (Hint: use of VLANs is expected here). The Faculty of Business is also situated in this building
- __Building B__: Faculty of Engineering and Computing and Faculty of Art and Design.
- __Building C__: Students’ labs and IT department. The IT department  hosts the University Web  server and other  servers - There is also an email  server hosted externally in the cloud.


Each department/faculty is expected to be on its own separate IP network.
The switches should be configured with appropriate VLANs and security settings.
RIPv2 will be used to provide  routing for the routers in the internal network and static routing for the external server.
The devices in building A will be expected to acquire dynamic IP addresses from a router-based DHCP server.


Configure in Packet Tracer the network with appropriate settings to achieve the connectivity and functionalities specified in the requirements.




##Project 2

__Project #2__
- Case Study and Requirements
- Radeon Company Ltd. is a US-owned company that deals with Banking and Insurance. The company is intending to expand its services across the African continent having the first branch to be located in Nairobi, Kenya. The company has secured a four-story building to operate within the Kenyan capital city. Therefore, the company would like to allow sourcing the knowledge from a group of final-year students from the local university to design and implement their company network. Assume you are among the students to take over this role, carefully read down the requirements then model the design and implement the network based on the company's needs. Each floor has departments as provided in the table below.

- <img width="515" alt="Screenshot 2024-06-30 at 23 19 50" src="https://github.com/DigitalSupportServices/DigitalSupportServices/assets/157905650/4f021139-ca10-40df-b91d-609393151e33">

- Use a  software modeling tool to visualize the network topology (Use Hierarchical Network Design
-  Software Modelling Tools: MS Visio, Visual Paradigm, or Draw.io for modeling network design.
Use any of the following network simulation  software to implement the above topology.

- [ ] Simulation software:  Cisco Packet tracer or GNS3 for design and implementation.
- [ ] Use OSPF as the  routing protocol to advertise routes.
- [ ] Each department is required to have a wireless network for the users.
- [ ] Each department except the server room will be anticipated to have around 60 users both wired and wireless users.
- [ ] Host devices in the network are required to obtain IPv4 addresses automatically.
- [ ] Devices in all the departments are required to communicate with each other.
- [ ] Create HTTP, and E-mail servers.
- [ ] All devices in the network are expected to obtain an IP address dynamically from the dedicated DHCP servers located at the server room.
- [ ] Configure SSH in all the  routers for remote login.
- [ ] Configure the basic configuration of the devices: Hostnames, Line Console and Enable passwords, Banner messages Disable domain IP lookup, encrypt all configured passwords.
- [ ] Each department should be in a different VLAN and subnetwork; VLANs you will use in your case, e.g. 10, 20, 30… etc..
- [ ] Planning of IP Addresses: You have been given 192.168.10.0 as the base address for this network. Do subnetting based on the number of hosts in every department as provided above. Identify subnet mask, useable IP address range, and broadcast address for each subnet.
- [ ] End Device Configurations: Configure all the end devices in the network with the appropriate IP address based on the calculations above.
- [ ] Configure port-security: Use sticky command to obtain MAC Address and Violation mode of the shutdown.

