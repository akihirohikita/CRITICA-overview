# CRITICA

> **Structure, Not Culture.**
> An AI Knowledge Infrastructure for capturing, structuring, preserving, and transferring field knowledge, tacit expertise, and operational know-how.

CRITICA helps organizations convert scattered documents, multimedia records, expert conversations, daily observations, and improvement proposals into structured, searchable, and continuously improving organizational knowledge — anchored to the actual structure of how work is done.

---

## What CRITICA Does

CRITICA links every piece of knowledge to the operational structures where it belongs:

**Framework → Phase → Category → Process → Step**

This means AI doesn't just answer from documents.
It answers from knowledge that is tied to the actual structure of work.

### A Concrete Example

A traditional swordsmith retires after 40 years.

- **Generic RAG tool**: Stores his interview transcripts. AI can quote them when asked.
- **CRITICA**: Links his knowledge to the exact *Process → Step* he performed. Validates it through a Human Expert Query workflow. Scores its operational relevance against real outcomes (via the γ/Ω metrics). Surfaces it the moment the next operator stands at that step — not when someone happens to search for the right keywords.

The knowledge doesn't just exist somewhere.
**It's at the right place, at the right time, in the right structural context.**

---

## Why Not Just RAG?

Most "AI knowledge management" products today are RAG chatbots wrapped around document storage. They retrieve text. They don't understand operations.

CRITICA is built on a different premise:

| Generic RAG | CRITICA |
|---|---|
| Knowledge = documents | Knowledge = documents tied to processes |
| Search by keyword similarity | Search by structural position in real work |
| One-shot Q&A | Continuous correction & improvement loop |
| AI alone | Human-in-the-loop expert validation |
| Data accumulates | Knowledge **structuralizes** |

The philosophy comes from Professor Murota (GRIPS):
> Don't depend on culture or individuals. **Embed knowledge into structure.**

---

## Core Capabilities

- **Multi-channel knowledge ingestion** — text, audio, image, video with timestamp playback, mobile field capture
- **Process / step-based knowledge structuring** — every artifact knows where it belongs
- **RAG-based AI chat** — grounded in operational structure, not just text similarity
- **Human Expert Query (HEQ) workflow** — bilingual translation, follow-up flows, expert validation gates
- **KAIZEN proposal workflow** — bottom-up improvements that flow into work orders, not into dead memos
- **Daily reflection & operational logging** — the foundation layer of organizational learning
- **Telegram-based field knowledge capture** — voice/photo from the shop floor, AI distillation, expert review
- **Knowledge correction & response correction flows** — when the AI is wrong, the structure learns
- **Knowledge Relevance Calibration (KRC)** — feedback-driven scoring of which knowledge actually helps
- **Knowledge Emergence Graph (KEG)** — visualizes how organizational knowledge forms, connects, and evolves
- **Multi-tenant architecture** — secure isolation per organization, with cross-tenant search for super-admins
- **Three-tier operational structure** — Daily Operations → Work Order Management → Executive Dashboard

---

## Target Use Cases

CRITICA is especially suited for organizations facing **structural knowledge loss**:

- Manufacturing knowledge transfer
- Craft and traditional skill preservation
- Plant operation and maintenance
- Field training programs for new operators
- Agricultural and dairy operation knowledge
- Internal enterprise knowledge infrastructure
- Cross-generational business succession

If your organization's most valuable expertise lives in a few people's heads — and walks out the door when they retire — CRITICA is built for that problem.

---

## Development Scale

Built in just over **3 months** by a single founder-developer working with Claude (Anthropic — Opus + Sonnet):

| Metric | Count |
|---|---|
| Application code | **153,154 lines** |
| Architecture & design documentation | **166,504 lines** |
| Source files (TypeScript / Python) | **473** |
| Total project files | **940** |
| Average daily code velocity | **~1,700 lines/day** |

**Note that the documentation volume exceeds the code volume.**

This is not an accident. It's a deliberate reflection of CRITICA's own philosophy applied recursively to its own development:

> **Structure first. Code second.**
>
> If the design judgment isn't written down, it doesn't exist —
> not for the next developer, not for the next session, not for the founder six months later.

CRITICA is built using the principles CRITICA exists to enable.

---

## Tech Stack

- **Frontend**: TypeScript / React
- **Backend**: Python / FastAPI
- **Infrastructure**: Google Cloud Run, Firebase Hosting, Firestore, Cloud Storage
- **LLM**: **Claude API (Anthropic)** — primary reasoning engine for chat, distillation, translation, and structural analysis
- **Embeddings & Speech**: OpenAI (text-embedding, Whisper)
- **Email**: Resend (inbound + outbound)
- **Multi-modal ingestion**: text, audio (with transcription), images (with vision analysis), video (with timestamped playback)
- **CI/CD**: GitHub Actions with Workload Identity Federation, fully automated staging deployment

---

## Founder-Developer Story

CRITICA is being developed by **Akihiro Hikita**, Founder & CEO of [Cosimo LLC](https://cosimo.jp).

His professional strength is in **upstream business flow design** — not traditional software engineering. CRITICA is being built through deep collaboration with Claude (Anthropic), representing a new model of **AI-augmented solo development** where domain expertise drives architecture, and AI handles implementation discipline under explicit, version-controlled rules.

The project originated from challenges Aki witnessed firsthand:
- Traditional craft preservation (including a working deployment with a Japanese swordsmith)
- Plant operations and technology transfer
- Cross-generational business succession in mid-sized manufacturing
- Knowledge loss as Japan's experienced workforce retires

CRITICA is the system Aki wished existed when those problems first surfaced.

---

## Status

CRITICA is in **active development with live deployments and active enterprise dialogue.**

- ✅ **Working pilot** with a traditional Japanese swordsmith (technology transfer use case)
- ✅ **3-hour live demonstration** completed with a manufacturing operations company in Kanagawa, Japan (waste oil collection & refining, fleet of ~60 trucks) — April 2026
- ✅ **Three-tier operational architecture complete**: Daily Operations Layer (DR-1) → Work Order Management Layer (KPM-1) → Executive Reporting Layer (MR-1)
- 🔄 In conversation with multiple enterprise prospects across manufacturing, dairy operations, and traditional craft sectors

This repository is a **public overview only**.
The main product source code remains private.

### Inquiries

For partnership, pilot deployment, evaluation, or investment inquiries:

📧 **a.hikita@cosimo.jp**
🌐 **[fixgaps.biz](https://fixgaps.biz)**

---

## Philosophy in One Line

> CRITICA is the nervous system. ERP and CMMS are the organs.
> An organization without a nervous system can move, but it cannot learn.

---

*© 2026 Cosimo LLC. CRITICA is a trademark of Cosimo LLC.*
