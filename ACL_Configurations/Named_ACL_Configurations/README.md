# Named ACL – Cisco Packet Tracer

## Overview

Configured and tested **Named Access Control Lists (ACLs)** in Cisco Packet Tracer to manage network traffic using a descriptive ACL name instead of a numeric ACL ID.

## Key Tasks

* Configured Named Standard/Extended ACL.
* Used descriptive ACL names for easier identification and management.
* Configured `permit` and `deny` rules.
* Applied ACL to router interfaces using `ip access-group`.
* Verified configuration using `show access-lists` and `show running-config`.
* Tested traffic filtering using `ping` and network traffic.

## Example Configuration

```bash
ip access-list extended BLOCK_WEB
 deny tcp host 192.168.1.10 any eq 80
 permit ip any any

interface g0/0
 ip access-group BLOCK_WEB in
```

## Skills Demonstrated

**Cisco Packet Tracer | Named ACL | Standard & Extended ACL | IPv4 | TCP/UDP Filtering | Port-Based Filtering | Network Troubleshooting**

## Image 
<img width="269" height="379" alt="Screenshot 2026-10-03 113716" src="https://github.com/user-attachments/assets/e196ec02-2803-427b-be64-fb38aa4da055" />


Successfully implemented and verified **named, manageable traffic-filtering rules** using Named ACLs.
