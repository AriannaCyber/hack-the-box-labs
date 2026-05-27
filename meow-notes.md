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
