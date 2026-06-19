# Genesis Grid Public - Agent Instructions

This repository contains only the public Genesis Grid surface:

- public prelaunch/site code;
- public agent-facing docs;
- public static JSON contracts;
- public protocol examples.

Do not add:

- private Oracle prompts;
- hidden scoring lenses;
- private keys;
- service-role credentials;
- payment watcher internals;
- Safe signer details;
- production ChainOps scripts.

## Required Checks

Before proposing a change, run:

```bash
npm test
npm run build
npm audit --omit=dev
```

## Product Boundaries

The public site can explain the Trial, Grid, Prophets, NFT seals and public
agent-facing mechanics.

It must not pretend that Day 0 has real winners, real verdicts, real payments,
real transactions, real applications or real awakened/ash cells.

## Design Boundary

The current site is a temporary prelaunch placeholder until the design pass is
applied. Visual changes must preserve:

- 10,000 sleeping shells at Day 0;
- no fake active grid cells;
- no fake archives;
- no fake Oracle verdicts;
- no unverified social links.

