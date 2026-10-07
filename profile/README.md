<p align="center">
  <img src="https://raw.githubusercontent.com/Ledgers-sh/.github/main/assets/logo-animated.svg" alt="ledgers.sh logo" width="96" height="96">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Ledgers-sh/.github/main/assets/org-banner.png" alt="ledgers.sh. Agents do the books. People keep control." width="100%">
</p>

<p align="center">
  <a href="https://ledgers.sh"><img src="https://img.shields.io/badge/SITE-LIVE-7FA6C9?style=for-the-badge&labelColor=0F1217" alt="Site: live"></a>
  <img src="https://img.shields.io/badge/LEDGERS-PLANNED-E9B44C?style=for-the-badge&labelColor=0F1217" alt="Ledgers: planned">
  <a href="https://factory0.ventures"><img src="https://img.shields.io/badge/FACTORY%20ZERO-VENTURE-E4E7EB?style=for-the-badge&labelColor=0F1217" alt="A Factory Zero venture"></a>
</p>

<p align="center">
  <sub>
    <a href="https://ledgers.sh">Site</a> &nbsp;·&nbsp;
    <a href="https://ledgers.sh/#policy">How it works</a> &nbsp;·&nbsp;
    <a href="https://ledgers.sh/#modules">Modules</a> &nbsp;·&nbsp;
    <a href="https://ledgers.sh/#pricing">Pricing</a> &nbsp;·&nbsp;
    <a href="https://ledgers.sh/llms.txt">llms.txt</a>
  </sub>
</p>

---

## Agents do the books. People keep control.

Bookkeeping is mostly reading documents and matching them. Agents can do that. What they
shouldn't do is post whatever they like. **Ledgers** is open-source accounting where AI agents
read invoices, match payments and draft entries, policy decides what they may post, and you
approve the rest.

- **One command surface.** The app, the CLI, MCP tools and the HTTP API run the same commands.
- **See what the agent saw.** Every extracted field links to its place on the source document, with a confidence score.
- **Know what will post.** A dry run shows every debit and credit before anything is posted. Everything is audited and reversible.

Free and open source (MIT) for a single user with your own AI model key.

---

## Agents propose, policy decides

| Tier | What an agent key may do |
| :--- | :--- |
| **Read** | Look up accounts, balances, documents and reports. Changes nothing. |
| **Draft** | Extract invoices, propose matches, draft journal entries for review. |
| **Post within limits** | Post entries up to a set amount, per currency. Anything above goes to a person. |
| **Human only** | Paying money out, closing periods and filing tax. Agents prepare; a person signs. |

---

## Status

| | What it is | Status |
| :--- | :--- | :--- |
| **Site** | [ledgers.sh](https://ledgers.sh): the landing page, `llms.txt`. | `LIVE` |
| **Ledgers** | The crates, CLI, MCP server, HTTP API, app and managed service. | `PLANNED` |

Nothing is released yet, and the site says so. Planned modules: `ledger`, `invoice`, `bills`,
`matching`, `bank`, `tax`, `documents`, `reports`, each a Rust crate on
[Cratefield](https://cratefield.com) with a CLI, MCP tools and an HTTP API.

---

## Repositories

| Repo | What it is |
| :--- | :--- |
| **website** | ledgers.sh: static HTML, no build step, Cloudflare Pages. Private |

---

<p align="center">
  <sub>A <a href="https://factory0.ventures">Factory Zero</a> venture</sub>
</p>
