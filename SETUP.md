# Weekly Research Report - Agent Setup

## What this repo is
This repository is automatically updated every Friday at 4pm EST by a Claude Code scheduled agent. Each week it adds one file: YYYY_MM_DD_Weekly_Report.md.

## Schedule
- **Frequency:** Every Friday
- **Time:** 4pm EST (8pm UTC)
- **Cron:** 0 20 * * 5

## What the agent does
1. Searches the web for research highlights from the past 7 days across 7 fields
2. Compiles a structured markdown report
3. Commits and pushes the file to this repo

## Fields covered
1. **Artificial Intelligence** - models, tools, techniques; focus on design & fabrication applications
2. **Computational Design** - generative/parametric design, CAD tools, fabrication-aware design
3. **3D Printing / Additive Manufacturing** - materials, hardware, flexible/soft printing
4. **Computational Sciences** - algorithms, simulations, topology optimization, physics-based sim
5. **Robotics** - manipulation, autonomous systems, new hardware platforms
6. **Soft Robotics & Compliant Mechanisms** - origami robots, inflatable/pneumatic actuators, deployable structures, shape-memory materials
7. **Biology & Medical Research** - disease discoveries, genetics, gene therapy, drug discovery

## Report format
Each file follows this structure:
- One ## section per field
- 3-5 bullet points per field: bold title + 1-2 sentence summary + source link
- Final ## Key Takeaways section with 3-5 cross-field highlights

## Agent config
- **Trigger ID:** trig_019nK9yTLVH2KybwYPpFx9Q2
- **Model:** claude-sonnet-4-6
- **Manage at:** https://claude.ai/code/scheduled
