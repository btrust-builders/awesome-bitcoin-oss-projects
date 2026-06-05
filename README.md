# Awesome Bitcoin Open Source Projects

> A curated list of open source Bitcoin projects worth contributing to.

This list helps newcomers and seasoned developers find actively maintained, openly licensed Bitcoin open source projects to contribute to. Beyond pointing to each project, every entry shows **what kind of help it needs**, **which skills are useful**, and **whether it's currently ready for contributors** — so you can find a project that matches both your interests and your skill set.

Every project listed here meets our [inclusion criteria](CONTRIBUTING.md): an OSI-approved open source license, publicly available source code, and recent development activity.

## How to read this list

Each project entry includes the following fields:

- **Description** — a one-line summary of what the project does.
- **Languages** — the primary programming language(s).
- **Looking for** — the *types* of contributions wanted (e.g. code, docs, testing, design, translation).
- **Skills needed** — the technical or domain knowledge that helps (e.g. Rust, React, cryptography).
- **Status** — contribution readiness (see legend below).
- **Maintainer / contact** — where to reach the team before diving in.

**Status legend:**

- 🟢 **Ready** — actively welcoming contributors.
- 🆕 **Beginner-friendly** — has good first issues for newcomers.
- 🟡 **Limited** — accepting help only in specific areas right now.
- 🔴 **Paused** — not currently accepting external contributions.

<!--
ENTRY TEMPLATE (copy this when adding a project; keep fields in this order):

### Project Name
One-line description.
- **Languages:** Language1, Language2
- **Looking for:** e.g. code, documentation, testing
- **Skills needed:** e.g. Rust, protocol knowledge
- **Status:** 🟢 Ready  (use one value from the legend)
- **Maintainer / contact:** Prefer a durable, PUBLIC contact — a GitHub handle, the repo's Issues/Discussions, or a project chat(Slack, Discord.. e.t.c). Avoid personal emails.

Add projects alphabetically within their section.
-->

## Contents

- [Node Implementations](#node-implementations)
- [Wallets](#wallets)
- [Lightning Network](#lightning-network)
- [Libraries & SDKs](#libraries--sdks)
- [Developer Tools](#developer-tools)
- [Block Explorers](#block-explorers)
- [Mining](#mining)
- [Privacy](#privacy)
- [Education & Documentation](#education--documentation)
- [Contributing](#contributing)
- [License](#license)

---

## Node Implementations

> Full node and protocol implementations.

### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
The reference implementation of the Bitcoin protocol.
- **Languages:** C++, Python
- **Looking for:** code review, testing, documentation
- **Skills needed:** C++, consensus/protocol knowledge
- **Status:** 🟢 Ready
- **Maintainer / contact:** via GitHub Issues and the project's developer mailing list

### [btcd](https://github.com/btcsuite/btcd)
An alternative full node implementation written in Go.
- **Languages:** Go
- **Looking for:** code, testing, documentation
- **Skills needed:** Go
- **Status:** 🟡 Limited
- **Maintainer / contact:** via GitHub Issues

## Wallets

> Desktop, mobile, and hardware wallet projects.

### [Sparrow Wallet](https://github.com/sparrowwallet/sparrow)
A desktop wallet emphasizing transparency and self-custody.
- **Languages:** Java
- **Looking for:** code, testing, UX feedback
- **Skills needed:** Java, JavaFX
- **Status:** 🆕 Beginner-friendly
- **Maintainer / contact:** via GitHub Issues

<!-- Add more wallets here using the entry template. -->

## Lightning Network

> Lightning node implementations and related infrastructure.

### [LND](https://github.com/lightningnetwork/lnd)
The Lightning Network Daemon, a complete Lightning implementation.
- **Languages:** Go
- **Looking for:** code, documentation, testing
- **Skills needed:** Go, Lightning/protocol knowledge
- **Status:** 🟢 Ready
- **Maintainer / contact:** via GitHub Issues and the project's community Slack

<!-- Add more Lightning projects here using the entry template. -->

## Libraries & SDKs

> Reusable libraries for building Bitcoin applications.

### [BDK (Bitcoin Dev Kit)](https://github.com/bitcoindevkit/bdk)
A modern library for building wallets and Bitcoin apps.
- **Languages:** Rust
- **Looking for:** code, documentation, examples/usages
- **Skills needed:** Rust
- **Status:** 🆕 Beginner-friendly
- **Maintainer / contact:** via GitHub Issues and the project's Discord

<!-- Add more libraries here using the entry template. -->

## Developer Tools

> Tooling for developing, testing, and debugging Bitcoin software.

<!-- Add developer tools here using the entry template. -->

## Block Explorers

> Self-hostable explorers and chain-analysis interfaces.

<!-- Add block explorers here using the entry template. -->

## Mining

> Mining software and pool infrastructure.

<!-- Add mining projects here using the entry template. -->

## Privacy

> Tools focused on transaction privacy and coin control.

<!-- Add privacy projects here using the entry template. -->

## Education & Documentation

> Books, tutorials, and reference material (open source repos).

<!-- Add education resources here using the entry template. -->

---

## Contributing

Contributions are welcome! Before submitting a project, please read the [contribution guidelines](CONTRIBUTING.md) to make sure it meets the inclusion criteria. In short:

1. Fork this repository.
2. Add your project to the appropriate section, in alphabetical order, using the
   entry template at the top of this file. Fill in **all** fields, and use a value from the status legend.
3. For the contact field, use a durable public channel (GitHub handle,
   Issues/Discussions, or a project chat) rather than a personal email.
4. Open a pull request describing the project and why it belongs here.

Keeping the `Status` and contact fields accurate is the most valuable ongoing contribution — if a project's readiness has changed, please open an issue or PR to update it. Suggestions to remove inactive or abandoned projects are equally welcome.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related rights to this work.
