# Awesome Bitcoin Open Source Projects

> A curated list of open source Bitcoin projects worth contributing to.

This list helps newcomers and seasoned developers find actively maintained, openly licensed Bitcoin projects to contribute to. Each entry shows **what the project needs**, **the skills involved**, **how ready it is for contributors**, and **who to contact** so you can find a project that matches your interests and skill set.

## Column guide

- **Project** — name, linked to its source repository.
- **Description** — a one-line summary.
- **Languages** — primary programming language(s).
- **Status** — contribution readiness (see legend below).
- **Contributor Needs** — the types of contributions wanted.
- **Required Skills** — technical/domain knowledge that helps.
- **Readiness** — how approachable contributing is (e.g. *good first issues available*, *intermediate*, *advanced*).
- **Maintainer / contact** — primary maintainer GitHub handle(s) or project socials.
- **Btrust Builders** — Btrust Builders community members active on the project.

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
- [Developer Tools](#developer-tools)
- [Contributing](#contributing)
- [License](#license)

## Full Node

> Full node and protocol implementations.

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness | Maintainer | Btrust Builders |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Bitcoin Core](https://github.com/bitcoin/bitcoin) | The reference implementation of the Bitcoin protocol. | C++, Python | 🟢 Ready | Protocol development, bug fixes, code review, test coverage | C++, Python, strong understanding of Bitcoin consensus rules | Intermediate to advanced — no labelled good-first issues; start with bitcoincore.academy | @laanwj, @fanquake, @achow101 | @eunovo, @naiyoma |
| [btcd](https://github.com/btcsuite/btcd) | An alternative full-node Bitcoin implementation written in Go. | Go | 🟡 Limited | Bug fixes, protocol compatibility, testing | Go, Bitcoin protocol fundamentals | Intermediate | btcsuite org | None confirmed yet |

## Lightning Network

> Lightning node implementations and related infrastructure.

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness | Maintainer | Btrust Builders |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [LND](https://github.com/lightningnetwork/lnd) | Full Lightning Network node implementation by Lightning Labs. | Go | 🟢 Ready | Bug fixes, feature development, documentation | Go, Lightning Network protocol basics | Good first issues available | @Roasbeef, @guggero | @Abdulkbk |
| [LDK (rust-lightning)](https://github.com/lightningdevkit/rust-lightning) | A highly modular Bitcoin Lightning library in Rust — the foundation that powers LDK Node and LDK Server. | Rust | 🟢 Ready | Core library development, protocol implementation, testing | Rust, Lightning protocol, deep Bitcoin knowledge | Intermediate to advanced | @TheBlueMatt, @valentinewallace | None confirmed yet |
| [LDK Node](https://github.com/lightningdevkit/ldk-node) | A ready-to-go Lightning node implementation built on LDK. | Rust | 🟢 Ready | Implementation work, testing, documentation | Rust, Lightning protocol knowledge | Active — good first issues available | @tnull, @jkczyz | @Anyitechs |
| [LDK Server](https://github.com/lightningdevkit/ldk-server) | A fully-functional Lightning node in daemon form built on LDK. | Rust | 🟢 Ready | Feature development, testing | Rust, Lightning protocol knowledge | Good first issues available | @G8XSU, @benthecarman | @Anyitechs |

## Wallets

> Desktop, mobile, and hardware wallet projects.

| Project | Description | Languages | Status | Contributor Needs | Required Skills | Readiness | Maintainer | Btrust Builders |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [Sparrow Wallet](https://github.com/sparrowwallet/sparrow) | A desktop wallet emphasizing transparency and self-custody. | Java | 🟢 Ready | Bug fixes, code, testing, UX feedback | Java, JavaFX | Good first issues available | @TBD | @TBD |

## Libraries & SDKs

> Reusable libraries for building Bitcoin applications.

_Projects coming soon — see [Contributing](#contributing) to add one._

## Developer Tools

> Tooling for developing, testing, and debugging Bitcoin software.

_Projects coming soon — see [Contributing](#contributing) to add one._

## Block Explorers

> Self-hostable explorers and chain-analysis interfaces.

_Projects coming soon — see [Contributing](#contributing) to add one._

## Mining

> Mining software and pool infrastructure.

_Projects coming soon — see [Contributing](#contributing) to add one._

## Privacy

> Tools focused on transaction privacy and coin control.

_Projects coming soon — see [Contributing](#contributing) to add one._

## Education & Documentation

> Books, tutorials, and reference material (open source repos).

_Projects coming soon — see [Contributing](#contributing) to add one._

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting. To add a project, add a new row to the relevant category table using the column order above, keeping rows alphabetical within their section.

Keeping the `Status` and contact fields accurate is the most valuable ongoing contribution — if a project's readiness has changed, please open an issue or PR to update it. Suggestions to remove inactive or abandoned projects are equally welcome.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related rights to this work.
