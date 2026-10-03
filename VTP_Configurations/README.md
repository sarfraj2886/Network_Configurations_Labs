# VTP – Cisco Packet Tracer

## Overview

Configured and tested **VTP (VLAN Trunking Protocol)** in Cisco Packet Tracer to understand centralized VLAN management and VLAN propagation across multiple switches.

## VTP Modes Practiced

* **Server Mode** – Creates, modifies, and manages VLANs.
* **Client Mode** – Receives and synchronizes VLAN information from the VTP Server.
* **Transparent Mode** – Maintains its own VLAN database and does not synchronize VLANs with the VTP Server.

## Key Tasks

* Configured VTP Server, Client, and Transparent modes.
* Configured VTP domain and password.
* Created and verified VLANs.
* Configured trunk links between switches.
* Verified VLAN synchronization and VTP status.

## Example Configuration

### VTP Server

```bash
vtp domain CAMPUS
vtp mode server
vtp password cisco123

vlan 10
name IT
```

### VTP Client

```bash
vtp domain CAMPUS
vtp mode client
vtp password cisco123
```

### VTP Transparent

```bash
vtp domain CAMPUS
vtp mode transparent
vtp password cisco123
```

## Verification

```bash
show vtp status
show vlan brief
show interfaces trunk
```

## Skills Demonstrated

**Cisco Packet Tracer | VTP | Server/Client/Transparent Modes | VLAN Management | Trunking | Switch Configuration | Network Troubleshooting**

## Image
<img width="1027" height="381" alt="image" src="https://github.com/user-attachments/assets/3b962a67-9fc4-4471-b9d9-24fdaf3cd672" />

Successfully configured and tested **VTP Server, Client, and Transparent modes** and verified VLAN behavior across interconnected switches.

