# Deep Clearance

<p align="center">
  <img src="DC_og_1200x630_v13_lockup.png" alt="Deep Clearance. Institutional intelligence." width="640">
</p>

Understand the system. Challenge the narrative.

Primary-source research on institutional power. Every answer comes with the source attached.

[deepclearance.com](https://deepclearance.com)

---

Deep Clearance is institutional intelligence for independent thinkers. It searches filings, court documents, released government files, patents, and interviews, and returns the passage with its source attached.

Every passage is labeled for what it can support. Documentation stays apart from inference, and the limits of the evidence are written down. Read the source. Draw your own conclusion.

The index is stored passages. It is not a live web crawl. About 1,476,000 passages sit under one standard. Classified documents are not in the index. Login does not mint a free key.

## Mission

To equip independent thinkers with the evidence and intelligence to understand the institutions, incentives, and decisions shaping our economic and political world, so they can challenge prevailing narratives with verifiable facts.

The work covers institutional mechanisms and incentives, monetary and economic context, and source trails, with an assessment of how strong each piece of evidence is. Unknowns are stated plainly. It does not assume hidden motives. It does not turn weak associations into allegations, or present a contested reading as settled fact.

## How a passage is labeled

Every passage carries two labels. Strength is what that passage can support. Depth is how far the writeup goes. A claim keeps the labels of the passages it actually uses.

**Strength**

- **S1** means the page shows the act. The dollar figure in a filing is S1 for that figure. An audit finding is S1 for the finding the report states. A lawsuit is S1 for what it alleges. A judgment, or another page that records the act, is what shows the act happened.
- **S2** means the papers force the conclusion even though no single page names it. If the contracts in the index cannot work unless someone is coordinating them, that coordination is S2.
- **S3** means it fits, and the documents do not rule it out, but they do not force it either. Motive, intent, and hidden coordination usually land here.
- **S4** means they said it about themselves. A press release, an official statement, or testimony about their own plans shows that they said it. A reason someone gives for an act stays S4 unless a different passage backs that reason.

**Depth**

Depth is not a second copy of strength. A government report can still quote a weak excuse. An essay can still quote a real filing.

- **T1** stays with what the institution put on paper. Filings, testimony, contracts, audits, and what that paper shows they did.
- **T2** is how the network got built. Who set it up, what they were paid to do, how the pattern spread. That only counts when the T1 papers are under it.
- **T3** is one argument, standing on its own, with the points that would knock it down written down.
- **T4** uses more than one of those arguments together, after each one has been checked on its own.

Contested subjects are read in full. When a subject has been labeled misinformation, deplatformed, or taken to court, Deep Clearance reads that history first. Who acted, when, and in what form, as the documents show it. Every major claim says how it could fail. The strongest account on the other side sits beside the thesis.

## What is in the index

Company files from chemical, drug, and oil firms. Court records, including the Epstein releases. Released CIA and FBI files. Patents. Federal Reserve transcripts from the 2008 crisis. The federal accounting standard for classified defense spending. Congressional hearings, oversight audits, contract awards, sanctions notices, SEC filings, and State human-rights reports. Interviews and talks, with the speaker named. Books as short excerpts. Research on financial control, institutional power, technology suppression, and the secrecy record.

Every plan searches the same documents. A plan buys days and a daily cap. Trial is 50 queries a day. Researcher is 250. Control is 500.

## How to start

1. Sign in with GitHub or Nostr.
2. Pay with Lightning. An upgrade keeps the same key.
3. Connect over MCP at [mcp.deepclearance.com/mcp](https://mcp.deepclearance.com/mcp). Claude uses OAuth from the [account](https://deepclearance.com/account/) page. Cursor and other clients send a Bearer key.
4. Ask. The passage comes back with the source attached.

## Where to read

| | |
| --- | --- |
| Product | [deepclearance.com](https://deepclearance.com) |
| About | [Mission and vision](https://deepclearance.com/about/) |
| Methodology | [How the labels stay apart](https://deepclearance.com/methodology/) |
| Docs | [Endpoint, tools, topic pins, caps](https://deepclearance.com/docs/) |
| Plans | [Trial, Researcher, Control](https://deepclearance.com/pricing/) |
| Checkout | [Start or change a plan](https://deepclearance.com/subscribe/) |
| Security | [Keys, checkout, and the index](https://deepclearance.com/security/) |
| Support | [Billing and keys](https://deepclearance.com/support/) |
| Terms | [Terms](https://deepclearance.com/terms/) |
| Privacy | [Privacy](https://deepclearance.com/privacy/) |

## Tools

| Tool | What it returns |
| --- | --- |
| `search` | Cited passages. If the reply says the index had no passage, stop there. |
| `get_passage` | The stored excerpt for a cite. Not a live crawl. |
| `verify_claim` | Whether a stored excerpt supports a claim. The judge is not a source. |
| `get_snapshot` | A dated report, replayed. It does not count against the daily cap. |
| `corruption_lookup` | Corruption events by actor, jurisdiction, mechanism, and date. Each event keeps its own standard. |
| `pattern_query` | A network or mechanism, with the events and cited passages. Each claim keeps its own standard. |

Pass `source` as one pin, or omit it to search the whole index. Pins include `financial_control`, `epstein_record`, `declassified_record`, `industry_record`, `wire`, `contractor_layer`, `postwar_record`, `disclosure_pressure`, `secrecy_labels`, `origin_literature`, `shelf`, `fiction_contamination`, and `system`. The [docs](https://deepclearance.com/docs/) hold the full list.

## Repositories

| Repo | What it is |
| --- | --- |
| [deepclearance.com](https://github.com/DeepClearance/deepclearance.com) | Source for the public site. |
| [.github](https://github.com/DeepClearance/.github) | This organization profile. |
