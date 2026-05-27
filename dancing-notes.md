# Hack The Box Notes: Dancing

## Machine Type
Windows

## Difficulty
Very Easy

## Goal
Practice SMB enumeration and shared folder access.

---

# What I Practiced

- SMB enumeration
- Windows networking basics
- Shared folder discovery
- Remote access concepts

---

# Commands Used

## Scan Target

```bash
nmap -sV target-ip
```

Used to identify SMB services.

---

## SMB Enumeration

```bash
smbclient -L //target-ip
```

Lists available SMB shares.

---

## Connect to Share

```bash
smbclient //target-ip/share-name
```

Connects to a shared folder.

---
# Hack The Box Notes: Dancing

## Commands Used

### Scan Open Ports

```bash
nmap -sV target-ip
```

### What It Does
Scans the target machine for open services.

### Why It Matters
Helps identify SMB services used for Windows file sharing.

---

## Enumerate SMB Shares

```bash
smbclient -L //target-ip
```

### What It Does
Lists available SMB shared folders on the target machine.

### Breakdown
- `smbclient` = SMB interaction tool
- `-L` = list shares

### Why It Matters
SMB shares can expose files, credentials, or sensitive information.

---

## Connect to SMB Share

```bash
smbclient //target-ip/share-name
```

### What It Does
Connects to a specific shared folder.

### Why It Matters
Allows access to files stored in SMB shares.

---

## List Files in Share

```bash
ls
```

### What It Does
Displays files inside the SMB share.

### Why It Matters
Used to identify important or exposed files.

---

# Skills Practiced

- Windows networking
- SMB enumeration
- Networking
- Nmap
- Command line
- File share analysis
# What I Learned

- SMB is commonly used on Windows systems
- Shared folders can expose sensitive files
- Enumeration helps identify weak configurations

---

# Skills Practiced

- Windows
- SMB
- Networking
- Enumeration
- Nmap
- Command line
