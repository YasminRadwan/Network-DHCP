# DHCP Configuration & Security – Cisco Packet Tracer

## Overview
This project demonstrates the configuration of DHCP services and DHCP security
mechanisms on Cisco devices. It covers DHCP server configuration on routers, as well
as protection against DHCP spoofing attacks using DHCP Snooping.

The lab focuses on secure and controlled IP address assignment within enterprise
networks.

---

## Tools & Technologies
- Cisco Packet Tracer
- Cisco IOS
- DHCP Server (Router-based)
- DHCP Snooping
- DHCP Spoofing Protection
- VLANs
- TCP/IP

---

## Configuration Summary
The configuration includes:

### Router DHCP Configuration
- Enabling DHCP service on the router
- Creating DHCP pools
- Defining network, default gateway, and DNS
- Excluding reserved IP addresses
- Assigning DHCP pools to VLANs

### DHCP Security (DHCP Snooping)
- Enabling DHCP Snooping globally
- Enabling DHCP Snooping per VLAN
- Configuring trusted and untrusted interfaces
- Preventing rogue DHCP servers (DHCP Spoofing)
- Binding IP-to-MAC addresses dynamically

---

## Key Concepts Covered
- Dynamic IP address allocation using DHCP
- Router-based DHCP server configuration
- DHCP Spoofing attacks and mitigation
- Trusted vs Untrusted ports
- DHCP Snooping binding table
- Network security at Layer 2

---

## Verification
Use the following commands to verify configurations:

- `show ip dhcp pool` – Verify DHCP pool configuration  
- `show ip dhcp binding` – Check assigned IP addresses  
- `show ip dhcp snooping` – Verify DHCP Snooping status  
- `show ip dhcp snooping binding` – View IP-MAC bindings  
- `show running-config` – Review full device configuration  
- `ping <destination_ip>` – Test client connectivity

---

## Files Included
- `DHCP_Security_Lab.pkt` – Packet Tracer file  
- `config.txt` – Full configuration exported from devices  
- `README.md` – This documentation

---

## How to Use
1. Open the `.pkt` file in Cisco Packet Tracer  
2. Review DHCP pool configuration on the router  
3. Review DHCP Snooping configuration on the switch  
4. Verify trusted and untrusted ports  
5. Test IP assignment and ensure rogue DHCP traffic is blocked

---

## Author
**Yasmin Radwan**  
Networking & Security Trainee  
CCNA Certified
