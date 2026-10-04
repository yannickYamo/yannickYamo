# Yannick Maurice

**I'm a product leader in San Francisco, technical across hardware, software and infrastructure at scale.**

I've worked on motor control systems, LiDAR traffic intelligence for safety infrastructure, ML for battery analytics, mobile EV charging, grid orchestration for distributed energy, and space awareness for sovereign environments. Now it's AI systems for strategic work.

The throughline: make the technology disappear, and absorb the complexity so the person using it doesn't have to.

## Portfolio

**[Atelier](https://github.com/yannickYamo/atelier)** turns examples of the work you want into an AI skill, with rules you approve once that no model update can move. Every output is checked against them and anything invented is cut, so you get work in your voice, run after run, without reading each draft.

**[receipts](https://github.com/yannickYamo/receipts)** - a small open-source guard for agents that research the web. The rule is blunt: every claim carries a quote from a page that code fetched, or it gets cut. A model may point at evidence; only code may vouch for it. Code does the fetching, the model is allowed to quote and nothing more, then code checks the quote actually sits on the page and carries the claim's figures. A small reader model reads the claim against the full sentence on the page, and its only power is to cut. I built it because agent research keeps handing me prices, ratings and counts I can't check without redoing the work myself. The trigger: I ran a popular seven-agent sales example on its own sample request. Its card held 175 specifics and zero links. The model wrote VERIFY on its own output 23 times.

Results from a pre-registered test, misses included. Both stages together: 60 of 60 unsupported claims cut, 52 of 60 true ones kept. The code check alone failed its own bar at 43 of 50, which is why the reader exists. On real pricing pages it kept nothing the page didn't state but cut about one true fact in four, the next thing to fix. Red teamed with the source code in hand, 15 of 40 false claims got through. Every number is rebuilt by the test suite, and every miss is listed in the repo.

**[Epitaph](https://github.com/yannickYamo/epitaph)** is an art installation where a language model runs on a small computer that I take away from it piece by piece while it's still thinking, until it dies and a new one is born. You get to watch how much of what a mind says comes from the mind, and how much from the machine shrinking around it.

**[skills](https://github.com/yannickYamo/skills)** is a set of AI skills for Claude Code covering product marketing, strategy and go-to-market. You get an agent that does that work the way a senior operator would, from the first run.

**[StratOS](https://getstratos.ai)** helps early-stage teams decide who to sell to, what to say, what to charge and what to build next. Their agents read those decisions before building anything. Each decision spells out what would prove it wrong, and StratOS flags it when that happens.

## How I think

Models are getting cheaper at everything objective. What stays scarce is the part that was always hardest to write down: what to emphasize, what to ignore, what feels wrong despite looking reasonable, which technically correct answer you'd never ship.

Agents now produce more than I can read. They can't own the outcome, and my attention doesn't scale with how many of them I run. My part is deciding what good looks like and checking that the work meets it.

Hardware taught me you can't hide behind iteration. You have to understand a thing all the way down to build it simply.
