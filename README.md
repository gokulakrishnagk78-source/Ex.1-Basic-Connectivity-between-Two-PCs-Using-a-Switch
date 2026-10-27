## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 27.10.26		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

Insert the network topology from Packet Tracer (Screenshot or drawing)

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)
<img width="1494" height="730" alt="image" src="https://github.com/user-attachments/assets/8883636d-3e72-4a13-9ece-80668fb61cac" />
<img width="1528" height="765" alt="image" src="https://github.com/user-attachments/assets/61e6eba3-4a29-447f-b37f-55b358e377f7" />
<img width="1503" height="642" alt="image" src="https://github.com/user-attachments/assets/54f7a27f-c3e6-45ff-a1be-042a0299b4f5" />

<img width="1375" height="751" alt="image" src="https://github.com/user-attachments/assets/82309a5f-d244-4f0b-b266-af14e5cec451" />

Insert screenshots showing ping success, configuration, or simulation results.
________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
