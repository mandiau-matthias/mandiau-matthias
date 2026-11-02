# Automatron

I'm Matthias Mandiau. I build security tests for software that acts on someone's behalf. The question I keep coming back to is whether the action a person approves is the one the system actually performs.

## What did the passkey approve?

A developer approves a commit for staging. Before the deployment runs, an agent changes the destination to production. The signature is still valid. Should the worker accept it?

I built a local deployment worker, a software passkey and 11 tests so you can try it yourself. Remove the check that compares the final deployment arguments with the approved request and two tests fail. One catches the destination change. The other catches a commit swap. [Run the experiment](https://github.com/mandiau-matthias/approval-binding-tests#run-it) · [Read the tests](https://github.com/mandiau-matthias/approval-binding-tests/blob/main/test/deploy.test.mjs)

## Engineering in public

- **Session isolation at Upswitch.** I fixed a credential-selection bug in our valuation workspace. When cookies identify conflicting sessions, the server now withholds the access token. [Merged fix and regression tests](https://github.com/UpswitchEU/venus/pull/38)
- **Replay protection in counter-sign.** I submitted a test that hands a previously accepted passkey receipt to a second deployment. It checks how many times the guarded function actually runs. [Upstream pull request](https://github.com/countersign-labs/counter-sign/pull/2)
- **Backup deletion in NoSignal.** An autonomous agent submitted a browser-test change from my account. It exercises password confirmation before deleting a backup and removes machine-specific fixture paths. The maintainer merged it. [Patch and attribution](https://github.com/DragonCuds/nosignal/pull/32)

I also publish Code Kai on Apify. It scans supplied code for potential secrets, risky patterns and dependency advisories, and points to the affected lines. [Try Code Kai](https://apify.com/automatron/code-kai-security-risk-scan)

I'm open to hands-on engineering roles and contracts in agent security and developer tooling. [Get in touch](https://matthias-mandiau-portfolio.lovable.app/#contact)
