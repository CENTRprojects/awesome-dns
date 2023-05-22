# Awesome DNS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Domain Name System (DNS) related tools.

This list supersedes CENTR R&D projects table with a broader scope of all useful resources for DNS enthusiasts and professionals.

## Contents

- [Authoritative servers](#authoritative-servers)
- [Crawlers](#crawlers)
- [DNSSEC](#dnssec)
- [Resolvers](#resolvers)
- [Testing and monitoring](#testing-and-monitoring)

<!--lint disable double-link-->

## Authoritative servers

- [BIND](https://www.isc.org/bind/) - Flexible, full-featured DNS system. [![License: MPL 2.0](https://img.shields.io/badge/License-MPL_2.0-blue.svg)](https://opensource.org/licenses/MPL-2.0) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [Drink](https://framagit.org/bortzmeyer/drink) - An experimental authoritative name server (DNS server), intended for dynamic answers. [![License: GPL v2](https://img.shields.io/badge/License-GPLv2-blue.svg)](https://www.gnu.org/licenses/gpl-2.0.en.html) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [Knot DNS](https://www.knot-dns.cz) - High-performance authoritative DNS server. [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [NSD](https://nlnetlabs.nl/projects/nsd/about/) - Authoritative DNS name server for environments where speed, reliability, stability and security are of high importance. [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [PowerDNS Authoritative](https://www.powerdns.com/auth.html) - Authoritative DNS name server with databases and scripting languages support. [![License: GPL v2](https://img.shields.io/badge/License-GPLv2-blue.svg)](https://www.gnu.org/licenses/gpl-2.0.en.html) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [YADIFA](https://www.yadifa.eu) - Clean room implementation with small memory footprint. [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)

## Crawlers

- [DNS crawler](https://gitlab.labs.nic.cz/adam/dns-crawler) - DNS crawler for getting info about a huge number of DNS domains. [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [Mercator](https://github.com/DNSBelgium/mercator) - An Open Source robust and scalable crawler for collecting information on the usage of domain names. [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [Signs of Life](https://gitlab.centr.org/centr/crawler/signs-of-life) - Domain name crawler tool used in CENTR ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)

## DNSSEC

- [DNSViz](https://dnsviz.net) - DNSSEC-signed zone status analysis and visualisation. [![License: GPL v2](https://img.shields.io/badge/License-GPLv2-blue.svg)](https://www.gnu.org/licenses/gpl-2.0.en.html) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [LDNS](https://nlnetlabs.nl/projects/ldns/about/) - C Library and command-line tools to simplify DNS and DNSSEC operations. [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [OpenDNSSEC](https://www.opendnssec.org) - Policy-based zone signer that automates the process of keeping track of DNSSEC keys and the signing of zones. [![License](https://img.shields.io/badge/License-BSD_2--Clause-blue.svg)](https://opensource.org/licenses/BSD-2-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [SoftHSM](https://www.opendnssec.org/softhsm/) - Software implementation of a cryptographic store accessible through a PKCS#11 interface. [![License](https://img.shields.io/badge/License-BSD_2--Clause-blue.svg)](https://opensource.org/licenses/BSD-2-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [validns](https://github.com/DENICeG/validns) - DNS and DNSSEC zone file validator. [![License](https://img.shields.io/badge/License-BSD_2--Clause-blue.svg)](https://opensource.org/licenses/BSD-2-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-no-red)

## Resolvers

- [BIND](https://www.isc.org/bind/) - Flexible, full-featured DNS system. [![License: MPL 2.0](https://img.shields.io/badge/License-MPL_2.0-blue.svg)](https://opensource.org/licenses/MPL-2.0) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [Knot Resolver](https://www.knot-resolver.cz) - A caching DNS resolver scalable from huge resolver farms down to home network routers. [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [PowerDNS Recursor](https://www.powerdns.com/recursor.html) - High-end, high-performance resolving name server with multi-processor and scripting support. [![License: GPL v2](https://img.shields.io/badge/License-GPLv2-blue.svg)](https://www.gnu.org/licenses/gpl-2.0.en.html) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [Unbound](https://nlnetlabs.nl/projects/unbound/about/) - A validating, recursive, caching DNS resolver designed to be fast and lean. [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)

## Testing and monitoring

- [blaeu](https://framagit.org/bortzmeyer/blaeu) - Programs to create distributed Internet measurements on the network of RIPE Atlas probes. [![License](https://img.shields.io/badge/License-BSD_2--Clause-blue.svg)](https://opensource.org/licenses/BSD-2-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [check-soa](https://framagit.org/bortzmeyer/check-soa) - A simple command-line DNS testing tool. [![License](https://img.shields.io/badge/License-BSD_2--Clause-blue.svg)](https://opensource.org/licenses/BSD-2-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [dns-lg](https://framagit.org/bortzmeyer/dns-lg) - DNS Looking Glass. [![License](https://img.shields.io/badge/License-BSD_2--Clause-blue.svg)](https://opensource.org/licenses/BSD-2-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)
- [Zonemaster](https://zonemaster.net) - A software package that validates the quality of a DNS delegation. [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) ![Maintained: yes](https://img.shields.io/badge/Maintained-yes-green)

<!--lint enable double-link-->

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## Footnotes

This awesome list is curated by [CENTR](https://centr.org) (Council of European National Top-Level Domain Registries)
