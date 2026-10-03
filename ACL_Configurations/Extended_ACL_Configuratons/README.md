# Extended ACL – Cisco Packet Tracer

## Overview

Configured and tested an **Extended Access Control List (ACL)** in Cisco Packet Tracer to control traffic based on **source IP, destination IP, protocol, and port number**.

## Key Tasks

* Configured Extended ACL using `permit` and `deny`.
* Restricted specific traffic between source and destination networks.
* Applied protocol and port-based filtering.
* Applied ACL to a router interface using `ip access-group`.
* Verified ACL using `show access-lists` and `show running-config`.
* Tested traffic filtering using `ping` and application-specific traffic.

## Example Configuration

```bash<img width="261" height="369" alt="Screenshot 2026-10-03 112846" src="https://github.com/user-attachments/assets/bf6dae59-419d-4538-940a-abbf02522781" />

access-list 100 deny tcp host 192.168.1.10 host 192.168.2.10 eq 80
access-list 100 permit ip any any

interface g0/0
ip access-group 100 in
```

## Skills Demonstrated

**Cisco Packet Tracer | Extended ACL | IPv4 | TCP/UDP Filtering | Port-Based Filtering | Router Configuration | Network Troubleshooting**

## Image
<img width="261" height="369" alt="Screenshot 2026-10-03 112846" src="https://github.com/user-attachments/assets/0601172b-42d6-44c9-8525-89f0a95aeb39" />




Successfully implemented and verified **granular traffic filtering** using Extended ACL.

