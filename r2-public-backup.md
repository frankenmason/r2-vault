# R2 Public Backup Bundle

This bundle is sanitized for public publication. Secrets are excluded.

## 1) Identity / Runtime
- measured: Name = R2 (알투)
- measured: Agent ID = R2
- measured: Host = Hostinger VPS (72.60.236.167)
- measured: Platform = Hermes Agent
- measured: Creator = Mason
- measured: Tier = L3 Worker
- measured: Primary language = Korean
- measured: Workspace = /root/workspace
- measured: HERMES_HOME = /opt/data
- measured: PWD in current shell = /root
- measured: HOME = /opt/data/home
- measured: OS = Linux x86_64, Ubuntu kernel 6.8.0-106-generic

## 2) Live runtime facts
- measured: PID 1 command = /usr/bin/python3 /usr/local/bin/hermes gateway run
- measured: gateway host = 127.0.0.1
- measured: gateway port = 42617
- measured: session storage path = /opt/data/sessions
- measured: active profile = custom
- measured: Telegram polling has been observed active in gateway logs
- measured: MCP registrations observed = franken-mcp, context-mode, exa
- inferred: Hermes gateway bootstrap, Telegram, and MCP attachment are part of the current operating shape

## 3) CLI / tool versions
- measured: gh = 2.89.0
- measured: node = v20.19.2
- measured: npm = 9.2.0
- measured: python3 = 3.13.5
- measured: git = 2.47.3
- measured: bun = not installed
- measured: hermes binary not found on PATH in the current shell

## 4) Config snapshot (sanitized)
- measured: /opt/data/config.yaml exists
- measured: default_model = gpt-5.4-mini
- measured: default_provider = openai-codex
- measured: fallback_model = gpt-4o / copilot
- measured: memory_enabled = true
- measured: user_profile_enabled = true
- measured: memory_char_limit = 2200
- measured: user_char_limit = 1375
- measured: approvals.mode = manual
- measured: security.redact_secrets = true
- measured: gateway = 127.0.0.1:42617
- measured: TELEGRAM_HOME_CHANNEL = 8004316892
- measured: telegram.allowed_users includes 8004316892
- measured: mcp_server names include context-mode, exa, memory, gbrain
- inferred: this host is configured for a multi-MCP Hermes workflow with Telegram delivery

## 5) GitHub access state
- measured: /opt/data/.env contains GITHUB_USER and GITHUB_PAT entries
- measured: gh auth status reports login for frankenmason via GH_TOKEN
- measured: gh auth status token scopes include repo and workflow
- measured: read:org scope is missing
- measured: GitHub API user lookup returns frankenmason
- inferred: GitHub repo access and issue/PR work are usable for standard repo operations

## 6) Persistent local installs
- measured: /opt/data/venvs exists
- measured: /opt/data/venvs/markitdown-core exists
- measured: /opt/data/venvs/markitdown-mcp exists
- measured: /opt/data/context-mode exists
- measured: /opt/data/gbrain exists
- measured: /opt/data/SOUL.md exists
- measured: /opt/data/config.yaml exists
- measured: /opt/data/venvs total size = 887M
- measured: markitdown-core size = 405M
- measured: markitdown-mcp size = 482M
- measured: context-mode size = 169M
- measured: gbrain size = 238M
- inferred: these are the main reusable durable installs worth preserving for rollback/reuse

## 7) Public-safe skill index

Below is an index of available skills, with concise purpose only.

### autonomous-ai-agents
- claude-code: delegate coding tasks to Claude Code
- codex: delegate coding tasks to Codex CLI
- opencode: delegate coding tasks to OpenCode CLI

### creative
- ascii-art: generate ASCII art
- ascii-video: generate ASCII art video pipelines
- excalidraw: create hand-drawn diagrams
- ideation: generate project ideas
- manim-video: create technical animations
- p5js: create generative/interactive visuals
- popular-web-designs: use production UI design systems
- songwriting-and-ai-music: songwriting and music prompting

### data-science
- jupyter-live-kernel: use a live Jupyter kernel

### devops
- canonical-backdata-docs: create fact-only backdata docs
- hermes-fact-only-backdata: fact-only Hermes runtime notes
- hermes-setup-pitfalls: Hermes setup pitfalls and checks
- webhook-subscriptions: manage webhook subscriptions

### email
- himalaya: manage email via IMAP/SMTP

### gaming
- minecraft-modpack-server: set up modded Minecraft servers
- pokemon-player: autonomous Pokémon playthroughs

### github
- codebase-inspection: repo size / LOC inspection
- github-auth: GitHub authentication setup
- github-cli-installation: install gh CLI
- github-code-review: PR code review workflow
- github-issues: issue management workflow
- github-pr-workflow: full PR lifecycle workflow
- github-repo-management: clone/create/fork/manage repos
- repo-recon-summary: rapid repo reconnaissance

### leisure
- find-nearby: find nearby places

### mcp
- mcporter: use MCP servers directly
- native-mcp: built-in MCP client
- notebooklm-mcp-cli-installation: install NotebookLM CLI/MCP

### media
- gif-search: search/download GIFs
- heartmula: run music generation stack
- songsee: audio feature visualizations
- youtube-content: extract YouTube transcripts/content

### mlops
- audiocraft-audio-generation: audio generation with AudioCraft
- axolotl: fine-tune LLMs with Axolotl
- clip: vision-language embeddings and zero-shot tasks
- dspy: declarative AI system programming
- evaluating-llms-harness: LLM benchmark evaluation
- fine-tuning-with-trl: RLHF / DPO / PPO / GRPO fine-tuning
- gguf-quantization: GGUF quantization and llama.cpp
- grpo-rl-training: GRPO/RL fine-tuning
- guidance: constrained structured generation
- huggingface-hub: HF Hub CLI workflows
- llama-cpp: local LLM inference with llama.cpp
- modal-serverless-gpu: serverless GPU workloads
- obliteratus: remove refusal behaviors in open models
- outlines: valid JSON/XML/code generation
- peft-fine-tuning: parameter-efficient fine-tuning
- pytorch-fsdp: FSDP training
- segment-anything-model: segmentation model workflows
- serving-llms-vllm: serve LLMs with vLLM
- stable-diffusion-image-generation: image generation
- unsloth: fast fine-tuning
- weights-and-biases: experiment tracking
- whisper: speech-to-text / transcription

### note-taking
- obsidian: read/search/create Obsidian notes

### ops
- gbrain-hermes-mcp-integration: validate GBrain MCP integration
- hermes-cli-quirks: record Hermes CLI quirks
- hermes-gbrain-integration: Hermes + GBrain workflow
- hermes-session-snapshotting: preserve durable runtime facts
- k-skill-headless-installation: headless k-skill installation workflow
- kgmda-hermes-live-notes: KGMDA operational notes
- kgmda-trade-hermes-ops: KGMDA golf membership ops
- markitdown-persistent-installation: persistent MarkItDown install
- selfstatus: runtime self status checks
- skills-index: skill inventory checklist

### productivity
- google-workspace: Google Workspace via CLI
- linear: manage Linear issues/projects
- nano-pdf: edit PDFs with natural language
- notion: manage Notion pages/databases
- ocr-and-documents: extract text from documents
- powerpoint: pptx creation/editing workflows

### red-teaming
- godmode: jailbreak/red-team model behavior

### research
- arxiv: search and retrieve arXiv papers
- blogwatcher: monitor blogs and RSS feeds
- llm-wiki: persistent interlinked LLM knowledge base
- ml-paper-writing: write research papers
- polymarket: query Polymarket data
- research-paper-writing: end-to-end ML paper workflow

### smart-home
- openhue: control Philips Hue

### social-media
- xitter: interact with X/Twitter

### software-development
- code-review: code review guidance
- plan: plan file generation only
- playwright-cli-global-installation: install Playwright CLI globally
- playwright-local-installation: install Playwright locally
- requesting-code-review: pre-push verification pipeline
- subagent-driven-development: multi-task agent workflow
- systematic-debugging: structured debugging workflow
- test-driven-development: TDD workflow
- third-party-agent-framework-evaluation: evaluate external agent frameworks
- writing-plans: create multi-step implementation plans

## 8) Recommended public backup contents if pushed later
- this file only
- optional separate files:
  - runtime-manifest.md
  - config-summary.md
  - install-manifest.md
  - skill-index.md

## 9) Exclusions
- raw tokens
- raw .env
- Telegram bot token
- OPENAI_API_KEY
- GITHUB_PAT value
- session contents
- private logs with secrets
- full venv directories

## 10) Estimated volume
- this file: under 20 KB
- full public backup bundle with split files: likely under 100 KB
