# 📑 Report: Effective Legal Prompting with LLMs

> This report provides a comprehensive overview of current best practices, frameworks, examples, and research-based recommendations for crafting effective legal prompts using Large Language Models (LLMs). All content is in English, intended for legal professionals, innovators, and researchers, and structured to be GitHub-readable.

---

## 📘 Introduction

Large Language Models (LLMs) are transforming legal practice, assisting in legal research, drafting, and decision support. However, their usefulness depends entirely on how we prompt them — i.e., how we formulate the questions and context.

While tools like ChatGPT have shown immense capacity, studies from Stanford and Harvard reveal substantial risks: up to **88% of legal queries** in some studies result in hallucinations (i.e., plausible-sounding but false information). These mistakes are not only errors — in law, they can be **dangerous**.

Therefore, learning how to craft prompts precisely, ethically, and with legal awareness is essential. This report outlines the landscape of legal prompting, domains of use, examples of strong vs. weak prompting, and actionable best practices.

---

## ⚖️ Legal Domains and Use Cases for Prompting

Legal prompting can enhance work across domains:

### 1. **Legal Research and Analysis**

Prompt: *"Summarize the holding of Roe v. Wade in under 200 words, using plain English for a client."*

* Benefits: Speeds up case comprehension and explanation
* Risks: Hallucinated holdings or missed exceptions

### 2. **Contract Drafting & Review**

Prompt: *"Draft a confidentiality clause allowing disclosures under HIPAA and GDPR exceptions."*

* Benefit: Fast prototyping of clauses with scenario-specific constraints
* Risk: Missing governing law, enforceability

### 3. **Litigation Strategy**

Prompt: *"Identify weaknesses in plaintiff's claim under Rule 12(b)(6), assuming the following facts."*

* Benefit: Brainstorming arguments or SWOT-style legal analysis
* Risk: Overreliance without critical review

### 4. **Client Counseling & Plain Language Law**

Prompt: *"Explain termination clauses in a lease to a first-time renter."*

* Benefit: Access to justice; legal literacy
* Risk: Oversimplification or omission of exceptions

### 5. **Access to Justice & Self-Help Tools**

Use: DoNotPay prompts used in chatbots

* Win rate in 250k+ cases: \~64% reported
* Illustrates value of structured, dynamic, rule-aware prompting for lay users

---

## 🎓 Academic and Research Foundations

* **Stanford RegLab (2024)**: "Large Legal Fictions" paper showed LLMs frequently generate confident but false case law. Recommended building prompts that ask models to show uncertainty and self-check.
* **Harvard CLP (2023)**: Teaching law students how to prompt effectively, finding that **specific format and tone** prompts work better than role-only prompts.
* **OpenAI Guides**: Suggest chaining thoughts, role-assigning, and breaking complex prompts into steps. Also emphasize the mantra: "**verify, verify, verify**."

---

## 🧠 Best Practices Summary

### ✅ Be Specific and Jurisdictionally Anchored

Instead of: *"What are the requirements for contract formation?"* → Prefer:

> *"List the elements of contract formation under New York law, including case citations from 2020–2024. Structure the answer in IRAC format.”*

### ✅ Provide Context or Background Facts

LLMs are stateless. Give relevant case facts or contract clauses in the prompt.

### ✅ Ask for Format, Depth, and Tone

Use explicit instructions:

* "500 words"
* "Bullet points with citations"
* "Academic tone, cite sources in Bluebook format"

### ✅ Break into Steps or Chain of Thought

"First, outline elements of negligence. Then analyze them under the following facts."

### ✅ Demand Sources and Self-Awareness

> *“If unsure, say so. Do not fabricate legal citations.”*
> This reduces hallucinations. Always verify.

### ✅ Mind Ethics and Jurisdictional Rules

Prompts should not request unauthorized practice of law or advice beyond the AI's limits. Include disclaimers or use prompts like:

> *“Provide a summary but state that a lawyer should be consulted before acting on it.”*

---

## 📋 Prompt Comparison Examples

### ❌ Weak Prompt

\_"Write an NDA for my startup."

### ✅ Strong Prompt

> *"Draft a mutual NDA for a SaaS company entering negotiations with a hospital client under HIPAA. Include: 3-year term, exclusions, standard legal remedies, and NY governing law."*

### ❌ Weak Prompt

\_"What’s the rule for hearsay?"

### ✅ Strong Prompt

> \_"Explain the hearsay rule under the U.S. Federal Rules of Evidence. Include three key exceptions commonly used in trial. Keep the tone formal and include Rule numbers (e.g., FRE 801)."

---

## 📦 Repository Structuring Tips (for Public Projects)

If you want to publish your legal prompting research on GitHub:

* Use a clear `README.md`
* Create folders: `/prompts`, `/docs`, `/examples`
* Use `report.md` for longform content like this
* Cite sources with footnotes or inline links
* Add `DISCLAIMER.md` and license for legal clarity

---

## 📚 References (Full list in `/docs/references.md`)

* Dahl, M. et al. (2024). *Large Legal Fictions*. Stanford RegLab.
* Harvard CLP (2023). *Generative Legal Minds*. The Practice.
* OpenAI (2023). *Prompt Engineering Guidelines*.
* ContractPodAI (2024). *Mastering Prompts for Legal Professionals*.
* Reuters (2023). *NY Lawyers Sanctioned for Fake ChatGPT Citations*.

---

## ✅ Conclusion

Prompting is not just engineering — it’s legal reasoning in a new dialect. Those who master it will not just use AI more safely — they’ll expand its use for justice, inclusion, and efficiency.

---

> 📌 “Technology should never outpace justice — it should help us reach it.”
