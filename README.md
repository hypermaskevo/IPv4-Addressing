# Cisco Packet Tracer Lab - IPv4 Addressing

## Description
This lab is a network simulation created in **Cisco Packet Tracer**, focusing on configuring IPv4 addresses on network devices and verifying connectivity. The topology includes:

### Devices Used:
- **Cisco 2911 Router** (R1)
- **Cisco 2960 Switches** (SW1, SW2, SW3)
- **PCs** (PC1, PC2, PC3)

### Network Structure:
- **Three subnetworks with assigned IP addresses:**
  - **15.0.0.0/8** (PC1 and SW1)
  - **182.98.0.0/16** (PC2 and SW2)
  - **201.191.20.0/24** (PC3 and SW3)
- **Router interfaces configured to connect all subnets**

## Objectives
- Configure the **hostname** of R1.
- Use `show` commands to check **interfaces, IP addresses, and status**.
- Assign and configure the **correct IPv4 addresses** on R1’s interfaces.
- Enable the interfaces and set **interface descriptions**.
- Verify interface status using `show` commands.
- Check the **running configuration** and save it.
- Assign **IP addresses** to PC1, PC2, and PC3.
- Test network connectivity using **ping** between PCs.

## Setup Instructions
1. Open the **.pkt** file in Cisco Packet Tracer.
2. Configure the **hostname** of Router R1.
3. Use `show ip interface brief` to check the interface status.
4. Assign the correct **IPv4 addresses** to R1’s interfaces.
5. Use `no shutdown` to enable each interface.
6. Verify the interface configuration using `show ip interface brief` again.
7. Check the running configuration with `show running-config`, then save it.
8. Configure the correct **IP addresses on PC1, PC2, and PC3**.
9. Test connectivity by **pinging PC2 and PC3 from PC1**.

## Screenshot
![IPv4 Addr](https://github.com/user-attachments/assets/4f0a1ca1-e7f6-4fe4-83b5-0e3739911a43)


## Notes
- Ensure that each PC’s **gateway is set correctly**.
- If pings fail, check **subnet masks and cable connections**.

## Author
Created for educational purposes in **Cisco Networking Labs**.

