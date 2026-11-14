# Aurelius-Rising
Aurelius Rising is a browser extension for AI roleplay that helps manage story context across ChatGPT and DreamJourney AI. Import and select Nexus memories, save scene notes, and preview or copy context for chats. It also offers archive tools, JLLM memory copying, and opt-in analytics with clearly labeled energy estimates.
Aurelius Rising v0.5.8.45

A browser extension for managing roleplay context and memories across ChatGPT, DreamJourney AI, and JanitorAI.

Included downloads:
- Orion extension v0.5.8.45
- Desktop extension v0.5.8.45
- Aurelius Archive Lab
- Cloudflare analytics receiver scaffold v1.0

Features:
- ChatGPT behavioral modules and user-controlled context handoff.
- DreamJourney AI Nexus import, memory selection and presets, scene context, and optional one-message context injection.
- JLLM Memory Nodes Lite for selecting, previewing, and copying memories to paste into JanitorAI’s memory fields. It does not modify JLLM requests.
- Archive Lab tools for importing, searching, and exporting chat archives.
- Optional analytics for generations, rerolls, continuity corrections, and estimated energy use.

Analytics are off by default. Reports are sent only after the user enables collection, gives consent, and presses Send. The endpoint is prefilled and editable. Reports contain aggregate counts, not chat messages or prompts. Energy figures are estimates, not provider measurements.

The analytics receiver is deployed, and a test report was confirmed in its database. Controlled long-session comparisons and additional platform adapters remain future work; they are not blockers for this release.
