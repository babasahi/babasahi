---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
tags: ["tryhackme", "writeup"]
categories: ["writeups"]
summary: "One-line summary of what this writeup covers."
ShowToc: true
TocOpen: false
cover:
  image: ""
  alt: ""
  caption: ""
---

## Overview

| Field      | Value                                       |
| ---------- | ------------------------------------------- |
| Platform   | TryHackMe                                   |
| Room       | [room-name](https://tryhackme.com/room/...) |
| Difficulty | Medium                                      |
| Tags       | enumeration, web, privesc                   |

## Reconnaissance

### Nmap

```bash
nmap -sC -sV -oN nmap/initial 10.10.x.x
```

What I noticed:

### Web enumeration

## Initial foothold

### What I tried first (and why it failed)

### What worked

## Privilege escalation

## Lessons learned

- What new technique did I learn?
- What would I try first next time I see this pattern?
- What was the key insight?

## References
