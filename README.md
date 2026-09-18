# Ryan Cox

Systems & AI engineer building local-first software across C++, CUDA, Rust, Swift/Metal, and self-hosted infrastructure.

I build end-to-end — from GPU-accelerated runtimes and native apps to model integration, APIs, containers, and the infrastructure that runs them. My current work centers on [AiRC.ai](https://airc.ai).

## Current flagship project

### [AiRC Orchestration](https://github.com/AiRC-ai/AiRC-Orchestration)

**One desktop workspace for AI work that outlasts a single prompt.** AiRC keeps your project, tasks, model state, capabilities, goals, plans, and execution evidence connected — then puts hosted, local, or remote models to work with tools, extensions, skills, recipes, apps, and automations.

<p align="center">
  <a href="https://github.com/AiRC-ai/AiRC-Orchestration">
    <img src="https://raw.githubusercontent.com/AiRC-ai/AiRC-Orchestration/main/assets/airc-whisper-browser-workflow.gif" alt="AiRC Orchestration using the in-app browser to inspect and summarize the public AiRC Whisper repository" width="900">
  </a>
</p>

<p align="center">
  <sub>Real session: the muse-glimmer model uses the in-app browser to find, inspect, and summarize the public AiRC Whisper repository.</sub>
</p>

**[Download the latest release](https://github.com/AiRC-ai/AiRC-Orchestration/releases/latest)** — signed and notarized for macOS (Apple silicon) and packaged for Debian-family Linux (amd64), with Windows support in active development.

#### Highlights

- **Sub-agent Swarm** — orchestrate a team, not a single thread. **Agent**, **Swarm**, and **Agents+Swarm** modes let the active model delegate to a roster of sub-agents you configure — any model, any provider. Sub-agents name themselves for the task, fan out in parallel where it's safe, and stream into a live **Sub-agents rail** with each agent's provider, model, status, tokens, and latest tool call.
- **Vision Bridge** — give every model eyes. The optional image sub-agent sends screenshots, charts, and photos to a multimodal model you choose and passes the description back as text — so text-only models keep working, and images are never silently dropped.
- **Provider usage page** — see what you're spending. Live account balances, plan usage, and peak/off-peak pricing windows where providers publish them, backed by refreshed rate cards across OpenAI, Anthropic, Google, xAI, Together, Fireworks, Moonshot, Z.ai, MiniMax, DeepSeek, and Ollama Cloud.
- **Session Messaging** — tasks that talk to each other. Send messages between sibling tasks with delivery receipts and attribution, steer a running turn, and stop any run — even ones started by another window or a scheduled automation.
- **Guardrails built in** — swarms respect each provider account's concurrent stream capacity, sub-agents start read-only with write access opt-in, a watchdog bounds every delegation, and a task budget guard keeps parallel work efficient.

#### Platform

- Persistent project tasks, goals, plans, and model state — pick up exactly where you left off
- Four approval modes from full autonomy to pure chat, plus read-only **Plan Mode** before any change
- Hosted, local, and remote models with model-aware context and reasoning controls — OpenAI-compatible and Anthropic-compatible APIs with a provider catalog that configures itself
- Supervised execution: the optional **Orchestrator** monitors, messages, and interrupts sessions while the main task stays coordinated
- Tools, MCP extensions, skills, recipes, apps, and natural-language automations
- Integrated work surfaces: developer tools, in-app browser, computer control, terminal, and an encrypted tunnel for mobile access
- Voice dictation through OpenAI, ElevenLabs, Groq, or fully local on-device models
- Privacy-first defaults, opt-in product feedback, and updates that verify before install
- An `airc` command-line interface and Agent Client Protocol integration for subscription-backed and external agents

## Shipped product

- **[AiRC Transcriber — App Store](https://apps.apple.com/us/app/airc-transcriber/id6780125744)** — Private, on-device transcription for iPhone, Apple Watch, and Apple Silicon Mac, with cross-device processing, searchable transcripts, captions, exports, and transcript-grounded local AI.

## Featured open-source projects

- **[AiRC Whisper](https://github.com/AiRC-ai/AiRC-Whisper)** — Native Apple Silicon transcription with an AppKit front end, whisper.cpp, Metal acceleration, AVFoundation media conversion, and local export workflows.
- **[Collatz Research System](https://github.com/AiRC-ai/Collatz)** — Reproducible C++20/CUDA path analysis, supervised embeddings, held-out validation, and tooling for falsifying proof candidates.

## Focus

Privacy-first, local-first AI products; desktop orchestration; reproducible high-performance computing; and reliable self-hosted systems.

C/C++ · CUDA · Rust · Swift · Metal · Python · Docker · Linux/macOS

## Connect

[AiRC.ai](https://airc.ai) · [LinkedIn](https://www.linkedin.com/in/ryancox9/)
