# Hack The Box Notes: Meow

## Machine Type
Linux

## Difficulty
Very Easy

## Goal
Practice basic enumeration and remote service access.

---

# What I Practiced

- Connecting to a target machine
- Basic Linux enumeration
- Understanding open ports
- Using terminal commands
- Reading service banners
- Learning remote access basics

---

# Commands Used

## Ping Target

```bash
ping target-ip
```

Checks if the target machine is reachable.

---

## Scan Open Ports

```bash
nmap -sV target-ip
```

- `-sV` detects service versions
- Used to identify running services

---

## Connect Using Telnet

```bash
telnet target-ip
```

Used to connect to the Telnet service.

---
# Hack The Box Notes: Meow

## Commands Used

### Check Connectivity

```bash
ping target-ip
```

### What It Does
Sends packets to the target machine to confirm it is online and reachable.

### Why It Matters
Helps verify network communication before scanning or connecting to services.

---

## Scan Open Ports

```bash
nmap -sV target-ip
```

### What It Does
Scans the target machine for open ports and identifies running services.

### Breakdown
- `nmap` = network scanning tool
- `-sV` = detects service versions

### Why It Matters
Enumeration starts by identifying open services attackers or analysts can investigate.

---

## Connect to Telnet

```bash
telnet target-ip
```

### What It Does
Connects to the Telnet service running on the machine.

### Why It Matters
Shows how insecure remote access services can expose systems.

---

# Skills Practiced

- Linux
- Networking
- Enumeration
- Nmap
- Telnet
- Command line

# What I Learned

- Why open ports matter
- Basic service enumeration
- How Telnet works
- How attackers gather information from systems

---

# Skills Practiced

- Linux
- Networking
- Enumeration
- Nmap
- Terminal usage
- Cybersecurity fundamentals
