# Project1
# Design and Implement a small company network
Company has three floors in the first floor there are three departments (Reception, store and 
Logistics), in the second floor (IT, Finance and Admin). And in third floor (HR and Sales) 
 1. There should be three routers connecting each floor. 
 2. Each floor is expected to have one switch (placed in the respective floor) 
 3.  Each floor is expected to have WIFI network connected to laptop and phones. 
 4. Each department is expected to have a printer 
 5. Each department is expected to have be in different VLAN with following details: 
 First Floor: 
 Logistic - VLAN 10, Network of 192.168.10.0/24 
 Reception-VLAN 20, Network of 192.168.20.0/24 
 Store - VLAN 30, Network of 192.168.30.0/24 
 Second Floor: 
 Admin - VLAN 40, Network of 192.168.40.0/24 
 IT - VLAN 50, Network of 192.168.50.0/24 
 Finance - VLAN 60, Network of 192.168.60.0/24 
 Third Floor: 
 HR - VLAN 70, Network of 192.168.70.0/24 
 Sales - VLAN 80 Network of 192.168.80.0/24 
 6. Use OSPF as the routing protocol to advertise routes. 
 7. All devices in the Network are expected to obtain IP address dynamically with their respective router configured as the DHCP server. 
 8. All the devices in the network are expected to communicate with each other. 
 9. Configure SSH in all the routers and Switches for remote access. 
 10. In IT department we can Install one PC to access all router and switches with ssh.

# Design of the small company network topology
<img width="1919" height="1919" alt="Screenshot 2025-12-25 003055" src="https://github.com/user-attachments/assets/ced293c7-e3c5-47b0-81ec-e1e6609d620d" />
