# Part III & IV: Strategy and the Product Management Process

Part III demystifies **product strategy**, showing how to connect high-level company goals to autonomous team execution without micromanagement. Part IV introduces the **Product Kata**, a practical, repeatable process for exploring problems, testing solutions cheaply, and measuring real impact.

---

**Part III: Strategy**

## Chapter 7: What Is Strategy?

> **The Big Idea:** Strategy is not a rigid, detailed plan of features to build; it is a deployable decision-making framework that aligns autonomous teams around clear goals so they can adapt as reality unfolds.

### Core Concepts & Notes

- **Strategy vs. Planning:** A plan assumes the future is predictable and lists exact steps. A **strategy** acknowledges uncertainty, clarifies the goal and constraints, and empowers people closest to the ground to decide the best tactics.
- **Stephen Bungay's *The Art of Action* & The Three Gaps:** When leaders try to bridge intention and execution, three gaps emerge:
    1. **The Knowledge Gap:** The difference between what we would *like* to know and what we *actually* know. (Trying to close this with endless upfront analysis slows you to a crawl.)
    2. **The Alignment Gap:** The difference between what leaders *want* people to do and what people *actually* do. (Trying to close this with detailed micromanagement crushes autonomy.)
    3. **The Effects Gap:** The difference between what we *expect* our actions to achieve and what they *actually* achieve. (Trying to close this with rigid controls prevents learning.)
- **Mission Command (*Auftragstaktik*):** Borrowed from the 19th-century Prussian army. Instead of issuing step-by-step orders from headquarters, commanders communicate clear **intent** (the objective and why it matters) and grant field officers freedom to adapt their tactics to changing battlefield conditions.
- **Good Strategy Says "No":** Strategy is just as much about choosing what *not* to pursue as what to pursue. If everything is a priority, you have no strategy.

### Mind-Blowing Anecdotes & Stories

- **The Prussian Army vs. Napoleon:** After suffering devastating defeats to Napoleon, the Prussian military realised that rigid, top-down battle plans collapsed the moment the first cannon fired (the "fog of war"). By pioneering *Auftragstaktik* (Mission Command), Prussian officers could seize fleeting opportunities on the battlefield without waiting hours for messengers from headquarters. Perri applies this exact lesson to product teams: executives set the strategic intent, and product squads figure out the best product solutions on the ground.

### Memorable Quotes

> "Strategy is not a detailed plan. It is a framework that helps you make decisions."

> "Good strategy enables autonomy. It tells people where we are going and why, without dictating every step of how to get there."

---

## Chapter 8: Strategic Intents

> **The Big Idea:** Strategic intents translate high-level business goals into a small set of concrete, urgent business challenges that focus the entire organisation's energy.

### Core Concepts & Notes

- **What Is a Strategic Intent?** A clear statement of the most critical business problem or opportunity the company must tackle right now (typically over a 1-to-3-year horizon) to achieve its overarching mission and financial goals.
- **Less Is More:** Companies should have only **1 to 3 strategic intents** at any given time. Spreading teams across 15 competing "top priorities" guarantees mediocre execution everywhere.
- **Business-Outcome Framed, Not Feature-Framed:**
    - *Bad (Feature-framed):* "Build an AI chatbot and redesign the mobile app."
    - *Good (Intent-framed):* "Expand into the mid-market enterprise segment by reaching \$10M in enterprise ARR while keeping churn under 5%."
- **Connecting Executives to Product:** Strategic intents are owned by senior leadership (CEO, CPO, CFO, VPs) and grounded in real market analysis, competitive positioning, and financial reality.
- **Guardrails Included:** Good strategic intents specify both the target outcome and the constraints (budget, brand values, target segment) so teams know their boundaries.

### Mind-Blowing Anecdotes & Stories

- **Marquetly's Strategic Reset:** Previously, Marquetly's CEO would walk into quarterly planning with a laundry list of 12 feature ideas. Under the new framework, leadership analyses the financials and realises two brutal truths: small schools are churning after 90 days, and large school districts won't buy because of missing compliance and admin workflows. They strip the plan down to **two clear strategic intents**: (1) Improve 90-day retention in existing schools, and (2) Capture mid-sized school districts. Suddenly, every team knows what matters and what to drop.

### Memorable Quotes

> "Strategic intents tell your organisation what the biggest business challenges are right now, so teams can focus their creativity on solving them."

> "When executives hand down solutions instead of strategic intents, they rob their teams of the chance to find a better way."

---

## Chapter 9: Product Vision and Product Initiatives

> **The Big Idea:** Product vision paints the inspiring 3-to-5-year destination for customers, while product initiatives break strategic intents into concrete customer-problem themes that guide teams.

### Core Concepts & Notes

- **Product Vision:** A compelling, customer-centric picture of what the product will become in **3 to 5 years**. It answers: *What future are we creating for our customers, and why will they love us for it?*
    - Keeps day-to-day decisions from drifting into short-term local maxima.
    - Stable enough to rally teams, yet flexible enough to evolve as technology and markets shift.
- **Product Initiatives:** The bridge between company-level **Strategic Intents** and team-level **Options (features/experiments)**.
    - Framed as specific customer or product problems to solve (e.g., "Reduce teacher onboarding friction so new users create their first lesson within 15 minutes").
    - Owned by VPs, Directors of Product, and Senior PMs.
- **Why Initiatives Beat Feature Lists:** An initiative defines the *problem space* and *target metric* (e.g., activation rate), leaving the cross-functional squad free to discover and test multiple **Options** (solution hypotheses) to move that metric.
- **Value-Driven Roadmaps:** Instead of a Gantt chart of features and dates, an outcome-oriented roadmap communicates themes, problems being explored, and expected outcomes across "Now / Next / Later" horizons.

### Mind-Blowing Anecdotes & Stories

- **Amazon's Working-Backwards Press Release:** Perri highlights Amazon's famous practice of writing a mock internal press release and FAQ *before* writing a single line of code. By forcing teams to articulate the customer benefit in plain English as if the product had already launched, weak ideas get exposed immediately and the team stays anchored to a clear customer vision.

### Memorable Quotes

> "A great product vision describes the value you want to deliver to your customers in the future, not a list of technical specs."

> "Product initiatives translate business problems into customer problems that product teams can actually solve."

---

## Chapter 10: Strategy Deployment

> **The Big Idea:** Strategy deployment (inspired by Toyota's *Hoshin Kanri*) cascades goals up and down the organisation through structured two-way alignment, ensuring every team's daily work ties directly to company outcomes.

### Core Concepts & Notes

- **The Four-Tier Strategic Framework Cascade:**
    1. **Vision (Executive / CPO):** Where are we going in 3 to 5 years?
    2. **Strategic Intents (Leadership):** What are the 1 to 3 biggest business challenges right now?
    3. **Product Initiatives (Product Leadership / Directors):** Which customer problems must we solve to achieve those intents?
    4. **Options (Product Teams / Squads):** Which specific experiments, features, or improvements might solve those problems?
- **Catchball / Backbriefing (Two-Way Alignment):** Strategy is not a one-way memo sent from the C-suite. Each level reviews the intent from above, analyses reality on the ground, and **backbriefs** leadership on: (1) what they understood the goal to be, (2) what initiatives/options they propose, and (3) what resources or trade-offs are required.
- **Cadence of Strategy Reviews:** Strategy is not a once-a-year offsite that gathers dust in a slide deck. Product-led organisations review strategic progress quarterly (or monthly) using real outcome data, adjusting initiatives when assumptions are disproved.
- **Making Dependencies Visible:** Because teams backbrief openly, cross-team conflicts and shared platform bottlenecks surface early instead of causing last-minute fire drills.

### Mind-Blowing Anecdotes & Stories

- **Toyota's *Hoshin Kanri* (Policy Deployment):** Toyota famously avoids top-down command-and-control by using "catchball" (tossing ideas back and forth between executives, middle managers, and frontline teams). Frontline workers often spot flaws in executive assumptions immediately; by embedding their feedback into the strategy before execution starts, Toyota achieves far higher alignment and speed than traditional hierarchies.

### Memorable Quotes

> "Strategy deployment turns strategy from a static slide deck into a living conversation across the entire organisation."

> "Alignment does not mean everyone agrees on every detail; it means everyone understands the intent and how their work contributes to it."

---

**Part IV: Product Management Process**

## Chapter 11: The Product Kata

> **The Big Idea:** The Product Kata adapts the scientific method (via Mike Rother's *Toyota Kata*) into a daily habit of setting small target conditions, running rapid experiments, and learning your way towards big goals.

### Core Concepts & Notes

- **What Is a *Kata*?** A Japanese martial arts term for a structured, practised routine that builds muscle memory until good habits become second nature.
- **The Product Kata Loop:**
    1. **Understand the Direction:** What is the overarching vision, strategic intent, or product initiative?
    2. **Analyse the Current State:** Where are we today? What does the data and qualitative research actually show?
    3. **Establish the Next Target Condition:** What is the next small, measurable milestone we want to reach on the way to the bigger goal?
    4. **Identify the Obstacles:** What is currently stopping us from reaching that target condition? (Pick the single biggest obstacle first.)
    5. **Run Experiments (PDCA: Plan, Do, Check, Act):** Form a hypothesis to overcome that obstacle, run the smallest possible test, compare actual results against expected results, and reflect on what you learned.
- **Process Enables Learning, Not Bureaucracy:** Teams often copy Spotify or Scrum rituals blindly without understanding *why*. The Product Kata is framework-agnostic: it is simply disciplined scientific thinking applied to product uncertainty.
- **Threshold of Knowledge:** Always explicitly ask, *"What do we know, and what do we need to learn next?"* before jumping to solutions.

### Mind-Blowing Anecdotes & Stories

- **Why Copying Toyota's Tools Failed in Detroit:** For decades, Western automakers toured Toyota factories, copied Kanban boards and Andon cords, and still couldn't match Toyota's quality. Mike Rother discovered the secret wasn't the visible tools; it was the invisible daily coaching habit (**Toyota Kata**) where managers asked workers: *"What is your target condition? What is the actual condition now? What obstacle is in your way? What is your next step, and what do you expect to learn?"* Perri translated those exact coaching questions directly into product management.

### Memorable Quotes

> "The Product Kata is not a rigid framework; it is a way of thinking that helps you navigate uncertainty through continuous learning."

> "You don't need to know the entire path from start to finish. You only need to know your direction, your current state, and the very next experiment to run."

---

## Chapter 12: Understanding Direction and Setting Success Metrics

> **The Big Idea:** Before exploring solutions or writing code, you must define what success looks like in measurable customer behaviour, using actionable metrics rather than vanity numbers.

### Core Concepts & Notes

- **Vanity Metrics vs. Actionable Metrics:**
    - **Vanity Metrics:** Numbers that look impressive in board decks but don't tell you what to do next (total cumulative sign-ups, total page views, total downloads). They always go "up and to the right" even if the product is dying.
    - **Actionable Metrics:** Ratios, cohorts, and behavioural rates that clearly reflect value delivery and guide decisions (e.g., Day-30 retention rate, percentage of new users completing core setup within 24 hours).
- **Pirate Metrics (AARRR, by Dave McClure):** Ideal for mapping the commercial funnel and growth levers:
    - **Acquisition:** How do users find you?
    - **Activation:** Do they have a great first experience ("aha!" moment)?
    - **Retention:** Do they come back repeatedly?
    - **Referral:** Do they tell others about you?
    - **Revenue:** How do you monetise the value delivered?
- **Google's HEART Framework:** Ideal for measuring user experience quality on specific features or workflows:
    - **Happiness:** User satisfaction, NPS, perceived ease of use.
    - **Engagement:** Depth and frequency of interaction.
    - **Adoption:** New users trying a specific product or feature.
    - **Retention:** Users continuing to return over time.
    - **Task Success:** Efficiency, effectiveness, and error rate on key workflows.
- **Leading vs. Lagging Indicators:** Revenue and annual churn are **lagging indicators** (by the time they drop, the damage was done months ago). Product teams must identify **leading indicators** (e.g., weekly active usage, onboarding completion) that predict future revenue and retention.

### Mind-Blowing Anecdotes & Stories

- **The "1 Million Downloads" Illusion:** Perri points out how easily teams fool themselves with cumulative metrics. A startup can boast "1 million total registered users" while 98% of them abandoned the app after five minutes. Switching to cohort-based retention and activation rates immediately exposes the leaky bucket so teams stop pouring marketing money into a broken onboarding flow.

### Memorable Quotes

> "If you don't know how you will measure success before you build something, you have no way of knowing whether you succeeded."

> "Vanity metrics make you feel good; actionable metrics help you make good decisions."

---

## Chapter 13: Problem Exploration

> **The Big Idea:** Fall in love with the customer's problem, not your first solution; deep qualitative research uncovers the real root causes hiding behind surface-level feature requests.

### Core Concepts & Notes

- **Customers Are Experts on Their Problems, Not on Solutions:** When a customer says, *"I need an export-to-Excel button,"* don't blindly build it. Ask *"Why? What are you doing with that spreadsheet?"* You may discover they are manually reconciling broken data that your product could automate completely.
- **Generative Research Techniques:**
    - **Customer Interviews:** Open-ended questions focused on past behaviour ("Walk me through the last time you tried to do X"), never hypotheticals ("Would you use a feature that does Y?").
    - **Contextual Inquiry / Observation:** Watching users work in their real environment. What people *do* often contradicts what they *say* they do.
    - **Journey Mapping & Pain-Point Analysis:** Visualising every step a user takes to accomplish a job, highlighting friction, workarounds, and emotional drop-offs.
- **Triangulating Quantitative and Qualitative Data:** Analytics tell you **what** is happening and **where** users drop off; user research tells you **why**. You need both.
- **Involve the Whole Team:** Designers and engineers should sit in on user interviews directly. Reading a second-hand summary never builds the same empathy or sparks the same creative solutions as watching a user struggle first-hand.

### Mind-Blowing Anecdotes & Stories

- **Marquetly's Onboarding Breakthrough:** Marquetly assumed teachers were churning because the platform lacked advanced grading features. When the PM and designer actually watched teachers try to set up their first class, they saw teachers spending 45 minutes manually typing student names one by one because there was no bulk CSV import or school-roster sync. Most teachers simply gave up in frustration before ever reaching the grading tools.

### Memorable Quotes

> "Never ask customers what features they want. Ask them what problems they are trying to solve and watch how they solve them today."

> "Quantitative data tells you what is happening; qualitative research tells you why."

---

## Chapter 14: Solution Exploration

> **The Big Idea:** The goal of solution exploration is to validate whether an idea actually solves the problem with the least amount of time, code, and money possible.

### Core Concepts & Notes

- **What an MVP Really Is (and Isn't):** A Minimum Viable Product is **not** a buggy, half-baked version of your final software. It is the smallest experiment designed to test your riskiest assumption and maximise validated learning.
- **High-Leverage Experimentation Techniques (From Cheapest to Most Involved):**
    1. **Concept Testing & Storyboards:** Sketching the core workflow to test whether the value proposition resonates before designing screens.
    2. **Clickable Prototypes:** Interactive wireframes (e.g., Figma/InVision) that let users click through a simulated experience to test usability and comprehension.
    3. **Smoke Tests / Fake Door Tests:** Putting a button, landing page, or pricing option in front of users to measure real demand (clicks/sign-ups) before building the backend.
    4. **Concierge MVP:** Manually delivering the service behind the scenes while the customer *knows* a human is doing it, allowing you to learn every nuance of the workflow before automating.
    5. **Wizard of Oz MVP:** Presenting a seemingly automated front-end interface while humans manually fulfil the work behind the curtain.
- **Kill Bad Ideas Early:** Disproving a bad hypothesis in three days with a clickable prototype is a massive win, not a failure; it just saved engineering three months of wasted build time.

### Mind-Blowing Anecdotes & Stories

- **Groupon's WordPress Concierge MVP:** Before building a massive e-commerce platform, Groupon's founder Andrew Mason launched a simple WordPress blog posting one local deal a day. When people bought a deal, the team manually generated PDF coupons in FileMaker and emailed them via Apple Mail. That scrappy concierge test proved massive demand before they wrote serious software.
- **Zappos's Wizard of Oz Shoe Store:** In 1999, nobody believed people would buy shoes online without trying them on. Instead of buying millions of dollars of inventory and warehouses, founder Nick Swinmurn walked into local shoe stores, photographed shoes on the shelves, and posted them on a basic website. When someone placed an order online, he walked back to the mall, bought the shoes at retail price, and shipped them himself. Once customers proved they would buy shoes online, he built the real supply chain.

### Memorable Quotes

> "An MVP is not a smaller, crappier version of your product. It is the smallest thing you can build to learn whether your hypothesis is true."

> "The fastest way to waste engineering talent is to build production-grade software for an unvalidated idea."

---

## Chapter 15: Building and Optimising Your Product

> **The Big Idea:** Shipping to production is the starting line, not the finish line; great teams pair continuous discovery with Agile delivery, measure real post-launch impact, and ruthlessly iterate or sunset features.

### Core Concepts & Notes

- **Agile as a Means, Not an End:** Scrum, Kanban, and CI/CD exist to shorten feedback loops so you can deliver value incrementally and respond to change. Measuring Agile maturity by story-point velocity alone drags you straight back into the build trap.
- **Dual-Track (Continuous) Discovery and Delivery:** Product discovery doesn't stop once coding starts. Teams continuously explore upcoming problems while refining, building, and measuring current solutions in parallel.
- **Post-Launch Measurement Is Mandatory:** After releasing a feature, compare actual behaviour against your pre-defined success metrics (from Chapter 12). Ask: *Did it move the needle?*
- **Three Decisions After Measuring:**
    1. **Optimise / Double Down:** It worked, so refine usability, performance, and scale.
    2. **Pivot / Iterate:** The problem is real, but our solution missed the mark; test a different approach.
    3. **Kill / Sunset:** Nobody uses it and it adds maintenance drag; remove it cleanly to keep the product focused.
- **Technical Debt and Product Debt:** Every unused feature you leave sitting in the codebase slows down future engineering and clutters the user interface. Pruning is a core product skill.

### Mind-Blowing Anecdotes & Stories

- **Marquetly Sunsets Its Bloated Features:** Once Marquetly instruments proper analytics, they discover that over 60% of the features built in the previous two years are used by fewer than 2% of customers. Instead of continuing to patch and maintain that dead weight, they deliberately sunset unused modules, simplifying the interface for teachers and freeing up engineering capacity to double down on high-impact workflows.

### Memorable Quotes

> "Agile is not about building faster; it is about learning faster so you can build the right thing."

> "Shipping a feature is not the end of the product management process; it is the moment you finally find out if you were right."
