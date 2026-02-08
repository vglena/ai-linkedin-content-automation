# 🤖 AI-Driven LinkedIn Content Automation

This repository contains an independent automation system built with **Make** that generates and publishes professional LinkedIn posts using **artificial intelligence**.

The system transforms structured ideas into:
- A polished LinkedIn post
- A realistic, AI-generated image
- A published LinkedIn post
- A fully documented content record in Airtable

The automation is designed for **real-world social media workflows**, with a strong focus on content quality, consistency, and traceability.

---

## 🎯 Purpose

The purpose of this automation is to:

- Streamline LinkedIn content creation
- Combine text and image generation using AI
- Eliminate manual publishing steps
- Maintain a historical content database
- Ensure professional and brand-consistent output

---

## 🧩 Automation Overview

The scenario performs the following steps:

1. Capture a new content idea via a Tally form
2. Generate a LinkedIn post using Gemini AI
3. Generate an image description aligned with the post
4. Create a realistic image using Stable Diffusion (via HTTP)
5. Upload the image to Google Drive
6. Apply public sharing permissions
7. Publish the post on LinkedIn with the generated image
8. Store all generated assets and metadata in Airtable

---

## 🛠️ Tools and Services

- **Make (Integromat)**
- **Tally**
- **Gemini AI**
- **Hugging Face (Stable Diffusion XL)**
- **Google Drive**
- **LinkedIn**
- **Airtable**

---

## 📄 Blueprint

The Make scenario blueprint is available in the `blueprints/` folder and can be imported directly into Make.

---

## 👤 End User

The end user does **not interact with Make**.

All interaction happens through:
- A Tally form (input)
- LinkedIn (published content)
- Airtable (content archive and review)

---

## 📌 Notes

- The automation is triggered instantly via webhook
- All AI prompts are embedded directly in the scenario
- Generated content is designed to be professional, realistic, and brand-safe
- The system can be extended to other social platforms

---


