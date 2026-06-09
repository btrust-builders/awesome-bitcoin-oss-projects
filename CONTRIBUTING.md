# Contributing

Thanks for helping grow this list! Contributions are welcome, whether you're adding a project, updating an existing entry, or flagging one that should be removed. This guide explains what qualifies and how to submit a change.

You don't need to be a developer to contribute. You can submit a change via a **pull request** (preferred) or simply by **opening an issue** and a maintainer will add it for you. See [How to contribute](#how-to-contribute) below.

## Contents

- [Inclusion criteria](#inclusion-criteria)
- [What doesn't belong](#what-doesnt-belong)
- [Table columns](#table-columns)
- [Status legend](#status-legend)
- [Readiness values](#readiness-values)
- [Adding an entry](#adding-an-entry)
- [How to contribute](#how-to-contribute)
- [Updating or removing an entry](#updating-or-removing-an-entry)
- [Review process](#review-process)
- [License of contributions](#license-of-contributions)

## Inclusion criteria

To be listed, a project must meet **all** of the following:

1. **Open source.** Released under an [OSI-approved license](https://opensource.org/licenses).
   "Source-available" or proprietary licenses don't qualify.
2. **Public repository.** The source must be publicly hosted (e.g. GitHub, GitLab, Codeberg) and browsable without an account.
3. **Actively maintained.** Meaningful commit activity within the **last 12 months**.
4. **Documented.** Has at least a README that explains what it is and how to get started, so a new contributor has somewhere to begin.
5. **Bitcoin-related.** Directly serves the Bitcoin ecosystem (protocol, wallets, Lightning, libraries, tooling, education, etc.).
6. **Open to participation.** Either accepts external contributions, or is a useful reference/learning project. Projects not currently accepting contributions may still be listed with a 🔴 **Paused** status.

If you're unsure whether a project fits, open an issue and ask before submitting.

## What doesn't belong

The following will generally be declined:

- Closed-source or source-available-but-not-OSI projects.
- Abandoned projects (no activity in over 12 months) — unless historically significant and clearly marked as a reference.
- Custodial services, exchanges, or commercial products with no open source component.
- Forks with no meaningful differences from their upstream project.
- Tokens, ICOs, or projects whose primary purpose is promotion or fundraising.
- Anything misleading, fraudulent, or designed to harvest funds or keys.

If you're unsure whether a project fits, open an issue and ask before submitting.

## Table columns

Each project is one row in its category's table. The columns, in order:

| Column | What goes in it |
| --- | --- |
| **Project** | The project name, linked to its source repository: `[Name](repo-url)`. |
| **Description** | One neutral, factual line. No marketing language. |
| **Languages** | Primary programming language(s), comma-separated. |
| **Status** | Project maturity — one value from [Status legend](#status-legend). |
| **Contributor Needs** | The *types* of contribution wanted (e.g. code, documentation, testing). |
| **Required Skills** | Technical/domain knowledge that helps (languages, frameworks, areas like cryptography). |
| **Readiness** | How approachable contributing is — one value from [Readiness values](#readiness-values), with an optional short note. |
| **Maintainer** | Maintainer GitHub **handle(s)** or a **durable, public** channel: a GitHub handle, the repo's Issues/Discussions, or an official project chat(Slack, Discord). **Do not list personal email addresses** — they go stale and create a privacy burden. |
| **Btrust Builders** | GitHub handles of Btrust Builders members active on the project, or `None confirmed yet`. |

## Status legend

Use exactly one of these values for the `Status` field:

- 🟢 **Ready** — actively welcoming contributors.
- 🆕 **Beginner-friendly** — has good first issues suitable for newcomers.
- 🟡 **Limited** — accepting help only in specific areas right now.
- 🔴 **Paused** — not currently accepting external contributions.

## Readiness values

Use one of these in the **Readiness** column. You may append a short clarifying note after an em dash (`—`):

- `Beginner-friendly` — has labelled good first issues for newcomers.
- `Intermediate`
- `Intermediate to advanced`
- `Advanced`

Examples:
`Beginner-friendly` ·
`Intermediate` ·
`Advanced — no labelled good-first issues; start with bitcoincore.academy`

Please don't invent new Status or Readiness values — if none fit, open an issue to discuss it.

## Adding an entry

Copy this row template, fill in every column, and place it in the correct category table in **alphabetical order**:

```
| [Project Name](repo-url) | One-line description. | Lang1, Lang2 | 🟢 Ready | code, documentation, testing | Rust, Lightning protocol | Intermediate | @maintainer | None confirmed yet |
```

If a project doesn't fit any existing category, open an issue proposing the new category rather than adding one ad hoc, so the structure stays consistent.

## How to contribute

### Option A — Pull request (preferred)

1. Fork the repository.
2. Add your row to the right category table, in alphabetical order, using the template above.
3. Open a pull request describing the project and why it belongs here.

Quick checklist before opening the PR:

- [ ] The project meets all [inclusion criteria](#inclusion-criteria).
- [ ] Every column is filled in.
- [ ] `Status` uses a value from [Status legend](#status-legend).
- [ ] `Readiness` uses a value from [Readiness values](#readiness-values).
- [ ] `Maintainer / Project Public Channel` is a GitHub handle or an official project chat(Slack, Discord) — not a personal email.
- [ ] The row is in alphabetical order within its section.
- [ ] The table still renders (the row has the right number of `|` separators).

### Option B — Open an issue

Not comfortable with pull requests? Open an issue titled "Suggest a project: <name>" with the repo link and as many columns as you can fill in. A maintainer will add it.

## Updating or removing an entry

Keeping entries accurate is one of the most valuable contributions:

- **Status changed or readiness changed?** Open a PR or issue to update it (e.g. a project moved from 🟢 Ready to 🔴 Paused).
- **Project went inactive or was abandoned?** Set `Status` to `Inactive` or suggest removal via an issue or PR.
- **Broken link or outdated info?** A small fix is always welcome.

## Review process

A maintainer will review your submission against the inclusion criteria and the column format. We may ask for small changes (a missing column, wording, a missing field, alphabetical order) before merging. Reviews are done as time allows, so thanks in advance for your patience.

## License of contributions

This project is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
By contributing, you agree that your contributions are dedicated to the public domain under the same terms.
