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
