<div align="center">

# 🚀 VYOM-X

### **AI-Powered Financial Transaction Intelligence & Voucher Classification**

**Structured Transactions → Contextual AI Reasoning → Validated Voucher Classification**
![](https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=VYOM-X&fontSize=80&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI-Powered%20Financial%20Transaction%20Intelligence%20%26%20Voucher%20Classification&descAlignY=60&descSize=18)

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&lines=Structured+Transactions+%E2%86%92+Accounting+Vouchers;Context-Aware+Classification+with+Gemma+4;Grounded+Reasoning+%2B+Rule-Based+Validation;Confidence-Aware+%C2%B7+Ambiguity-Safe+%C2%B7+Explainable)

![Hackathon](https://img.shields.io/badge/Hacktoberfest-Hack%20Day%20Nagpur-blueviolet?style=for-the-badge&logo=hackaday&logoColor=white)
![Track](https://img.shields.io/badge/VYOM%2B-Voucher%20Classification-orange?style=for-the-badge)
![AI](https://img.shields.io/badge/Open--Weight%20AI-Gemma%204-2ea44f?style=for-the-badge&logo=google&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

> **VYOM-X transforms structured financial transactions into accounting voucher classifications using open-source AI — combining contextual reasoning, accounting knowledge grounding, rule-based validation, confidence estimation, and human-review handling.**

🏆 **Hacktoberfest Hack Day Nagpur × Elevate IIITN** ・ 📌 **Problem Statement #4 — VYOM+ Intelligent Voucher Classification Using Open-Source LLMs**

</div>

---

## 👥 Team

| Role | Name | GitHub |
| :--- | :--- | :--- |
| 🏷️ Team Name | **404 : Team Not Found** |https://github.com/Miht008/VYOM |
| 👤 Member 1 | Mihit Bide | Miht008 |
| 👤 Member 2 | Nitinraj Tiwari | Nitin0-Jade |
| 👤 Member 3 | Sahil Kate | SahilKirankate |
| 👤 Member 4 | Akshat Sharma | Akshat-dev12 |

📞 **Contact:** +91 9699656154

---

## 📑 Table of Contents

- [⚡ VYOM-X At a Glance](#-vyom-x-at-a-glance)
- [🎯 Objectives](#-objectives)
- [💡 Why VYOM-X?](#-why-vyom-x)
- [🎯 Problem Statement](#-problem-statement)
- [🧩 Proposed Solution — Core Pipeline](#-proposed-solution--core-pipeline)
- [🔬 Worked Example — A Hard Case](#-worked-example--a-hard-case)
- [🗂️ Target Voucher Categories](#️-target-voucher-categories)
- [👤 Target Users & Use Case](#-target-users--use-case)
- [🤖 Open-Source AI — Gemma 4](#-open-source-ai--gemma-4)
- [🧠 AI's Role in the System](#-ais-role-in-the-system)
- [📚 Accounting Knowledge Grounding](#-accounting-knowledge-grounding)
- [🏗️ System Architecture](#️-system-architecture)
- [🧱 Component-Level Architecture](#-component-level-architecture)
- [🔄 Data & Information Flow](#-data--information-flow)
- [🤖 Agentic Workflow](#-agentic-workflow)
- [📊 Confidence Estimation](#-confidence-estimation)
- [✨ What Makes VYOM-X Different](#-what-makes-vyom-x-different)
- [🛠️ Technology Stack](#️-technology-stack)
- [✨ Expected Features](#-expected-features)
- [🧭 Implementation Approach](#-implementation-approach)
- [📦 Open-Source Dependencies & Components](#-open-source-dependencies--components)
- [📦 Expected Output](#-expected-output)
- [⚠️ Challenges & Mitigations](#️-challenges--mitigations)
- [🚀 Future Scope & Scalability](#-future-scope--scalability)
- [🌍 Expected Impact](#-expected-impact)
- [🤝 Contributions](#-contributions)
- [📄 License](#-license)

---

## ⚡ VYOM-X AT A GLANCE

| 🧠 Intelligence | 📚 Knowledge | 🛡️ Reliability | 📦 Output |
|---|---|---|---|
| Gemma 4 | Accounting Grounding | Validation + Confidence | JSON / Excel |
| Context Reasoning | Voucher Taxonomy | Ambiguity Detection | Batch Processing |
| Multi-field Analysis | Decision Cues | Human Review | API Ready |

> 🎯 **Core Idea:** Don't classify the transaction by what words it contains.  
> **Understand what the transaction actually represents.**

---

## 🎯 Objectives

| 🎯 Objective | 💡 Purpose |
|---|---|
| 🧠 Contextual Classification | Understand complete transaction context instead of relying on keywords |
| 🤖 Meaningful AI Integration | Use Gemma 4 for semantic reasoning across multiple transaction fields |
| 📚 Accounting Grounding | Provide voucher definitions and decision cues to guide classification |
| 🛡️ Reliable Decisions | Validate AI predictions using deterministic rules and transaction evidence |
| 📊 Confidence Awareness | Measure prediction reliability and identify uncertain cases |
| ⚠️ Ambiguity Handling | Route low-confidence or incomplete transactions for human review |
| 📦 Structured Output | Produce consistent JSON / Excel results for evaluation and downstream systems |
| 🚀 Future Scalability | Keep the architecture modular for ERP integration and future AI improvements |

---

## 💡 Why VYOM-X?

Accounting transaction classification is **not** a keyword-matching problem.

A transaction containing a supplier, customer, GST amount, payment information, inventory details, or return information can map to *different* voucher categories depending on the **relationship between multiple fields** — not any single field.

The objective is not merely to ask an LLM:

> ❝ What voucher type is this? ❞

Instead, VYOM-X builds a **controlled classification pipeline** in which AI reasons over normalized transaction context *grounded in accounting definitions*, and a deterministic validation layer verifies that the classification is consistent with the available evidence.

**🧹 Preprocessing → 🧠 LLM Reasoning → 📚 Knowledge Grounding → ✅ Validation → 📊 Confidence → 🔍 Ambiguity Detection → 📦 Structured Output**

---

### 🔄 What VYOM-X Does

```text
📊 Structured Transaction
          ↓
🧠 Contextual Understanding
          ↓
📚 Accounting Knowledge
          ↓
🤖 Gemma 4 Reasoning
          ↓
🛡️ Validation
          ↓
📊 Confidence
          ↓
📦 Voucher Classification
```

## 🎯 Problem Statement

Financial and accounting systems often contain structured transaction records **without an explicitly assigned voucher category**. A single transaction row may contain:

| 🧑‍🤝‍🧑 Party Info | 📄 Document Info | 💰 Financial Info | 📦 Inventory Info | 🚦 Indicators |
| --- | --- | --- | --- | --- |
| Seller / Supplier | Invoice No. & Date | Taxable Value | Items | Payment info |
| Buyer / Customer | Order / Delivery refs | GST | Quantity | Return info |
| — | — | Discounts, Freight | — | Import / Export |
| — | — | Currency | — | Payroll, Debit / Credit |

The voucher type is missing — and must be inferred from the **complete transaction context**.

The problem becomes genuinely hard when categories are semantically similar:

**`Purchase ⚔️ Sales`** ・ **`Purchase Return ⚔️ Sales Return`** ・ **`Payment ⚔️ Receipt`** ・ **`Contra ⚔️ Payment/Receipt`** ・ **`Journal ⚔️ Purchase/Sales`** ・ **`Material Movement ⚔️ Purchase/Sales`** ・ **`Import ⚔️ Export`**

The system must also handle **incomplete or ambiguous records** and produce structured output suitable for automated evaluation and downstream accounting workflows.

---

## 🧩 Proposed Solution — Core Pipeline

VYOM-X is a multi-stage classification system that deliberately separates **AI reasoning** from **validation and decision control**.

```text
Excel Transaction Data
        ↓
Data Validation & Cleaning
        ↓
Transaction Normalization
        ↓
Accounting Context Representation
        ↓
Voucher Knowledge Grounding (definitions + decision cues)
        ↓
Open-Source AI Reasoning (Gemma 4)
        ↓
Candidate Voucher Classification
        ↓
Rule & Consistency Validation
        ↓
Confidence / Ambiguity Analysis
        ↓
Final Classification Decision
        ↓
JSON / Excel Output
```

### 🔍 Stage-by-Stage Breakdown

**Stage 1 — 🧹 Data Processing**
The input Excel dataset is parsed and normalized: field detection, missing-value handling, numerical/text normalization, and standardization — while preserving important financial relationships between fields.

**Stage 2 — 🧾 Transaction Understanding**
Instead of sending raw spreadsheet rows to the model, VYOM-X constructs a structured transaction context:

```text
Transaction
├── Parties
│   ├── Seller / Supplier
│   └── Buyer / Customer
├── Document Information
│   ├── Invoice
│   └── Date
├── Financial Information
│   ├── Taxable Value
│   ├── GST
│   ├── Discount
│   └── Freight
├── Inventory Information
│   ├── Items
│   └── Quantity
└── Transaction Indicators
    ├── Payment
    ├── Return
    ├── Import / Export
    └── Order / Delivery References
```

**Stage 3 — 📚 Knowledge Grounding**
The model receives compact voucher-category definitions and decision cues alongside the transaction, so it classifies against *accounting meaning* rather than general language intuition.

**Stage 4 — 🤖 AI Classification**
An open-source LLM reasons over the grounded transaction context and classifies it into one of the permitted voucher categories, with constrained structured output.

**Stage 5 — ✅ Validation**
A rule-based engine checks for contradictions between the predicted category and the available transaction evidence.

**Stage 6 — 📊 Confidence & Ambiguity Handling**
Instead of forcing every uncertain transaction into an apparently certain answer, VYOM-X flags low-evidence records for human review.

**Stage 7 — 📦 Structured Output**
Every record produces a consistent, machine-readable result suitable for programmatic evaluation.

**Overall Objective 🎯** Build a reliable, explainable and open-source voucher classification pipeline that can operate on real-world financial transaction data.

---

## 🔬 Worked Example — A Hard Case

Two transactions that share **every keyword** — yet mean opposite things in the books:

```text
Row A                              Row B
Seller:     ABC Traders            Seller:     ABC Traders
Buyer:      XYZ Pvt Ltd            Buyer:      XYZ Pvt Ltd
Items:      Raw Materials          Items:      Raw Materials
GST:        Present                GST:        Present
Value:      ₹50,000                Value:      ₹50,000
Reference:  Purchase Order         Reference:  Original Invoice + "goods returned"
```

A keyword classifier **cannot** separate them. VYOM-X reasons over the distinguishing signals:

| 🔎 Signal | Row A | Row B |
| --- | --- | --- |
| 📄 Document reference | Purchase Order (pre-transaction intent) | Original invoice + return note (post-transaction reversal) |
| 📦 Goods movement | Incoming, new | Incoming, *returned* |
| 📒 Accounting meaning | Acquisition of goods | Reversal of a prior purchase |
| 🏷️ **Classification** | **Purchase Order / Purchase** | **Purchase Return / Debit Note** |
| 📊 Confidence basis | Strong order-reference evidence | Return indicator + linked invoice |

> ⚡ Same surface fields. Different accounting meaning. This is exactly the class of distinction VYOM-X is architected around.

---

## 🗂️ Target Voucher Categories

Each transaction is classified into exactly **one** of the defined categories:

| 💼 Trade | 🔁 Returns | 💸 Funds | 📒 Adjustments |
| --- | --- | --- | --- |
| Purchase | Purchase Return / Debit Note | Payment | Journal |
| Sales | Sales Return / Credit Note | Receipt | Contra |
| Purchase Order | Rejection In | Advance / Prepayment | Expense |
| Sales Order | Rejection Out | Salary / Payroll | Attendance |

| 📦 Inventory & Movement | 🏭 Job Work | 🌐 International & Misc |
| --- | --- | --- |
| Receipt Note | Job Work In Order | Import |
| Delivery Note | Job Work Out Order | Export |
| Stock Journal ・ Physical Stock | Material In ・ Material Out | Other / Miscellaneous |

---

## 👤 Target Users & Use Case

**Built for:** 🧾 accounting teams ・ 🏦 finance departments ・ 🖥️ ERP developers ・ 📚 bookkeeping systems ・ 🏢 organizations processing large transaction datasets.

**The flow:** upload an Excel dataset of structured transactions → VYOM-X outputs `Transaction → Voucher Category`, with confidence and review flags where appropriate.

```text
Input:
   Supplier      = ABC Traders
   Buyer         = XYZ Pvt Ltd
   Items         = Raw Materials
   GST           = Present
   Taxable Value = ₹50,000
        ↓
   Knowledge-Grounded AI Reasoning + Validation
        ↓
Output:
   Voucher Type = Purchase
```

---

## 🤖 Open-Source AI — Gemma 4

![Gemma 4](https://img.shields.io/badge/Gemma_4-Primary_Reasoning_Engine-4285F4?style=for-the-badge&logo=google&logoColor=white)

VYOM-X uses **Gemma 4** (open-weight) as its primary AI reasoning component.

**🧠 Gemma 4 is responsible for:**

- 🔗 Understanding transaction context and relating multiple fields semantically
- ⚖️ Distinguishing semantically similar voucher categories
- 🕳️ Handling incomplete or missing information gracefully
- 🎯 Producing constrained voucher classifications
- 📝 Providing short, evidence-based rationales

### 🧠 Why VYOM-X Needs an LLM

| ❌ Keyword Matching | ✅ VYOM-X |
|---|---|
| `"invoice"` → guess | Invoice + party + items + financial context |
| `"payment"` → guess | Payment + accounts + transaction relationship |
| `"return"` → guess | Return + original document + goods movement |
| One field at a time | Full transaction context |

> 🤖 **Gemma 4 handles semantic reasoning. The surrounding system handles control, validation and decision-making.**

The model is **not** treated as an unrestricted chatbot — it operates as a controlled classification component inside a larger engineering pipeline.

### 💭 Why open-weight AI?

This task demands language-based reasoning over transaction descriptions, business relationships, financial context, and missing information — precisely where a keyword classifier fails:

```text
"Invoice"  ----X---->  does NOT determine Purchase vs Sales vs Returns
```

An open-weight model enables **controlled inference, reproducible experimentation, local/self-hosted execution, and zero dependence on proprietary APIs** in the classification path.

---

## 🧠 AI's Role in the System

AI is a **core component**, not an optional add-on. A purely rule-based system would require hand-encoding enormous numbers of semantic relationships between fields — and would break on ambiguous descriptions and incomplete records. The LLM interprets the *relationship* between fields; deterministic software controls everything else.

| 🧩 Component | 🎯 Responsibility |
| --- | --- |
| 🧹 Data processor | Cleaning and normalization |
| 🏗️ Context builder | Converts raw row → meaningful context |
| 📚 Knowledge base | Voucher definitions & decision cues |
| 🤖 **Gemma 4** | **Contextual reasoning and classification** |
| ✅ Validation engine | Consistency and contradiction checks |
| 📊 Confidence layer | Identifies uncertain cases |
| ⚖️ Decision engine | Auto-classify vs human review |
| 📦 Output engine | Structured JSON/Excel results |

---

## 📚 Accounting Knowledge Grounding

A general-purpose LLM knows language — it does not reliably know **Indian accounting voucher semantics** (what separates a Contra from a Receipt, a Receipt Note from a Purchase, a Stock Journal from a Material Out). Un-grounded, this gap shows up as confident but wrong predictions.

VYOM-X closes this gap with a compact, curated **voucher knowledge base** — one entry per category:

```json
{
  "category": "Contra",
  "definition": "Transfer of funds between cash and bank accounts of the same entity; no third party, no goods, no GST.",
  "positive_signals": ["same-entity accounts", "cash deposit/withdrawal", "no party", "no items", "no tax"],
  "confusable_with": ["Payment", "Receipt"],
  "distinguishing_test": "Is money moving between the entity's OWN accounts with no external party?"
}
```

### 🎯 Grounding Strategy

```text
Transaction Context
        +
Voucher Definitions
        +
Decision Cues
        ↓
   🤖 Gemma 4
        ↓
Classification
        +
Evidence
```

Each classification prompt receives the transaction context **plus the definitions of the most plausible candidate categories** (selected by lightweight field-signal matching), so Gemma 4 performs *grounded discrimination*:

```text
Transaction Context
    +  Candidate Category Definitions & Decision Cues
                    ↓
        Gemma 4 (grounded reasoning)
                    ↓
     Classification + Evidence-Based Rationale
```

This is retrieval-grounded classification kept deliberately simple: a static, versioned knowledge file rather than a heavy vector store — appropriate for a well-defined, bounded category set. It also directly reduces hallucination, because the model's answer must align with an explicit definition that the validation layer can re-check.

---

## 🏗️ System Architecture

```text
                    ┌───────────────────────┐
                    │     Excel Dataset     │
                    └───────────┬───────────┘
                                ▼
                    ┌───────────────────────┐
                    │   Data Validation &   │
                    │       Cleaning        │
                    └───────────┬───────────┘
                                ▼
                    ┌───────────────────────┐
                    │     Transaction       │
                    │     Normalization     │
                    └───────────┬───────────┘
                                ▼
                    ┌───────────────────────┐
                    │     Accounting        │
                    │    Context Builder    │
                    └───────────┬───────────┘
                                ▼
              ┌──────────────────────────────────┐
              │      Voucher Knowledge Base      │
              │   (definitions + decision cues)  │
              └──────────────────┬───────────────┘
                                 ▼
                    ┌───────────────────────┐
                    │      Gemma 4 AI       │
                    │   Grounded Reasoning  │
                    └───────────┬───────────┘
                                ▼
                    ┌───────────────────────┐
                    │      Candidate        │
                    │    Classification     │
                    └───────────┬───────────┘
                                ▼
                      ┌───────────────────┐
                      │ Validation Engine │
                      └─────────┬─────────┘
                                ▼
                    ┌───────────────────────┐
                    │     Confidence &      │
                    │    Ambiguity Check    │
                    └───────────┬───────────┘
                                ▼
                    ┌───────────────────────┐
                    │    Decision Engine    │
                    └───────────┬───────────┘
                  ┌─────────────┴─────────────┐
                  ▼                           ▼
        ┌───────────────────┐       ┌───────────────────┐
        │  Auto Classified  │       │   Human Review    │
        └─────────┬─────────┘       └─────────┬─────────┘
                  └─────────────┬─────────────┘
                                ▼
                    ┌───────────────────────┐
                    │   JSON / Excel Output │
                    └───────────────────────┘
```

> 🧭 **Design principle:** every component has one clearly defined responsibility. This prevents the project from degrading into `Excel → LLM → Answer`. The real architecture is:
>
> **`Data → Understanding → Grounded AI Reasoning → Validation → Decision`**

---

## 🧱 Component-Level Architecture

| 🧩 Component | 🎯 Responsibility | 🔌 Input | 📤 Output |
|---|---|---|---|
| 📥 Data Ingestion | Reads and parses the supplied transaction dataset | Excel / tabular data | Raw transaction rows |
| 🧹 Validation & Cleaning | Checks required fields, missing values, data types and basic consistency | Raw rows | Clean transaction records |
| 🔄 Normalization | Standardizes field formats while preserving transaction relationships | Clean records | Normalized transaction schema |
| 🧠 Context Builder | Converts structured records into accounting-focused semantic context | Normalized records | Transaction context |
| 📚 Voucher Knowledge Base | Stores category definitions, decision cues and confusable categories | Voucher taxonomy | Grounding context |
| 🤖 Gemma 4 | Performs contextual semantic reasoning and classification | Transaction context + grounding | Candidate voucher + evidence |
| 🛡️ Validation Engine | Checks predictions against deterministic rules and transaction evidence | Prediction + transaction | Validation result / flags |
| 📊 Confidence Layer | Combines measurable signals to estimate prediction reliability | Model + validation signals | Confidence score + review flag |
| ⚖️ Decision Engine | Determines whether to auto-classify or request human review | Prediction + confidence | Final decision |
| 📦 Output Engine | Produces consistent machine-readable results | Final decision | JSON / Excel |

> 🧭 **Design principle:** Each component has a clearly defined responsibility, allowing preprocessing, knowledge, AI reasoning, validation, and output handling to evolve independently.

---

## 🔄 Data & Information Flow

```text
 1. Excel Input
 2. Validate available columns
 3. Clean missing / invalid values
 4. Normalize transaction fields
 5. Build transaction context
 6. Retrieve relevant voucher definitions
 7. Send grounded context to Gemma 4
 8. Receive constrained classification
 9. Validate prediction against evidence
10. Estimate confidence
11. Flag ambiguity when required
12. Generate structured output
```

**✨ Confident record:**

```json
{
  "transaction_id": "TXN-1024",
  "voucher_type": "Purchase",
  "confidence": 0.94,
  "review_required": false,
  "reason": "Supplier, purchased items and taxable transaction information support a purchase classification."
}
```

**🚩 Ambiguous record:**

```json
{
  "transaction_id": "TXN-1098",
  "voucher_type": "Contra",
  "confidence": 0.54,
  "review_required": true,
  "reason": "Available information suggests an account transfer, but evidence is insufficient for high-confidence classification."
}
```

## 🤖 Agentic Workflow

```text
Transaction
    ↓
🧠 Context Construction
    ↓
📚 Knowledge Retrieval
    ↓
🤖 Gemma 4
    ↓
🛡️ Validation
    ↓
📊 Confidence
    ↓
✅ Auto-Classification
      OR
⚠️ Human Review
```

The rationale is a **short evidence-based explanation**, not unrestricted model reasoning.

---

## 📊 Confidence Estimation

Confidence is **computed from measurable signals** — never asserted by the model. VYOM-X fuses four independent signals into a single calibrated score:

| 📡 Signal | 🔬 How it is measured |
| --- | --- |
| 🔁 Self-consistency | The model classifies the same transaction under small prompt/context perturbations; agreement rate across runs |
| 📏 Margin | Gap between the top candidate and the runner-up category |
| ✅ Validation outcome | Number and severity of rule/contradiction flags raised |
| 🧩 Field completeness | Proportion of decision-relevant fields present in the record |

The auto-classify / human-review **threshold is calibrated on held-out data** — maximizing accuracy on auto-classified records while keeping the review queue small. If a signal proves uninformative, it is dropped: the methodology is empirical, not decorative.

---

## ✨ What Makes VYOM-X Different

| 🥇 Principle | ❌ Typical Approach | ✅ VYOM-X Approach |
| --- | --- | --- |
| **Context, not keywords** | `Keyword → Voucher` | `Seller + Buyer + Items + Financials + Indicators → Contextual Decision` |
| **Grounded, not bare AI** | Model guesses from general knowledge | `Transaction + Voucher Definitions → Accounting-meaning reasoning` |
| **AI + validation** | Trust the model blindly | `AI Prediction + Transaction Evidence → Validated Decision` |
| **Honest uncertainty** | Force an answer for everything | `High confidence → auto-classify` ・ `Low confidence → human review` |

---

## 🛠️ Technology Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![OpenPyXL](https://img.shields.io/badge/OpenPyXL-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Gemma](https://img.shields.io/badge/Gemma_4-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

| 🧩 Layer | ⚙️ Technology |
| --- | --- |
| Language | Python |
| Data Processing | Pandas |
| Excel Handling | OpenPyXL |
| AI Model | Gemma 4 (open-weight) |
| Model Runtime | Local / open-source inference framework |
| Backend | FastAPI |
| Interface | Streamlit |
| Output | JSON / XLSX |
| Version Control | Git + GitHub |

> 📌 **Dependency principle:** every dependency has a defined role. Nothing is added just to make the architecture look complex.

---

## ✨ Expected Features

| 🚀 Feature | 🎯 Purpose |
|---|---|
| 📥 Excel Ingestion | Process structured transaction datasets |
| 🧹 Data Normalization | Clean and standardize transaction fields |
| 🧠 Contextual Understanding | Understand relationships between fields |
| 📚 Knowledge Grounding | Supply accounting definitions and cues |
| 🤖 Gemma 4 Classification | Perform semantic voucher classification |
| 🛡️ Validation | Detect logically inconsistent predictions |
| 📊 Confidence Scoring | Measure prediction reliability |
| ⚠️ Ambiguity Detection | Route uncertain cases for review |
| 👨‍💼 Human Review | Prevent forced low-confidence decisions |
| 📦 JSON / Excel Output | Produce machine-readable results |
| 📈 Evaluation | Measure Accuracy, Precision, Recall and F1 |

---

## 🧭 Implementation Approach

### 🛠️ Development Flow

```text
📥 Ingest
   ↓
🧹 Clean
   ↓
🔄 Normalize
   ↓
🧠 Build Context
   ↓
📚 Ground
   ↓
🤖 Classify
   ↓
🛡️ Validate
   ↓
📊 Score
   ↓
📦 Export
```

---

## 📦 Open-Source Dependencies & Components

| 🧩 Component | 📌 Planned Role |
|---|---|
| 🤖 Gemma 4 | Primary open-weight AI reasoning and classification model |
| 🐍 Python | Core implementation language |
| 🐼 Pandas | Transaction preprocessing and dataset manipulation |
| 📊 OpenPyXL | Excel input and output handling |
| ⚡ FastAPI | Backend API and service layer |
| 🖥️ Streamlit | Lightweight evaluator-facing interface |
| 🔧 Open-Source Inference Runtime | Local / self-hosted model execution |
| 🌐 Git + GitHub | Version control and open-source collaboration |

> 🔓 **Open-source principle:** Every external component will have a clearly defined role, and the final implementation will document the versions and licenses used.

---

## 📦 Expected Output

**Minimum:**

### ✅ Example Result
```json
{ "transaction_id": "TXN-1024", "voucher_type": "Purchase" }
```

### 📊 Extended Result
**Extended:**

```json
{
  "transaction_id": "TXN-1024",
  "voucher_type": "Purchase",
  "confidence": 0.94,
  "review_required": false,
  "reason": "Transaction evidence is consistent with a purchase."
}
```

### 📑 Batch Classification
**Batch view:**

```text
Transaction ID | Voucher Type    | Confidence | Review
-------------------------------------------------------
TXN-001        | Purchase        | 0.94       | No
TXN-002        | Sales           | 0.91       | No
TXN-003        | Payment         | 0.88       | No
TXN-004        | Purchase Return | 0.71       | Yes
```

---

## ⚠️ Challenges & Mitigations

| ⚡ Challenge | 🛡️ Mitigation |
| --- | --- |
| Similar voucher categories | Full transaction context, not keywords |
| Model lacks accounting vocabulary | Curated voucher knowledge base grounding every prompt |
| Missing fields | Explicit missing-value representation |
| Ambiguous records | Confidence analysis + review flag |
| LLM hallucination | Grounded prompts + constrained output + validation layer |
| Invalid voucher category | Category whitelist validation |
| Inconsistent responses | Fixed structured output format |
| Limited compute | Model-size / quantization / inference optimization |
| Rare categories underperform | Per-category evaluation + targeted improvement |
| Over-reliance on AI | Deterministic preprocessing & validation |

---

## 🚀 Future Scope & Scalability

VYOM-X is designed as a modular classification layer that can grow into a broader financial-automation pipeline:

```text
Invoice / Document
        ↓
Document Intelligence
        ↓
Structured Transaction
        ↓
VYOM-X Classification
        ↓
Voucher Creation
        ↓
Accounting / ERP System
```

**🔮 On the horizon:**

- 🔗 Invoice-extraction system integration
- 📒 Automated voucher creation & ERP connectors
- 🎯 Domain-specific fine-tuning (LoRA / QLoRA)
- 🌐 Multilingual transaction descriptions
- 🧑‍🏫 Human feedback loops & continuous improvement
- 🤖 Model comparison & intelligent routing
- ☁️ Deployment as an internal financial-data service

The separation of input processing, knowledge grounding, AI reasoning, validation, and output means each component can be upgraded **independently**.

---

### 🛣️ VYOM-X Evolution

```text
Current
  ↓
Voucher Classification
  ↓
Invoice Understanding
  ↓
Automated Voucher Creation
  ↓
ERP Integration
  ↓
Financial Intelligence Layer
```

---

## 🌍 Expected Impact

| 🌍 Impact | 💡 Benefit |
|---|---|
| ⏱️ Less manual work | Faster transaction classification |
| ⚡ Higher consistency | Standardized classification decisions |
| 🧭 Better ambiguity handling | Uncertain records can be reviewed |
| 🤝 Structured outputs | Easier downstream automation |
| 🔗 ERP readiness | Future accounting-system integration |
| 🔓 Open-source AI | Reduced dependence on proprietary APIs |

---

## 🤝 Contributions

VYOM-X is intended to remain an open and extensible project.

Contributions are welcome in areas such as:

| 🛠️ Area | 💡 Examples |
|---|---|
| 🧠 AI & Models | Model evaluation, prompt improvements, fine-tuning experiments |
| 📚 Accounting Knowledge | Voucher definitions, decision cues, edge cases |
| 🔧 Backend | API improvements, validation logic, processing pipelines |
| 🖥️ Interface | Streamlit UI improvements and usability enhancements |
| 🧪 Evaluation | New test cases, benchmarks and error analysis |
| 📖 Documentation | Tutorials, examples and technical documentation |

### 🚀 Contribution Workflow

```text
Fork the Repository
        ↓
Create a Feature Branch
        ↓
Make Your Changes
        ↓
Test & Validate
        ↓
Open a Pull Request
        ↓
Review & Discussion
        ↓
Merge
```

---

## 📄 License

This project will be released under the **MIT License** upon final implementation, as required by the challenge rules.

---

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer)

**🏆 Hacktoberfest Hack Day Nagpur × Elevate IIITN**
*Problem Statement #4 — VYOM+ Intelligent Voucher Classification Using Open-Source LLMs*

**Made with 💙 by 404 : Team Not Found**
