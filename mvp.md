# What is a Minimum Viable Product (MVP)?

A **Minimum Viable Product (MVP)** is a development technique in which a new product or website is developed with sufficient features to satisfy early adopters. The final, complete set of features is only designed and developed after considering feedback from the product's initial users.

## Management Summary

A Minimum Viable Product (MVP) is a strategic product development approach focused on launching a new offering with just enough core features to satisfy early adopters and validate market demand. By prioritizing speed-to-market and capital efficiency over feature completeness, organizations mitigate financial and operational risk. The primary objective is not immediate commercial scale, but initiating a continuous feedback loop to guide iterative, data-driven product evolution based on real-world user behavior.

## Origin and History

The term **Minimum Viable Product** was coined around 2001 by **Frank Robinson**, though it was popularized and brought into widespread mainstream use later by **Eric Ries** through the Lean Startup methodology, as well as **Steve Blank** in his customer development framework. 

Frank Robinson originally defined the MVP while working on synchronized business models at SyncDev. Later, Eric Ries popularized the concept in his 2011 book *The Lean Startup*, defining it as that version of a new product which allows a team to collect the maximum amount of validated learning about customers with the least effort.

## Core Characteristics of an MVP

1. **Minimum:** It contains only the core features necessary to deploy the product and nothing more. It minimizes the time and effort spent building features that users might not actually want or need.
2. **Viable:** It must be functional enough to solve a real problem for the user and deliver core value so that early adopters are willing to use it or pay for it.
3. **Product:** It is a tangible solution (an app, website, service, or prototype) put in front of real users to generate actionable learning.

## Why Build an MVP?

- **Risk Reduction:** Validates market demand before investing heavy capital and engineering resources.
- **Faster Time-to-Market:** Gets the product into users' hands quickly.
- **Feedback-Driven Development:** Aligns future product iterations with actual user behavior and preferences rather than assumptions.

## Quality and the MVP

An MVP does not mean sub-par or broken quality. "Minimum" refers exclusively to the **scope of features** (building only what is necessary to test the core value proposition), not to the quality, reliability, or security of those features. If a product is buggy, unstable, or poorly engineered, users will attribute that poor experience to the product's overall value rather than its early stage, skewing feedback and invalidating the experiment. An MVP must still be robust, dependable, and usable enough to solve the specific user problem it targets.

## MVP vs. Proof of Concept (PoC) vs. Demonstrator

In product development, an MVP is frequently confused with other early-stage validation artifacts. They differ significantly in purpose, audience, and scope:

1. **Proof of Concept (PoC):**
   - *Focus:* Technical feasibility ("Can we build it?").
   - *Audience:* Internal engineering and technical teams.
   - *Nature:* A rough, internal experiment or prototype built to test a specific underlying technology, algorithm, or system architecture. It is usually discarded and not designed for production use.
2. **Demonstrator (Demo):**
   - *Focus:* Visual, conceptual, or stakeholder alignment ("What will it look like / how might it work?").
   - *Audience:* Investors, management, stakeholders, or potential clients.
   - *Nature:* A mock-up, simulation, or showcase model highlighting UI/UX concepts or system vision without requiring fully functioning backend logic.
3. **Minimum Viable Product (MVP):**
   - *Focus:* Market viability and behavioral validation ("Do people want it and will they use/pay for it?").
   - *Audience:* External early adopters and real end-users.
   - *Nature:* A fully functional, production-ready release containing only the core features needed to solve a real problem and initiate a feedback loop.

### How They Relate
In complex or high-risk innovations, a project might start with a **PoC** to prove technical viability, evolve into a **Demonstrator** to secure funding or alignment, and finally culminate in an **MVP** to test real-world market demand with actual users.

## The "Product-Over-Project" Mindset

In agile software development and lean product management, the **product-over-project** mindset is a foundational paradigm shift:

- **The Project Mindset:** Views software development as a finite, temporary undertaking with a fixed scope, schedule, and budget. Success is measured by delivering on time and on budget ("Did we build the thing correctly?"). Once delivered, the project is considered "finished" and handed off or maintained.
- **The Product Mindset:** Views software as an ongoing, evolving value stream centered around user needs and business outcomes. Success is measured by the continuous value delivered and metric-driven impact ("Are we building the right thing?"). 

### Relation to MVPs
An MVP is inherently a product-centric concept rather than a project-centric one. In a project mindset, an MVP might be misconstrued as just the first "phase" or "release milestone" of a rigid project plan. In a product mindset, an MVP is the starting point of an ongoing journey of experimentation, measurement, learning, and continuous iteration. It acknowledges that the initial release is only a hypothesis, and the team remains responsible for evolving the product based on continuous user feedback long after the initial launch.

### Does an MVP Stop Being an MVP When Features Are Added?
Yes. Once an MVP has launched, gathered user feedback, and is being actively iterated on with added features based on that validated learning, it has graduated from being an **MVP** into an **evolving product** (or a mature product version). An MVP is strictly a *starting point* or a *vehicle* designed specifically for initial market validation and learning. Once that hypothesis is tested and the product enters continuous development, the "minimum" and "experimental" constraints no longer apply in the same way.

## MVP and CI/CD (Continuous Integration, Delivery, and Deployment)

An MVP and CI/CD share a symbiotic relationship centered around speed, feedback loops, and risk reduction:

- **Enabling Rapid Feedback Loops:** The purpose of an MVP is to test hypotheses with real users and gather actionable learning. CI/CD automates the path from code change to production, ensuring insights gained from early adopters can be deployed, tested, and measured immediately without manual release friction.
- **Small Batches over Big Bang Releases:** Both practices emphasize small, incremental changes. Rather than waiting months to build and deploy a feature-complete product, an MVP combined with CI/CD allows teams to release small iterations, measure impact, and pivot or persevere rapidly.
- **Quality and Reliability:** Automated testing and integration (CI) ensure that even with a minimal feature set, code remains stable, secure, and robust every time changes are pushed.
- **Continuous Delivery/Deployment as the Lifecycle Engine:** Once an MVP transitions into an evolving product, a robust CI/CD pipeline becomes the operational backbone that sustains continuous learning and feature delivery.

## MVP and Documentation

In an MVP approach, documentation should mirror the philosophy of the product itself: lean, purposeful, and focused on speed and validation rather than exhaustive upfront planning. Over-documentation before launching an MVP can lead to wasted time if the product pivots based on user feedback. However, documentation remains essential for guiding development and enabling early users.

### Product Documentation vs. Project Documentation

There is a distinct difference in scope, audience, and intent between product documentation and project documentation within an MVP context:

- **Product Documentation (Specifications & Designs):** 
  - *Focus:* What the product is, how it behaves, and what features it includes (e.g., functional specifications, UI/UX wireframes, user stories).
  - *MVP Approach:* Kept minimal and high-level. Detailed feature specs for unvalidated ideas are avoided. Only the specifications required to build the core MVP value proposition are written down, allowing flexibility to change direction rapidly based on user testing.
- **Project Documentation (Installation, Setup & Operations):** 
  - *Focus:* How the project is built, deployed, configured, and run (e.g., `README` files, installation guides, deployment instructions, environment setup).
  - *MVP Approach:* Even a minimal product requires clear project documentation so that developers, stakeholders, or early adopters can actually install, run, and deploy it. While it should still be concise, having functional setup instructions is critical because code that cannot be run or deployed cannot serve as a viable MVP.

---

© 2026. All rights reserved.
