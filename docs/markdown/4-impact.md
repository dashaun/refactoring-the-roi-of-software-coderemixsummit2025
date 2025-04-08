### Good, Better, Best

Notes:
- I want to show you what I’ve been seeing
- out there
- across the customers I’ve worked with
- across industries
- across the globe.
- Most organizations fall into one of three buckets.
- Let’s walk through what I’m calling: Good, Better, and Best.
- Around Continuous Migration and OpenRewrite Adoption

---

### Good

- ✅ At least one N-0 application
- ❌ Not automated across all workloads
- ❌ Not migrating at scale
- 🔒 Preventing CVEs from going to production

Notes:
- In the 'Good' bucket, there’s usually at least one Big-A Application
- that’s made it to N-0, on Spring Boot 3.x and Java 21.
- That team found value, measured it
- They are leveraging OpenRewrite recipes, but manually
- But the effort hasn’t scaled organically
- Limited to a handful of teams
- Preventing CVEs from going to production, sounds good
- However, its also preventing the ***Reduction*** of CVEs from going to production
- Going from Spring Boot 2.3, to Spring Boot 2.4, closes CVEs, but not all of them

---

### Better

- ✅ Migration Automation
- ❌ Not automated across all workloads
- ✅ Knowledge & Visibility of Dependencies
- ✅ At least one "dead" dependency
- ✅ At least one "feature complete" N-0 application
- ✅ Measuring migration outcomes in $$$

Notes:
- Have migration automation in places (not everywhere)
- Know which libraries are in use but no longer supported
- The also know where those libraries are used
- Have migrated at least one "dead"/"unsupported"/"no longer maintained" dependency to something new
- Have multiple N-0 applications
- Have at least one application, that is no longer under active development, that is N-0

---

### Best

- ✅ Migration Automation Momentum
- ✅ Matured from reactive to proactive
- ✅ Migration Engineers
- ✅ Focused efforts at scale
- ❌ Struts

Notes:
- Teams/repositories are being added *monthly*
- The migration automation has its own *gravity* pulling in more workloads
- No need for internal marketing
- Have 2 or 3 migration engineers that know how to create and maintain OpenRewrite recipes for their internal projects
- Can identify which applications to focus on for the most value
- Can address critical issues quickly and at scale
- Still haven't migrated everything off of Struts
- but they know where Struts is being used
- They have a plan to address it

---

### Migration Engineers

- ❌ Not a title that they wear
- ✅ A responsibility that they share
- ✅ Increased Job Satisfaction

Notes:
- Let’s talk about these engineers for a second.
- They’re not wearing a special title. It’s not even their full-time job.
- But they’re curious, they learn the tooling, and they help others succeed.
- They deliver outcomes that affect the whole org.
- And you know what? They love this work.
- Because when you help reduce risk and improve performance at scale, that’s deeply satisfying.
