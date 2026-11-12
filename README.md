<h1 align="center">Maxime Pierrot</h1>

<p align="center">
  Software engineering student at <strong>École 42</strong> — building things around <strong>data, machine learning and backend</strong>.
</p>

<p align="center">
  <a href="https://maxime-pierrot.com"><img src="https://img.shields.io/badge/Portfolio-maxime--pierrot.com-0A0A0A?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/maxime-pierrot"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:pierrot.maxime.49@icloud.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=maildotru&logoColor=white" alt="Email"></a>
</p>

> [!NOTE]
> **Looking for a 6-month internship in AI / Data development** — available from **December 2026**.
> Based in Rennes, mobile for **Paris / Rennes**. Fluent French, English C1. Resume on request — or just drop me a line.

## About

I came to code the long way round: psychology, then economics at the University of Angers, before joining **42** in 2023. That detour left me with a habit I still rely on — understand the problem properly before writing a single line.

- 🎓 **École 42 Angoulême** (2023–2027) — *Expert en architecture informatique*, RNCP level 7. Common Core done, now on the **databases & data / AI** track.
- 🔬 Currently digging into **retrieval, NLP pipelines and classical ML** — TF-IDF, cosine similarity, gradient descent, model evaluation. Writing the algorithms myself before reaching for a library.
- ⚙️ Equally at home in **C and systems programming** as in **TypeScript and Python** — three years of peer-reviewed projects will do that.
- 🧩 I care about code that the next person can actually pick up: small single-purpose modules, business logic kept out of the view layer, explicit names.

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Data & machine learning**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)

**Backend & infrastructure**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

## Selected projects

| Project | Stack | What it is |
| :--- | :--- | :--- |
| **[rag_discovery](https://github.com/MaximePirt/rag_discovery)** | TypeScript | The retrieval half of a RAG pipeline, built from scratch: document parsing, cleaning, tokenisation, chunking, TF-IDF vectorisation and cosine-similarity ranking. Split into swappable modules so embeddings or hybrid search can drop in — and the limits of a purely lexical approach are documented, not hidden. |
| **[ft_linear_regression](https://github.com/MaximePirt/ft_linear_regression)** | Python | Linear regression trained by gradient descent with **no ML library**. Training and prediction live in two separate programs, with learned parameters persisted between them. Scored **MAE 558 €** / **RMSE 668 €** on the dataset. |
| **[dslr](https://github.com/MaximePirt/dslr)** | Python · pandas · Matplotlib | Data exploration for a multiclass classification problem (the 42AI "Sorting Hat"): descriptive statistics computed by hand, pair plots and scatter plots to drive feature selection. |
| **[Ft_Transcendance](https://github.com/MaximePirt/Ft_Transcendance)** | Node.js · Fastify · React · SQLite · Docker | A real-time multiplayer quiz. I designed and built the **microservice backend** — auth with JWT and email-based 2FA, quiz engine, users and the social layer — plus WebSocket gameplay behind an Nginx reverse proxy. Each service containerised; team of 4. |
| **[Inception-of-Things](https://github.com/MaximePirt/Inception-of-Things)** | K3s · K3d · Vagrant · ArgoCD | Kubernetes and GitOps end to end: a multi-node K3s cluster provisioned with Vagrant, apps routed through a Traefik ingress, then a K3d cluster where **ArgoCD deploys straight from a Git repo**. |
| **[minishell](https://github.com/MaximePirt/minishell)** | C | A bash-like shell with a **recursive AST parser** — pipes, redirections, logical operators and syntactic precedence — process and signal handling via system calls, and autocompletion backed by a binary search tree. Built with one excellent teammate. |


Also around here: **[ft_irc](https://github.com/MaximePirt/ft_irc)** (an IRC server in C++), **[Cub3D](https://github.com/MaximePirt/Cub3D)** (raycasting engine in C), **[Philosophers](https://github.com/MaximePirt/Philosophers)** (threads and mutexes), **[Inception](https://github.com/MaximePirt/Inception)** (a multi-service Docker infrastructure) and the rest of the 42 Common Core.

## Get in touch

I'm always happy to talk about a project, an internship, or just how something works under the hood.

**[maxime-pierrot.com](https://maxime-pierrot.com)** · **[LinkedIn](https://linkedin.com/in/maxime-pierrot)** · <img src="https://cdn.simpleicons.org/discord/5865F2" height="14" alt="Discord" align="center"> **Discord:** `m_pinte`
