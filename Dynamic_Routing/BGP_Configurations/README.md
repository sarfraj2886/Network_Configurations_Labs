# BGP Routing – Cisco Packet Tracer

## Overview

Configured and tested **BGP (Border Gateway Protocol)** in Cisco Packet Tracer to exchange routing information between different Autonomous Systems (AS).

## Key Tasks

* Configured **eBGP** between multiple routers.
* Configured BGP using different **AS numbers**.
* Established and verified BGP neighbor relationships.
* Advertised networks using BGP.
* Verified BGP-learned routes and routing tables.
* Tested end-to-end connectivity using `ping`.
* inside RIP and EIGRP.

## Example Configuration

```bash
router bgp 65001
 neighbor 10.0.0.2 remote-as 65002
 network 192.168.1.0 mask 255.255.255.0
```

## Verification

```bash
show ip bgp
show ip bgp summary
show ip route
ping <destination-IP>
```

## Skills Demonstrated

**Cisco Packet Tracer | BGP | eBGP | Autonomous Systems | Dynamic Routing | BGP Neighbors | Routing Tables | Network Troubleshooting**

## Image
<img width="1070" height="390" alt="Screenshot 2026-10-03 120226" src="https://github.com/user-attachments/assets/5595c7f1-ecbf-4fc3-a84f-ba998d0b6d19" />


Successfully established **BGP neighbor adjacency and route exchange between different Autonomous Systems**.

