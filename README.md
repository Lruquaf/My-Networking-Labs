# Yavuz Selim Tunçer

**Software Engineer · Backend & Full-Stack · Blockchain · Linux & Networking**

I’m a computer engineer with 3+ years of experience building software. I’ve taken products from definition through production, building the interfaces, APIs, and background services behind them. I’m especially interested in how systems behave when traffic grows, an event goes missing, or a deployment fails.

[Public projects](#public-projects) · [Production work](#production-work) · [Networking labs](#networking-labs) · [LinkedIn](https://www.linkedin.com/in/yavuz-selim-tun%C3%A7er-6634581b4/)

## Public projects

**[ScoreLogic](https://github.com/Lruquaf/score-logic-app)** is a daily football logic puzzle app built with Next.js and PostgreSQL. I built a publishing workflow that validates puzzles, stages revisions for review, and lets editors schedule releases or roll them back. The repository also includes automated tests, request tracing, and Redis-backed rate limiting.

**[ZKBoys](https://github.com/Lruquaf/ZKBoys)** is an NFT minting contract with whitelist and public sale flows. I tested it on zkSync Era testnet before deploying it to mainnet. The repository includes the contract address and explains the differences between the local and zkSync test setups.

**[Smart contract security reviews](https://github.com/Lruquaf/my-security-reviews)** collects my practice reviews of smart contracts. It complements my development work with a focus on contract behavior, failure cases, and security assumptions.

**[Walmart M5 forecasting](https://github.com/Lruquaf/walmart-m5-forecasting)** is the companion repository for my bachelor’s thesis at Turkish-German University. I developed and evaluated FCNN and LightGBM pipelines for retail sales forecasting, including time-series feature engineering and analysis of model performance and resource use.

## Production work

**ProtoHQ · Dashone Tech.** As product owner and sole software engineer, I built a multi-tenant Web3 operations platform for contract monitoring, alerts, and transaction workflows. I moved event processing to background workers and reworked the live feed with WebSockets, bringing observed update latency from about 17 seconds to 2–2.5 seconds. In production, a TLS reverse proxy handled public traffic while the API, PostgreSQL, and Redis stayed on the internal Docker network.

**ArtSense · Dashone Tech.** I built the smart contract protocol and the application used to manage artwork sales, inventory, and refunds. A worker verified signed webhooks and recovered missed events before sending live updates to the dashboard. I deployed the stack to an Ubuntu host through an SSH bastion.

**Choz.** I built TypeScript REST APIs for quizzes and scoring and used Redis-backed jobs to process results. I integrated Mina-based rewards and kept payout status synchronized with application records.

**Fluton Labs.** I helped build a prototype for confidential cross-chain token transfers between Fhenix and Zama. I implemented the Zama-side fully homomorphic encryption (FHE) integration.

## Networking labs

I’m developing hands-on networking skills through the Jeremy’s IT Lab CCNA 200-301 course, Cisco Packet Tracer, and Tanenbaum’s *Computer Networks*. Here are three things I’ve worked through in the lab.

- **Static routing.** Diagnosed routing faults involving next hops, outgoing interfaces, and IPv4 addresses across a three-router topology.
- **Switching.** Identified the root bridge and traced spanning-tree port roles across four switches to explain which links forwarded traffic.
- **Dynamic routing.** Configured single-area OSPF and EIGRP in separate multi-router labs, working with loopbacks, passive interfaces, and default route origination.

The course also covers IPv6, DHCP, NAT, access control, wireless fundamentals, and network programmability.

I’m interested in network automation because it builds on work I already do with Python, REST APIs, and shell scripts. My deployment work has also given me experience with SSH, container networking, and service health checks. I’m bringing the same habit of checking observable system state to my routing and switching labs.

## Tools I work with

| Area | Tools and practices |
| --- | --- |
| Application development | TypeScript, Node.js, React, Next.js, NestJS, Python, Flask |
| Backend and infrastructure | REST APIs, PostgreSQL, Redis, MongoDB, Linux, Docker Compose, GitHub Actions |
| Blockchain and quality | Solidity, EVM, Foundry, Safe, fuzz and invariant testing, API integration tests |
| Networking practice | Cisco IOS, Packet Tracer, TCP/IP, subnetting, VLANs, STP, OSPF, EIGRP |

I co-founded and taught at TAU Blockchain. I use AI coding tools to help plan changes, explore implementations, and test behavior. I own the architecture decisions and verify the results.
