---
title: "Riseupvpn"
short_description: "This test provides an automated way of examining whether RiseupVPN works in a
tested network."
groups: ["proxies"]
---

# RiseupVPN

This test provides an automated way of examining whether RiseupVPN works in a tested network.


## About RiseupVPN
[RiseupVPN](https://riseup.net/vpn) is a non-commercial, donation-based VPN service. It offers simple to use clients to secure your internet traffic against survaillance and to circumvent internet censorship. RiseupVPN doesn't log any user data and doesn't require registration.
The software is based on [LEAP VPN](https://leap.se/), an open source VPN solution, and is run by the [Riseup collective](https://riseup.net/about-us) which offers privacy preserving online services for activists since more than 20 years. 

## About the test

This test evaluates if the bootstrap servers used during the self-configuration of the VPN clients can be reached. The test also checks if RiseupVPN's gateways can be reached on different ports and transports.

For the future we aim to use this test as a blueprint to offer a generic way to test the reachability of LEAP instances deployed by other providers and users who self-host their VPN.
Other providers, who self-host their LEAP powered VPN infrastructure, can use this test as a blueprint for probing its own reachability.
In the future this test can form the base to offer a generic way to probe the reachability of other LEAP powered VPN infrastructure, self-hosted by other providers.

For more details read the **[RiseupVPN test specification](https://github.com/ooni/spec/blob/master/nettests/ts-026-riseupvpn.md)**.