# Lior Cohen

QA Automation Engineer at [AiQ & Kaleidoo](https://kaleidoo.ai) · Building AI infrastructure in public

`Rust` · `Python`

---

## What I'm Building

### ShrimPK — AI Memory Kernel
> *Push-based memory. Memories find you — you don't search for them.*

Pure Rust AI-OS memory kernel that inverts the standard pull-based model. Every message auto-stored. Every prompt auto-echoed. No user intervention.

- **3.50ms P50** retrieval at 100,000 memories
- **100% LongMemEval** accuracy (isolated benchmark)
- Pipeline: `Bloom → LSH → Cosine → Hebbian → Recency → HyDE → Reranker`
- Full daemon architecture: HTTP service + MCP server + CLI + system tray
- Registered as a Claude Code MCP tool globally

[![GitHub](https://img.shields.io/badge/bellkisai%2Fkernel-Apache_2.0-blue?logo=github)](https://github.com/bellkisai/kernel)

---

### MLTK — ML Test Kit
> *Every ML tool tests one thing. MLTK tests everything.*

Most ML testing tools pick a lane — LLM eval, or data monitoring, or compliance. I built MLTK to cover the whole stack in a single pytest plugin: raw data through deployed model, training loop through production inference, open-source assertions through regulated compliance.

The architecture I designed is a Python + Rust hybrid — statistical computations (KS, PSI, Wasserstein, SIMD cosine, PII scanning) are implemented in Rust via PyO3 and compiled into the wheel. No Rust toolchain required. Just `pip install`.

**What no other tool does:**

| Capability | MLTK | Everyone Else |
|---|---|---|
| Behavioral consistency testing | 7 assertions | Nobody |
| Training bug detection | P0 / P1 / P2 coverage | Nobody |
| Generates committable test code | `mltk scan` → `.py` files | Competitors generate PDFs |
| Full lifecycle in one plugin | data → model → inference → LLM → compliance | DeepEval: LLM only · Evidently: monitoring only |
| VS Code extension | Test Inspector, inline results | Nobody (in ML testing) |
| Rust-accelerated stats | Pre-compiled wheel | Nobody |

**215 assertions · 3,080+ tests · 24 CLI commands · 8 compliance frameworks**
EU AI Act · FDA 21 CFR Part 11 · OWASP LLM Top 10 · NIST AI RMF
`Python 3.10+` · `Rust / PyO3 / Maturin` · `pytest plugin` · `FastAPI` · `VS Code extension`

---

### Bellkis HUB — AI Desktop App
> *One app to run, route, and evaluate every AI model you work with.*

A feature-packed desktop application built with Tauri + Rust + React. Local model management, cloud provider routing, fine-tuning workflows, ML training platform, secure air-gapped mode, custom themes, and a built-in spending tracker — with ShrimPK memory kernel under the hood.

`Tauri 2.x` · `Rust / Axum` · `React 19 / TypeScript` · `PostgreSQL` · `Stripe` · `Docker`

---

## Currently Building

| Project | Stack | Status |
|---------|-------|--------|
| **ShrimPK** — AI memory kernel | Pure Rust, fastembed, LSH, Hebbian | v0.4.0 live, v0.5.0 in progress |
| **MLTK** — ML testing toolkit | Python + Rust (PyO3), pytest, FastAPI | v0.9.0 |
| **Bellkis HUB** — AI desktop app | Tauri 2.x, Rust/Axum, React 19 | Pre-launch |

---

## Tech Stack

**Systems & Backend**
`Rust` · `Python` · `Axum` · `FastAPI` · `PyO3` · `Maturin` · `Tokio` · `PostgreSQL` · `SQLite` · `Redis`

**AI / ML**
`fastembed` · `LSH` · `Bloom filters` · `Hebbian learning` · `SIMD cosine` · `cross-encoders` · `HyDE` · `ONNX` · `embeddings`

**Frontend & Desktop**
`React 19` · `TypeScript` · `Tauri 2.x` · `shadcn/ui` · `Zustand` · `Tailwind CSS`

**Testing & QA**
`pytest` · `Playwright` · `cargo-fuzz` · `cargo test` · `E2E` · `behavioral consistency testing`

**DevOps**
`GitHub Actions` · `Docker` · `Fly.io` · `Stripe` · `MCP (Model Context Protocol)`

---

## Open Source

- [bellkisai/kernel](https://github.com/bellkisai/kernel) — ShrimPK AI memory kernel · Apache 2.0 · PRs welcome

---

*Israel · Working at [AiQ & Kaleidoo](https://kaleidoo.ai) · Building in public · [lior@bellkis.com](mailto:lior@bellkis.com)*
