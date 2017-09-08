---
layout: page
title: DD-WRT Setup
permalink: /get-started/advanced/dd-wrt/
---

### DNS Servers

Before you begin, you will need to choose two DNS servers. You can either pick from [this list](https://servers.opennic.org/), or use these two:

* 198.251.90.143 (ModernTLD Anycast Server)
* 138.197.25.214 (ModernTLD New York Server)

*[More info](/infrastructure)*

### Setup Guide

1. Select Setup > Basic Setup from the DD-WRT control panel. (You will need admin credentials to login, if you haven’t changed the defaults these will be “admin” and “password).
![](https://i.imgur.com/65qGoMR.png)
2. Under the Router IP section, enter any IP address from this list in Local DNS.
![](https://i.imgur.com/khW6PPM.png)
3. Under Network Address Server Settings (DHCP), enter up to 3 IP addresses from the list above (2 or more recommended):
![](https://i.imgur.com/YP9hOVL.png)
4. At the bottom of the page, click Save, then Apply Changes.

That's all! You're now configured to access any ModernTLD or OpenNIC website!
