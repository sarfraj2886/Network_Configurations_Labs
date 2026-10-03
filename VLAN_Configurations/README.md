# VLAN – Cisco Packet Tracer

## Overview

Configured and tested **VLANs (Virtual Local Area Networks)** in Cisco Packet Tracer to logically segment a network and isolate broadcast domains.

## Key Tasks

* Created and configured VLANs.
* Assigned switch ports to specific VLANs.
* Configured access ports.
* Verified VLAN membership and port assignments.
* Tested communication between devices within the same VLAN.

## Example Configuration

```bash
vlan 10
 name IT

interface fa0/1
 switchport mode access
 switchport access vlan 10
```

## Verification

```bash
show vlan brief
show interfaces switchport
```

## Skills Demonstrated

**Cisco Packet Tracer | VLAN | Network Segmentation | Access Ports | Broadcast Domains | Switch Configuration | Network Troubleshooting**

## Image
<img width="680" height="402" alt="Screenshot 2026-10-03 121955" src="https://github.com/user-attachments/assets/1813fe33-bc3d-4bd8-871e-2559bfb8036e" />


Successfully implemented **VLAN-based network segmentation** and verified connectivity between devices within the same VLAN.

