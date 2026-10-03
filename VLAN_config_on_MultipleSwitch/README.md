# VLAN Across Multiple Switches – Cisco Packet Tracer

## Overview

Configured and tested **VLANs across multiple switches** in Cisco Packet Tracer to provide logical network segmentation and communication between devices within the same VLAN.

## Key Tasks

* Created VLANs on multiple switches.
* Assigned access ports to appropriate VLANs.
* Configured **802.1Q trunk links** between switches.
* Allowed required VLANs across trunk connections.
* Verified VLAN membership and trunk status.
* Tested communication between devices in the same VLAN across different switches.

## Example Configuration

```bash
vlan 10
 name IT

interface fa0/1
 switchport mode access
 switchport access vlan 10

interface fa0/24
 switchport mode trunk
 switchport trunk allowed vlan 10
```

## Verification

```bash
show vlan brief
show interfaces trunk
show interfaces switchport
```

## Skills Demonstrated

**Cisco Packet Tracer | VLAN | Multi-Switch Networking | 802.1Q Trunking | Access Ports | VLAN Segmentation | Switch Configuration | Troubleshooting**

## Image
<img width="864" height="393" alt="Screenshot 2026-10-03 121624" src="https://github.com/user-attachments/assets/0b25f311-8baa-49be-bc7a-0c2982470f14" />


Successfully implemented **VLAN segmentation across multiple switches** and verified same-VLAN connectivity through trunk links.

