# 🔍 Prompt Comparison: Weak vs. Strong Prompts

This file demonstrates how legal prompting improves drastically with clarity, context, and structure. Below are side-by-side comparisons of weak and strong prompts, based on real legal use cases.

---

## 🧪 Example 1 – Legal Research

**🟥 Weak Prompt**:

```
What’s the law on patent infringement?
```

**🟩 Strong Prompt**:

```
Provide a detailed analysis of direct patent infringement under 35 U.S.C. § 271(a). Explain each required element a plaintiff must prove, and cite at least two U.S. Federal Circuit cases (2020–2023) that illustrate how the law applies. Also distinguish between literal infringement and the doctrine of equivalents. Limit to 3 paragraphs in formal tone.
```

**✅ Why It’s Better**:

* Identifies statute and case law
* Sets jurisdiction and timeframe
* Requires structure and real citations
* Controls tone and scope

---

## 🧪 Example 2 – Contract Drafting

**🟥 Weak Prompt**:

```
Write a confidentiality agreement.
```

**🟩 Strong Prompt**:

```
Draft a mutual NDA between a SaaS company and a healthcare enterprise. Include HIPAA-related exclusions, a 3-year term, mutual obligations, legal exceptions (court orders), and New York governing law. Organize it into sections and keep it enforceable yet clear.
```

**✅ Why It’s Better**:

* Sets context (parties + sector)
* Lists precise legal clauses
* Includes jurisdiction
* Guides tone and enforceability

---

## 🧪 Example 3 – Document Review

**🟥 Weak Prompt**:

```
Review this contract.
```

**🟩 Strong Prompt**:

```
Review the lease contract below and extract all early termination clauses. Summarize each clause in plain English and indicate its page number. Flag any clauses that are non-standard and briefly explain why.
```

**✅ Why It’s Better**:

* Clear scope (termination clauses)
* Structured output expected
* Encourages critical analysis (non-standard)
* Plain language + citation format

---

## 💡 Prompting Principle

> Strong prompts reduce hallucinations, increase task precision, and reflect legal judgment. Always define **what**, **how**, **why**, and **for whom**.

---

### 📎 Source References

* Harvard CLP Prompting Guidelines
* OpenAI Legal Prompt Frameworks
* ContractPodAI Prompting Use Cases
* Stanford RegLab Research on Legal Hallucinations
