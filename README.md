# Hi, Welcome to Alessandro Bruno's Profile! 👋

As a Junior Full Stack Developer, I thrive on turning ideas into reality. My journey is fueled by a passion for open source and a deep appreciation for the Rust programming language. I'm always eager to learn, contribute, and tackle new challenges.

---
## 🎓 Education

**Bachelor's Degree in Computer Systems Technologies (Tecnologie dei Sistemi Informatici)** — University of Bologna
*Graduated July 10, 2026*

**Thesis:** *"Design and Development of PETRA, an Event-Driven Platform for Real-Time Asynchronous Telemetry and Analysis"*

---
## 💼 Work Experience

**Software Developer Intern** — [L'una S.r.l.](https://www.lunapartner.it) — 1 year

Worked across three projects for the company's clients:

1. **Fleet Tracking & Route Management System** — Backend in Spring Boot, frontend in Angular, mobile app in Expo (React Native), for a client managing street-sweeping vehicles. Routes were designed and assigned to vehicles from the Angular management dashboard; the mobile app, linked to a specific vehicle, showed the assigned route (not turn-by-turn navigation, but the streets to be swept). The dashboard displayed the vehicle's progress along the route in real time via WebSocket, as well as historical route data.

2. **Legacy System Maintenance** — Bug fixing (both frontend and backend) on a legacy management system built in Java and Angular, based on issues reported by the client.

3. **Event-Driven Microservices Architecture in Rust** — Designed and developed an event-driven microservices architecture using Rust, with Valkey for messaging and AWS S3 for persistence. Started early design work for a Kubernetes deployment. Built scalable, async code with Tokio, with observability provided by Grafana, Alloy, Loki, and Tempo.

---
## 🤝 Open Source Contributions

I believe in giving back to the community. Here are some of my recent contributions, including successful merges and valuable learning experiences.

- 🟡 [New UI & Dynamic port forwarding](https://github.com/zed-industries/zed/pull/55248) - `Open` in [zed-industries/zed](https://github.com/zed-industries/zed) - 
- ✅ [Add jdl language support](https://github.com/zed-industries/extensions/pull/3339) - `Merged` in [zed-industries/zed](https://github.com/zed-industries/extensions)
- 📦 [ducklake-orm](https://crates.io/crates/ducklake-orm) - `Published` on crates.io - a lightweight Rust ORM for DuckDB with derive-macro-based type-safe queries

---
## 💪 My Tech Stack & Confidence Level

*(See the legend below for a description of the competency levels.)*

### ⭐ Primary Technologies

#### 🦀 Rust - Competent
- **Backend:** Actix, Axum, Tokio
- **Frontend:** Leptos, Sycamore, Dioxus, Freya, Gpui, Topcat
- **Database:** Sqlx, Seaorm, Diesel, ducklake-orm
- **GameEngine:** Bevy
- **CLI:** clap, ratatui
- **WebAssembly:** wasm-bindgen, web-sys, js-sys

#### 💛 JavaScript & TypeScript - Competent
- **Frontend:** React, Angular, Svelte, Expo, React Native
- **Backend:** Express.js, NestJs
- **Styling:** Tailwind CSS, Storybook

#### ☕ Java - Competent
- **Spring Ecosystem:** SpringBoot
- **Enterprise:** JHipster, Hibernate
- **Build Tools:** Maven, Gradle

### 🛠️ Infrastructure & Tools

- **Containers & Versioning:** Docker, Git
- **Microservices & Event-Driven Systems:** designing and building distributed, event-driven microservices architectures
- **Messaging:** Valkey Streams/Queues, Redis
- **Databases:** PostgreSQL, DuckLake
- **Cloud Storage:** AWS S3

---

## 🌟 Featured Repos

1. **[Mnemosyne](https://github.com/alessandrobrunoh/Mnemosyne)** Sync Local History across all IDE's (Rust)

2. **[ducklake-orm](https://github.com/alessandrobrunoh/ducklake-orm)** Lightweight Rust ORM for DuckDB — derive macros, type-safe CRUD, connection pooling, migrations (Rust)

3. **[KetchApp](https://github.com/orgs/ketchapp-for-study)** (Rust, Java, Flutter)

4. **[VAPT Research](https://github.com/alessandrobrunoh/Relazione-Sicurezza-Privacy)** 

5. **[Briscola Online](https://github.com/alessandrobrunoh/Progetto-Ingegneria-Web)** (Vue, TypeScript)

6. **[ML Research](https://github.com/alessandrobrunoh/Progetto-Machine-Learning)** (Python)
   
## 🌟 Featured Forks
   
1. **[Zed](https://github.com/alessandrobrunoh/zed)** (Rust)
  
2. **[Juice Shop](https://github.com/alessandrobrunoh/Relazione-Sicurezza-Privacy)** 

---

## 🎯 Learning Goals

A set of projects planned to deepen my understanding of Rust across trading/blockchain, storage engines, distributed systems, and observability tooling — from low-level systems to high-level applications. Click on each project to learn more!

<details>
<summary><strong>1. [ ] Mini DEX on Solana — On-Chain Order Matching</strong></summary>

*   **Description:** A minimal decentralized exchange built as a Solana on-chain program (Anchor). Users deposit two SPL tokens, place buy/sell orders, and the program matches and settles compatible orders automatically via escrow PDAs.
*   **Key Concepts:** Cross-Program Invocation (CPI), Program Derived Addresses (PDA), SPL Token program, on-chain order matching logic.
*   **Why it's a good project:** Combines Web3/Solana skills with order-matching logic similar to real trading systems, under the stricter constraints of a blockchain execution environment.
*   **Repo:** [solana-mini-dex](https://github.com/alessandrobrunoh/solana-mini-dex)

</details>

<details>
<summary><strong>2. [ ] Mini Database Engine with B-Tree</strong></summary>

*   **Description:** An embedded database engine built from scratch: data persisted to disk in fixed-size pages, indexed with a B-Tree for efficient lookups, supporting insert/get/delete/range-scan.
*   **Key Concepts:** B-Tree data structure, page-based file I/O, serialization, write-ahead logging for durability.
*   **Why it's a good project:** Demonstrates deep understanding of on-disk data structures and storage engine internals, complementing ORM-level work like ducklake-orm.
*   **Repo:** [mini-db-btree](https://github.com/alessandrobrunoh/mini-db-btree)

</details>

<details>
<summary><strong>3. [ ] Load Testing Tool for Valkey-Backed Microservices</strong></summary>

*   **Description:** A load-testing and observability CLI for microservices that communicate through Valkey (pub/sub/streams) instead of direct HTTP. Measures end-to-end latency and consumer lag across the whole pipeline, with a live terminal dashboard.
*   **Key Concepts:** Pub/Sub and Streams, consumer lag/backpressure, async concurrency with Tokio, distributed observability.
*   **Why it's a good project:** Goes beyond generic HTTP load testing to address real event-driven architecture problems, directly relevant to Valkey/Redis-based infrastructure.
*   **Repo:** [valkey-loadtest](https://github.com/alessandrobrunoh/valkey-loadtest)

</details>

<details>
<summary><strong>4. [ ] Distributed Key-Value Store with Raft Consensus</strong></summary>

*   **Description:** A key-value store replicated across multiple nodes that stays consistent even if a node crashes, implementing the Raft consensus algorithm for leader election and log replication.
*   **Key Concepts:** Leader election, log replication, quorum/majority agreement, term numbers.
*   **Why it's a good project:** Hands-on understanding of consensus and replication, the same category of problem underlying real distributed databases and clustered Valkey/Redis deployments.
*   **Repo:** [raft-kv-store](https://github.com/alessandrobrunoh/raft-kv-store)

</details>

---

<details>
<summary><strong>📖 Competency Level Legend</strong></summary>

*   **Expert:** I have completed numerous complex projects independently.
*   **Proficient:** I have successfully completed several medium-complexity projects.
*   **Competent:** I have used the technology in projects for small/medium specific tasks.
*   **Familiar:** I have foundational knowledge and have done personal experiments.
*   **Exploring:** I’ve just taken a quick look at this technology.

</details>
