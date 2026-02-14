# OSI-Model-Wireshark-Lab
Packet capture lab demonstrating OSI layers using Wireshark

## 🛡️ Project Overview

This lab demonstrates how network traffic flows across OSI layers through hands-on packet capture analysis. 
Using two Ubuntu virtual machines, I analyzed ARP resolution, ICMP reachability, TCP handshakes, and HTTP traffic 
to understand how security analysts observe normal network behavior before detecting anomalies.

## Lab Enviorment

- VMware Fusion
- Ubuntu Client & Server
- NAT Network
- Wireshark
- Python HTTP Server

## OSI Layer Analysis

### Layer 2 – ARP
Observed MAC resolution through broadcast ARP requests and replies.

### Layer 3 – ICMP
Verified network reachability using echo request and reply.

### Layer 4 – TCP
Captured SYN, SYN-ACK, ACK handshake.

### Layer 7 – HTTP
Analyzed GET requests from Python HTTP server.


## What I Learned

- How devices establish identity using MAC addresses
- How ICMP verifies connectivity
- How TCP establishes reliable sessions
- How application traffic depends on lower OSI layers



