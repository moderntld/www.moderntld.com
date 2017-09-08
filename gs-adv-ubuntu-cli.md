---
layout: page
title: Ubuntu CLI Setup
permalink: /get-started/advanced/ubuntu-terminal/
---

### DNS Servers

Before you begin, you will need to choose two DNS servers. You can either pick from [this list](https://servers.opennic.org/), or use these two:

* 198.251.90.143 (ModernTLD Anycast Server)
* 138.197.25.214 (ModernTLD New York Server)

*[More info](/infrastructure)*

### Setup Guide

1. In a Terminal, enter: `sudo nano /etc/resolvconf/resolv.conf.d/tail`
2. Delete the entire contents of the file, if anything exists.
3. Enter the following as a new line, replacing the IP address with whichever IP you chose: `nameserver 45.55.97.204`
4. Repeat Step 4 for as many nameserver IP addresses as you’ve chosen to use, replacing the IP each time with another one. We recommend using at least 2 to 4 to ensure adequate uptime. Your file should now look something like this:
```
nameserver 198.251.90.143
nameserver 138.197.25.214
```
5. Press Ctrl + O on your keyboard, then Ctrl + X to exit Nano.

That's all! You're now configured to access any ModernTLD or OpenNIC website!
