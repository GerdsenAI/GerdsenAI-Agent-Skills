---
name: coding
description: "Agentic coding standards, software engineering practices, local-first development for GerdsenAI/GRUMMAN AI. Triggers on coding, agentic, software, CLI, Local, devtools, consolidate issues, branding."
type: workflow
lifecycle: active
---

# Coding & Agentic Development Skill

**Brand**: GRUMMAN AI / GerdsenAI. Four-section enclosing G logo. Local-first. Sourced claims only. Dark neural theme with rainbow accents. No GitHub Actions ever.

![GRUMMAN AI Logo](https://avatars.githubusercontent.com/u/217308685?s=200&v=4)

## Principles
1. Prefer local inference (Ollama, vLLM, LM Studio, DGX Spark, Jetson) over hosted when possible. Document evidence for performance claims.
2. Source every claim about APIs, hardware, or results. Use grumman-research patterns for hardware.
3. No GitHub Actions. Use local scripts, manual processes, or agent-driven commits.
4. Secure inter-app connections: Tailscale/WireGuard mesh, local MCP, Infisical-style vaults, mTLS, Dot receipts, session invalidation on credential changes.
5. Preserve branding in all outputs (docs, GUIs, screenshots, PDFs). Follow Brand 2.1.0.
6. Issue consolidation: Inventory all pages of issues/PRs (bypass single-page limits), classify (keep/integrate/archive/investigate), preserve history, link duplicates in place, update existing issues. See GerdsenAI-Local #474 P0 epic for Portal/Repowise/wiki patterns.
7. Code classification: active runtime, conditional, tooling, vendored, archived, orphan. Cross-check imports, routes, entrypoints before any removal.

## When to use
- Implementing features in Local (Portal), CLI, Research-Chat, Fleet, Agentic-Devtools, Isaac-SHim, Jetson nodes.
- Code review, refactoring, consolidation of issues across org.
- Creating or updating skills and repos.
- Drawing connections between apps via secure means.

## Procedure for Issue Consolidation
1. Search org:GerdsenAI is:open, paginate fully.
2. Group by theme (security, research, hardware, UI, skills).
3. Identify canonical owners (e.g. Local #474 for portal, Communicator #1 for Meshtastic).
4. Link related issues, note breaking changes in changelogs.
5. Update skills to reflect current priorities without inventing.

## Connections
- Cyber-defense for secure code and inter-app links (Local #457 sessions, #434 trust paths).
- AI-training for model-related code and pipelines.
- Schematics for engineering code and DFM.
- Intelligence for evidence grounding in docs and research.
- Edge-communication and Jetson for hardware-related code and edge deployment.
- Mapping for geo/spatial features.

Related open issues: Local #474 (consolidation epic), #434 (security), Research-Chat backlog, Isaac research epics, Communicator #1.

## Breaking Changes Notes
None in this update. Future changes to secure connection APIs or branding must be noted in CHANGELOG.md with migration steps.
