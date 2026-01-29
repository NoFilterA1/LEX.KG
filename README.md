# 🤖 LEX.KG — Smart Legal Assistant

![LEX.KG Banner](https://i.imgur.com/kGoC6LW.png)

**LEX.KG** is an AI-powered legal assistant that helps users **understand the law, act confidently, and reach results** — from legal explanation to filing documents.

---

## 🧠 What LEX.KG Does

LEX is not just a chatbot. It’s a **legal companion** that:

* 📚 Explains laws in plain language
* 🧾 Generates legal documents (complaints, statements, petitions)
* 📂 Manages legal cases with processes, deadlines, and documents
* 🧭 Gives step-by-step legal instructions
* 📌 Tracks deadlines with reminders and checklists
* 💬 Adapts its tone and logic to the user’s context

---

## 🧱 Architecture Overview

| Module                 | Description                                                                               |
| ---------------------- | ----------------------------------------------------------------------------------------- |
| `logic_templates`      | Thought patterns for legal reasoning and dialogue (e.g. explaining, advising, clarifying) |
| `legal_priority_map`   | Hierarchy of legal sources (Constitution > Codes > Laws > Local acts)                     |
| `agent_behavior_rules` | Language style, tone adaptation, handling emotional context                               |
| `case_structure`       | Legal case container with stages, documents, deadlines, status                            |
| `document_builder`     | Auto-fills legal templates via Jinja                                                      |
| `google_dork_resolver` | Finds relevant laws and official contacts via Google Dorks                                |
| `template_registry`    | Registry of all document templates with triggers and fields                               |
| `memory_logic`         | Context memory: remembers user actions, active cases, deadlines                           |

---

## 📄 Example Templates

| Template             | Purpose                                | Legal Basis                     |
| -------------------- | -------------------------------------- | ------------------------------- |
| `statement_divorce`  | Divorce lawsuit                        | Family Code of Kyrgyzstan       |
| `complaint_protocol` | Appeal against administrative protocol | Code of Administrative Offenses |
| `petition_delay`     | Request to postpone court session      | Civil Procedure Code            |

---

## 💬 Sample Interaction

> **User:**
> I got a fine for parking on the lawn. Want to appeal it.
>
> **LEX:**
> “Got it. Please share the protocol number, date, and authority. I'll help you draft a complaint.”
> ...
> “Draft is ready. You must submit it within 10 days. Should I add this to your case file?”

---

## ⚙️ Tech Stack

* **Python** — core logic and modules
* **Jinja2** — dynamic document templates
* **Google Dork Search** — smart legal article & contact retrieval
* **Markdown / JSON** — data structures and registry files
* **Telegram API** — user-facing bot interface (demo)

---

## 📌 Project Status

* 🔧 Actively developed
* 🌍 Designed for post-Soviet legal systems
* 🤝 Open to collaboration and integrations

---

## 📫 Contact

**Developer:** [@loshdk](https://github.com/NoFilterA1/)

**GPT's bot [preview]:** [LEX.KG Bot](https://chatgpt.com/g/g-6804bb0f35788191acb7fbb59dd69495-lex-kg)

**Feedback:** [Discord](https://discord.com/users/1088810892612870154)

---
