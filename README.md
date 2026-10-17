## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 	17/09/2026	

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1920" height="1080" alt="Screenshot 2026-10-17 143715" src="https://github.com/user-attachments/assets/d15d91de-37ff-4b3d-ba03-8f5d183c532f" />


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

<img width="1920" height="1080" alt="Screenshot 2026-10-17 145105" src="https://github.com/user-attachments/assets/f863b606-a201-432f-9e6a-b050744f0553" />

<img width="1920" height="1080" alt="Screenshot 2026-10-17 171333" src="https://github.com/user-attachments/assets/8aeab0e8-2fdf-455d-a8ba-03d48188e9c6" />

<img width="1920" height="1080" alt="Screenshot 2026-10-17 145140" src="https://github.com/user-attachments/assets/7a2be703-0175-4aab-b761-636b47212617" />


<img width="1920" height="1080" alt="Screenshot 2026-10-17 144650" src="https://github.com/user-attachments/assets/5a402169-b291-4ad7-b52b-05a259d4e783" />

<img width="1920" height="1080" alt="Screenshot 2026-10-17 143715" src="https://github.com/user-attachments/assets/41436df8-cfda-480a-90b6-fef72c8becc1" />

<img width="1920" height="1080" alt="Screenshot 2026-10-17 144028" src="https://github.com/user-attachments/assets/e4d7d047-ed8a-478c-914f-640004faef2e" />



________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
