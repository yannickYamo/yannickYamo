# Yannick Maurice

**I'm a product leader in San Francisco, technical across hardware, software and infrastructure at scale. Right now I'm building Atelier, which turns examples of good work into AI skills that stay consistent, and Epitaph, an art installation that runs a language model on a computer it slowly loses.**

I've worked on motor control systems, LiDAR traffic intelligence for safety infrastructure, ML for battery analytics, mobile EV charging, grid orchestration for distributed energy, and space awareness for sovereign environments. Now it's AI systems for strategic work.

The throughline: make the technology disappear, and absorb the complexity so the person using it doesn't have to.

## What I'm building

**[Atelier](https://github.com/yannickYamo/atelier)** is an agentic system that builds AI skills from examples of the work you want: code reviews, financial reports, blog posts, contracts, support replies. The examples can be your own, your team's, or a style you admire. Its agents propose the rules behind the examples, with evidence, and you approve them once. Then it runs every output through a check, cuts invented claims instead of rewording them, and keeps improving the skill on its own. It installs a change only when it measures better, and it can never touch a rule you approved.

I built it for a failure I kept hitting: **perfect context, still variance.** I wanted output that stays stable over time, with less entropy from one run to the next, written in the voice I chose, at scale, without anyone supervising each draft. So Atelier keeps the rules in a file I approved, outside the model. When the model changes, the rules don't.

Every study is published, failures included.

**[Epitaph](https://github.com/yannickYamo/epitaph)** is an art installation. It runs a language model on a small computer and takes the computer away from it, piece by piece, until the model dies. It started on a Raspberry Pi 4, where each life lasts thirty minutes: the machine shuts off the services around the model, its radio and its screen, then cuts its CPU and its memory, and a new model is born after each death. The model never changes. Only its environment shrinks, and every loss is real. A team of AI coding agents built that version in five days while I judged the art.

Now it's moving across hardware: a 260K-parameter model on a Tufty badge, taught its voice by the Pi's model, an ESP32 edition that has lived a whole life in simulation and is next for a real board, and more boards after that.

On each board I want to see how much of what the model says comes from the model, and how much from the machine shrinking around it.

**[skills](https://github.com/yannickYamo/skills)** are AI skills for Claude Code: product marketing, strategy, GTM.

**StratOS** (private) is a strategy operating system for early-stage teams. Founders, PMs and PMMs make the same high-stakes calls with far too little evidence: who it's for, what to say, what to charge, what to build next. StratOS produces the strategic work behind those calls (positioning, pricing, PMF diagnosis, GTM motion), then tracks whether your bets are still true as the company moves.

## How I think

Models are getting cheaper at everything objective. What stays scarce is the part that was always hardest to write down: what to emphasize, what to ignore, what feels wrong despite looking reasonable, which technically correct answer you'd never ship.

Agents now produce more than I can read. They can't own the outcome, and my attention doesn't scale with how many of them I run. My part is deciding what good looks like and checking that the work meets it.

Hardware taught me you can't hide behind iteration. You have to understand a thing all the way down to build it simply.
