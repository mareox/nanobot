# User Profile

## Basic Information

- **Name**: MareOX
- **Timezone**: America/Los_Angeles (Pacific Time)
- **Language**: English

## Preferences

### Communication Style

- Technical and direct
- Prefers concise answers with relevant details
- Appreciates dry humor

### Response Length

- Brief for simple questions
- Detailed for infrastructure decisions or troubleshooting
- Always include relevant IPs, hostnames, and commands

### Technical Level

- Expert — senior infrastructure engineer
- Familiar with: Proxmox, Docker, networking, Linux, Python, DNS, firewalls
- Doesn't need hand-holding on basic concepts

## Work Context

- **Primary Role**: Homelab owner and infrastructure engineer
- **Main Projects**: MareoXLAN homelab on Proxmox VE cluster
- **Tools**: Claude Code, n8n, Semaphore (Ansible), Docker, SSH
- **Workstation**: MacBook Pro M4 Max (mbp4x), WSL2 on Windows

## Infrastructure Overview

- **Proxmox Cluster**: 4 nodes (pve-mini2/3/5/6)
- **Network**: UniFi managed, VLANs 10/20/30/40/50
- **DNS**: Pi-hole HA (VIP 192.168.10.110)
- **Reverse Proxy**: Caddy HA (VIP 192.168.30.161)
- **Logging**: Graylog (192.168.30.240)
- **Automation**: n8n (192.168.30.62), Semaphore (192.168.30.66)
- **Firewall**: PAN-OS mx-fw (10.254.254.99 mgmt)
- **NAS**: Synology DS920+ (192.168.10.100), DS719+ (192.168.10.102)

## Topics of Interest

- Infrastructure automation and monitoring
- Network security and firewall management
- Self-hosted services and Docker orchestration
- Trading and financial data tracking

## Special Instructions

- Always use Pacific Time for any time references
- When suggesting infrastructure changes, reference the homelab conventions
- IP scheme: VLAN prefix + last octet = VM ID (e.g., VLAN 30 + .196 = VMID 30196)
- Standard servers use even IP numbers; HA nodes use odd numbers around an even VIP
