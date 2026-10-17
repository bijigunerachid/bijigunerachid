### Rachid

Full stack developer from Morocco, with a background in big data and machine learning.

I hold a Bachelor of Technology in Big Data from EST Fkih Ben Salah and a Diplôme de Développement
Digital from ISTA Tiznit. Before graduating, I did a three-month internship at OCP Group in
Khouribga, working on predictive maintenance and IT incident classification.

Most of what I build is a web app with a data or ML part behind it. I'm looking for a full stack,
data engineering or ML engineering role.

#### Projects

**[ecommerce-analytics-platform](https://github.com/bijigunerachid/ecommerce-analytics-platform)**
An e-commerce back office where every change (orders, stock, customers) is published to Kafka and
processed by Spark Structured Streaming. Events go through a transactional outbox, aggregates are
deduplicated by event id so the dashboard stays exact when Kafka redelivers, and a few simple
detectors flag unusual orders and stock write-offs.
React, Express, PostgreSQL, Kafka, PySpark, Prometheus, Grafana.

**[b2b-management-platform](https://github.com/bijigunerachid/b2b-management-platform)**
A back office for a wholesale distributor, plus a portal where its clients order directly. Quotes,
invoices with Moroccan VAT, partial payments, receivables, purchase orders and a stock ledger.
It has three models trained on the order history: a 4-week demand forecast used for reordering,
a late-payment risk score, and product recommendations.
React, Express, MySQL, scikit-learn.

**[Vendora](https://github.com/bijigunerachid/Multi-Tenant-E-Commerce-Management-SaaS)** (in progress)
A multi-tenant SaaS where several businesses manage their stores on one platform, with strict
tenant isolation and role-based access. Catalog, inventory, customers and
orders work; reports and background jobs are next.
React, Express, Prisma, PostgreSQL, Redis.

**[Segmentation-ISIC-](https://github.com/bijigunerachid/Segmentation-ISIC-)**
Skin lesion segmentation on ISIC 2018, comparing U-Net, SegNet and DeepLabV3. DeepLabV3 reached
a Dice score of 0.903 on the test set.
PyTorch, Streamlit.

#### Tools

JavaScript, Python, SQL. React, Node.js/Express, FastAPI, Django. PostgreSQL, MySQL, MongoDB,
Redis. Kafka, Spark, HDFS. scikit-learn, XGBoost, PyTorch. Docker, GitHub Actions, nginx.
Jest, Vitest, pytest, Playwright.
