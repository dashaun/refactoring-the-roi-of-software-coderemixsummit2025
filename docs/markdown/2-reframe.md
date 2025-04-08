<!-- This is the "Reframe"

Well prepared insights
Catch audience off guard with unexpected viewpoint
Looking for 'I never thought of it that way' response
This needs to teach the audience something new - not something they have already considered solutions for - define the next RFP
Do not be timid - surprise the audience
-->
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
Let’s zoom out.
Yes, you run tests locally, in your IDE, in your inner-loop, fast-feedback cycle.
But you have pipelines for integration, e2e, smoke, performance, and others, automated.
CI/CD fundamentally changed how we deliver software.  
Some of us remember "Patch Tuesday" right?
Now we have pipelines: reliable, testable, automatable.  
But while we’ve solved *delivery*, we haven’t solved *evolution*.  
We’ve actually made it easier to deploy outdated-software, faster.

---

### What CI/CD Did for Delivery 🚀
### CI/CM Can Do for Resilience 🛡️

- 🔄 Continuous Integration / Continuous Migration
- 📜 Codify migrations into policy
- ⚙️ Automate transformation
- 🌱 Keep your codebase evergreen

Notes:
Let’s introduce a new idea: **CI/CM**—Continuous Integration and Continuous Migration.  
CI/CD gave us speed. CI/CM gives us resilience.
With OpenRewrite, we can now treat migrations like we treat tests: automated, repeatable, safe.  
Not a big-bang refactor every 3 years—small, targeted changes every day.  
Modernization becomes a feature, not a fire drill.
I'll come back to Continuous Integration with Continuous Migration later.

---

![CI vs CM Pipeline](images/ci_cm_pipeline_looping_large.svg)

Notes:
Let’s visualize it.  
On top: your traditional CI/CD pipeline — Build, Test, Deploy.  
It’s streamlined. Safe. Automated.  
But we’re missing a layer: CI/CM.  
Imagine a system that detects drift from best practices, rewrites your code with verified recipes, and submits a pull request — **automatically**.  
Not once a year.
Every single day.
Or, every 3-hours, because that's how often the CVE databases get updated.

---

<!-- Slide 9 -->
## Migration Becomes a Continuous Background Process

* ✅ Like testing, e2e  
* ✅ Like security scans  
* ✅ Like deployments

Notes:
Automated recipes 
Policy-driven upgrades
Opt-in or opt-out guardrails
This is the future of software maintenance.  
We already do this with security scans. With tests. With dependency updates.  
Why not framework migrations?  
They should run quietly in the background, creating pull requests or patches, ready to be merged when you're ready.  
And most importantly—they should follow policy, not tribal knowledge.

migration engineers, not a title that they wear, but a responsibility that they share

---

## CVEs Are the Dinner Bell for bad actors
![CVE Dinner Bell](images/cve_dinner_bell.svg)

- New CVEs drop **daily**
- The larger your org, the larger the target
- Delay = exposure

⛔ Reactive patching ≠ security  
✅ Continuous patching = survivability

Notes:
Here’s a harsh reality: new CVEs are released every day.  
And for bad actors, CVEs are the dinner bell.  
If they don’t act, they don’t eat.  
And if your company is large, the buffet is bigger.  
We can’t afford to respond to vulnerabilities on a case-by-case basis anymore.  
Security has to be proactive. Continuous. Automated.

---

## It’s More Than Security
> “You’re stealing from your own wallet.”

- Java updates every 6 months
- Spring Boot every 6 months
- Upgrades = performance, efficiency, cost savings

💰 Efficient apps cost less to run  
📉 Measurable improvements, real money at scale

Notes:
Let’s go beyond security.  
If you’re not continuously upgrading Java or Spring Boot, you’re literally **stealing from your own wallet**.  
That’s what they say in the Netherlands—and they’re right.  
New versions bring better GC, more throughput, virtual threads, AOT.  
That’s not just theoretical. It means lower cloud bills, fewer servers, faster response times.  
Unlike CVE patching, **these benefits are measurable in real dollar values**.  
And when you multiply that across hundreds of services or millions of requests… it’s no longer optional—it’s a competitive advantage.
