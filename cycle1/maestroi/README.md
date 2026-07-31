# NimConnect

> Human-friendly crypto starts here.

<img src="icon.png" alt="App icon" width="128">

| Field | Value |
| --- | --- |
| Category | Social |
| Pricing | Free |
| Team name | _Not provided — optional_ |
| Team members | _Not provided — optional_ |
| X account | https://x.com/nimiqminiapps |
| Contact email | meastro@protonmail.com |
| GitHub login | @maestroi |
| Submitted at | 2026-07-26T20:10:56.181Z |

## Links

| Link | URL |
| --- | --- |
| Repo | [https://github.com/NimMiniApps/NimConnect](<https://github.com/NimMiniApps/NimConnect>) |
| Demo | [https://nimconnect.nimiqminiapps.com](<https://nimconnect.nimiqminiapps.com>) |
| Video | [https://www.youtube.com/watch?v=vFwWc2TUGXw](<https://www.youtube.com/watch?v=vFwWc2TUGXw>) |

## Description

Nimiq wallets identify you by a 44-character address — hard to remember, awkward to share, impossible to build anything social around. NimConnect fixes that. Claim a permanent @handle, get a public profile, and use it to send, request, split, and tip NIM with people instead of strings. Contacts, shared trip buckets, and a handle marketplace round it out — and any Nimiq Mini App can plug into the same identity via the open profile-client package.

## Builder story

Every Mini App I tried re-solved "who is this wallet" from scratch, and users paid the tax of memorizing addresses. I wanted an identity layer other apps could reuse, not another silo. NimConnect answers four questions in one place — who am I (on-chain @handles, public profiles), who do I know (private, local-first contacts), how do we pay (send, request, split, tip), and how do we save together (shared trip buckets). Handles are ownable, so I built a marketplace to trade them with escrow-backed trades. Private data — notes, tags, contact history — never leaves the device; only what you choose to publish does. The whole thing ships as a reusable TypeScript client, so the next Mini App doesn't reinvent identity — it just resolves an @handle.

## Thumbnail

![Thumbnail](thumbnail.png)

## Screenshots

![Screenshot 1](screenshot-1.png)

![Screenshot 2](screenshot-2.png)

![Screenshot 3](screenshot-3.png)

![Screenshot 4](screenshot-4.png)

![Screenshot 5](screenshot-5.png)

---

_Generated from the submission form. `submission.yaml` in this folder is the machine-readable source of truth._
