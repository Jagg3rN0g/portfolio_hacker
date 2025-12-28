---
layout: ../../layouts/PostLayout.astro
title: "Bypassing WAF via HTTP Request Smuggling"
date: "2024-02-28"
platform: "Research"
---

In this article, I discuss how to bypass a Web Application Firewall (WAF) using HTTP Request Smuggling techniques.

## The Theory

HTTP Request Smuggling occurs when the front-end and back-end servers interpret the boundary of an HTTP request differently.

## The Lab

Setting up a vulnerable environment with HAProxy and Gunicorn.

```python
# Exploit script snippet
def smuggler():
    payload = "TRANSFER-ENCODING: chunked"
    ...
```

## Results

We successfully bypassed the WAF rules and accessed the internal admin panel.
