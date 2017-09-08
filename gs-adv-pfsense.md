---
layout: page
title: pfSense Setup
permalink: /get-started/advanced/pfsense/
---

### DNS Servers

Before you begin, you will need to choose two DNS servers. You can either pick from [this list](https://servers.opennic.org/), or use these two:

* 198.251.90.143 (ModernTLD Anycast Server)
* 138.197.25.214 (ModernTLD New York Server)

*[More info](/infrastructure)*

### Setup Guide

1. Login to your pfSense interface. (Generally located at 192.168.1.1 or 10.0.0.1)
2. Navigate to System > General Setup
3. Add your chosen DNS IP addresses to DNS Server Settings in General Setup:
![](https://i.imgur.com/aNSJyh1.png)

That's all! You're now configured to access any ModernTLD or OpenNIC website!
