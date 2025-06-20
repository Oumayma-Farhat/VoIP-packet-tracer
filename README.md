# 📞 VoIP Telephony Networking Project (Cisco Packet Tracer)

This project simulates a small enterprise VoIP network using Cisco Packet Tracer. It demonstrates key networking concepts such as VLANs, inter-VLAN routing, DHCP, OSPF, and VoIP configuration.

---

## ⚙️ Configuration Steps

1. *Network Design*  
   Design the network topology using routers, switches, PCs, IP phones, and servers. 

2. *Basic Device Configuration*  
   - Set hostnames.
   - Enable SSH and secure access on routers.
   - Set passwords for console and VTY lines.

3. *VLAN Configuration*  
   - Create VLANs for departments (e.g., Sales, Voice).
   - Assign access and trunk ports on the switches.

4. *IP Addressing and Subnetting*  
   - Subnet the IP address space according to network design.
   - Assign IPs to interfaces and devices.

5. *Static IP Assignment for Servers and Phones*  
   - Assign static IP addresses to critical devices such as servers and IP phones.

6. *DHCP Configuration*  
   - Configure DHCP on routers to serve IPs to end-user devices.

7. *Voice VLAN and DHCP for IP Phones*  
   - Create a dedicated Voice VLAN.
   - Configure a DHCP pool for IP phones.

8. *Inter-VLAN Routing and DHCP Helper Addresses*  
   - Enable routing between VLANs on routers.
   - Use the ip helper-address command to forward DHCP requests.

9. *OSPF Routing Protocol Configuration*  
   - Configure OSPF on all routers to enable dynamic routing.

10. *VoIP Services Setup*  
    - Enable telephony services on routers.
    - Set up ePhones and ePhone-dns.

11. *Dial-Peer Configuration*  
    - Define dial-peer voice configurations for call routing between sites.

---

## 📁 Files Included

- .pkt file: Packet Tracer project file
- README.md: Project documentation and configuration steps

---

## 🧠 Concepts Covered

- VLANs and Trunking
- DHCP Server
- OSPF Routing
- Inter-VLAN Routing
- Voice VLAN and VoIP Configuration
- Dial-Peer and Telephony Services
