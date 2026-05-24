<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo_primary_white.svg">
    <source media="(prefers-color-scheme: light)" srcset="logo_primary_black.svg">
    <img src="logo_primary_color.svg" width="100%" alt="Opener logo">
  </picture>
</p>

The **Opener Initiative** hosts DECT-2020-related software projects and is the developer and maintainer of *Opener*, an open reference implementation of the DECT-2020 NR protocol stack, covering the MAC and upper layers.
We start by hosting stacks, in various forms and states, by the members. The aim is to **work together to make a unified open-source stack**. DECT NR+ technology supports many features and use cases, namely

- Audio streaming with scheduled access in a star network
- IoT sensor networks with random access in mesh networks

Members have started developing stacks for different use cases, picking different features from the standard. The **Opener Initiative** allows exploration of these different stacks and brings developers together to combine their efforts into creating a unified stack that will, in the end, have all the features for any need.

The following core principles guide the development of *Opener* and shape the project's technical vision:

1. **Ready for commercial use:** *Opener* not only fosters academic research but is also suitable for integration into demanding commercial products. For this reason, we chose the Apache 2.0 license for the project. Apache 2.0 is a business-friendly, OSI-approved permissive software license with no copyleft provisions that restrict commercial use. In addition to broad usage rights, Apache 2.0 includes an express grant of patent rights from contributors, providing legal protection and peace of mind for adopters.
2. **Application- and platform-agnostic:** *Opener* addresses the needs of applications across various domains and use cases, ranging from building automation or smart metering to professional audio. At the same time, it is portable across different hardware and software platforms, enabling integration on a wide variety of target systems without being tied to a specific vendor, architecture, or operating system.
3. **Interoperable and standards-compliant:** *Opener* complies with harmonized European norms and targets to pass ETSI-defined conformance tests.

## What is DECT-2020 NR?

DECT-2020 NR, marketed as DECT NR+ by the DECT Forum, is a Radio Interface Technology (RIT) specified by the European Telecommunications Standards Institute (ETSI) in the [TS 103 636 series of standards](https://www.etsi.org/standards-search#keyword=DECT-2020). Since late 2021, the ITU-R recognizes it as part of the IMT-2020 (i.e., 5G) family for fulfilling the requirements for massive Machine-Type Communications (mMTC) and Ultra-Reliable Low-Latency Communications (URLLC). The technology serves a wide variety of use cases, powering large-scale, high-density network deployments as well as cable-replacement solutions for mission-critical applications. Beyond point-to-point links and star networks, DECT-2020 supports mesh topologies in the form of clustered trees.

Unlike 3GPP cellular communication networks, DECT-2020 does not rely on centralized infrastructure and uses context-based rather than fixed device roles. In addition to the flexibility of nomadic ad-hoc deployments, users benefit from low costs and reduced operational complexity, as networks can be deployed and maintained independently of a Mobile Network Operator (MNO).

While DECT-2020 can operate in IMT and ISM frequency bands, it also has access to license-exempt spectrum in the 1880-1930 MHz range, with the specific allocation varying by region. In many markets, parts of this band are assigned exclusively to DECT technologies. With [Implementing Decision (EU) 2025/2425](https://docdb.cept.org/document/28661), the European Commission has established a regulatory framework that harmonizes the technical conditions for the shared use of the 3.8-4.2 GHz band across all member states, potentially enabling future DECT-2020 deployments in this spectrum, subject to national assignments.

## Is integrated hardware available?

Nordic Semiconductor offers the nRF91 series (e.g., nRF9151 and nRF9131 mini SiPs), which is currently the only off-the-shelf integrated hardware for DECT-2020. With Last Mile Semiconductor, a second vendor is set to enter the market soon.

## How to contribute to the Opener Initiative?

Collaboration with the **Opener Initiative** can take many forms, and we aim to keep the barrier to participation low. You can contribute in ways that best fit your goals and constraints, including:

- Sharing implementations of ETSI TS 103 636 with other organization members. These can be made publicly available or shared privately within the organization. While *Opener* is published under the Apache 2.0 license, contributors are free to choose the license that best suits their existing work.
- Working towards a unified reference implementation of ETSI TS 103 636 (*Opener*) by engaging in technical discussions and community activities such as workshops or plugtests.

Whether you contribute code, expertise, feedback, or testing support, all forms of participation are welcome.
