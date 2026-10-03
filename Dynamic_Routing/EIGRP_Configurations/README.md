# EIGRP Routing – Cisco Packet Tracer

## Overview

Configured and tested **EIGRP (Enhanced Interior Gateway Routing Protocol)** in Cisco Packet Tracer to establish dynamic routing between multiple networks.

## Key Tasks

* Configured EIGRP on multiple routers.
* Configured EIGRP using an **AS number**.
* Advertised connected networks.
* Verified EIGRP neighbor relationships and learned routes.
* Tested end-to-end connectivity using `ping`.

## Example Configuration

```bash
router eigrp 100
 no auto-summary
 network 192.168.1.0
 network 10.0.0.0
```

## Verification

```bash
show ip eigrp neighbors
show ip route
show ip protocols
ping <destination-IP>
```

## Skills Demonstrated

**Cisco Packet Tracer | EIGRP | Dynamic Routing | IPv4 | Neighbor Adjacency | Routing Tables | Network Troubleshooting**

## Image
<img width="840" height="383" alt="Screenshot 2026-10-03 115429" src="https://github.com/user-attachments/assets/dab49fd2-3d4b-4137-bec6-37633acea508" />


Successfully established **dynamic routing and end-to-end connectivity using EIGRP**.

