# LinkedIn Content Plan — Rachid Bijigune

A practical two-week plan to showcase full-stack development, data engineering, and applied machine learning. Publish only claims that match the current repository and screenshots.

## Posting schedule

| Day | Topic | Format | Goal |
|---|---|---|---|
| Day 1 | B2B Management Platform | Text + 2–3 real app screenshots | Show business-focused full-stack development and applied ML |
| Day 4 | Real-Time E-Commerce Analytics | Text + architecture diagram or dashboard screenshot | Show event-driven systems and streaming data engineering |
| Day 8 | Vendora SaaS | Text + real product screenshots | Show multi-tenant architecture and security thinking |
| Day 11 | Engineering lesson learned | Short text + diagram/code snippet | Demonstrate how you solve problems, not just list technologies |

Use real screenshots from each repository when possible. Do not use mockups that imply unfinished features are implemented. Never include credentials, tokens, private customer data, or environment files.

---

## Post 1 — B2B Management Platform

🚀 Building a useful business application takes more than CRUD operations.

I built a **B2B Management Platform** for wholesale workflows, bringing operational tools and applied machine learning into one application.

The platform covers:
- Customer, product and order management
- Quotes, invoices with Moroccan VAT, partial payments and receivables
- Stock tracking and supplier purchase orders
- Demand forecasting to support replenishment decisions
- Late-payment risk estimation
- Customer-specific product recommendations
- A help assistant supporting English, French and Arabic

The most interesting part was connecting machine-learning features to real business workflows instead of leaving them as isolated notebook experiments.

🛠️ **Stack:** React, Node.js, Express, MySQL, Python and scikit-learn.

🔗 Code: https://github.com/bijigunerachid/b2b-management-platform

I'm continuing to improve the application and strengthen my skills in full-stack engineering and applied ML.

#FullStackDevelopment #ReactJS #NodeJS #MachineLearning #SoftwareEngineering

**Visual:** Use 2–3 actual screenshots, ideally the dashboard, invoice/order workflow and ML feature. Confirm each screenshot reflects the current version.

---

## Post 2 — Real-Time E-Commerce Analytics

⚡ How do you turn everyday e-commerce operations into useful analytics without losing track of duplicate events?

I built a **Real-Time E-Commerce Analytics Platform** to explore the connection between a transactional application and a streaming data pipeline.

The flow combines:
- React for product, customer, order and inventory operations
- Node.js and Express for application APIs
- PostgreSQL for transactional data
- A transactional outbox to publish business events reliably
- Kafka to transport events
- Spark Structured Streaming to process events and maintain analytics
- Parquet for historical event data

A key engineering concern was correctness: the pipeline deduplicates events by ID so redelivery does not automatically mean that metrics are counted twice.

The project also includes detectors for unusual order activity and inventory write-offs, plus automated tests across major components.

🛠️ **Stack:** React, Express, PostgreSQL, Kafka, Spark Structured Streaming and Parquet.

🔗 Code: https://github.com/bijigunerachid/ecommerce-analytics-platform

This project has been a great way to explore how full-stack development and data engineering can work together.

#DataEngineering #ApacheKafka #ApacheSpark #PostgreSQL #FullStackDevelopment

**Visual:** Use the real dashboard screenshot plus a simple architecture diagram: application → PostgreSQL/outbox → Kafka → Spark Structured Streaming → Parquet/dashboard.

---

## Post 3 — Vendora Multi-Tenant SaaS

🏗️ Building a SaaS product changes the way you think about application architecture.

I'm developing **Vendora**, a multi-tenant e-commerce management platform where different businesses can manage their operations on a shared platform.

The project focuses on:
- Organizations and stores
- Team invitations, roles and permissions
- Product catalog, inventory, customers and orders
- Analytics and subscription workflows
- Tenant isolation so one business cannot access another business's data

One of the most important design questions in a multi-tenant system is not only whether a feature works, but whether every request is scoped to the correct tenant and permission.

🛠️ **Stack:** React, Node.js, Express, PostgreSQL, Prisma, Redis and Docker.

🔗 Code: https://github.com/bijigunerachid/Multi-Tenant-E-Commerce-Management-SaaS

I'm using Vendora to deepen my understanding of SaaS architecture, backend security, database design and deployment practices.

#SaaS #SoftwareArchitecture #ReactJS #NodeJS #PostgreSQL #WebDevelopment

**Before publishing:** verify that the README, demo and current code agree about project status. Show only features you can demonstrate. Never expose Stripe keys, webhook secrets or production credentials.

**Visual:** Use genuine screenshots of the dashboard/store management, team/roles and subscription page if those screens are implemented.

---

## Post 4 — Technical reflection (publish after the first three)

A technical project becomes much more valuable when you can explain the decisions behind it.

While building my projects, I'm learning to think beyond the happy path:
- How should a streaming pipeline behave when an event is delivered again?
- How can tenant boundaries be enforced consistently across API endpoints?
- How can a machine-learning prediction fit into a real business workflow?
- How do automated tests help protect those decisions as the application grows?

These questions are pushing me to connect frontend development, backend engineering, data systems and security rather than treating them as separate topics.

I'm continuing to build, test and document projects that reflect these skills.

🔗 GitHub: https://github.com/bijigunerachid

#SoftwareEngineering #FullStackDevelopment #DataEngineering #ContinuousLearning

**Personalize before posting:** add one specific example from code or a bug you actually solved. Do not claim a challenge or result unless it happened.

---

## Profile checklist

- [ ] Keep the profile README concise and consistent with each project's current status.
- [ ] Pin B2B Management Platform, Real-Time E-Commerce Analytics and Vendora.
- [ ] Add those three projects to LinkedIn's Projects section with their GitHub URLs.
- [ ] Add real screenshots or a short screen recording to the project READMEs.
- [ ] Check that each repository has clear installation steps, environment-variable examples (never secrets), test instructions and a license if appropriate.
- [ ] Check GitHub Actions status before describing tests as passing.
- [ ] Use the same professional headline across platforms: **Full-Stack Developer | React, Node.js, SQL | Big Data & Applied ML**.
- [ ] Reply to comments with concrete technical details and link to relevant code when helpful.

## Accuracy rules

- Do not invent users, production deployments, performance gains, customer outcomes or model results.
- Distinguish implemented features from planned work.
- For ML projects, explain the dataset, evaluation split and metrics; avoid implying a research model is a clinical tool.
- Never publish credentials, personal data, private datasets or secrets.
