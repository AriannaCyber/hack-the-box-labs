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
