# Hack The Box Notes: Fawn

## Machine Type
Linux

## Difficulty
Very Easy

## Goal
Learn about FTP services and anonymous login access.

---

# What I Practiced

- FTP enumeration
- Service scanning
- Anonymous login testing
- Basic networking concepts

---

# Commands Used

## Scan Open Ports

```bash
nmap -sV target-ip
```

Used to identify open services.

---

## Connect to FTP

```bash
ftp target-ip
```

Used to connect to the FTP service.

---

## Anonymous Login

Username:
```text
anonymous
```

Password:
```text
anonymous
```

---

# What I Learned

- FTP can allow anonymous access
- Misconfigured services create security risks
- Enumeration is important during investigations

---

# Skills Practiced

- Linux
- FTP
- Networking
- Enumeration
- Nmap
- Cybersecurity basics
