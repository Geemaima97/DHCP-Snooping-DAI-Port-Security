# DHCP Snooping + DAI + Port Security

## Objective
Secure the access layer by enabling DHCP Snooping, Dynamic ARP Inspection (DAI), and port security. Prevent rogue DHCP servers and ARP spoofing.

### Skills Learned
- Configuring DHCP Snooping on VLANs and trusted uplinks.
- Enabling DAI to prevent ARP spoofing.
- Configuring port security with MAC address limits and violation actions.
- Monitoring DHCP bindings and DAI counters.

### Tools Used
- Cisco access layer switches.
- Packet Tracer for lab simulation.
- Commands: `show ip dhcp snooping binding`, `show ip arp inspection statistics`, `show port-security interface`.

## Steps
1. Enable DHCP Snooping globally and for VLAN 10.
2. Set uplink port to R1 as trusted.
3. Enable DAI for VLAN 10.
4. Configure port security on access ports (max 2 MAC addresses, shutdown on violation).
5. Verify DHCP bindings, DAI statistics, and port security using show commands.

## Network topology
<img width="285" height="452" alt="image" src="https://github.com/user-attachments/assets/8ab63c5d-3798-492c-b4d0-041b03e0e27c" />
