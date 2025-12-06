# Advice on AI use of OFFICIAL information

## 🔍 What Is “OFFICIAL Information”?

**OFFICIAL** is the lowest classification level in the Australian Government’s information hierarchy. It includes:

- Routine business data  
- Internal communications  
- Service delivery content  
- Non-sensitive operational documents  

It does **not** include OFFICIAL: Sensitive, PROTECTED, SECRET or TOP SECRET information.  
Even OFFICIAL information must be protected from unauthorised access, profiling, and misuse.  
→ PSPF Requirement 0046, ISM-0820, ISM-0821

---

## 🧭 Clarifying the Boundary: OFFICIAL Classification Is Not Enough

While OFFICIAL classification indicates a lower sensitivity level, it does **not automatically mean** the information is safe to process with generative AI tools. The PSPF and ISM require additional considerations:

- **Technology system authorisation** (PSPF Requirement 0086)  
- **Risk acceptance and system listing** (PSPF Requirement 0087, 0089)  
- **Aggregation risk assessment** (ISM-0820, PSPF Requirement 0060)  
- **Foreign access and control checks** (PSPF Requirement 0046, 0049)

This means that even OFFICIAL content — such as meeting notes, draft communications, or internal templates — may be **inappropriate for AI processing** if it contains personal data, operational context, or policy deliberation.

---

## ✅ Principle for AI Use: Processing Publicly Available Information

> **APS staff may use authorised AI tools to process publicly available information, provided the content is non-sensitive, non-personal, and not part of internal deliberations.**

This principle offers a clear and compliant boundary for practical use. It supports business enablement (PSPF Requirement 0010) while maintaining proportionate security controls.

### ✅ What “Publicly Available” Means in Practice

- **Published reports** (e.g. annual reports, legislation, open datasets)  
- **Public-facing communications** (e.g. media releases, FAQs)  
- **Open consultations or stakeholder briefings**  
- **Templates cleared for public use**

### ❌ What It Does Not Cover

- Internal emails, meeting notes, or draft documents  
- Personalised communications (e.g. appointment details, names, locations)  
- Policy deliberations, even if based on public data  
- Aggregated content that could infer sensitive insights

---

## ✅ What APS Staff Can Practically Do with Approved AI Tools

If the AI tool (e.g. ChatGPT Enterprise, Gemini for Government) is **formally authorised** under PSPF Requirement 0086 and listed in the entity’s technology system register (Requirement 0089), APS staff may:

### 1. **Summarise Public Reports**
- Uploading publicly available documents (e.g. annual reports, published legislation) to generate summaries.
- ✅ Compliant and low-risk if the document is public and the tool is authorised.

### 2. **Draft Routine Communications (Refined)**
- Using AI to generate **generic, non-personalised messages** such as:
  - “Reminder: the office will be closed on Friday.”
  - “Thank you for attending today’s briefing.”
  - “Please submit your form by COB Thursday.”
- ✅ Compliant only if:
  - The AI tool is authorised.
  - The message contains **no personal information**, **no agenda items**, and **no policy content**.
  - The template and content are both reviewed and cleared for use with generative AI.
- ❌ Not compliant if:
  - The message includes names, dates, locations, or agenda items that imply policy deliberation or operational planning.
  - The AI tool is used to generate content based on sensitive context or internal discussions.

### 3. **Generate Meeting Notes (Refined)**
- Feeding in transcripts from:
  - **Public briefings**
  - **Open stakeholder consultations**
  - **Non-sensitive community engagement sessions**
- ✅ Compliant if:
  - The content is OFFICIAL and non-sensitive.
  - The AI tool is authorised.
- ❌ Not compliant for internal strategy meetings, policy development sessions, or anything involving operational planning.

### 4. **Brainstorm Policy Ideas (With Aggregation Risk Awareness)**
- Using AI to explore options based on:
  - Public legislation
  - Open data
  - Non-sensitive frameworks
- ✅ Compliant if:
  - The AI tool is authorised.
  - No internal policy positions or deliberations are included.
- ⚠️ Must consider **aggregation risk**:
  - Even benign inputs can be combined to infer sensitive insights.
  - PSPF Requirement 0060 and ISM-0820 require originators to assess the **value and sensitivity of aggregated content**.

---

## ❌ What APS Staff Must Not Do

### 1. **Use Unauthorised AI Tools**
- Copy-pasting work content into public ChatGPT or Gemini via browser.
- ❌ Breach of PSPF Requirement 0086 and ISM-0820.

### 2. **Paste Internal Content into Search Engines**
- Typing phrases like “draft policy for X” or “internal meeting notes” into Google or Bing.
- ❌ Breach of ISM-0820 and ISM-0821 — even if the content seems benign, it may be ingested and profiled by AI systems behind the search engine.

### 3. **Assume OFFICIAL Means “Safe to Use Anywhere”**
- OFFICIAL information still requires protection from foreign access, aggregation, and misuse.
- ❌ Breach of PSPF Requirement 0046 and ISM-0821.

---

## 🧠 Why Search Engines Are Risky

Search engines like Google and Bing:

- **Log search terms**, IP addresses, and behavioural metadata.
- Use AI to **post-process search logs** for personalisation, ad targeting, and model training.
- May store and analyse search inputs in jurisdictions subject to **extrajudicial access**.

Even if you don’t upload a file, **pasting internal content into a search bar** is a form of data exposure.

---

## 🛡️ PSPF/ISM Treatment of AI vs Search Engines

| Tool | Treated As | Requires Authorisation | Risk Level |
|------|------------|------------------------|------------|
| **ChatGPT / Gemini** | Technology System | ✅ Yes (PSPF 0086, 0089) | High |
| **Google / Bing Search** | Online Service | ❌ No (unless integrated) | Moderate |

AI tools are **technology systems** and must be authorised before use.  
Search engines are **online services**, but still subject to usage controls (ISM-0820, ISM-1146, ISM-0821).

---

## 🧷 Final Guidance Summary

### ✅ What’s Safe
- Use authorised AI tools for summarising public content.
- Use AI for generic, non-personalised communications.
- Use AI for meeting notes only from open, public sessions.
- Use AI for policy brainstorming only with public data and aggregation awareness.

### ❌ What’s Not Safe
- Using public AI tools without authorisation.
- Drafting messages that include personal or operational content.
- Generating notes from internal meetings or policy discussions.
- Assuming OFFICIAL means “no risk” — it still requires classification and aggregation review.
