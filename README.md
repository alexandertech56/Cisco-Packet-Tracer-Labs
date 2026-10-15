# Cisco-Packet-Tracer-Labs

Beginner-friendly Cisco Packet Tracer labs for cybersecurity and networking. 

## Lab 1: Build Your First Network

A hands-on lab designed for a 1 to 1.25 hour session. You will cable a router, two switches, three PCs, and a server, assign IP addresses, configure the router through the CLI, test connectivity with ping, host a web page, and watch packets move in Simulation mode.

### Topology

```
 PC1 ---+                                +--- PC3
        +--- S1 ---- R1 (2 ports) ---- S2 +
 PC2 ---+                                +--- Server

   LAN A: 192.168.10.0/24         LAN B: 192.168.20.0/24
```

### What students learn

- Network cables and which one to use where
- What switches, routers, and servers do
- IP addressing, subnet masks, and default gateways
- Basic router configuration in the CLI
- Testing a network with ping
- Hosting and loading a web page
- How packets travel (ARP and ICMP) in Simulation mode
- Why `enable secret` is safer than `enable password`

### What's included

| File | Description |
|---|---|
| `Packet_Tracer_Lab_Student_Handout.docx` | Student handout with steps, commands, and fill-in questions |

### Requirements

- Cisco Packet Tracer (free through Cisco Networking Academy)
- One computer
- No prior networking experience needed
