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

```bash
access-list 100 deny tcp host 192.168.1.10 host 192.168.2.10 eq 80
access-list 100 permit ip any any

interface g0/0
ip access-group 100 in
```

## Skills Demonstrated

**Cisco Packet Tracer | Extended ACL | IPv4 | TCP/UDP Filtering | Port-Based Filtering | Router Configuration | Network Troubleshooting**

## image 
<img width="269" height="379" alt="Screenshot 2026-10-03 113716" src="https://github.com/user-attachments/assets/eb928c01-74dd-4af3-9560-1f19c0e066a2" />


Successfully implemented and verified **granular traffic filtering** using Extended ACL.

