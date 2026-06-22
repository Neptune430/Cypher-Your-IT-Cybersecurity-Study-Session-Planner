# Cypher-Your-IT-Cybersecurity-Study-Session-Planner (🛡️ AI-Powered Cybersecurity Application)
### Built with Amazon Bedrock & PartyRock | AI Foundations Projects

---

![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-Powered-orange?style=for-the-badge&logo=amazon-aws)
![PartyRock](https://img.shields.io/badge/PartyRock-No--Code%20AI-blue?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)

---

## 📌 Overview

This repository documents two AI application projects completed as part of an AI Foundations discipline, built using **PartyRock** , Amazon's no-code generative AI playground powered by **Amazon Bedrock**. Both projects were designed with a deliberate focus: instead of building generic template apps, every application was tailored to solve real, daily problems faced by a working **cybersecurity analyst and tutor**.

These projects explore the intersection of **generative AI** and **cybersecurity education** — demonstrating how AI-powered tools can bring consistency, repeatability, and scale to learning and operational workflows that would otherwise depend on one-off chatbot conversations.

---

## 🧠 What is PartyRock?

PartyRock is Amazon's no-code AI application builder — think of it as the visual, accessible front end to **Amazon Bedrock**, the same enterprise-grade AI infrastructure used by Fortune 500 companies.

> **The distinction that matters:** PartyRock is the platform. The applications built on it — the problem framing, the input structure, the output logic, the use case — those belong to the builder.

---

## 📁 Project Index

| # | Project | Type | Status |
|---|---------|------|--------|
| 01 | [CYPHER — Cybersecurity Study Session Planner](#-project-01--cypher--cybersecurity-study-session-planner) | Productivity App | ✅ Live |
| 02 | [Body Measurements Data Analysis](#-project-02--body-measurements-data-analysis) | Data Analysis | ✅ Complete |

---

## 🔐 Project 01 | CYPHER — Cybersecurity Study Session Planner

### The Problem

As a cybersecurity analyst and tutor, one of the most consistent friction points I observed, in myself and in the students I mentor.. is the gap between *wanting to study* and *knowing how to study effectively*. A learner sits down with 45 minutes and a topic in mind, and within minutes they're scattered across YouTube, Reddit, documentation, and blogs with no structure, no direction, and nothing meaningful to show at the end of the session.

Generic chatbots can answer questions, but they can't replace a structured system. Every time you start a new conversation, you lose context, consistency, and continuity. There was no tool purpose-built for cybersecurity learners that could adapt to their level, respect their time, and produce the same quality output every single run.

**CYPHER was built to solve that.**

---

### What CYPHER Does

CYPHER is a personalized cybersecurity study session planner. A learner inputs four pieces of information and receives a fully structured, adaptive study session in return — every time, without fail.

---

### ⚙️ Input Fields

| Field | Description | Example |
|-------|-------------|---------|
| **Cybersecurity Topic** | The concept or skill to study | SQL Injection, MITRE ATT&CK, Phishing Investigation |
| **Experience Level** | Learner's current skill tier | Absolute Beginner / Junior Analyst / Intermediate / Advanced |
| **Available Study Time** | Time available in minutes | 30, 45, 60, 90 |
| **Learning Goal** | What the learner wants to walk away knowing | "Understand how buffer overflows work" |

---

### 📤 Output Widgets

**1. Personalized Study Plan**
A time-blocked session broken into four structured phases:

- 🔥 **Warm-Up** — Context setting and mental model activation
- 📖 **Core Learning** — Targeted resources, key concepts, field breakdowns
- 🧪 **Hands-On Practice** — TryHackMe rooms, real tools, live exercises
- ✅ **Review** — Retrieval practice, SOP snippets, next session planning

Each phase includes specific free resources (TryHackMe, HackTheBox, MITRE ATT&CK, YouTube channels), realistic time allocations, and guiding analytical questions.

**2. Knowledge Check**
Thirty quiz questions scaled to the learner's experience level — starting accessible and increasing in difficulty — with correct answers included for self-assessment.

**3. Key Takeaways & Next Steps**
A distilled summary of the session's most critical concepts, followed by two to three logical next-topic recommendations to maintain learning momentum.

**4. Analyst Tip of the Session**
One practitioner-level insight connecting the study topic to how it actually appears in a live Cybersecurity/SOC environment or penetration test engagement — the kind of context that textbooks don't give you.

---

### 🆚 CYPHER vs. A Regular Chatbot

One of the core objectives of this project was to experience and articulate the difference between a reusable AI application and a one-time chatbot conversation. Here's what that comparison revealed:

| Dimension | Regular Chatbot | CYPHER |
|-----------|----------------|--------|
| **Consistency** | Output varies every session | Same structure, every run |
| **Repeatability** | Requires re-prompting from scratch | Four inputs, instant structured session |
| **Shareability** | Conversation stays in your tab | Public link — share with any student |
| **Adaptability** | Generic unless heavily prompted | Adapts to level, topic, and time automatically |
| **Retention** | Lost when tab closes | Persistent, accessible anytime |

> *"A chatbot gives you a conversation. CYPHER gives you a tool. One lives in a chat window. The other lives at a link you can bookmark, share, and come back to every single day."*

The same phishing investigation study request was run through both ChatGPT and CYPHER. ChatGPT produced a solid, well-formatted response — but it was reactive, one-time, and non-transferable. CYPHER produced a structured, time-blocked, resource-rich session plan that a student at any level could follow independently. The difference was not the quality of the AI — it was the consistency of the system built around it.

---

### 🧪 Test Runs

CYPHER was tested across multiple input combinations to validate repeatability and adaptability:

- **Run 1:** SQL Injection / Absolute Beginner / 30 minutes / "Understand what it is and how it works"
- **Run 2:** MITRE ATT&CK Framework / Intermediate / 60 minutes / "Map TTPs to a real-world attack chain"
- **Run 3:** Phishing Investigation — Email Header Analysis / Junior Analyst / 45 minutes / "Learn how to analyze email headers to identify phishing indicators"

Each run produced a completely different output tailored to the inputs — while maintaining the same structural quality standard across all sessions.

---

### 🔗 Live App

> 🚀 **[Launch CYPHER on PartyRock](#)** ← *((https://partyrock.aws/u/cremescene/9P7alB2qO/CyPher%253A-Your-IT-and-Cybersecurity-Study-Session-Planner))*

---

---

## 📊 Project 02 | Body Measurements Data Analysis

### The Problem

Raw data means nothing without the right questions. The ability to interrogate a dataset, identify patterns, spot anomalies, and communicate findings clearly is a foundational skill — not just in data science, but in cybersecurity. SOC analysts do this every day: they establish behavioral baselines, detect statistical outliers, and determine whether deviations are noise or signal.

This project used PartyRock's **Analyze Data** feature to practice exactly that analytical mindset — applied to a body measurements dataset, and interpreted through the lens of a security analyst.

---

### Dataset

**Source:** BodyM Dataset (Body Measurements)
**Content:** Numerical body measurement data including height, weight, and related physical metrics across multiple subjects.
**Format:** Structured tabular data (CSV)

---

### Analytical Questions Asked

Three targeted questions were posed to PartyRock's Whiskers AI to extract meaningful insights:

**Question 1 — Baseline & Central Tendency:**
> *"What is the average height and weight across the entire dataset, and are there any entries that fall significantly outside the normal range?"*

**Analyst framing:** Establishing baselines is the first step in any behavioral analytics workflow. In a SIEM environment, this is how User and Entity Behavior Analytics (UEBA) tools build normal profiles before flagging deviations.

**Question 2 — Correlation Analysis:**
> *"Is there a strong correlation between height and weight in this dataset? Are there any unexpected relationships between other measurements?"*

**Analyst framing:** Correlation analysis in cybersecurity surfaces hidden relationships — lateral movement patterns, co-occurring events, linked user behaviors. Unexpected correlations are often where the most interesting findings live.

**Question 3 — Anomaly Detection:**
> *"Which data points or entries appear to be anomalies or outliers compared to the rest of the dataset, and what could explain them?"*

**Analyst framing:** Anomaly detection is the foundation of threat hunting. Training the analytical eye to ask *"does this belong here?"* transfers directly from body measurement data to network traffic, authentication logs, and endpoint telemetry.

---

### Analysis Table

Whiskers was prompted to generate a structured summary analysis table:

> *"Generate a summary analysis table showing the minimum, maximum, average, and standard deviation for each numerical measurement in the dataset. Flag any values that deviate more than 2 standard deviations from the mean."*

The standard deviation threshold request mirrors how security tools classify behavioral anomalies — anything beyond 2σ from baseline is considered statistically significant and worthy of investigation.

---

### 📋 Key Findings

**1. Baseline measurements were clearly defined and internally consistent**
The dataset produced well-clustered averages for height and weight, with most subjects falling within an expected distribution range. In security terms, this represents a healthy baseline — the kind of "normal" that makes outliers visible.

**2. Height and weight showed a strong positive correlation**
As expected, taller subjects generally recorded higher weight measurements. This correlation was consistent enough to serve as a reliable predictor. However, several subjects fell outside this expected relationship — deviating significantly from the pattern — which in a security context would immediately flag as anomalous behavior worth investigating.

**3. Outliers were statistically identifiable and analytically meaningful**
Multiple data points exceeded the 2 standard deviation threshold from the mean. These were not random noise — they represented genuine deviations from the population norm. The ability to distinguish meaningful outliers from statistical noise is exactly the skill that separates reactive alert responders from proactive threat hunters.

**4. AI-generated analysis accelerated pattern recognition but required human validation**
Whiskers surfaced patterns quickly and accurately for the core statistical metrics. However, interpreting *why* outliers existed — and whether they warranted further investigation — required human analytical judgment. This mirrors the SOC analyst's role precisely: AI handles the volume, humans handle the context.

**5. The same analytical framework applies across domains**
Whether the dataset is body measurements, network flow logs, authentication events, or endpoint telemetry — the process is identical: establish baseline, identify correlations, surface anomalies, validate with context. This project reinforced that data analysis is a transferable analytical discipline, not a domain-specific one.

---

### 🧠 Evaluation: Was the AI Analysis Accurate?

**Largely yes — with important caveats.**

Whiskers performed well on quantitative tasks: averages, ranges, and standard deviation calculations were accurate and consistently formatted. The generated analysis table was clean, structured, and immediately usable.

Where human oversight remained essential was in contextual interpretation. Whiskers identified *that* outliers existed — but determining *whether* those outliers were meaningful, erroneous, or expected required domain knowledge and analytical judgment that the AI could not supply on its own.

This is not a limitation unique to PartyRock. It is the fundamental truth of AI-assisted analysis: the tool accelerates the work, but the analyst owns the conclusion.

---

### 💡 Prompts That Generated the Best Insights

The questions that produced the most analytically rich responses shared three characteristics:

- They asked for **specific statistical thresholds** (e.g., "2 standard deviations from the mean") rather than vague requests for "anything unusual"
- They requested **structured output formats** (tables, flagged entries) rather than open-ended prose
- They framed the question with **investigative intent** — not "what is in this data" but "what in this data demands attention"

> This mirrors effective querying in a SOC environment: the quality of the intelligence you extract is directly proportional to the precision of the question you ask.

---

---

## 🛠️ Tools & Technologies

| Tool | Role |
|------|------|
| **PartyRock (partyrock.aws)** | No-code AI app builder and data analysis platform |
| **Amazon Bedrock** | Underlying AI infrastructure powering PartyRock |
| **Whiskers (PartyRock AI)** | Conversational AI used for app generation and data analysis |
| **BodyM Dataset** | Body measurements dataset used for Project 02 |

---

## 📚 Skills Demonstrated

- Generative AI application design and development
- No-code AI tooling (PartyRock / Amazon Bedrock)
- Problem framing and use case development for AI tools
- Cybersecurity education systems design
- Data analysis and pattern recognition
- Anomaly detection methodology
- AI output evaluation and critical assessment
- Technical communication and documentation

---

## 🔭 What's Next

These two projects represent the foundation of a larger body of work applying AI to cybersecurity operations and education. Future projects in development include:

- **SENTINEL** — A highly personalized AI cybersecurity assistant with biometric login sequence, operational HUD, and multi-domain SOC functionality
- **LOG WHISPERER** — Paste any raw log, receive instant plain-English analysis, MITRE ATT&CK mapping, and recommended next investigative steps
- **INCIDENT COMMANDER** — A live, adaptive SOC playbook engine that updates in real time as incident details develop

---

## 👤 Author

**John**
Cybersecurity Analyst & Tutor | SOC Operations | Penetration Testing | GRC | AI Applications
2+ Years of Field Experience

*Practitioner-first. Education-driven. Building at the intersection of cybersecurity and artificial intelligence.*

---

<div align="center">

*Built with curiosity, deployed with purpose.*

**© 2026 John. All rights reserved.**

</div>

