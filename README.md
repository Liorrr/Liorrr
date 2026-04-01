# Lior

QA Automation Engineer at [AiQ & Kaleidoo](https://kaleidoo.ai) · Indie founder · Rust + Python + Godot

Building open-source tools at the intersection of AI reliability and developer experience.

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
> *pytest for ML — unified testing across the entire ML lifecycle.*

Open-source Python + Rust toolkit that extends pytest into every stage of ML: data quality, model validation, inference latency, training bug detection, LLM evaluation, compliance.

- **3,080+ tests** · **215 assertions** · **24 CLI commands**
- **7 behavioral consistency assertions** — first-mover, no competitor has this
- Rust-accelerated stats (KS, PSI, KL, chi2, Wasserstein, SIMD cosine) via PyO3
- Full ML lifecycle: data → model → inference → training → LLM → compliance
- Compliance modules: EU AI Act · FDA 21 CFR Part 11 · OWASP LLM Top 10
- pytest plugin: drop `--mltk-report` onto any existing test run
- VS Code extension for inline test results

[![PyPI](https://img.shields.io/pypi/v/mltk?label=PyPI&logo=python)](https://pypi.org/project/mltk)
[![GitHub](https://img.shields.io/badge/Liorrr%2Fmltk-Apache_2.0-blue?logo=github)](https://github.com/Liorrr/mltk)

---

## Currently Building

| Project | Stack | Status |
|---------|-------|--------|
| **ShrimPK** — AI memory kernel | Pure Rust, fastembed, LSH, Hebbian | v0.4.0 live, v0.5.0 in progress |
| **MLTK** — ML testing toolkit | Python + Rust (PyO3), pytest, FastAPI | v0.9.0 on PyPI |
| **Bellkis HUB** — AI desktop app | Tauri 2.x, Rust/Axum, React 19, Stripe | Pre-launch |
| **Void Recursion** — space shooter | Godot 4.6, GDScript | Sprint 9 complete |
| **Rift Gardener** — tower defense | Godot 4.6, GDScript | Pre-production |

---

## Tech Stack

**Systems & Backend**
`Rust` · `Python` · `Axum` · `FastAPI` · `PyO3` · `Maturin` · `Tokio` · `PostgreSQL` · `SQLite` · `Redis`

**AI / ML**
`fastembed` · `LSH` · `Bloom filters` · `Hebbian learning` · `SIMD cosine` · `cross-encoders` · `HyDE` · `ONNX` · `embeddings`

**Frontend & Desktop**
`React 19` · `TypeScript` · `Tauri 2.x` · `shadcn/ui` · `Zustand` · `Tailwind CSS` · `Expo (React Native)` · `PixiJS`

**Testing & QA**
`pytest` · `Playwright` · `cargo-fuzz` · `cargo test` · `E2E` · `behavioral consistency testing`

**DevOps**
`GitHub Actions` · `Docker` · `Fly.io` · `Stripe` · `MCP (Model Context Protocol)`

**Game Dev**
`Godot 4.6` · `GDScript` · `2D pixel art pipeline`

---

## By the Numbers

| | |
|---|---|
| ShrimPK retrieval speed | **3.50ms P50** at 100K memories |
| ShrimPK accuracy | **100% LongMemEval** (isolated) |
| MLTK tests | **3,080+** passing |
| MLTK assertions | **215** (7 behavioral consistency — first in space) |
| MLTK CLI commands | **24** |

---

## Open Source

All public projects are **Apache 2.0** licensed. PRs welcome on both repos.

- [bellkisai/kernel](https://github.com/bellkisai/kernel) — ShrimPK AI memory kernel
- [Liorrr/mltk](https://github.com/Liorrr/mltk) — MLTK ML testing toolkit

---

*Israel · Working at [AiQ & Kaleidoo](https://kaleidoo.ai) · Building in public*
