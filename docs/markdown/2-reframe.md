### At the platform?
## Stop shifting left

- Pressure
- Time
- Energy

Notes:
- Once you get to the platform, you can stop shifting left.
- Developers have enough to deal with already.
- Developers are already tasked with maintaining software while also delivering business value.
- Fix these unscheduled/unplanned CVEs while simultaneously delivering the next feature on time.
- What I see, are not  migration problems, I see process problems.
- Having a powerful platform helps

---

## CI/CD Solved Delivery

* No one completes testing manually anymore
* Pipelines made releases safe, repeatable, fast
* ✅ CI/CD = Confidence + Velocity  
* ❌ Still no systematized modernization

Notes:
- Let’s zoom out.
- Yes, you run tests locally, in your IDE, in your inner-loop, fast-feedback cycle.
- But you have pipelines for integration, e2e, smoke, performance, and others, automated.
- CI/CD fundamentally changed how we deliver software.  
- Some of us remember "Patch Tuesday" right?
- Now we have pipelines: reliable, testable, automatable.  
- But while we’ve solved *delivery*, we haven’t solved *evolution*.  
- We’ve actually made it easier to deploy outdated-software, faster.

---

### What CI/CD Did for Delivery 🚀
### CI/CM Can Do for Resilience 🛡️

- 🔄 Continuous Integration / Continuous Migration
- 📜 Codify migrations into policy
- ⚙️ Automate transformation
- 🌱 Keep your codebase evergreen

Notes:
Let’s introduce a new idea:
**CI/CM**—Continuous Integration and Continuous Migration.  
CI/CD gave us speed.
CI/CM gives us resilience and more.
With OpenRewrite, we can now treat migrations
like we treat tests: automated, repeatable, safe.  
Not a big-bang refactor every 3 years—small, targeted changes every day.  
This way, Modernization becomes a feature, not a fire drill.

---

![CI vs CM Pipeline](images/ci_cm_pipeline_w.svg)

Notes:
- Let’s visualize it.  
- On top: your traditional CI/CD pipeline — Build, Test, Deploy.  
- It’s streamlined. Safe. Automated.  
- But we’re missing a layer: CI/CM.  
- Imagine a system that detects "drift".Drift in the form of best practices, CVEs, or N-0 library, framework or Java version
- Then, rewrites your code with verified recipes, and submits a pull request — **automatically**.
- Not once a year.
- Every single day.
- Or, every 3-hours, because that's how often the CVE databases get updated.

---

## Migration Becomes a Continuous Background Process

* ✅ Like testing, e2e  
* ✅ Like security scans  
* ✅ Like deployments
* ✅ Delivering value

Notes:
- This is the future of software maintenance.  
- We already do this with security scans. With tests. With dependency updates.  
- Now, we can deliver real business value.
- Not just a report about something that needs to be fixed.  With OpenRewrite, we are delivering the upgrade, as code!
- They should run quietly in the background, creating pull requests or patches, ready to be merged when you're ready.  
- And most importantly—they follow policy, not tribal knowledge.

---

#### CVEs Are the Dinner Bell for bad actors

<img src="images/dinnerbell.png" alt="CVE Dinner Bell" width="450"/>


Notes:
- Every new CVE that gets released
- Is ringing the dinner bell for the bad actors and hackers
- If they don't act quickly, they may not eat

---

* 🆕 New CVEs drop **daily**
* 🎯 The larger your org, the larger the target
* ⏳ Delay → Exposure → Risk
* ⛔ Reactive patching ≠ security  
* ✅ Continuous patching = survivability

Notes:
- The reality we live in: new CVEs are released every day.
- And if your company is large, the buffet is bigger, the target is bigger  
- We can’t afford to respond to vulnerabilities on a case-by-case basis anymore.  
- Security has to be proactive. Continuous. Automated.

---

<img src="images/worldbestciso.png" alt="World's Best CISO" width="425"/>

Notes:
- Patching CVEs is hard to measure in real dollar value.
- Patching CVEs does allow your CISO to sleep better at night.
- The best security teams know this.
- Burning down 10,000 CVEs last year looks great on paper.
- The real metric, for mature security teams, is time from CVE publish to CVE remediate
- That can only work with automation at scale.

---

#### "You’re stealing from your own wallet!"

Notes:
- Now, I want you think think beyond just security for a moment.
- I picked up this phrase during a recent visit to Netherlands, from my friend David.
- If you’re not continuously upgrading Java or Spring Boot, you are **stealing from your own wallet**.

---

* ☕  Java upgrades every 6 months 
* 🌱 Spring Boot upgrades every 6 months
* ⚡  Upgrades = performance, efficiency, cost savings
* 💰 Efficient apps cost less to run  
* 📉 Measurable improvements, real money at scale

Notes:
- Upgrading Java, upgrading Spring Boot, continuously, has real, measurable value
- New versions bring better GC, more throughput,
- Add in virtual threads, AOT and CDS.
- This is not just theoretical.
- CTO, CFO, CEO are all smiling
- when you lower cloud bills,
- require fewer servers,
- and deliver better performance to your customers and partners
- for your consideration:
- even a single-digit percentage improvement,
- multiplied across hundreds of services
- or millions of requests… 
- is no longer optional
- it’s a competitive advantage.
