# Daniel Ramirez.

**Sound Designer & Infrastructure Engineer — I build the audio and the systems it runs on.**

---

I've spent a decade designing interactive audio for games, UX, and media — then started building the infrastructure to run it myself. Today that means a 100+ container homelab across ~10 machines on a Tailscale zero-trust mesh, local AI audio inference servers, and a growing suite of agent-first tools that sit at the exact boundary of audio engineering and platform work. Earning CompTIA A+, Network+, and Security+ in 2026.

---

## Pillar I — Audio / DSP / Music Tooling

- **[echo-bridge](https://github.com/danialrami/echo-bridge)** — Partitioned-convolution reverb in C++ on a Daisy Seed (ARM); early-reflection FFT at 64 pts, late-tail at 1024 pts, USB IR loading, deployed in a guitar pedal
- **[lufs-workchain](https://github.com/danialrami/lufs-workchain)** — YAML-driven modular audio pipeline with an agent-first npm CLI: EBU R128 normalization, AI-training protection, spectrogram artwork, structured JSON output and NDJSON progress for agent consumption
- **[midi-audio-recorder](https://github.com/danialrami/midi-audio-recorder)** — Max/MSP patch that simultaneously records dual stereo pairs + MIDI from a Nord Stage 3 into timestamped folders; real-time spectroscope and level monitoring
- **[voice-treatment-utility](https://github.com/danialrami/voice-treatment-utility)** — Python post-processing chain for AI TTS output: RNNoise → EQ → SOXR 48 kHz upsample → Matchering reference master → 24-bit WAV + 320 kbps MP3
- **[canvas-generator_spotify](https://github.com/danialrami/canvas-generator_spotify)** — Converts album art to BPM-synced Spotify Canvas MP4 via glitch effects and FFmpeg; PIL + NumPy + configurable intensity

---

## Pillar II — Infrastructure / Homelab / Networking

- **[homelab](https://github.com/danialrami/homelab)** — 100+ containers across ~10 hosts, Docker Compose stacks per machine, orchestrated via a custom OpenCode automation agent; services span Prometheus + Grafana observability, Forgejo, n8n, Matrix, Immich, Plex, and more
- **[tailscale-acls](https://github.com/danialrami/tailscale-acls)** — ACL policy as code (HuJSON) for a multi-site Tailscale mesh; PR-gated CI runs `tailscale acl test` before auto-deploying policy to the live tailnet — GitOps applied to zero-trust networking
- **[backup-scripts](https://github.com/danialrami/backup-scripts)** — Cross-platform rsync backup suite with Docker-aware exclusions, configurable retention windows, and Markdown system-report generation
- **[system-report](https://github.com/danialrami/system-report)** — Shell script producing Markdown-formatted host health snapshots: disk, packages, running services, Docker images

---

## Pillar III — AI Agents / Automation

- **[ffmpeg-mcp-server](https://github.com/danialrami/ffmpeg-mcp-server)** — MCP server that exposes FFmpeg batch-processing to AI assistants; Docker-sandboxed execution, whitelist flag validation, shell-injection protection, network-disabled containers
- **[lufs-agents](https://github.com/danialrami/lufs-agents)** — Nix-flakes multi-agent coordination framework for professional audio workflows; 7 specialized agents (engineering, creative, ops, QA, etc.) + an audio MCP server + EBU R128 analyzer
- **[civic-agent](https://github.com/danialrami/civic-agent)** — Local civic voting assistant built on OpenCode: permission-bounded Python tool calls the Google Civic API, checks data freshness, and answers questions via SearXNG; read-only by design
- **[opencode-agent-definitions](https://github.com/danialrami/opencode-agent-definitions)** — 8-doc internal reference covering OpenCode agent architecture, configuration patterns, permission design, and prompt engineering; the knowledge base behind the automation layer

---

## Stack

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Wwise](https://img.shields.io/badge/Wwise-00A0DC?style=flat-square&logo=audiokinetic&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Max/MSP](https://img.shields.io/badge/Max%2FMSP-525252?style=flat-square&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)

**Audio:** Wwise (cert. 101/201) · Unreal Engine 5 (cert.) · Max/MSP (cert.) · Reaper · SuperCollider · IRCAM training  
**Infra:** Docker Compose · Tailscale · Prometheus/Grafana · n8n · Forgejo · Nginx · PostgreSQL/MariaDB/Redis  
**AI/Agents:** MCP · OpenCode agents · FastAPI · LiteLLM · Whisper · Stable Audio · Qwen3-TTS  
**Languages:** Python · Bash/Shell · C++ · Lua · TypeScript · HuJSON  

---

## Currently

Earning **CompTIA A+ / Network+ / Security+** — all three in progress, expected 2026.

---

## Links

[daniel-ramirez.io](https://daniel-ramirez.io) &nbsp;·&nbsp;
[lufs.audio](https://lufs.audio) &nbsp;·&nbsp;
[Audio Reel](https://reel.danialrami.com) &nbsp;·&nbsp;
[LinkedIn](https://linkedin.com/in/danialrami)

---

*San Antonio, TX · Remote-first · Clearance-eligible*
