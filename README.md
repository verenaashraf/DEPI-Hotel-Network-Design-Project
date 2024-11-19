# DEPI-Hotel-Network-Design-Project
# 🌟 AMAN Hotel Network Project 🌟

## 🏨 Overview  
I am thrilled to share my first network design project, **AMAN Hotel**, a four-floor hotel with two departments on each floor:  
- **Floor 1:** 🖥️ IT, 🛎️ Reception  
- **Floor 2:** 🧑‍💼 HR, 🏢 Management  
- **Floor 3:** 📈 Marketing, 💰 Sales  
- **Floor 4:** ✔️ Quality, 📊 Finance  

The project was designed using **Cisco Packet Tracer**, featuring a robust and scalable network infrastructure with routers, switches, PCs, laptops, and servers.

---

## 🔗 Key Technologies and Protocols  

### 🔧 Switching and LAN Technologies  
- **VLAN**: For network segmentation.  
- **VTP (VLAN Trunking Protocol)**: To centrally manage VLAN configurations.  
- **STP (Spanning Tree Protocol)**: Enhanced with RSTP and PortFast for loop prevention and rapid convergence.  
- **BPDU Guard**: To protect against BPDU-related attacks.  
- **LACP EtherChannel**: For link aggregation and redundancy.  

### 🌍 Routing  
- **OSPF**: Dynamic routing between network segments.  
- **Inter-VLAN Routing**: Using Layer 3 switches.  

### 🛡️ Backup and Redundancy  
- **HSRP**: Ensuring gateway redundancy.  

### 🖧 Services and Subnetting  
- **DHCP**: For dynamic IP allocation.  
- **Wireless Access Points**: Providing wireless connectivity.  
- **Remote Access**: Secured using SSH.  
- **VLSM Subnetting**: Optimized IP address allocation.  
- **PAT**: Port Address Translation for external access.

---

## 💾 Servers Configured  
- **FTP & TFTP**: For file and configuration backups.  
- **DNS**: Translating domain names into IP addresses.  
- **HTTPS**: For secure web communication.  
- **NTP**: Network time synchronization.  
- **Syslog**: Centralized log management.  
- **AAA Server**: For authentication, authorization, and accounting.

---

## 🔒 Security Measures  

### 📜 Access Control Lists (ACLs)  
- Mitigating **IP Spoofing** by blocking:  
  - Private IPs  
  - Loopback IPs  
  - Multicast IPs (Class D)  
  - Broadcast addresses  
- **ICMP Flood Prevention**: Allowing only echo replies from trusted networks.  
- ⏰ **Time-based ACLs**: Restricting services to working hours.

### 🔑 SSH Hardening  
- Using **RSA encryption** with a 1024-bit key.  
- Customizing retries and timeouts to deter brute force attacks.

### 🛠️ Server Security  
- **TACACS+** for access layer security.  
- **RADIUS** between core and distribution layers for performance and security.

### ⚙️ Layer 2 Security  
- **Port Security**: Preventing MAC address table overflow.  
- **DTP Manual Configuration**: To mitigate VLAN hopping attacks.  
- **DHCP Snooping**: Blocking DHCP starvation/spoofing.  
- **DAI (Dynamic ARP Inspection)**: Countering ARP attacks.  
- **CDP Disabled**: Preventing reconnaissance.

### 🔐 Routing Security  
- **OSPF MD5 Authentication**: Ensuring secure routing communications.

---

## ✨ Future Work  
- 🌍 Integrate more branches of the hotel.  
- 🔥 Use Firepower Firewall for advanced security.  
- 🚀 Implement **EIGRP** for routing.  
- 🛡️ Deploy **IPS** for intrusion prevention.  
