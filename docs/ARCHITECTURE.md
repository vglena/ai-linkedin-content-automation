# 🧱 Architecture – AI LinkedIn Content Automation

## Overview

This automation implements an **end-to-end AI content pipeline** for LinkedIn.

Structured user input is transformed into:
- Textual content
- Visual content
- A published social media post
- A stored content record

Each step is fully automated and auditable.

---

## High-Level Flow

1. Webhook trigger from Tally
2. AI-based text generation (Gemini)
3. AI-based image prompt generation (Gemini)
4. Image generation via Stable Diffusion (HTTP API)
5. Asset storage in Google Drive
6. Public access configuration
7. LinkedIn publication
8. Content archival in Airtable

---

## Design Characteristics

- Event-driven architecture
- Clear separation between content generation and distribution
- Stateless execution
- External services used only where they add value

---

## Output

The final outputs are:
- A public LinkedIn post
- A shareable image
- A structured Airtable record containing all assets and prompts
