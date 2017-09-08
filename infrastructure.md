---
layout: page
title: Infrastructure
permalink: /infrastructure/
---

### About Our Servers

ModernTLD provides multiple servers contributing to the OpenNIC DNS infrastructure, as listed below.

### Tier 1

ns11.opennic.glue: **45.55.97.204** / 2604:a880:800:a1::14c1:1 / Authoritative for **.o**

### Tier 2

ns5.any.dns.opennic.glue: **198.251.90.143** / Public Anycast Resolver (NA and EU)
ns5.nh.nl.dns.opennic.glue: **52.174.55.168** / Public Resolver (Amsterdam, Netherlands)
ns6.sg.dns.opennic.glue: **52.230.17.182** / Public Resolver (Singapore)
ns10.ny.us.dns.opennic.glue: **138.197.25.214** / 2604:a880:800:10::1f02:d001 / Public Resolver (New York, USA)
ns5.wa.us.dns.opennic.glue<sup>1</sup>: **52.175.214.157** / Public Resolver (Washington, USA)

<sup>1</sup>ns5.wa.us.dns.opennic.glue is an experimental testing server. It is completely functional, but may be prone to stability issues. It also supports the latest technologies such as DNSCrypt and DNSSEC Validation.
