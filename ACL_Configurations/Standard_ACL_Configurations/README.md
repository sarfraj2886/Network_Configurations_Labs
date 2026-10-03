# Standard ACL – Cisco Packet Tracer

## Overview

Configured and tested a **Standard Access Control List (ACL)** in Cisco Packet Tracer to control network traffic based on **source IPv4 addresses**.

## Key Tasks

* Configured numbered Standard ACL using `permit` and `deny`.
* Blocked traffic from a specific source IP while allowing other hosts.
* Applied ACL to a router interface using `ip access-group`.
* Verified ACL using `show access-lists` and `show running-config`.
* Tested traffic filtering using `ping`.

## Example Configuration

```bash
access-list 10 deny host 192.168.1.10
access-list 10 permit any

interface g0/0/0
ip access-group 10 in
```

## Skills Demonstrated

**Cisco Packet Tracer | IPv4 | Standard ACL | Source IP Filtering | Router Configuration | Network Troubleshooting**

## Image 
<img width="640" height="361" alt="Screenshot 2026-10-03 094007" src="https://github.com/user-attachments/assets/835cd6f3-5e38-4984-a40f-440c48f54277" />


Successfully implemented and verified **source-based traffic filtering** using Standard ACL.

