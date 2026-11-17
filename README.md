# Automatron

I'm Matthias Mandiau. I build small tools that show you what actually happened — which setup command a project will run before you run it, whether an agent did what it said it did, which record sits behind an answer.

Most software asks you to trust the summary. These ask you to open it.

## Start here

**Before You Run** — paste a public GitHub link and read the install scripts before you download the coding exercise. Three unauthenticated requests to GitHub, no account, no analytics, no server of mine in between.
[Inspect a repository](https://mandiau-matthias.github.io/before-you-run/)

**Approval Binding Tests** — approve staging, then try to switch the destination to production. Eleven offline WebAuthn tests for substitution, expiry and replay.
[Run the tests](https://github.com/mandiau-matthias/approval-binding-tests#run-it)

**Argus Harness** — keep metric definitions, units, freshness and missing data visible across BigQuery, Snowflake, Redshift, Athena, Postgres, DuckDB, HTTP, CSV and static sources. One catalog for a code-owned dashboard and Looker Studio.
[Try the workshop](https://automatron-workflows.github.io/argus-harness/) · [Download v0.2.1](https://github.com/Automatron-workflows/argus-harness/releases/tag/v0.2.1)

**Inflectiv Source Inspector** — open the exact record behind an answer, then disconnect a source and watch the gap appear.
[Try both examples](https://mandiau-matthias.github.io/inflectiv-source-inspector/)

## The thread

These are the same question in different clothes: **can you check the claim, or only believe it?**

An inspection of install hooks says: here is the command, at this commit, before you run it. An approval-binding test says: you approved staging, so production must be refused. A source inspector says: here is the record the answer came from, and here is what disappears when it is disconnected.

I care about this because most of my career has been in analytics, where the number on the dashboard was usually right and occasionally quietly wrong. The quietly wrong ones are the expensive ones.

## Selected work

| Project | Something you can try |
| --- | --- |
| [Before You Run](https://github.com/mandiau-matthias/before-you-run) | Inspect the setup commands of a repository or the built-in example, without installing anything. |
| [Approval Binding Tests](https://github.com/mandiau-matthias/approval-binding-tests) | Approve staging, switch to production, and watch the suite refuse it. |
| [Inflectiv Source Inspector](https://github.com/mandiau-matthias/inflectiv-source-inspector) | Inspect the record behind an answer and handle a disconnected source. |
| [Trend Line](https://github.com/mandiau-matthias/trend-line) | Download editable Pine scripts and reproduce a weekly warning that cleared without a sell. |
| [Ilara Trend Spotter](https://github.com/mandiau-matthias/ilara-trend-spotter) | Replay fictional search and video observations, including a rise that did not last. |
| [Inflectiv Coffee](https://github.com/mandiau-matthias/inflectiv-coffee) | Change a brew at the coffee counter and inspect the fictional batch records behind the answer. |

<details>
<summary>More projects, contribution forks, and work from earlier roles</summary>

| Project | Something you can try |
| --- | --- |
| [Hardwire](https://github.com/Automatron-workflows/hardwire) | Turn a saved HTML form into a testable action contract without calling its endpoint. |
| [Functional Minimalism](https://github.com/Automatron-workflows/functional-minimalism) | Bring a design system and accepted decisions into the next screen brief. |
| [nosignal](https://github.com/mandiau-matthias/nosignal) | Contribution fork. Merged upstream in #32: portable browser fixtures and a backup-deletion test. |
| [counter-sign](https://github.com/mandiau-matthias/counter-sign) | Contribution fork. Passkey replay test across deployments. |
| [fakegreen](https://github.com/mandiau-matthias/fakegreen) | Contribution fork. Detects skipped tests and weakened assertions in AI-generated changes. |
| [8f4e](https://github.com/mandiau-matthias/8f4e) | Contribution fork. Removes a test-only fixture from the production API upstream #1200. |

Repositories from earlier roles — `llm-privacy`, `company-graph` and `valuation-iq` (Upswitch), `mercury-ab` (Despyke) — are public under their own copyright notices. They are not part of the work I promote here.

</details>

## Background

Ten years of product analytics and engineering. At PlayPilot I set up the experimentation programme and helped build the A/B framework behind sign-up and onboarding. In Stockholm I built Despyke's behavioural data platform. I wrote the first code for Inflectiv, where developers could publish and find datasets.

At Upswitch I built the workflow from importing accounts to producing a valuation report. In the forecast preview, a recorded zero could be mistaken for a missing earnings figure and be replaced with an estimate. I fixed it so that an accountant who entered zero would see zero. [The fix and its tests](https://github.com/UpswitchEU/venus/pull/108)

## Outside software

How do you tell the story of a place? For Unnavigated I wrote about my travels and photographed what caught my eye. At home in Belgium that curiosity took me into the kitchen — I'm developing Tafelreizen with my parents, dinners that pair homemade food with stories from the towns our family comes from in Belgian Limburg.

I'm open to hands-on engineering roles and collaborations on developer tools and data products. [Get in touch](https://matthias-mandiau-portfolio.lovable.app/#contact)
