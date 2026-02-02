# DAGknight-pv

A real-time visualization of Kaspa's DAGknight consensus protocol.

**[Live Demo](https://rossku.github.io/dagknight-pv/)**

## What you'll see

- Blocks arriving at 10 BPS (6000x Bitcoin's speed)
- Parallel blocks forming a DAG structure
- Conflict zones — where the "heaviest" path splits into parallel competing chains
- Blue/Red coloring — honest vs potentially adversarial blocks
- The Selected Chain — the heaviest path through the DAG
- LCCA (Latest Common Chain Ancestor) — where all paths converge and finality begins
- Active conflict zones with frequent reordering — watch consensus happen in real-time
- Linearization — parallel chaos becoming a single ordered sequence

## Features

- **Built-in interactive tutorial** — beginner-friendly guide to understanding DAGknight behavior
- **Live Kaspa mainnet connection**
- **DAG view** (parallel structure) & **Linear view** (ordered chain)
- **Pause mode** — freeze time to explore, switch views freely
- **Block Info panel** — tap any block to see hash, DAA score, blue score. Direct link to [kaspa.stream](https://kaspa.stream)
- **30 BPS simulation mode** — experience the future of Kaspa
- **dkoder-compliant algorithm implementation** (cascade voting not yet implemented)

## Usage

No install. No signup. Just open and watch consensus happen.
