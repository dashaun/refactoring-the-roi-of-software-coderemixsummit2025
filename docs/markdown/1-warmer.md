<!-- This is the "Warmer"

The goal of the warmer:
Something to connect with the audience. Know the audience.
I have seen and heard some of these challenges from other customers very similar to yours
These 3 challenges come up as the most troubling
Is that what you are seeing? Or would you add something to that list?
-->

## Who Here Has Put Off a Migration?

- Too risky
- Too time-consuming
- Too many unknowns
- “We’ll do it next sprint…”

🤔 Sound familiar?

Notes:
How many of you have ever delayed a framework upgrade—not because you didn’t want to do it, but because it felt too risky, too time-consuming, or just plain exhausting?  
You’re not alone. Migrations are the software equivalent of moving apartments. Necessary, inevitable—and somehow always worse than you thought.  
We tell ourselves, ‘Let’s wait until the next sprint.’ Or worse—‘Let’s wait until there’s a breaking change.’

---
## Software over time

![Software over time](images/software_over_time_animated.svg)

Notes:

An idea that is still very popular, "we will upgrade that repository, the next time we touch it", however, it doesn't always play out that way.
This is a pattern we’ve all fallen into. Migrations feel like a side quest—something we’ll get to later, when it’s quieter, or safer.  
But that “later” often becomes “never,” and we end up shipping features on top of aging, brittle foundations.  
"We didn't have time to do the upgrade, but we really needed to get that feature out."
---

## Why Are Migrations So Hard?

* ❌ Not because they’re complex  
* ❌ Not because we’re lazy  
* ✅ Because we’re doing them **manually**  
* ✅ Over and over again

Notes:
- Let’s be honest—it’s not about capability.  
- Migrations aren’t hard because we don’t understand them.  
- They’re hard because they’re manual.  
- Because there’s no pipeline.
- No safety net.
- No way to validate changes until someone opens a PR and says, “hope this works.”

---

## What If…

We treated migrations not as a project…  
…but as a **process**?

* Let’s talk about **automation**.  
* Let’s talk about **OpenRewrite**.

Notes:
- But what if we flipped that thinking entirely?  
- What if migrations weren’t something we scheduled every 6 months—but something we ran in the background every day?  
- That’s the promise of continuous migration.  
- And that’s what OpenRewrite enables.  
- Let’s dig into what that looks like.
