---
layout: default
---

# PIVOT

The emerging Internet of Things (IoT) is expected to host billions of
devices that regularly report sensor readings by using long or short range
radio channels. Generated content items and also collateral metadata are
not well protected today because (i) channel encryption is commonly
intercepted at gateways, (ii) identifiers reveal communication partners and
contexts, and (iii) cryptographic protection embedded in the low-end
transmission infrastructure remains too weak to resist attacks. In the
current IoT, sensing sources lose control over their data often even before
it reaches its destinations.

## Core concept and innovation: Naming protected content 
In PIVOT, we start from two fundamental observations. First, a
privacy-friendly IoT requires to protect content objects by themselves, in
addition to commonly deployed channel encryption. Content disclosure can
thus be attributed to designated receivers. Second, names can serve as the
principle interface to access IoT data, eliding source identities. Hence,
individual end point identifiers will disappear from public Internet
metadata.

The innovation in PIVOT is to address the prevalent privacy and
security issues in IoT by proposing content object security principles that
build on privacy-friendly names, while remaining globally and seamlessly
interoperable between IoT devices regardless of networks to which they may
connect.


## Goals and ambitions: Privacy-friendly object security in the constrained IoT 

PIVOT will focus on four core goals:

1. A crypto framework for privacy-friendly service primitives on constrained IoT devices.
2. Protocols that integrate decentralized object security.
3. Minimal trust anchor provisioning on IoT devices to enable object security.
4. Multi-stakeholder name management that preserves privacy requirements and generates, allocates,
and resolves names globally---regardless of the IoT applications or networks.

A demonstrator based on [RIOT](https://riot-os.org) will verify our solutions in constrained IoT networks such as
LoRaWAN.

PIVOT follows the perspective of "immediate action is required". This implies that we will extend existing
architectures and protocol standards conjoined with standardization bodies, while introducing new
first-hand primitive where necessary. Our ambitious roadmap will allow for incremental deployment
of the PIVOT solutions, which is the most promising path to quick adoption.
