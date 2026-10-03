# OSPF Routing – Cisco Packet Tracer

## Overview

Configured and tested **OSPF (Open Shortest Path First)** in Cisco Packet Tracer to establish dynamic routing between multiple networks.

## Key Tasks

* Configured OSPF on multiple routers.
* Configured **OSPF Process ID and Area 0**.
* Advertised connected networks.
* Established and verified OSPF neighbor adjacencies.
* Verified learned routes and routing tables.
* Tested end-to-end connectivity using `ping`.

## Example Configuration

```bash
router ospf 1
 network 192.168.1.0 0.0.0.255 area 0
 network 10.0.0.0 0.0.0.3 area 0
```

## Verification

```bash
show ip ospf neighbor
show ip route
show ip protocols
ping <destination-IP>
```

## Skills Demonstrated

**Cisco Packet Tracer | OSPF | Dynamic Routing | IPv4 | OSPF Neighbors | Area 0 | Routing Tables | Network Troubleshooting**

## Image
<img width="817" height="386" alt="Screenshot 2026-10-03 115831" src="https://github.com/user-attachments/assets/e8a33d77-3858-444f-b174-743d0b7e748a" />


Successfully established **dynamic routing and end-to-end connectivity using OSPF**.

