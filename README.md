# Hi, Welcome to Alessandro Bruno's Profile! 👋

As a Junior Full Stack Developer, I thrive on turning ideas into reality. My journey is fueled by a passion for open source and a deep appreciation for the Rust programming language. I'm always eager to learn, contribute, and tackle new challenges.

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
- **Frontend:** Leptos, Sycamore, Dioxus, Freya, Gpui
- **Database:** Sqlx, Seaorm, Diesel, ducklake-orm
- **GameEngine:** Bevy
- **CLI:** clap, ratatui
- **Ai:** Rig
- **WebAssembly:** wasm-bindgen, web-sys, js-sys

#### 💛 JavaScript & TypeScript - Competent
- **Frontend:** React, Angular, Svelte, Mastra, Expo, React Native
- **Backend:** Express.js, NestJs
- **Styling:** Tailwind CSS, Storybook

#### ☕ Java - Competent
- **Spring Ecosystem:** SpringBoot
- **Enterprise:** JHipster, Hibernate
- **Build Tools:** Maven, Gradle

#### C - Familiar
#### C++ - Familiar
#### 💎 Ruby - Exploring
#### 🧉 Kotlin - Exploring
#### 🦫 Go - Exploring
#### 🐍 Python - Familiar
#### 🤖 Flutter - Familiar

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

Here is a list of projects I'm planning to build to deepen my understanding more languages and their ecosystems, from low-level systems to high-level applications. Click on each project to learn more!

<details>
<summary><strong>1. [ ] Mini Database Engine with B-Tree</strong></summary>

*   **Description:** Build a simple, embedded database engine from scratch. It will support basic `CREATE`, `INSERT`, and `SELECT` operations, using a B-Tree index on disk for efficient data storage and retrieval.
*   **Key Concepts:** B-Tree data structure, file I/O, serialization, memory management, query parsing.
*   **Why it's a good project:** It's a challenging but incredibly rewarding project that demonstrates a deep mastery of data structures, performance, and systems programming in Rust.

</details>

<details>
<summary><strong>2. [ ] Solana Program (Smart Contract)</strong></summary>

*   **Description:** Develop and deploy a simple program on the Solana blockchain. For example, a decentralized voting system or a simple token minting dApp, and build a basic client to interact with it.
*   **Key Concepts:** Solana SDK, Anchor framework, on-chain program logic, client-side interaction, cryptography.
*   **Why it's a good project:** This project dives into the world of Web3, showing you can apply Rust's performance and safety to the exciting field of decentralized finance and applications.

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

---

## 🚀 Upcoming CV Projects

A set of projects planned to build deeper expertise in Rust across trading/blockchain, storage engines, distributed systems, and observability tooling.

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
