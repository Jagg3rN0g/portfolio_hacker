---
layout: ../../layouts/PostLayout.astro
title: "HackTheBox - Retired Machine Walkthrough"
date: "2024-03-15"
platform: "HackTheBox"
---

This is a walkthrough for a retired HackTheBox machine.

## Reconnaissance

Starting with Nmap scan:

```bash
nmap -sC -sV -oA nmap/initial 10.10.10.X
```

We found port 22 (SSH) and 80 (HTTP) open.

## Enumeration

Checking the web server, we found a vulnerable CMS.

> "Enumeration is the key."

## Exploitation

Using the known vulnerability CVE-202X-XXXX, we managed to get a reverse shell.

## Privilege Escalation

Enumerating SUID binaries...
