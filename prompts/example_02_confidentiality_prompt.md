# 🤝 Prompt Example 02: Confidentiality Agreement (NDA)

### 🎯 Objective

Help legal professionals prompt LLMs to draft a mutual NDA with sector-specific constraints and compliance concerns.

---

### 🔍 Prompt (Strong Version)

```
Draft a mutual Non-Disclosure Agreement (NDA) between a SaaS software provider and an enterprise client in the healthcare sector.

The NDA should be approximately 5 pages, written in clear language but legally enforceable. Include the following:

1. Definitions of “Confidential Information,” with carve-outs for information already known, independently developed, or protected under HIPAA.
2. A 3-year confidentiality term after the end of the partnership.
3. Mutual obligations (both parties disclose and receive information).
4. Standard exceptions for compelled disclosure (e.g., court order) with advance notice.
5. A governing law and venue clause set to New York.

Organize the agreement with clear section headings.
```

---

### 📝 Why This Prompt Works

* Contextualized: specifies sector (healthcare) and roles (SaaS provider + client)
* Structured: breaks down each clause to include
* Legally aware: includes HIPAA and jurisdiction
* Formal tone expected, with page length as proxy for depth

---

### ⚠️ Common Weak Prompt

```
Write a confidentiality agreement for my business.
```

**Why it fails**:

* No parties or context specified
* Missing scope, exclusions, governing law
* No structure, tone, or enforceability guidance

---

### ✅ Use Case

* Drafting template agreements in startup legal ops
* LegalTech tools generating automated NDAs
* Legal education in contract clause construction

> 📎 Outputs should always be reviewed by a licensed attorney. Legal validity may vary by jurisdiction.

---

### 🧠 Source Inspired by:

* OpenAI usage guide for contracts
* Harvard CLP research on prompt tone
* ContractPodAI prompt samples
