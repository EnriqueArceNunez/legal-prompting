# 📄 Prompt Example 03: Commercial Lease Document Review

### 🎯 Objective

Enable legal professionals to prompt an LLM to identify and summarize early termination clauses in a long-form lease agreement.

---

### 🔍 Prompt (Strong Version)

```
Review the following commercial lease agreement (text provided below).

Identify all provisions that pertain to early termination rights for both the landlord and the tenant. For each provision:

1. Summarize the clause in 1-2 sentences.
2. Indicate the section or page number where it appears.
3. Highlight any unusual or non-standard terms and briefly explain why they may raise legal concerns.

Present your findings as a bullet list.
```

---

### 📝 Why This Prompt Works

* Task-focused: targets a specific clause type (termination)
* Structured output: specifies format (summary, location, explanation)
* Realistic: replicates common due diligence work
* Encourages analytical output beyond basic summarization

---

### ⚠️ Common Weak Prompt

```
Summarize this lease agreement.
```

**Why it fails**:

* Too broad, lacks focus
* No indication of what to extract
* No format guidance or legal nuance expected

---

### ✅ Use Case

* Legal assistants reviewing leases for startups
* Real estate lawyers checking client agreements
* AI-enhanced due diligence tools in transactional law

> 📎 Always verify outputs against the original document. AI reviews should be considered a first pass only.

---

### 🧠 Source Inspired by:

* Real estate legal tech use cases
* ContractPodAI review automation examples
* PromptStacks and OpenAI commercial analysis prompts
