---
layout: page
title: DD-WRT Setup
permalink: /get-started/advanced/windows-2016-dhcp/
---

### DNS Servers

Before you begin, you will need to choose two DNS servers. You can either pick from [this list](https://servers.opennic.org/), or use these two:

* 198.251.90.143 (ModernTLD Anycast Server)
* 138.197.25.214 (ModernTLD New York Server)

*[More info](/infrastructure)*

### Setup Guide

**Note:** This is not configuration on Windows clients locally, see the [Windows](/get-started/windows) guide if you wish to change DNS servers on your local PC.

1. Open DHCP Manager, either on your Windows Server or through RSAT.
2. In the sidebar, navigate to Your Server > IPv4 > Scope [Your Scope] > Scope Options
 ![](https://i.imgur.com/RgpA22S.png)
3. If the option 006 DNS Servers exists to the right, double click it. Otherwise right click the space to the right and choose Configure Options…
4. Under Available Options, check the box next to 006 DNS Servers if it isn’t checked already.
5. In scope options, after selecting 006 DNS Servers, enter an IP address you just chose above into the IP address box, then click Add to add it to the list below.
 ![](https://i.imgur.com/MhmSQkd.png)
6. Repeat Step 6 until you’ve entered all the IP addresses you’ve chosen. Technically you only need one but we recommend 2 to 4 to ensure uptime and load balancing.
7. Click OK and exit out of DHCP Manager.

That's all! You're now configured to access any ModernTLD or OpenNIC website!
