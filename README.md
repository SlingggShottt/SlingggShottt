# 👋 Hi, I'm Divyansh Pankaj Mishra

### 🚀 Software Development Engineer | MCA @ RV College of Engineering
I am a results-driven backend and cloud-native engineer passionate about designing, building, and deploying production-grade distributed systems. Currently pursuing my **Master of Computer Applications** in Bangalore with a **9.79 GPA**.

---

### 🛠️ Technical Stack

- **Languages:** Python, JavaScript, C++
- **Frameworks & Libraries:** FastAPI, Pytest
- **AI/ML:** LangChain, LangGraph, LangSmith, ML, DL, NLP, Generative AI, Pandas, NumPy
- **Databases:** SQL
- **DevOps & Cloud:** AWS, Docker, Terraform, GitHub Actions (CI/CD)
- **Tools:** Power BI, Git, Linux

---

### 🚀 Featured Projects

#### 📦 **Argus — Agentic Supply Chain Decision Intelligence Platform**
*FastAPI, React, XGBoost, LangGraph, Groq (Llama 3.3 70B), AWS, Docker Compose*
- Built the backend and agent orchestration layer for an agentic AI decision-intelligence platform for supply chain demand forecasting and inventory risk management — designed a LangGraph state graph sequencing 3 deterministic agents (Forecast, Risk/Anomaly Detection, Inventory Optimization), plus a Groq-hosted LLM tool-calling agent for natural-language queries grounded in their structured outputs to reduce hallucination.
- Implemented XGBoost-based demand forecasting across 500 SKU-store combinations, benchmarking accuracy (MAPE) against a seasonal-naive baseline; built rule-based stockout detection, statistical (zscore) anomaly detection, and EOQ/safety-stock-based reorder point and quantity calculations.
- Exposed the full pipeline via a 5-endpoint FastAPI REST layer consumed by the dashboard; containerized the full stack with Docker for one-command local orchestration and deployed on Render.

#### 🏢 **Multi-Tenant SaaS Platform (Jira Alternative)**
*FastAPI, React, PostgreSQL, MongoDB, Redis, AWS, Terraform, GitHub Actions*
- Built a production-ready project management platform featuring full tenant isolation, team-scoped visibility, JWT auth, and RBAC.
- Implemented **40+ REST API endpoints**, 3-tier Razorpay billing, drag-and-drop Kanban board, and automated email/in-app notification systems.
- Provisioned AWS infrastructure via single-command **Terraform** scripts and established GitHub Actions CI/CD executing **97 automated tests** on push.

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
