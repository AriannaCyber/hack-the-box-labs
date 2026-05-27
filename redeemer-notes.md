# Hack The Box Notes: Redeemer

## Machine Type
Linux

## Difficulty
Very Easy

## Goal
Learn about Redis services and database enumeration.

---

# What I Practiced

- Redis enumeration
- Service identification
- Basic database interaction
- Command-line usage

---

# Commands Used

## Scan Target

```bash
nmap -sV target-ip
```

Used to identify open services.

---

## Connect to Redis

```bash
redis-cli -h target-ip
```

Used to connect to the Redis service.

---

## View Keys

```bash
keys *
```

Lists available keys in Redis.

---

## Get Key Value

```bash
get key-name
```

Retrieves stored values.

---
# Hack The Box Notes: Redeemer

## Commands Used

### Scan Open Ports

```bash
nmap -sV target-ip
```

### What It Does
Scans for open ports and identifies services.

### Why It Matters
Used to discover Redis running on the target system.

---

## Connect to Redis

```bash
redis-cli -h target-ip
```

### What It Does
Connects to the Redis database service.

### Breakdown
- `redis-cli` = Redis command-line tool
- `-h` = specifies target host

### Why It Matters
Allows interaction with the Redis database.

---

## View Database Keys

```bash
keys *
```

### What It Does
Lists all available keys stored in Redis.

### Why It Matters
Enumeration often involves identifying stored data or sensitive values.

---

## Retrieve Stored Values

```bash
get key-name
```

### What It Does
Retrieves the value associated with a Redis key.

### Why It Matters
Helps analysts understand exposed data inside databases.

---

# Skills Practiced

- Redis
- Linux
- Networking
- Enumeration
- Databases
- Cybersecurity fundamentals
# What I Learned

- Redis databases can expose sensitive information
- Open services create security risks
- Enumeration is critical during investigations

---

# Skills Practiced

- Linux
- Redis
- Networking
- Enumeration
- Databases
- Cybersecurity fundamentals
