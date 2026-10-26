# 👋 Hi, I'm Divyansh Pankaj Mishra

### 💻 Software Engineer | MCA @ RV College of Engineering
Software engineer with strong **C++ and Python** fundamentals, a solid grounding in object-oriented design, operating systems and multi-threaded programming, and hands-on experience building, testing and shipping systems with CI/CD on Linux. Currently pursuing MCA at **RV College of Engineering (GPA 9.12/10)**; BCA from BIT Mesra (GPA 8.51/10). Experienced in Agile/Scrum workflows and in using modern AI tools to speed up design, coding and testing.

---

### 🛠️ Technical Stack

- **Languages:** C++, Python
- **Core CS:** Object-Oriented Design, Operating Systems, Multi-threading & Synchronization, Computer Networks
- **Backend:** FastAPI, SQLAlchemy, Alembic, Pydantic, REST APIs, JWT Auth, Pytest
- **AI/ML & AI Tools:** LangChain, LangGraph, LangSmith, XGBoost, Pandas, NumPy, Generative AI
- **DevOps & Tools:** Linux, Git, GitHub Actions (CI/CD), Docker, Make, AWS
- **Methodologies:** Agile, Scrum
- **Data & Databases:** SQL, Power BI

---

### 🚀 Featured Projects
<!--
#### 🏢 **FlowSpace - Multi-Tenant SaaS Project Management Platform**
*FastAPI, React, PostgreSQL, MongoDB, Redis, Azure, Terraform, GitHub Actions*
- Built the backend for a multi-tenant Jira-style project management SaaS with tenant-isolated workspaces — designed a 40+ endpoint async FastAPI REST API using a router–service–repository architecture, with PostgreSQL (SQLAlchemy async ORM, Alembic migrations) for core relational data and MongoDB for task comments and activity feeds.
- Implemented JWT authentication with access/refresh tokens and bcrypt hashing, role-based access control (Admin/Member) with team-scoped project visibility, Razorpay subscription billing across 3 tiers with plan-limit enforcement, in-app notifications, transactional emails via Resend, and an APScheduler cron job for daily overdue-task digests.
- Provisioned the Azure infrastructure (Linux VM, Azure Database for PostgreSQL Flexible Server, Azure Managed Redis, Blob Storage, VNet, NSGs, Managed Identity) as code with Terraform for one-command deploy and teardown; built a GitHub Actions CI/CD pipeline that runs 97 pytest tests against a PostgreSQL service container before auto-deploying the backend to the VM and static builds to Blob Storage.
-->

#### ⚡ [**LRU Cache Simulator — In-Memory Cache in C++**](https://github.com/SlingggShottt/lru-cache-simulator)
*C++, STL, Make*
- Implemented an in-memory LRU cache in modern C++ by pairing `std::unordered_map` with a `std::list` of nodes, storing list iterators in the map so that `get`, `put` and eviction all run in **O(1)** time; relied on RAII containers for leak-free memory management.
- Built a simulation runner that replays 10,000+ queries with an 80/20 skewed access pattern (80% of requests on 50 hot keys out of 200), reporting hit/miss counts and an **89.97% cache hit ratio**.
- Wrote an automated test suite of 27 assertions across 8 test cases (eviction order, key updates, capacity-1 edge case, hit/miss statistics), run through a Makefile build with `make test`.

#### 🧵 [**Bounded Producer–Consumer Queue & Thread Pool**](https://github.com/SlingggShottt/cpp-bounded-queue-thread-pool)
*C++17, std::thread, mutexes, condition variables, ThreadSanitizer*
- Built a dependency-free, thread-safe generic bounded blocking queue (one mutex, two condition variables) with backpressure, non-blocking `try_pop`, and graceful `close()` shutdown that lets consumers drain remaining items, plus a fixed-size thread pool on top of it with RAII shutdown (close, drain, join) and tasks executed outside the queue's lock.
- Deliberately reproduced and fixed classic concurrency bugs — lost updates, check-then-act races, missed wakeups, shutdown deadlocks — and measured the results: replacing busy-waiting with condition variables cut consumer CPU time from ~1–2 s to **0.002 s**, and a 10-task workload dropped from **1.0 s to 0.1 s** going from 1 to 10 workers.
- Verified the thread pool demo runs clean under ThreadSanitizer.

#### 📦 [**Argus — Agentic Supply Chain Decision Intelligence Platform**](https://github.com/SlingggShottt/argus)
*Python, FastAPI, XGBoost, LangGraph, Docker*
- Architected a modular LangGraph pipeline of 3 specialised agents (Forecast, Risk, Inventory) plus an LLM tool-calling agent that answers natural-language queries grounded in the agents' structured outputs, applying AI tooling to a multi-component system design.
- Built a global XGBoost forecaster across 500 SKU-store pairs, achieving **15.5% MAPE vs. 24.9%** for a seasonal-naive baseline (38% lower error); flagged 86 stockout-risk SKUs and computed EOQ/safety-stock reorder points.
- Exposed the system through a FastAPI service to a dashboard; containerized with Docker Compose and deployed on Render.

#### 📊 [**Power BI Data Modelling — Galaxy Schema from 23 Messy Source Tables**](https://github.com/SlingggShottt/powerbi-data-modelling-project)
*Power BI, Power Query (M), DAX, Dimensional Modelling*
- Modelled a deliberately messy 23-sheet Excel workbook into a governed galaxy schema: 6 fact tables, 6 dimensions, 33 Power Query queries, 14 loaded tables and 20 relationships, using transaction, periodic-snapshot, accumulating-snapshot, factless and mini-fact patterns plus a junk dimension and role-playing date and geography dimensions.
- Used a control-total check (`total_sales` = 526,643.91) after every merge to catch a hidden 27,518.94 revenue inflation caused by duplicate product names, then traced and fixed it at the dimension level.
- Implemented row-level security by region, a shared `dim_dates` with Auto Date/Time disabled, and a dedicated measures table.

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

- **Master of Computer Applications (MCA)** — RV College of Engineering, Bengaluru | Nov 2025 – Present | **GPA: 9.12**
- **Bachelor of Computer Applications (BCA)** — BIT Mesra (Off Campus Jaipur) | Aug 2022 – May 2025 | **GPA: 8.51**

---

### 📫 Connect with Me

- 📍 **Location:** Bengaluru, Karnataka / Jaipur, Rajasthan *(Open to relocate in India and abroad & Remote)*
- 💼 **LinkedIn:** [Divyansh Pankaj Mishra](https://www.linkedin.com/in/divyansh-pankaj-mishra-4719b4204/)
- 🐙 **GitHub:** [SlingggShottt](https://github.com/SlingggShottt)
- 🟡 **LeetCode:** [SlingggShottt](https://leetcode.com/u/SlingggShottt/)
- 📧 **Email:** [slingggshottt.work@gmail.com](mailto:slingggshottt.work@gmail.com)
