# Awesome Bitcoin Open Source Projects

> A curated list of open source Bitcoin projects worth contributing to.

This list helps newcomers and seasoned developers find actively maintained,
openly licensed Bitcoin projects to contribute to. Each entry shows what the
project needs, the skills involved, how ready it is for contributors, and who
to contact so you can find a project that matches your interests and skill set.

## Column guide

- **Project** — name, linked to its source repository.
- **Description** — a one-line summary.
- **Languages** — primary programming language(s).
- **Status** — contribution readiness (see legend below).
- **Contributor Needs** — the types of contributions wanted.
- **Required Skills** — technical/domain knowledge that helps.
- **Readiness** — how approachable contributing is (e.g. *good first issues available*, *intermediate*, *advanced*).

**Status legend:**

- 🟢 **Ready** — actively welcoming contributors.
- 🆕 **Beginner-friendly** — has good first issues for newcomers.
- 🟡 **Limited** — accepting help only in specific areas right now.
- 🔴 **Paused** — not currently accepting external contributions.

## Contents

- [Full Node](#full-node)
- [Lightning Network](#lightning-network)
- [Wallets](#wallets)
- [Libraries & SDKs](#libraries--sdks)
- [Privacy & Scaling](#privacy--scaling)
- [Mining](#mining)
- [Hardware Wallets](#hardware-wallets)
- [Developer Tools](#developer-tools)
- [Contributing](#contributing)
- [License](#license)

---

## Full Node

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness |
| --- | --- | --- | --- | --- | --- | --- |
| [Bitcoin Core](https://github.com/bitcoin/bitcoin) | The reference implementation of the Bitcoin protocol. | C++, Python | 🟢 Ready | Protocol development, bug fixes, code review, test coverage | C++, Python, strong understanding of Bitcoin consensus rules | Intermediate to advanced — no labelled good-first issues; start with [bitcoincore.academy](https://bitcoincore.academy) |
| [btcd](https://github.com/btcsuite/btcd) | An alternative full-node Bitcoin implementation written in Go. | Go | 🟢 Ready | Bug fixes, protocol compatibility, testing | Go, Bitcoin protocol fundamentals | Intermediate | btcsuite org | None confirmed yet |
| [Elements Project](https://github.com/elementsproject/elements) | Open-source implementation of advanced blockchain features extending Bitcoin — powers the Liquid sidechain. | C++, Python | 🟢 Ready | Protocol development, sidechain features, testing | C++, Python, Bitcoin protocol, confidential transactions | Intermediate to advanced |

---

## Lightning Network

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness |
| --- | --- | --- | --- | --- | --- | --- |
| [LND](https://github.com/lightningnetwork/lnd) | Full Lightning Network node implementation by Lightning Labs. | Go | 🆕 Beginner-friendly | Bug fixes, feature development, documentation | Go, Lightning Network protocol basics | Good first issues available |
| [LDK (rust-lightning)](https://github.com/lightningdevkit/rust-lightning) | A highly modular Bitcoin Lightning library in Rust — the foundation that powers LDK Node and LDK Server. | Rust | 🟢 Ready | Core library development, protocol implementation, testing | Rust, Lightning protocol, deep Bitcoin knowledge | Intermediate to advanced |
| [LDK Node](https://github.com/lightningdevkit/ldk-node) | A ready-to-go Lightning node implementation built on LDK. | Rust | 🟢 Ready | Implementation work, testing, documentation | Rust, Lightning protocol knowledge | Intermediate |
| [LDK Server](https://github.com/lightningdevkit/ldk-server) | A fully-functional Lightning node in daemon form built on LDK. | Rust | 🟢 Ready | Feature development, testing | Rust, Lightning protocol knowledge | Intermediate |
| [Core Lightning (CLN)](https://github.com/ElementsProject/lightning) | Blockstream's C-based Lightning Network implementation with a plugin-based architecture. | C, Python | 🟢 Ready | Protocol work, plugin development, testing | C, Python, Lightning protocol | Intermediate |
| [Eclair](https://github.com/ACINQ/eclair) | A Scala implementation of the Lightning Network by ACINQ. | Scala | 🟢 Ready | Protocol implementation, bug fixes | Scala, Lightning protocol | Intermediate to advanced |
| [lightning-kmp](https://github.com/ACINQ/lightning-kmp) | Kotlin Multiplatform implementation of the Lightning Network protocol — powers Phoenix wallet. | Kotlin | 🟢 Ready | Protocol implementation, mobile integration, testing | Kotlin, Kotlin Multiplatform, Lightning protocol | Intermediate to advanced |
| [RTL (Ride The Lightning)](https://github.com/Ride-The-Lightning/RTL) | A web-based interface for managing Lightning Network nodes — LND, CLN, and Eclair. | TypeScript, JavaScript | 🆕 Beginner-friendly | UI/UX improvements, new node type support, bug fixes | TypeScript, Angular, basic Lightning node operations | Beginner-friendly issues available |
| [Thunderhub](https://github.com/apotdevin/thunderhub) | A Lightning node manager with a modern interface, supporting LND nodes. | TypeScript | 🆕 Beginner-friendly | Feature development, UI improvements, bug fixes | TypeScript, React, Next.js, LND API basics | Beginner-friendly issues available |
| [Lightning Loop](https://github.com/lightninglabs/loop) | A non-custodial service for moving funds in and out of Lightning payment channels. | Go | 🟢 Ready | Bug fixes, feature development | Go, Lightning Network, channel management | Intermediate |
| [Lightning Terminal](https://github.com/lightninglabs/lightning-terminal) | A browser-based interface for managing Lightning nodes and liquidity. | Go | 🟢 Ready | UI improvements, Lightning tools, liquidity features | Go, TypeScript, Lightning concepts | Intermediate |

---

## Wallets

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness |
| --- | --- | --- | --- | --- | --- | --- |
| [Bitcoin Dev Kit (BDK)](https://github.com/bitcoindevkit/bdk) | A modern descriptor-based Bitcoin wallet library written in Rust. | Rust | 🆕 Beginner-friendly | Wallet features, descriptor support, testing, language bindings | Rust, Bitcoin descriptors, wallet construction | Good first issues available |
| [Blue Wallet](https://github.com/bluewallet/bluewallet) | A feature-rich Bitcoin and Lightning mobile wallet for iOS and Android. | TypeScript, JavaScript | 🆕 Beginner-friendly | Mobile feature development, bug fixes, UI improvements | TypeScript, React Native, Bitcoin/Lightning basics | Good first issues available |
| [BtcPayServer](https://github.com/btcpayserver/btcpayserver) | Self-hosted, open-source Bitcoin and Lightning payment processor. | C#, Shell | 🆕 Beginner-friendly | Feature development, UI improvements, integrations, documentation | C#, .NET, Bitcoin basics | Good first issues available |
| [Electrum](https://github.com/spesmilo/electrum) | One of the oldest and most widely-used Bitcoin desktop wallets. | Python | 🟢 Ready | Bug fixes, hardware wallet support, Python improvements | Python, Bitcoin transaction fundamentals | Intermediate |
| [LNbits](https://github.com/lnbits/lnbits) | Free and open-source Lightning accounts and wallet management system. | Python | 🆕 Beginner-friendly | Extension development, bug fixes, UI improvements | Python, Lightning Network basics | Good first issues available |
| [Phoenix](https://github.com/ACINQ/phoenix) | A self-custodial Bitcoin wallet using Lightning to send and receive payments. | Kotlin, Swift | 🟢 Ready | Mobile feature development, bug fixes, UX improvements | Kotlin or Swift, Lightning protocol, mobile development | Intermediate |
| [Sparrow Wallet](https://github.com/sparrowwallet/sparrow) | A desktop wallet emphasising transparency and self-custody, with full coin control. | Java | 🆕 Beginner-friendly | Bug fixes, code, testing, UX feedback | Java, JavaFX, Bitcoin transaction fundamentals | Good first issues available |
| [Wasabi Wallet](https://github.com/zkSNACKs/WalletWasabi) | A privacy-focused Bitcoin desktop wallet with built-in coinjoin coordination. | C# | 🆕 Beginner-friendly | C# development, privacy protocol improvements, testing | C#, .NET, Bitcoin privacy concepts | Good first issues available |
| [Zeus](https://github.com/ZeusLN/zeus) | A mobile Bitcoin wallet with Lightning — connects to your own node. | TypeScript | 🟢 Ready | Mobile features, UI improvements, bug fixes | TypeScript, React Native, Lightning node APIs | Intermediate |

---

## Libraries & SDKs

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness | Maintainer | Btrust Builders |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [bitcoin-s](https://github.com/bitcoin-s/bitcoin-s) | Bitcoin implementation and toolkit in Scala — wallets, nodes, and scripting support. | Scala | 🟢 Ready | Protocol implementation, tooling, library improvements | Scala, Bitcoin protocol | Intermediate |
| [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib) | A JavaScript/TypeScript library for Bitcoin — transaction construction, scripting, and key management. | TypeScript, JavaScript | 🟢 Ready | Bug fixes, TypeScript improvements, test coverage | TypeScript/JavaScript, Bitcoin scripting basics | Intermediate |
| [Bitcoinj](https://github.com/bitcoinj/bitcoinj) | A library for working with Bitcoin in Java and other JVM languages. | Java | 🟢 Ready | Bug fixes, API improvements, documentation | Java, Bitcoin protocol fundamentals | Intermediate |
| [libsecp256k1](https://github.com/bitcoin-core/secp256k1) | Optimised C library for elliptic curve operations on the secp256k1 curve — used in Bitcoin Core. | C | 🟡 Limited | Cryptographic improvements, testing, documentation | C, cryptography, elliptic curve mathematics | Advanced |
| [LNDHub](https://github.com/BlueWallet/LndHub) | A wrapper for the Lightning Network Daemon providing custodial wallet accounts via a REST API. | JavaScript | 🟢 Ready | API improvements, bug fixes, documentation | JavaScript, LND API, REST APIs | Intermediate |
| [ln-service](https://github.com/alexbosworth/ln-service) | Node.js interface to the Lightning Network Daemon (LND). | JavaScript | 🟢 Ready | API improvements, testing, documentation | JavaScript/Node.js, LND gRPC API | Intermediate |
| [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) | The foundational Rust library for working with Bitcoin data structures and primitives. | Rust | 🆕 Beginner-friendly | API improvements, test coverage, documentation | Rust, Bitcoin protocol fundamentals | Good first issues and help wanted available |

---

## Privacy & Scaling

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness |
| --- | --- | --- | --- | --- | --- | --- |
| [Ark SDK](https://github.com/arkade-os/rust-sdk) | Rust crates for building Bitcoin wallets with on-chain and off-chain (Ark protocol) support. | Rust | 🟡 Limited | SDK development, wallet integrations, testing | Rust, Bitcoin scripting, Ark protocol | Early-stage; issues available |
| [Cashu / Coco](https://github.com/cashubtc/coco) | TypeScript implementation of the Cashu eCash protocol. | TypeScript | 🟢 Ready | Protocol implementation, testing, documentation | TypeScript, Chaumian eCash concepts | Early-stage; issues available |
| [Cashu Nutshell](https://github.com/cashubtc/nutshell) | Reference Python implementation of the Cashu Chaumian eCash protocol for Bitcoin. | Python | 🟢 Ready | Protocol implementation, testing, tooling | Python, Chaumian eCash concepts | Intermediate |
| [Fedimint](https://github.com/fedimint/fedimint) | A federated Chaumian eCash protocol enabling community custody of Bitcoin. | Rust, Shell | 🆕 Beginner-friendly | Protocol development, module building, testing, documentation | Rust, cryptography basics, Lightning Network | Good first issues available |
| [RGB](https://github.com/RGB-WG/rgb) | A smart contract system built on Bitcoin and Lightning, using client-side validation. | Rust | 🟡 Limited | Protocol implementation, tooling, documentation | Rust, Bitcoin scripting, cryptography basics | Advanced — early-stage protocol |
| [RoboSats](https://github.com/RoboSats/robosats) | A peer-to-peer Bitcoin exchange over Lightning, designed for privacy. | Python, TypeScript | 🆕 Beginner-friendly | Backend features, frontend UI, Tor/privacy improvements | Python (Django), TypeScript (React), Lightning basics | Good first issues available |
| [rust-payjoin](https://github.com/payjoin/rust-payjoin) | Supercharged payment batching using PayJoin — saves fees and preserves privacy on Bitcoin. | Rust | 🆕 Beginner-friendly | Protocol implementation, testing, wallet integrations | Rust, Bitcoin transaction construction, PayJoin protocol | Good first issues available |
| [Taproot Assets](https://github.com/lightninglabs/taproot-assets) | A layer 1 protocol for issuing assets on Bitcoin using Taproot — enables asset transfers over Lightning. | Go | 🟢 Ready | Protocol implementation, tooling, documentation | Go, Bitcoin Taproot, Lightning Network | Intermediate |

---

## Mining

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness |
| --- | --- | --- | --- | --- | --- | --- |
| [P2Pool v2](https://github.com/p2poolv2/p2poolv2) | A decentralised peer-to-peer Bitcoin mining pool, rebuilt from the ground up. | Rust, C++ | 🟡 Limited | Core protocol work, P2P networking, testing | Rust or C++, Bitcoin mining/Stratum protocol | Early-stage; issues available |
| [Stratum v2 Reference Implementation (SRI)](https://github.com/stratum-mining/stratum) | The reference implementation of Stratum v2, the next-generation Bitcoin mining protocol. | Rust | 🆕 Beginner-friendly | Protocol implementation, testing, documentation | Rust, Bitcoin mining, Stratum protocol | Good first issues available |

---

## Hardware Wallets

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness |
| --- | --- | --- | --- | --- | --- | --- |
| [BitBox Wallet App](https://github.com/BitBoxSwiss/bitbox-wallet-app) | The BitBox desktop and mobile wallet app — companion to BitBox hardware wallets. | Go, TypeScript | 🟢 Ready | UI features, backend improvements, hardware wallet integration | Go, TypeScript, React Native, hardware wallet protocols | Intermediate |
| [Coldcard Firmware](https://github.com/Coldcard/firmware) | Firmware and simulator for the Coldcard hardware wallet. | Python, C | 🟢 Ready | Firmware improvements, security review, simulator enhancements | Python, C, Bitcoin signing, hardware wallet internals | Intermediate |
| [Trezor Firmware](https://github.com/trezor/trezor-firmware) | Firmware monorepo for Trezor hardware wallets. | C, Python | 🟢 Ready | Firmware development, testing, security review | C, Python, embedded systems, cryptography | Intermediate to advanced |

---

## Developer Tools

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness |
| --- | --- | --- | --- | --- | --- | --- |
| [Bitcoin Dev Project](https://github.com/bitcoin-dev-project/bitcoin-dev-project) | An open platform for learning about and navigating Bitcoin open-source development. | TypeScript | 🆕 Beginner-friendly | Content, UI features, contributor-matching tooling | TypeScript, React, Bitcoin development literacy | Good first issues and help wanted available |
| [electrs](https://github.com/romanz/electrs) | An efficient re-implementation of Electrum Server in Rust — enables lightweight Bitcoin wallets. | Rust | 🟢 Ready | Performance improvements, bug fixes, documentation | Rust, Bitcoin indexing, Electrum protocol | Intermediate |
| [JAM (JoinMarket WebUI)](https://github.com/joinmarket-webui/jam) | A modern web interface for JoinMarket, making Bitcoin coinjoin accessible. | TypeScript | 🆕 Beginner-friendly | UI/UX, documentation, accessibility improvements | TypeScript, React, JoinMarket basics | Good first issues available |
| [Mempool](https://github.com/mempool/mempool) | The leading open-source Bitcoin blockchain and mempool explorer. | TypeScript | 🟢 Ready | Frontend features, backend data improvements, deployment tooling | TypeScript, Angular, Bitcoin transaction data | Intermediate |
| [Nigiri](https://github.com/vulpemventures/nigiri) | A Docker-based local Bitcoin and Lightning development environment. | Go | 🟢 Ready | Docker tooling, environment improvements, documentation | Go, Docker, Bitcoin/Lightning basics | Intermediate |
| [Polar](https://github.com/jamaljsr/polar) | One-click local Bitcoin Lightning networks for development and testing. | TypeScript, Docker | 🆕 Beginner-friendly | UI features, new node type support, bug fixes | TypeScript, React, Electron, Docker basics | Good first issues available |
| [Warnet](https://github.com/bitcoin-dev-project/warnet) | Monitor and analyse the emergent behaviours of Bitcoin networks at scale. | Python | 🟢 Ready | Network simulation features, testing tools, documentation | Python, Bitcoin P2P networking, network analysis | Intermediate |

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting. To add a project, add a new row to the relevant category table using the column order above, keeping rows alphabetical within their section.

Keeping the `Status` and contact fields accurate is the most valuable ongoing contribution — if a project's readiness has changed, please open an issue or PR to update it. Suggestions to remove inactive or abandoned projects are equally welcome.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related rights to this work.
