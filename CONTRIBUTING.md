# Contributing

Thanks for helping grow this list! Contributions are welcome — whether you're adding a project, updating an existing entry, or flagging one that should be removed. This guide explains what qualifies and how to submit a change.

You don't need to be a developer to contribute. You can submit a change via a **pull request** (preferred) or simply by **opening an issue** and a maintainer will add it for you. See [How to contribute](#how-to-contribute) below.

## Contents

- [Inclusion criteria](#inclusion-criteria)
- [What doesn't belong](#what-doesnt-belong)
- [Entry format and field reference](#entry-format-and-field-reference)
- [Status legend](#status-legend)
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

## What doesn't belong

The following will generally be declined:

- Closed-source or source-available-but-not-OSI projects.
- Abandoned projects (no activity in over 12 months) — unless historically significant and clearly marked as a reference.
- Custodial services, exchanges, or commercial products with no open source component.
- Forks with no meaningful differences from their upstream project.
- Tokens, ICOs, or projects whose primary purpose is promotion or fundraising.
- Anything misleading, fraudulent, or designed to harvest funds or keys.

If you're unsure whether a project fits, open an issue and ask before submitting.

## Entry format and field reference

Each entry is a small block. Copy this template and fill in **every** field:

```
### [Project Name](repository-url)
One-line description of what the project does.
- **Languages:** Language1, Language2
- **Looking for:** e.g. code, documentation, testing
- **Skills needed:** e.g. Rust, protocol knowledge
- **Status:** 🟢 Ready
- **Maintainer / contact:** how to reach the team
```

Field-by-field:

- **Project name & link** — link the project name to its source repository.
- **Description** — one neutral, factual line. Avoid marketing language.
- **Languages** — the primary programming language(s), comma-separated.
- **Looking for** — the *types* of contribution the project wants: code, documentation, testing, design, translation, etc.
- **Skills needed** — the technical or domain knowledge that helps a contributor
  be effective (specific languages, frameworks, or areas like cryptography).
- **Status** — exactly one value from the [status legend](#status-legend).
- **Maintainer / contact** — a **durable, public** channel: a GitHub handle, the repo's Issues/Discussions, or an official project chat(Slack, Discord). **Do not list personal email addresses** — they go stale and create a privacy burden.

Add entries **alphabetically** within their category section.

## Status legend

Use exactly one of these values for the `Status` field:

- 🟢 **Ready** — actively welcoming contributors.
- 🆕 **Beginner-friendly** — has good first issues suitable for newcomers.
- 🟡 **Limited** — accepting help only in specific areas right now.
- 🔴 **Paused** — not currently accepting external contributions.

Please don't invent new status values — if none fit, open an issue to discuss it.

## How to contribute

### Option A — Pull request (preferred)

1. Fork this repository.
2. Find the right category section. If no category fits, see [requesting a category](#requesting-a-new-category) below.
3. Add your entry in alphabetical order using the template above, filling in all fields.
4. Commit and open a pull request. In the description, briefly say what the project is and why it belongs here.

A quick checklist before you open the PR:

- [ ] The project meets all [inclusion criteria](#inclusion-criteria).
- [ ] All fields are filled in.
- [ ] The `Status` uses a value from the legend.
- [ ] The contact is a public, durable channel (not a personal email).
- [ ] The entry is in alphabetical order within its section.

### Option B — Open an issue

Not comfortable with pull requests? Open an issue titled "Suggest a project: <name>" and include the project link plus as many of the fields above as you can. A maintainer will review and add it.

### Requesting a new category

If a project doesn't fit any existing category, open an issue proposing the new category and a short rationale, rather than adding it ad hoc. This keeps the structure consistent.

## Updating or removing an entry

Keeping entries accurate is one of the most valuable contributions:

- **Status changed?** Open a PR or issue to update it (e.g. a project moved from 🟢 Ready to 🔴 Paused).
- **Project went inactive or was abandoned?** Suggest removal via an issue or PR.
- **Broken link or outdated info?** Same — a small fix is always welcome.

## Review process

A maintainer will review your submission against the inclusion criteria and the field format. We may ask for small changes (formatting, wording, a missing field) before merging. Reviews are done as time allows, so thanks in advance for your patience.

## License of contributions

This project is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
By contributing, you agree that your contributions are dedicated to the public domain under the same terms.
