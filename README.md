# NETWORKWALKS-TARUN-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
Week 1 Kali Linux ARM64 lab setup on macOS
# Week 1 Cybersecurity Lab Setup

Kali Linux ARM64 lab configured in Oracle VirtualBox on macOS.

## Configuration

| Item | Value |
|---|---|
| NAT Network | `NatNetwork` |
| Network range | `10.0.0.0/24` |
| Kali IP | `10.0.0.2/24` |
| Gateway | `10.0.0.1` |
| Snapshot | `Week 1 Baseline` |

## Completed

- Created a custom NAT Network with DHCP enabled.
- Connected Kali Linux to `NatNetwork`.
- Configured and verified static IP address `10.0.0.2/24`.
- Verified gateway and internet access with 0% packet loss.
- Enabled clipboard, drag-and-drop, and shared folder integration.
- Created a baseline snapshot for recovery.

## Evidence

![NAT Network](screenshots/01-nat-network.png)

![Kali Network Adapter](screenshots/02-kali-vm-network.png)

![Connectivity Checks](screenshots/03-connectivity-checks.png)

![Week 1 Baseline](screenshots/04-week-1-baseline.png)
