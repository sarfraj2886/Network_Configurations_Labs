# Network_Configurations_Labs Portfolio
# Enterprise Network Architecture & Configuration Portfolio

Welcome to my Networking portfolio repository. This project serves as a comprehensive log of my hands-on experience in designing complex network topologies, optimizing routing paths, and implementing Cisco IOS CLI configurations.

The primary objective is to demonstrate my core technical skills in network engineering, infrastructure design, infrastructure security, and protocol deployment to technical interviewers and hiring managers.

---

##  Repository Structure & Network Protocols

This repository is structured into dedicated modules based on specific networking protocols, layout topologies, and security mechanisms:
## 1 Types of [Static Routes](./Static_Routing/) Implemented
* **Standard Static Route:** Configured for explicit network-to-network path communication.
* **Default Static Route (0.0.0.0/0):** Deployed as a Gateway of Last Resort for untracked Internet traffic destination paths.
* **Floating Static Route:** Configured with a higher Administrative Distance (AD = 130) to act as a redundant backup link for dynamic paths.
*

## 2 [Dynamic Routing](./Dynamic_Routing/) Protocols Portfolio

This section architecture covers the implementation, comparison, and analysis of various Dynamic Routing Protocols used to automate network topology discovery.

---

##  Interior Gateway Protocols

### 1. Distance Vector Protocols
* **RIP [Routing Information Protocol](./RIP/):** Deployed classless routing updates using hop count (Max 15) as the metric, suitable for smaller networks.

### 2. Hybrid / Advanced Distance Vector
* **EIGRP [Enhanced Interior Gateway Routing Protocol](./EIGRP/):** Configured Cisco's hybrid protocol utilizing the DUAL algorithm for fast convergence based on bandwidth and delay.

### 3. Link-State Protocols
* **OSPF [Open Shortest Path First](./OSPF/):** Implemented link-state routing using the Dijkstra SPF algorithm across hierarchical areas (Area 0) for large enterprise scalability.
* **IS-IS (Intermediate System to Intermediate System):** Analyzed provider-grade link-state routing operating directly over Layer 2.

### 4. Path Vector (Exterior Gateway Protocol)
* **BGP [Border Gateway Protocol](./BGP/):** Configured exterior routing boundaries to connect distinct Autonomous Systems (AS) across internet-scale architectures.

---

###  2. Enterprise Switching & Infrastructure
* **[VLAN and Trunking](./VLAN_and_Trunking/):** Local Area Network (LAN) segmentation into logical broadcast domains and multi-switch trunking configurations.
* **[VTP Configuration](./VTP_Configuration/):** VLAN Trunking Protocol deployment in Server, Client, and Transparent modes for automated database synchronization.
* **[Spanning Tree Protocol](./Spanning_Tree_Protocol/):** Layer 2 loop detection and avoidance operations to maintain redundant, loop-free network links.
* **[DNS & Web Server Administration](./DNS_and_Web_Server/):** Active Domain Name System mapping and local web server daemons hosting within a CentOS environment.

###  3. Network Security & Address Translation
* **[Access Control Lists (ACL)](./Access_Control_Lists_ACL/):** Standard and Extended ACL traffic filtering to permit or deny packets based on Source/Destination IPs and specific application ports (e.g., Port 80/443).
* **[NAT Configurations](./NAT_Configurations/):** Implementation of Static NAT, Dynamic NAT, and NAT Overload (PAT) to securely map private IP addresses to global public routable IPs.

---

##  Network Simulation Frameworks Used
All architectures and topologies documented here were built, designed, and tested using:
* **Cisco Packet Tracer** 
---

---

##  Disclaimer --   Educational Purpose 

The materials, configurations, and walkthroughs documented in this repository are created strictly for **educational and learning purposes only**. 

* **Controlled Environment:** All dynamic routing configurations, network topologies, and security practicals were built and tested inside safe simulation software (like Cisco Packet Tracer/GNS3) and isolated local virtual labs.
* **Academic Integrity:** The primary goal of this project is to log my academic progress and demonstrate my practical understanding of networking and cybersecurity architectures for career development.
3. **Verification Logs:** Output validation screenshots of commands like `show ip route`, `show ip protocols`, `show ip nat translations`, and successful `ping` confirmations.
4.
