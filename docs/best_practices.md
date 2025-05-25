# ✅ Best Practices for Effective Legal Prompting

This document summarizes key guidelines for crafting accurate, safe, and useful prompts when using Large Language Models (LLMs) in legal contexts.

---

## 🔹 1. Be Specific and Detailed

Avoid vague queries. Include:

* Relevant statute or legal domain
* Jurisdiction (e.g. U.S. federal, EU, etc.)
* Timeframe (e.g. 2021–2023)
* Desired format or tone (e.g. IRAC, plain English)

**Example**:

```
Analyze the requirements for direct patent infringement under 35 U.S.C. § 271(a) based on Federal Circuit cases from 2020–2023.
```

---

## 🔹 2. Provide Background Context

Include facts, clauses, or legal positions so the model can reason with specifics.

**Example**:

```
Given this clause: 'Tenant may terminate the lease if...', explain how it applies if the landlord fails to provide heating services for 10+ days.
```

---

## 🔹 3. Clarify the Jurisdiction

Always specify the legal system or country.

**Example**:

```
Under California contract law, what constitutes a material breach?
```

---

## 🔹 4. Specify Format, Depth, and Output Style

Let the model know what type of answer you need:

* Length: “In 300 words”
* Format: “Use bullet points” / “Write as a formal legal memo”
* Style: “Plain English summary for a non-lawyer”

---

## 🔹 5. Break Down Complex Tasks

Use step-by-step or “chain of thought” prompts:

```
Step 1: List key causes of action. Step 2: Identify applicable statutes. Step 3: Assess weaknesses.
```

---

## 🔹 6. Ask for Evidence and Prevent Hallucinations

Use explicit guardrails:

```
Cite only real, verifiable case law. If unsure, say so.
```

Or:

```
Base your response only on the following clause:
[Insert clause here]
```

---

## 🔹 7. Reinforce Ethical Constraints

Add ethical roles and disclaimers:

```
You are a legal assistant trained in professional responsibility. Flag any potential ethical risks in this scenario.
```

---

## 🔹 8. Iterate, Review, and Refine

Prompting is an iterative process. After a first answer:

* Ask for clarification or expansion
* Narrow the scope
* Add or modify context

---

## 📎 Source-Inspired Framework

* Harvard CLP: Prompt tone and format experiments
* Stanford RegLab: Legal hallucination mitigation
* OpenAI: Structured prompting and instruction tuning
* ContractPodAI: Prompt templates for real use cases

> 🧠 Prompt engineering is not just technical — it’s legal reasoning in a new format. Use these practices to guide AI, not be guided by it.
