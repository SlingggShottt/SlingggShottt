# 👋 Hi, I'm Divyansh Pankaj Mishra

### 🚀 Software Development Engineer | MCA @ RV College of Engineering
Aspiring **AI \& Data Engineer** with hands-on experience in Python, FastAPI, Azure, Machine Learning, and Generative AI. I build **cloud native agentic AI systems and decision-intelligence platforms.** Currently pursuing MCA at **RV College of Engineering (GPA 9.12/10)** and BCA from BIT Mesra (GPA 8.51/10). Skilled in designing, building, and deploying AI/ML pipelines and distributed systems on AWS with Docker and CI/CD pipelines.

---

### 🛠️ Technical Stack

- **Languages:** Python, JavaScript, C++
- **Backend:** FastAPI, SQLAlchemy, Alembic, Pydantic, REST APIs, JWT Auth, Pytest
- **AI/ML:** LangChain, LangGraph, LangSmith, XGBoost, Pandas, NumPy, NLP, Generative AI
- **Databases:** SQL
- **Data Engineering:** Databricks, Power BI
- **DevOps & Cloud:** Azure, Terraform, Docker, GitHub Actions (CI/CD), Linux, Git

---

### 🚀 Featured Projects

#### 🏢 **FlowSpace - Multi-Tenant SaaS Project Management Platform**
*FastAPI, React, PostgreSQL, MongoDB, Redis, AWS, Terraform, GitHub Actions*
- Built the backend for a multi-tenant Jira-style project management SaaS with tenant-isolated workspaces — designed a 40+ endpoint async FastAPI REST API using a router–service–repository architecture, with PostgreSQL (SQLAlchemy async ORM, Alembic migrations) for core relational data and MongoDB for task comments and activity feeds.
- Implemented JWT authentication with access/refresh tokens and bcrypt hashing, role-based access control (Admin/Member) with team-scoped project visibility, Razorpay subscription billing across 3 tiers with plan-limit enforcement, in-app notifications, transactional emails via Resend, and an APScheduler cron job for daily overdue-task digests.
- Provisioned the Azure infrastructure (Linux VM, Azure Database for PostgreSQL Flexible Server, Azure Managed Redis, Blob Storage, VNet, NSGs, Managed Identity) as code with Terraform for one-command deploy and teardown; built a GitHub Actions CI/CD pipeline that runs 97 pytest tests against a PostgreSQL service container before auto-deploying the backend to the VM and static builds to Blob Storage.


#### 📦 **Argus — Agentic Supply Chain Decision Intelligence Platform**
*FastAPI, React, XGBoost, LangGraph, Groq (Llama 3.3 70B), AWS, Docker Compose*
- Built the backend and agent orchestration layer for an agentic AI decision-intelligence platform for supply chain demand forecasting and inventory risk management — designed a LangGraph state graph sequencing 3 deterministic agents (Forecast, Risk/Anomaly Detection, Inventory Optimization), plus a Groq-hosted LLM tool-calling agent for natural-language queries grounded in their structured outputs to reduce hallucination.
- Implemented XGBoost-based demand forecasting across 500 SKU-store combinations, benchmarking accuracy (MAPE) against a seasonal-naive baseline; built rule-based stockout detection, statistical (zscore) anomaly detection, and EOQ/safety-stock-based reorder point and quantity calculations.
- Exposed the full pipeline via a 5-endpoint FastAPI REST layer consumed by the dashboard; containerized the full stack with Docker for one-command local orchestration and deployed on Render.

#### 🤖 **LRU Cache Simulator — In-Memory Caching System**
*C++, STL (unordered map, list)*
- Designed and implemented an LRU (Least Recently Used) cache from scratch in modern C++, combining a hash map and doubly linked list via iterator-based node references to achieve O(1) time complexity for get, put, and eviction operations — using STL containers exclusively for RAII-based memory safety with zero manual allocation.
- Built a query simulation harness modeling real-world 80/20 access patterns (10,000+ queries across a 200-key space with 50 ”hot” keys), mimicking CDN and social-feed caching workloads, achieving an 89.97% cache hit ratio with live hit/miss tracking and periodic cache-state snapshots.
- Developed a self-contained automated test suite (8 test cases, 27 assertions, 100% pass rate) covering eviction ordering, capacity edge cases, and hit/miss counter accuracy, alongside a Makefile-based build system for one-command compilation, testing, and cleanup.
---

### 📊 Coding & GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SlingggShottt&show_icons=true&theme=radical" alt="GitHub Stats" width="400" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SlingggShottt&layout=compact&theme=radical" alt="Top Languages" width="300" />
</p>

<p align="center">
  <img src="https://leetcode-stats-six.vercel.app/?username=SlingggShottt&theme=dark" alt="LeetCode Stats" width="400" />
</p>

---

### 🎓 Education

- **Master of Computer Applications (MCA)** — RV College of Engineering, Bangalore | **GPA: 9.12**
- **Bachelor of Computer Applications (BCA)** — BIT Mesra, Jaipur | **GPA: 8.51**

---

### 📫 Connect with Me

- 📍 **Location:** Bangalore, Karnataka / Jaipur, Rajasthan *(Open to relocate & Remote)*
- 💼 **LinkedIn:** [Divyansh Pankaj Mishra](https://www.linkedin.com/in/divyansh-pankaj-mishra-4719b4204/)
- 🐙 **GitHub:** [SlingggShottt](https://github.com/SlingggShottt)
- 🟡 **LeetCode:** [SlingggShottt](https://leetcode.com/u/SlingggShottt/)
- 📧 **Email:** [slingggshottt.work@gmail.com](mailto:slingggshottt.work@gmail.com)
