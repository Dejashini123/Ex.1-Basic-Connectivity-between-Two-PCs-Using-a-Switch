## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 		

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
<img width="1918" height="1142" alt="Screenshot 2026-10-15 160655" src="https://github.com/user-attachments/assets/69cb3a61-f4f6-4f3d-9ec8-e3dedb95623d" />

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
<img width="1918" height="1163" alt="Screenshot 2026-10-15 160728" src="https://github.com/user-attachments/assets/8a60e3df-f95f-4898-aea0-fccd241deb1f" />
<img width="1918" height="1138" alt="Screenshot 2026-10-15 160741" src="https://github.com/user-attachments/assets/84b48230-34b4-429b-8c69-6d49a4b324e4" />
<img width="1918" height="1137" alt="Screenshot 2026-10-15 160756" src="https://github.com/user-attachments/assets/4553a15f-3cfb-459f-add9-70c937cadede" />
<img width="1918" height="1140" alt="Screenshot 2026-10-15 161159" src="https://github.com/user-attachments/assets/604fe0dc-3eb6-4e0c-bfdf-f1626f792907" />





Insert screenshots showing ping success, configuration, or simulation results.
________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
