# 🚀 n8n SEO Content Automation Pipeline

An end‑to‑end **AI‑powered SEO content automation workflow** built with **n8n**, **OpenAI**, **Google Sheets**, and **WordPress**.

This project automates the complete journey of a blog post — from **idea planning** to **SEO‑optimized draft publishing** — without manual copy‑paste or repetitive effort.

---

## 📌 What This Project Does

This n8n workflow:

* Reads blog topics from **Google Sheets**
* Generates **long‑form, SEO‑optimized WordPress articles** using OpenAI
* Outputs content in **WordPress Gutenberg block HTML** format
* Publishes the article as a **draft in WordPress**
* Generates **Meta Title & Meta Description** using an AI SEO expert chain
* Updates **status, post ID, and live URL** back into Google Sheets

All steps are fully automated and logged.

---

## 🧩 Workflow Overview

**Flow:**

Google Sheets → n8n → OpenAI (Article) → WordPress (Draft) → OpenAI (SEO Meta) → Google Sheets

The workflow is triggered manually (can be extended to cron or webhook triggers).

---

## ⚙️ Tech Stack

* **n8n** – Workflow orchestration
* **OpenAI (GPT‑5 / GPT‑4.1‑mini)** – Content & SEO meta generation
* **Google Sheets API** – Content planning & tracking
* **WordPress REST API** – Draft publishing
* **LangChain (n8n nodes)** – Structured AI chains

---

## ✨ Key Features

* ✅ Fully automated SEO content pipeline
* ✅ WordPress‑ready Gutenberg block HTML output
* ✅ Featured‑snippet optimized structure
* ✅ EEAT & Helpful Content aligned writing logic
* ✅ AI‑generated Meta Title & Meta Description
* ✅ Google Sheets based tracking system
* ✅ Scalable for bulk content production

---

## 📄 Google Sheets Structure (Required)

Your Google Sheet should include columns like:

* `Rows` (unique identifier)
* `TITLE` (Blog topic)
* `MetaTitle`
* `MetaDescription`
* `Status`
* `Live URL`
* `ID Post`

Additional optional columns:

* Focus KWs
* Section
* AI Tools used
* Humanised
* Proofread

---

## 📝 Article Generation Rules

The AI article generator is configured to:

* Start with a **featured snippet (45–60 words)**
* Use **H2 for main headings, H3 for subheadings**
* Follow **modern Google SEO & EEAT guidelines**
* Maintain **beginner‑friendly, professional tone**
* Avoid fluff, emojis, keyword stuffing
* Produce **1,500–4,000 word** in‑depth articles

Output is strictly in **WordPress block HTML** format.

---

## 🔐 Credentials Required

Before running the workflow, configure:

* Google Sheets **Service Account** credentials
* WordPress **REST API** credentials
* OpenAI API key

All credentials are managed securely via n8n.

---

## ▶️ How to Use

1. Import the workflow JSON into n8n
2. Set up all required credentials
3. Prepare your Google Sheet with blog topics
4. Click **“Test workflow”**
5. Review the generated WordPress draft
6. Publish when ready

---

## 🎯 Use Cases

* SEO agencies automating blog production
* Hosting companies producing technical content
* SaaS teams scaling content marketing
* Bloggers building AI‑assisted workflows

---

## 🚧 Future Improvements

* Scheduled publishing
* Internal linking automation
* Image generation integration
* Multi‑language content support
* Editorial approval workflows

---

## 🤝 Contributing

Contributions, improvements, and ideas are welcome.

If you work with **n8n, AI automation, or SEO workflows**, feel free to open an issue or submit a pull request.

---

## 📜 License

This project is open‑source and intended for learning, experimentation, and production use with proper review.

---

## ⭐ Final Note

This project focuses on **practical automation**, not hype — solving real SEO and publishing workflow problems using AI and orchestration.

If this helped you, consider giving the repo a ⭐
