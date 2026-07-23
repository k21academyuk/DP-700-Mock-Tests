# ⚡ DP-700 Mock Tests — Microsoft Fabric Data Engineer Associate

<div align="center">

[![Exam](https://img.shields.io/badge/Exam-DP--700-7b5ea7?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/credentials/certifications/fabric-data-engineer-associate/)
[![Level](https://img.shields.io/badge/Level-Intermediate-F25022?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/credentials/certifications/fabric-data-engineer-associate/)
[![Questions](https://img.shields.io/badge/Questions-150%20Total-FF6B35?style=for-the-badge)](https://github.com/k21academyuk/DP-700-Mock-Tests)
[![Mock Tests](https://img.shields.io/badge/Mock%20Tests-3-8A2BE2?style=for-the-badge)](https://github.com/k21academyuk/DP-700-Mock-Tests)
[![Made by K21 Academy](https://img.shields.io/badge/Made%20by-K21%20Academy-1B1A33?style=for-the-badge)](https://k21academy.com)

**Free, browser-based practice tests for the Microsoft Certified: Fabric Data Engineer Associate exam.**  
No sign-up. No install. No backend. Just open and practice.

[▶ Start Mock Test 1](./dp-700-mock-test-1.html) &nbsp;•&nbsp;
[▶ Start Mock Test 2](./dp-700-mock-test-2.html) &nbsp;•&nbsp;
[▶ Start Mock Test 3](./dp-700-mock-test-3.html)

</div>

---

## 📋 About This Resource

This repository contains **3 full-length DP-700 practice exam simulators** built and maintained by [K21 Academy](https://k21academy.com). Each simulator replicates the real exam environment with a live countdown timer, interactive question navigator, flagging system, and instant results with domain-wise feedback.

All **150 questions** are original, freshly written to match the style, difficulty, and topic coverage of the official DP-700 exam — aligned to the **skills-measured outline updated July 21, 2026**.

---

## 📦 Repository Contents

| File | Description |
|---|---|
| `index.html` | Landing page — choose your mock test |
| `dp-700-mock-test-1.html` | **Mock Test 1** — 50 questions (Starter) |
| `dp-700-mock-test-2.html` | **Mock Test 2** — 50 questions (Practice) |
| `dp-700-mock-test-3.html` | **Mock Test 3** — 50 questions (Challenge) |
| `README.md` | This file |

---

## 🎯 Exam Facts

| Detail | Value |
|---|---|
| **Exam Code** | DP-700 |
| **Certification** | Microsoft Certified: Fabric Data Engineer Associate |
| **Level** | Intermediate |
| **Product** | Microsoft Fabric |
| **Questions** | Approximately 40–60 |
| **Time Limit** | 100 minutes |
| **Passing Score** | 700 / 1000 |
| **Price (USD)** | $165 |

---

## 🗂️ Domain Coverage

All three mock tests are proportionally aligned to the official DP-700 **skills-measured blueprint**. Uniquely for DP-700, all three domains carry equal weight (30–35% each):

| # | Domain | Official Weight | Questions / Test |
|---|---|---|---|
| 1 | Implement and manage an analytics solution | 30–35% | **17** |
| 2 | Ingest and transform data | 30–35% | **17** |
| 3 | Monitor and optimize an analytics solution | 30–35% | **16** |

### What's tested within each domain

<details>
<summary><strong>Domain 1 — Implement and manage an analytics solution</strong></summary>

**Configure Microsoft Fabric workspace settings**
- Configure Spark, domain, OneLake, and Apache Airflow workspace settings
- Configure version control (Git integration with Azure Repos or GitHub)

**Implement lifecycle management in Fabric**
- Implement database projects
- Create and configure deployment pipelines (dev → test → prod)
- Promote and certify (endorse) Fabric items

**Configure security and governance**
- Implement workspace-level roles (Admin, Member, Contributor, Viewer)
- Implement item-level access controls
- Implement row-level, column-level, object-level, and folder/file-level security
- Implement dynamic data masking
- Apply sensitivity labels to Fabric items
- Implement and use Microsoft Fabric audit logs
- Configure and implement OneLake security

**Orchestrate processes**
- Choose between Dataflow Gen2, a pipeline, and a notebook for orchestration
- Design and implement schedules and event-based triggers
- Implement orchestration patterns with notebooks and pipelines including parameters and dynamic expressions

</details>

<details>
<summary><strong>Domain 2 — Ingest and transform data</strong></summary>

**Design and implement loading patterns**
- Full vs incremental data loads (watermark, change data capture patterns)
- Prepare data for loading into a dimensional model (SCD types, star schema)
- Design and implement a loading pattern for streaming data

**Choose appropriate data stores and tools**
- Choose between a Lakehouse, Warehouse, and KQL Database/Eventhouse
- Choose between Dataflows Gen2, notebooks, KQL, and T-SQL for transformation
- Create and manage OneLake shortcuts
- Implement mirroring

**Ingest and transform batch data**
- Ingest data using pipelines (Copy Data activity, data flows)
- Transform data using PySpark, SQL, and KQL
- Denormalize data; group and aggregate data
- Handle duplicate, missing, and late-arriving data
- MERGE/UPSERT patterns with Delta Lake

**Ingest and transform streaming data**
- Choose appropriate streaming engine (Eventstreams vs Spark Structured Streaming)
- Choose between native tables and OneLake shortcuts in Real-Time Intelligence
- Choose between Query acceleration and standard OneLake shortcuts in RTI
- Process data using Eventstreams, Spark Structured Streaming, and KQL
- Create windowing functions (tumbling, sliding, session)

</details>

<details>
<summary><strong>Domain 3 — Monitor and optimize an analytics solution</strong></summary>

**Monitor Fabric items**
- Monitor data ingestion and transformation
- Monitor semantic model refresh
- Configure alerts in Fabric
- Use Fabric monitoring hub and capacity metrics

**Identify and resolve errors**
- Identify and resolve pipeline errors and retry logic
- Identify and resolve Dataflow Gen2 errors
- Identify and resolve notebook errors
- Identify and resolve Eventhouse and Eventstream errors
- Identify and resolve T-SQL errors
- Identify and resolve OneLake shortcut errors

**Optimize performance**
- Optimize Lakehouse tables (OPTIMIZE, VACUUM, V-Order, Z-Order)
- Optimize pipeline performance (parallelism, concurrency, copy settings)
- Optimize data warehouse performance (statistics, caching, distribution)
- Optimize Eventstreams and Eventhouses
- Optimize Spark performance (executor sizing, caching, broadcast joins)
- Optimize query performance (predicate pushdown, partitioning, materialized views)

</details>

---

## ✨ Simulator Features

| Feature | Details |
|---|---|
| ⏱️ **Live countdown timer** | 100-minute timer matching the real exam; turns red at 5 minutes remaining |
| 🗺️ **Question navigator** | Visual grid showing answered ✅, flagged 🚩, and unanswered ⬜ questions |
| 🚩 **Flag for review** | Mark any question to revisit before submitting |
| 🔢 **4 question types** | Single-select, multi-select (select 2), ordering (sequence steps), matching (pair concepts) |
| 🛡️ **Tab-switch detection** | 3 warnings before automatic submission — simulating proctored conditions |
| ✅ **Confirm before submit** | Modal shows count of unanswered questions before final submission |
| 📊 **Results screen** | Scaled score (out of 1000), pass/fail at 700, domain-wise performance bar chart |
| 🔍 **Full review mode** | Your answer vs. the correct answer with a full explanation for every question |
| 📱 **Mobile-friendly** | Responsive layout works on phone, tablet, and desktop |

---

## 🚀 How to Use

### Option 1 — Run locally (no server needed)
```bash
git clone https://github.com/k21academyuk/DP-700-Mock-Tests.git
open dp-700-mock-test-1.html
```
Or simply **double-click** any `.html` file — no server or dependencies required.

### Option 2 — Host on GitHub Pages
1. Fork or push to your GitHub account
2. Go to **Settings → Pages**
3. Source: `Deploy from a branch` → `main` → `/ (root)`
4. Save — live at `https://<your-username>.github.io/DP-700-Mock-Tests/`

---

## ✏️ Editing and Adding Questions

Each file has one embedded `questions` array. Search for `const questions = [` to find it.

```js
// Single-select
{ "domain": "D1", "q": "...", "options": ["A","B","C","D"], "answer": [2], "explanation": "..." }

// Multi-select (exactly 2 correct)
{ "domain": "D2", "q": "...", "options": [...], "answer": [0,2], "multi": true, "explanation": "..." }

// Ordering
{ "domain": "D3", "type": "ordering", "q": "...", "items": [...], "correctSequence": [2,0,3,1], "explanation": "..." }

// Matching
{ "domain": "D1", "type": "matching", "q": "...", "left": [...], "right": [...], "correctMap": [1,3,0,2], "explanation": "..." }
```

`domain` must be `D1`, `D2`, or `D3`. All indices are **0-based**.

---

## 📚 Official Study Resources

| Resource | Link |
|---|---|
| DP-700 Certification Page | [Microsoft Learn](https://learn.microsoft.com/en-us/credentials/certifications/fabric-data-engineer-associate/) |
| DP-700 Study Guide | [Skills Measured Outline](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/dp-700) |
| Free Practice Assessment | [Microsoft Learn Practice](https://learn.microsoft.com/en-us/credentials/certifications/fabric-data-engineer-associate/practice/assessment?assessment-type=practice) |
| Microsoft Fabric Documentation | [learn.microsoft.com/fabric](https://learn.microsoft.com/en-us/fabric/) |
| K21 Academy DP-700 Course | [k21academy.com](https://k21academy.com) |

---

## ⚠️ Disclaimer

This is an independent practice resource created by K21 Academy. Not affiliated with or endorsed by Microsoft. "Microsoft," "Fabric," and "DP-700" are trademarks of Microsoft Corporation used for descriptive purposes only. All questions are original and do not reproduce content from official Microsoft certification exams.

---

<div align="center">

**Made with ❤️ by [K21 Academy](https://k21academy.com)**  
*Helping 46,000+ professionals across 40+ countries achieve cloud & AI certifications*

[![Website](https://img.shields.io/badge/Website-k21academy.com-0078D4?style=flat-square&logo=microsoft-azure)](https://k21academy.com)
[![YouTube](https://img.shields.io/badge/YouTube-K21Academy-FF0000?style=flat-square&logo=youtube)](https://youtube.com/@k21academy)

⭐ **If this helped you, please star the repo — it helps others find it too!**

</div>
