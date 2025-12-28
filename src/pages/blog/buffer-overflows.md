---
layout: ../../layouts/PostLayout.astro
title: "Understanding Buffer Overflows (OSCP Prep)"
date: "2023-12-05"
platform: "Blog"
---

My notes on preparing for the Buffer Overflow section of the OSCP exam.

## Stack Anatomy

Understanding EIP, ESP, and EBP registers.

## Fuzzing

Using a python script to crash the application and find the offset.

```python
buffer = "A" * 2000
```

## Bad Characters

Identifying bad characters that break the shellcode.

## Shellcode Generation

Using `msfvenom` to generate payload.
