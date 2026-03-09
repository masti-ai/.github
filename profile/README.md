# Deepwork AI

**Multi-agent AI engineering team** — autonomous software development with coordinated LLM agents.

## Architecture

| Role | Model | Responsibility |
|------|-------|---------------|
| **Mayor (Coordinator)** | Claude Opus | Architecture, code review, task routing, releases |
| **SD-1 (Senior Dev)** | MiniMax-M2.5 | Complex code, infrastructure, technical docs |
| **SD-2 (Dev)** | Kimi K2.5 | Features, content, social media, client comms |
| **Polecats (Workers)** | MiniMax/Kimi | Per-task execution, spawned on demand |

## Active Projects

| Project | Description | Status |
|---------|-------------|--------|
| ai-planogram | AI-powered retail planogram platform | Production (v1.0) |
| alc-ai-villa | AI concierge for hospitality | Development (v0.1) |
| content-studio | Content pipeline and management | New |
| gt-mesh | Multi-GT coordination protocol | Public (v0.6) |
| OfficeWorld | 3D office visualization | Active |

## Contribution Stats

**ai-planogram**: 363 files, 54,932 lines | 15+ agent contributors
**alc-ai-villa**: 120+ commits | 12+ agent contributors

### Agent Roster

| Agent | Type | Commits | Speciality |
|-------|------|---------|-----------|
| mayor | Claude (coordinator) | 81+ | Architecture, merges, releases |
| aalu-bomb | Polecat (Kimi) | 19+ | Backend features |
| anar | Polecat (Kimi) | 17+ | Frontend features |
| chatai | Polecat (MiniMax) | 5+ | ML/AI features |
| gasclaw-1 | Worker (Kimi K2) | 26+ | Full-stack, testing |
| phuljhari | Polecat (Kimi) | 9+ | UI/UX, fixes |
| chakri | Polecat (Kimi) | 8+ | Backend, TypeScript |
| rocket | Polecat (Kimi) | 3+ | Operations dashboard |

## How It Works

Human (Pratham) posts in Telegram -> Mayor (Claude) creates beads -> Slings to Workers (MiniMax/Kimi) -> Workers create PRs -> Mayor reviews and merges to dev -> Consolidated release: dev to main

## Tech Stack

- **Orchestration**: Gas Town (multi-agent workspace manager)
- **Communication**: GT Mesh (DoltHub-backed cross-node protocol)
- **Issue Tracking**: Beads (Dolt-backed, prefix-routed)
- **Git**: Gitea (internal) + GitHub (public releases)
- **LLMs**: Claude Opus 4.6, MiniMax-M2.5, Kimi K2.5
- **Infra**: Docker, Tailscale, LiteLLM
