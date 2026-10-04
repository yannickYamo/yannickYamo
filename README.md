# Yannick Maurice

**I'm a product leader in San Francisco, technical across hardware, software and infrastructure at scale.**

I've worked on motor control systems, LiDAR traffic intelligence for safety infrastructure, ML for battery analytics, mobile EV charging, grid orchestration for distributed energy, and space awareness for sovereign environments. Now it's AI systems for strategic work.

The throughline: make the technology disappear, and absorb the complexity so the person using it doesn't have to.

## Portfolio

**[Atelier](https://github.com/yannickYamo/atelier)** is an agentic system that builds an AI skill from examples of the work you want: code reviews, financial reports, blog posts, contracts, support replies, whether the examples are yours, your team's, or a style you admire. Its agents propose the rules behind the examples with evidence, you approve them once, and every output is then checked against them: invented claims get cut rather than reworded, the skill installs a change only when it measures better, and it can never touch a rule you approved. I built it because of a failure I kept hitting, perfect context, still variance; the rules now live in a file outside the model, so when the model changes the rules don't, and every study is published, failures included.

**[receipts](https://github.com/yannickYamo/receipts)** is a small open-source guard for the output of AI agents that research the web: every claim carries a quote from a page that code fetched, or it gets cut. An agent that researches the web hands you prices, ratings and counts you can't check without redoing the research, and when I ran a popular seven-agent sales example on its own sample request I counted 175 pattern hits for specifics and not one link. On a pre-registered test both stages cut 60 of 60 unsupported claims and kept 52 of 60 true ones, while on real pricing pages it still cuts one true fact in four and a red team with the source got 15 of 40 false claims through.

**[Epitaph](https://github.com/yannickYamo/epitaph)** is an art installation: a language model runs on a small computer, and I take the computer away from it piece by piece while it thinks, until it dies and a new one is born. There are three boards so far, a Raspberry Pi 4 running a 4B model at about a token a second, a $30 badge running a 260,000-parameter model whose voice lives in the weights because a model that small can't read instructions, and a $5 ESP32 running the same weights in 260 KB of flash, so far only in simulation. What I want to know across all of them is how much of what the model says comes from the model, and how much from the machine shrinking around it.

**[skills](https://github.com/yannickYamo/skills)** is a set of AI skills for Claude Code covering product marketing, strategy and GTM.

**[StratOS](https://getstratos.ai)** is a strategy operating system for early-stage teams, built because founders, PMs and PMMs make the same high-stakes calls with far too little evidence: who it's for, what to say, what to charge, what to build next. It produces the strategic work behind those calls, positioning, pricing, PMF diagnosis, GTM motion, as a record the founder commits, with a threshold that would prove each bet wrong. Then it tracks whether the bets are still true as the company moves, and the team's agents read the record before they build.

## How I think

Models are getting cheaper at everything objective. What stays scarce is the part that was always hardest to write down: what to emphasize, what to ignore, what feels wrong despite looking reasonable, which technically correct answer you'd never ship.

Agents now produce more than I can read. They can't own the outcome, and my attention doesn't scale with how many of them I run. My part is deciding what good looks like and checking that the work meets it.

Hardware taught me you can't hide behind iteration. You have to understand a thing all the way down to build it simply.
