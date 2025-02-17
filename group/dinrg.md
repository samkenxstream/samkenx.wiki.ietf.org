---
title: DIN RG - IRTF Decentralized Internet Infrastructure
description: IRTF Decentralized Internet Infrastructure (DIN RG)
published: true
date: 2023-01-24T20:35:08.534Z
tags: 
editor: markdown
dateCreated: 2022-12-06T22:56:28.677Z
---

#  Decentralized Internet Infrastructure (DIN) -- Proposed Research Group Wiki

The Decentralized Internet Infrastructure Proposed Research Group (DINRG) investigates open research issues in decentralizing infrastructure services such as trust management, identity management, name resolution, resource/asset ownership management, and resource discovery. The focus of DINRG is on infrastructure services that can benefit from decentralization or that are difficult to realize in local, potentially connectivity-constrained networks.

## DINRG Administrative Information

* [Official DINRG web page](https://irtf.org/dinrg)
* [Mailing list](https://www.irtf.org/mailman/listinfo/din)
* [Charter](https://datatracker.ietf.org/rg/dinrg/charter/)
 * [Previous wiki page](https://trac.ietf.org/trac/irtf/wiki/blockchain-federation)
* Current chairs <dinrg-chairs@ietf.org>
     *   Dirk Kutscher
     *   Melinda Shore 

## Motivation

The Internet was designed as a distributed, decentralized system. For example, intra- and inter-domain routing, DNS, and so on were designed to operate in a distributed manner. However, over time the dominant deployment model for applications and some infrastructure services evolved to become more centralized and hierarchical. Some of the increase in centralization is due to business models that rely on centralized accounting and administration.

However, we are simultaneously seeing the evolution of use cases (e.g., certain IoT deployments) that cannot work (or which work poorly) in centralized deployment scenarios along with the evolution of decentralized technologies which leverage new cryptographic infrastructures, such as DNSSEC, or which use novel, cryptographically-based distributed consensus mechanisms, such as a number of different ledger technologies. For example, these use cases include identity/trust management leveraging reputation for authentication, authorization and decentralized management of shared resources.

The evolution of distributed ledger technologies and the platforms that leverage them has given rise to the development of decentralized communication and infrastructure systems, and experiments with the same. Some examples include name resolution (Namecoin, Ethereum Name Service), identity management (OneName?), distributed storage (IPFS, MaidSafe?), distributed applications, or DApps (Blockstack), and IP address allocation and delegation.

These systems differ with respect to the problem they are solving, the specific technologies that they apply, the consensus algorithms that are employed, and the incentives that are built into the system. Now is a good time to investigate these systems from an Internet technologies perspective, and to connect the domain expertise in the IRTF and IETF with the distributed systems and decentralized ledgers community.

## Research Challenges

* Identification of specific use case requirements
* Scalability - what are the problems that prevent decentralized infrastructure services from achieving global scale?
* Trust management in decentralized communication settings
* Privacy and targeted, verifiable disclosure
* Applicability of distributed ledger and related technologies to different use cases and environments (including constrained nodes and networks)
* Consensus algorithms for specific scenarios with a focus on Internet infrastructure services
* The ability of constrained nodes to benefit from elements of a consensus item that they cannot process or store as a complete set
* Distributed Trust and Delegated Computing
* Economic drivers and roadblocks for decentralizing network infrastructure
* Identification of common requirements and properties of selected technologies
* Design and implementation of one or more general-purpose infrastructure systems
* Deployment and operation of one or more actual implementations 

## DINRG Presentations and Meetings
### March 2018 (IETF 101, London)

* [Minutes](https://datatracker.ietf.org/meeting/101/materials/minutes-101-dinrg-01)
* **Decentralized Internet Infrastructure: Overview of Potential Use-Cases and Drivers**, Paolo Mendes - [Youtube](https://youtu.be/VgP42xgH5bo?t=7m53s),  [slides](https://datatracker.ietf.org/meeting/101/materials/slides-101-dinrg-paulo-mendes-overview-of-potential-use-cases-and-drivers-01)
* **The Stellar Consensus Protocol (SCP)**, David Mazières - [Youtube](https://youtu.be/VgP42xgH5bo?t=21m50s),  [slides](https://datatracker.ietf.org/meeting/101/materials/slides-101-dinrg-david-mazieres-stellar-consensus-protocol-00)
* **Distributed Authenticated Mappings**, Colin Man - [Youtube](https://youtu.be/VgP42xgH5bo?t=52m18s),  [slides](https://datatracker.ietf.org/meeting/101/materials/slides-101-dinrg-colin-man-distributed-authenticated-mapping-00)
* **Chainspace: A Scalable Smart Contracts Platform**, Shehar Bano - [Youtube](https://youtu.be/VgP42xgH5bo?t=1h12m48s), [slides](https://datatracker.ietf.org/meeting/101/materials/slides-101-dinrg-shehar-bano-chainspace-a-scalable-smart-contracts-platform-00)
* **Distributed Transaction Ledger for Utility-Scale Solar**, Lixia Zhang - [Youtube](https://youtu.be/VgP42xgH5bo?t=1h40m55s),  [slides](https://datatracker.ietf.org/meeting/101/materials/slides-101-dinrg-lixia-zhang-applying-distributed-ledger-to-iot-app-01)
* **A Decentralized Mapping System**, Dino Farinacci - [Youtube](https://youtu.be/VgP42xgH5bo?t=2h1m3s),  [slides](https://datatracker.ietf.org/meeting/101/materials/slides-101-dinrg-dino-farinacci-colin-cantrell-a-decentralized-mapping-system-00)

&nbsp; 
### Interim meeting on 2018-02-17 (co-located with [NDSS-2018](https://www.ndss-symposium.org/ndss2018/))

### Logistics

* Date: Saturday, February 17, 2018; 09:30 -- 17:00
* Location: [Catamaran Resort Hotel & Spa](https://catamaranresort.com/), Room Rousseau Suite
* [Meeting material](https://datatracker.ietf.org/meeting/interim-2018-dinrg-01/session/dinrg)
* [Etherpad for notes](https://etherpad.tools.ietf.org/p/notes-dinrg-interim-ndss2018?useMonospaceFont=true)
* [Minutes](https://datatracker.ietf.org/meeting/interim-2018-dinrg-01/materials/minutes-interim-2018-dinrg-01-201802170900)

### Agenda
| **Time** |	**Topic** |	**Presenter** |	**Duration**|
|----|----|----|-----|
|09:30 |	**Welcome, Intro, Agenda Bashing** |	Melinda, Dirk |	10 min
|09:40 |	Secure Open Federation for the Internet Everywhere |	George Polyzos |	30 min
|10:10 |	Decentralized Computing Environments |	Michal Krol |	30 min|
|10:40 |	**Break** (no refreshments provided) 		
|11:10 |	Distributed Authenticated Mapping 	|Sydney Li, Colin Man, Jean-Luc Watson |	30 min
|11:40 |	Blockchain as an Audit-Able Communication Channel |	Shigeya Suzuki |	30 min|
|12:10 |	Distributed Name Rewriting |	Christian Tschudin |	20 min
|12:30 |	**Lunch** (self-organized) 		
|14:00 |	NDSS DISS Workshop preview |	Dirk |	20 min|
|14:20 |	Decentralized Internet Infrastructure: Discussion on research scope, use cases, next steps |	Melinda, Dirk |	120 min|
|16:20 	|Summary, Wrap up, Next Steps |	Melinda, Dirk |	10 min|
|16:30 |	**	End of Meeting** 		

### Attendees
|**Name** 	|**Affiliation**|
|----|------|
|Melinda Shore |	Fastly|
|Dirk Kutscher |	Huawei|
|Christian Tschudin |	Universität Basel|
|Carsten Bormann |	Universität Bremen|
|Michal Krol |	University College London|
|George Polyzos |	Athens University of Economy and Business|
|Sydney Li |	Stanford University|
|Colin Man |	Stanford University|
|Jean-Luc Watson |	Stanford University|
|David Mazières |	Stanford University|
|Shigeya Suzuki |	Keio University|
|Vishnu Ram |	Independent Consultant|
|Mat Ford |	Internet Society|
|Lijun Dong |	Huawei|
|Paul Hoffman |	ICANN|

## Past Meetings

[list of past meetings with links to presentation material](https://trac.ietf.org/trac/irtf/wiki/blockchain-federation)

&nbsp;
&nbsp;
&nbsp;

---

*The content of this page was last updated on 2018-02-24. It was migrated from the old Trac wiki on 2023-01-24.*