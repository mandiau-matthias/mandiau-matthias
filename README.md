# Automatron

I'm Matthias Mandiau. I build security tools for developers. My work starts with everyday decisions like opening a coding exercise from a stranger or letting an AI agent deploy a change.

### Before You Run

A recruiter sends you a GitHub project and asks you to run `npm install`. Paste its public link into Before You Run to see the setup commands declared by the root package, with links to the exact revision. You can try the example in your browser before downloading anything. The tool never executes the project. [Try Before You Run](https://mandiau-matthias.github.io/before-you-run/) · [Read the source](https://github.com/mandiau-matthias/before-you-run)

### What did the passkey approve?

You approve a commit for staging. An agent changes the destination to production. The original signature still verifies. I built a deployment worker and 11 tests to check what happens next. Remove the final comparison and two tests catch the mistake, one for a destination change and one for a commit swap. [Run the tests](https://github.com/mandiau-matthias/approval-binding-tests#run-it) · [Review the proposed counter-sign test](https://github.com/countersign-labs/counter-sign/pull/2)

### Merged patches

- **Upswitch.** I fixed a bug that could select the wrong access token when cookies identified conflicting sessions. [Fix and regression tests](https://github.com/UpswitchEU/venus/pull/38)
- **NoSignal.** An autonomous agent submitted a browser test from my account covering password confirmation before backup deletion. [Patch and attribution](https://github.com/DragonCuds/nosignal/pull/32)

I also publish as Automatron on Apify, where Code Kai flags risky patterns in source code. [Automatron on Apify](https://apify.com/automatron) · [Code Kai](https://apify.com/automatron/code-kai-security-risk-scan)

Found an npm setup command the inspector misses? A small, public example and the output you expected would help me fix it. [Report a case](https://github.com/mandiau-matthias/before-you-run/issues)

I'm open to hands-on engineering roles and contracts in developer security. [Get in touch](https://matthias-mandiau-portfolio.lovable.app/#contact)
