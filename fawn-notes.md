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

--# Hack The Box Notes: Fawn

## Commands Used

### Scan Open Ports

```bash
nmap -sV target-ip
```

### What It Does
Scans the machine for open ports and identifies services running on them.

### Why It Matters
Used during enumeration to identify accessible services like FTP.

---

## Connect to FTP

```bash
ftp target-ip
```

### What It Does
Connects to the FTP server on the target machine.

### Why It Matters
FTP is used for file transfers and may allow anonymous access if misconfigured.

---

## Anonymous Login

```text
Username: anonymous
Password: anonymous
```

### What It Does
Attempts to log into the FTP server without valid credentials.

### Why It Matters
Anonymous FTP access is a common security weakness.

---

## List Files

```bash
ls
```

### What It Does
Lists files and folders available on the FTP server.

### Why It Matters
Helps identify sensitive files or useful information during enumeration.

---

# Skills Practiced

- FTP
- Linux
- Networking
- Enumeration
- Nmap
- Cybersecurity fundamentals

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
