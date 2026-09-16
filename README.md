# Hi, I'm Pavlo Khomliuk 👋

**Software Development student at Munster Technological University · Backend & cloud-native developer · Applied AI**

I build event-driven backend systems and applied-AI tools, and I like owning a service end to end: from design and CI/CD through deployment, autoscaling, and teardown. Most of my work is in **Java / Spring Boot** and **Python / Django**, running on **Docker, Kubernetes, and Google Cloud**.

- 🎓 BEng (Hons) Software Development at MTU, Cork (2024 – 2028) · 2nd-year average **78.4%**
- 💼 Previously a backend developer at **NowTechStart**, building Django REST APIs for two commercial web apps
- 🔭 Currently working with Kafka-based microservices, RAG pipelines, and Model Context Protocol (MCP) agents
- 📍 Cork, Ireland

---

## 🚀 Featured projects

### [PriceWatch](https://gitlab.com/my-group9105233/pricewatch): event-driven price tracker
Four Spring Boot microservices communicating asynchronously over Apache Kafka, deployed to GKE Autopilot on Google Cloud.

- PostgreSQL on Cloud SQL, with Workload Identity for secure pod-to-database authentication
- Helm charts with per-environment values files; Horizontal Pod Autoscaling from 1 → 3 pods under load
- GitLab CI/CD with parallel tests, Docker images tagged by commit SHA, automatic deploy to dev, and a manual tag-gated deploy to prod with Helm rollback
- Total cloud spend kept under €6 using budget alerts

`Java` `Spring Boot` `Apache Kafka` `PostgreSQL` `GCP` `GKE Autopilot` `Helm` `GitLab CI/CD`

### [TaskFlow MCP](https://github.com/Pashokkkk/taskflow-mcp): task-management MCP server & agent
A custom Model Context Protocol server that exposes a task-management domain as seven typed tools over streamable HTTP.

- LangGraph agent that chains dependent tool calls to complete multi-step requests
- Client-agnostic design: drives both the custom agent and Claude Code with no integration code
- Containerised with Docker, tested with pytest, linted and built on every push via GitHub Actions

`Python` `MCP` `LangGraph` `Docker` `pytest` `GitHub Actions`

### [RAG Lecture Assistant](https://github.com/Pashokkkk/rag-lecture-assistant): Q&A over university lecture slides
A retrieval-augmented generation assistant using local embeddings, a Chroma vector store, and hybrid semantic + keyword retrieval.

- Found that 74% of the source corpus was duplicate content; deduplication raised **recall@4 from 0.88 to 1.00** on a hand-labelled test set
- Deployed on a free tier at €0 running cost

`Python` `RAG` `Chroma` `Embeddings` `Hybrid retrieval`

---

## 🗂️ Earlier projects

| Project | What it does | Stack |
|---|---|---|
| [Comment System](https://github.com/Pashokkkk/comment-sys-test) · [live demo](https://comment-sys-test.onrender.com/) | Comments with nested replies, JWT auth, CAPTCHA, file uploads, and live updates over WebSockets | Django, DRF, Vue 3, Channels, Docker |
| [Customer Conversion Predictor](https://github.com/Pashokkkk/customer_conversion_predictor) | Predicts whether a customer will buy based on behaviour data (Logistic Regression, tuned Random Forest) | scikit-learn, Pandas, Seaborn |
| [Smart Student Analyzer](https://github.com/Pashokkkk/student_analyzer) | Predicts final grades and risk of failure | scikit-learn, SQLite, Pandas |
| [Library Database System](https://github.com/Pashokkkk/library-database) | Windows Forms app to add, edit, delete, and search books | C#, SQL Server, ADO.NET |

---

## 💼 Experience

**Backend Developer (Django REST Framework)** · NowTechStart · Remote · *May – Aug 2025*
- Designed and built REST APIs for two commercial web applications, including PostgreSQL schemas, authentication flows, and core business logic
- Containerised services with Docker; handled API testing, debugging, and documentation for each release
- Worked with frontend developers in a distributed Agile/Scrum team, shipping features to sprint deadlines

---

## 🛠️ Tech stack

| Area | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/Django_REST_Framework-A30000?style=flat-square&logo=django&logoColor=white) ![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Cloud SQL](https://img.shields.io/badge/Cloud_SQL-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **Cloud & DevOps** | ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **AI & ML** | ![RAG](https://img.shields.io/badge/RAG-6E40C9?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-111111?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Chroma](https://img.shields.io/badge/Chroma-FF6446?style=flat-square) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |
| **Testing & tools** | ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) |

---

## 🌱 Beyond code

- 🏆 Winner of **Rivne Game Jam 2022**: team lead & developer, working game prototype in 48 hours
- 🔐 Regular attendee of **Cork|Sec**, the Cork security meetup
- 🏐 Volleyball with **VC West Cork Sharks** (Division 3)
- 🗣️ English (fluent) · Ukrainian (native) · Russian (fluent)

---

## 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pavlo_Khomliuk-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pavlo-khomliuk-234799251/)
[![Email](https://img.shields.io/badge/Email-homlukpavlo%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:homlukpavlo@gmail.com)
[![GitLab](https://img.shields.io/badge/GitLab-PriceWatch-FC6D26?style=flat-square&logo=gitlab&logoColor=white)](https://gitlab.com/my-group9105233/pricewatch)
