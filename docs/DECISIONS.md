# 🧠 Technical Decisions – AI LinkedIn Content Automation

## Why a Standalone System?

This automation is independent to:

- Allow reuse for different brands or campaigns
- Avoid coupling with unrelated automations
- Enable future multi-platform extensions

---

## AI Model Selection

- **Gemini** is used for text generation due to its language quality and instruction-following
- **Stable Diffusion XL** is used for image generation to ensure realistic, professional visuals

This combination provides flexibility and control over both modalities.

---

## Image Generation via HTTP

The Hugging Face API is accessed using a raw HTTP request to:

- Avoid platform lock-in
- Maintain full control over model parameters
- Demonstrate API-level integration beyond native modules

---

## Storage and Traceability

Airtable is used to store:
- Original idea
- Context
- Generated post text
- Image prompt
- Final image

This enables:
- Content review
- Reuse
- Auditing and iteration

---

## Future Improvements

- Manual approval step before publishing
- Multi-language content generation
- Support for additional social networks
- Scheduling instead of instant publishing
