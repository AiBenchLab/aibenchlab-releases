# AiBenchLab — Beta (vcomponents-v1)

**Stop guessing which AI model works. Prove it.**

AiBenchLab is a professional Windows desktop app for benchmarking local and cloud AI models on **your** hardware — 254 tests across 998 scoring dimensions, 11 domains, and 22 pre-built suites. Your prompts, models, and results stay on your machine.

> 🧪 **This is a public beta (vcomponents-v1).** Expect a few rough edges — your results and feedback shape v1.0.

---

## What's New (v0.7.3)

- Enterprise audit trail with SHA-256 hash-chain integrity verification
- Offline activation for air-gapped deployments
- SIEM webhook integration (Splunk, Datadog, ELK)

[Full release notes →](https://github.com/AiBenchLab/aibenchlab-releases/releases/latest)

---

## Why AiBenchLab

- **100% local.** Benchmarks run on your computer. **No telemetry** — nothing about your prompts, models, or results ever leaves your machine.
- **Hardware-honest.** Scores reflect *your* CPU/GPU, not a vendor's lab.
- **Verifiable.** Every result exports as a tamper-evident `.mbx` file (SHA-256 + hardware fingerprint) you can independently check.

---

## Install

1. Download **`AiBenchLab-Beta_components-v1_x64_en-US.msi`** from the **[latest release](https://github.com/AiBenchLab/aibenchlab-releases/releases/latest)**.
2. Double-click the `.msi` and follow the prompts.
3. Launch **AiBenchLab** from the Start Menu.

> **Windows SmartScreen warning?** The beta isn't code-signed yet, so Windows may show "unknown publisher." Click **More info → Run anyway**.

> **Verify your download (optional).** Match the file's hash against the SHA-256 shown on the release page:
> ```powershell
> Get-FileHash .\AiBenchLab-Beta_components-v1_x64_en-US.msi -Algorithm SHA256
> ```

---

## 📖 Documentation & Quick Start

Full guides live on the docs hub — **[aibenchlab.com/docs](https://aibenchlab.com/docs/)**:

- **Quick Start Guide** — run your first benchmark in under 5 minutes
- **The Benchmark Wizard** — describe what you need; it builds the test suite
- **Understanding Your Score** — what the composite Score means
- **Setting Up Local & Cloud Providers** — Ollama, LM Studio, OpenAI, Anthropic, Gemini, Groq, and more
- **Cost Estimator** — API + electricity costs before you run

---

## Support

Questions? Reply to your trial email, or reach us through **[aibenchlab.com](https://aibenchlab.com)**.

---

*© The Molen Company*
