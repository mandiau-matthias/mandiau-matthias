# Automatron

I'm Matthias Mandiau. I build security tools for the person at the keyboard. Two decisions interest me in particular. What will happen if I run this project someone sent me? And if I approve one action, can the software quietly do something else?

### Before You Run

Someone sends you a coding exercise. Before cloning it, paste the public GitHub link into **Before You Run**. It shows the commands the root project can start during `npm install` and the files they come from. You can try a harmless example in one click. The check runs in your browser and never executes the project. Dependencies and the sender's identity are outside its scope. [Try Before You Run](https://mandiau-matthias.github.io/before-you-run/) · [Inspect the code](https://github.com/mandiau-matthias/before-you-run)

### What did the passkey approve?

A developer approves a commit for staging. An agent switches the destination to production. The signature is still valid. My deployment lab checks the arguments again just before execution. Remove that check and two of the 11 tests fail, one for a destination change and one for a commit swap. [Run the experiment](https://github.com/mandiau-matthias/approval-binding-tests#run-it) · [Upstream replay test](https://github.com/countersign-labs/counter-sign/pull/2)

### Fixes you can inspect

- **Session isolation at Upswitch.** I fixed a bug that could select the wrong access token when cookies identified conflicting sessions. [Merged fix and tests](https://github.com/UpswitchEU/venus/pull/38)
- **Backup deletion in NoSignal.** An autonomous agent submitted a browser test from my account covering password confirmation before backup deletion. The maintainer merged it. [Patch and attribution](https://github.com/DragonCuds/nosignal/pull/32)

I also publish Code Kai, which points developers to risky patterns in source code. [Code Kai on Apify](https://apify.com/automatron/code-kai-security-risk-scan)

I'm open to hands-on engineering roles and contracts in developer security. [Get in touch](https://matthias-mandiau-portfolio.lovable.app/#contact)
