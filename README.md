# Yannick Maurice

**I'm a product leader in San Francisco, technical across hardware, software and infrastructure at scale.**

I've worked on motor control systems, LiDAR traffic intelligence for safety infrastructure, ML for battery analytics, mobile EV charging, grid orchestration for distributed energy, and space awareness for sovereign environments. Now it's AI systems for strategic work.

The throughline: make the technology disappear, and absorb the complexity so the person using it doesn't have to.

## What I'm building

**[Atelier](https://github.com/yannickYamo/atelier)** is an agentic system that builds AI skills from examples of the work you want: code reviews, financial reports, blog posts, contracts, support replies. The examples can be your own, your team's, or a style you admire. Its agents propose the rules behind the examples, with evidence, and you approve them once. Then it runs every output through a check, cuts invented claims instead of rewording them, and keeps improving the skill on its own. It installs a change only when it measures better, and it can never touch a rule you approved.

I built it for a failure I kept hitting: **perfect context, still variance.** I wanted output that stays stable over time, with less entropy from one run to the next, written in the voice I chose, at scale, without anyone supervising each draft. So Atelier keeps the rules in a file I approved, outside the model. When the model changes, the rules don't.

Every study is published, failures included.

**[Epitaph](https://github.com/yannickYamo/epitaph)** is an art installation. A language model runs on a small computer, and I take the computer away from it piece by piece while it thinks, until it dies. Then a new one is born. Every loss is real: a reading only ever reports something the machine just did. The model never changes; only its machine shrinks.

Three boards so far. The **Raspberry Pi 4** (4-core Cortex-A72, 4 GB) runs Qwen3 4B at 4-bit, 2.5 GB, and gets its voice from a prompt; it loses services, radio, light, screen, CPU, clock, memory, RAM, at about 1 token a second. v1.0, running. The **Tufty 2350** badge (RP2350, 8 MB PSRAM, $30) runs a 260,000-parameter model, float32, 1 MB. A model that small can't read instructions, so Qwen3 4B taught it the voice and the voice lives in the weights. It loses light, memory window, clock (250 to 48 MHz), screen, RAM, at about 8 tokens a second. It ran on the badge. The **ESP32** (Xtensa LX6, 520 KB SRAM, $5) runs the same 260K weights at int8, 260 KB in flash, losing light, memory window, clock (240 to 80 MHz), heap. It runs in a simulated ESP32 on my laptop, not yet on a real board.

More boards are planned. What I want to know across all of them: how much of what the model says comes from the model, and how much from the machine shrinking around it.

**[skills](https://github.com/yannickYamo/skills)** are AI skills for Claude Code: product marketing, strategy, GTM.

**[StratOS](https://getstratos.ai)** is a strategy operating system for early-stage teams. Founders, PMs and PMMs make the same high-stakes calls with far too little evidence: who it's for, what to say, what to charge, what to build next. StratOS produces the strategic work behind those calls (positioning, pricing, PMF diagnosis, GTM motion), then tracks whether your bets are still true as the company moves.

## How I think

Models are getting cheaper at everything objective. What stays scarce is the part that was always hardest to write down: what to emphasize, what to ignore, what feels wrong despite looking reasonable, which technically correct answer you'd never ship.

Agents now produce more than I can read. They can't own the outcome, and my attention doesn't scale with how many of them I run. My part is deciding what good looks like and checking that the work meets it.

Hardware taught me you can't hide behind iteration. You have to understand a thing all the way down to build it simply.
