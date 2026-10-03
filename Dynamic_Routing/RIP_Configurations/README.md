# RIP Routing – Cisco Packet Tracer

## Overview

Configured and tested **RIP (Routing Information Protocol)** in Cisco Packet Tracer to enable dynamic routing between multiple networks.

## Key Tasks

* Configured **RIPv2** on multiple routers.
* Advertised connected networks using `network` commands.
* Disabled automatic summarization using `no auto-summary`.
* Verified routing tables and learned routes.
* Tested end-to-end connectivity using `ping`.

## Example Configuration

```bash
router rip
 version 2
 no auto-summary
 network 192.168.1.0
 network 10.0.0.0
```

## Verification

```bash
show ip route
show ip protocols
ping <destination-IP>
```

## Skills Demonstrated

**Cisco Packet Tracer | RIP/RIPv2 | Dynamic Routing | IPv4 | Routing Tables | Network Troubleshooting**

## Image 
<img width="802" height="402" alt="Screenshot 2026-10-03 114516" src="https://github.com/user-attachments/assets/7808bf4a-b7af-4d39-8e69-5896ef7b1c8a" />


Successfully implemented **dynamic routing using RIPv2** and established communication between different networks.

