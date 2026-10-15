## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 15.10.2026		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1918" height="1141" alt="image" src="https://github.com/user-attachments/assets/ea4c2035-d93e-487f-b2af-0dc979dee15b" />


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

<img width="1918" height="1132" alt="image" src="https://github.com/user-attachments/assets/619ab17f-5318-457d-9dcc-9805777d11cf" />
<img width="1918" height="1137" alt="image" src="https://github.com/user-attachments/assets/e70b7436-ca46-4888-ae46-d77de4ed65f0" />
<img width="1918" height="1140" alt="image" src="https://github.com/user-attachments/assets/30cdc584-bff8-4f46-9a4a-156187e05aa6" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
