# GerdsenAI Agent Skills

Consolidated, branded agent skills for **GRUMMAN AI** / GerdsenAI workflows.

![GRUMMAN AI Logo](https://avatars.githubusercontent.com/u/217308685?s=200&v=4)

**Branding**: Four-section enclosing G logo, GRUMMAN AI wordmark. Preserve exact copy and visual system from Brand 2.1.0. Dark neural theme with rainbow accents.

Sovereign Intelligence Builds a Brighter Tomorrow. Local-first. Sourced claims only. No GitHub Actions ever.

## Skills Overview

| Domain | Path | Description |
|--------|------|-------------|
| Coding | `skills/coding/` | Agentic coding standards, software engineering, local-first development |
| Intelligence Gathering | `skills/intelligence/` | OSINT, research pipelines, evidence grounding |
| Edge Communication | `skills/edge-communication/` | SDR, Meshtastic, network, secure edge mesh |
| Jetson | `skills/jetson/` | Flash, prep, programming, carriers, Orin edge AI |
| Cyber Defense | `skills/cyber-defense/` | Hardening, provenance, secure inter-app connections |
| Mapping | `skills/mapping/` | Geo, paths, Gaussian splat, field mapping |
| AI Training | `skills/ai-training/` | Local datasets, fine-tune, pipelines |
| Engineering Schematics | `skills/schematics/` | Drawings, blueprints, CAD, 3D renditions (links functional-3d-design) |

## Secure Inter-App Connections

All apps (Local, Research-Chat, Fleet, Isaac-SHim, Jetson nodes, OSINT, Communicator) connect via:
- Tailscale / WireGuard private mesh (fail-closed exit nodes)
- Local MCP servers and Infisical-style vaults
- mTLS where applicable, loopback preferred
- Meshtastic for low-bandwidth offline fallback
- Dot-owned receipts and session invalidation on credential changes
- UniFi segmentation, no public endpoints for sensitive data

See cyber-defense skill for policy details.

## Installation

Copy skill folders into agent skill directories (e.g. `~/.claude/skills/`, `~/.cursor/skills/`, or Grok skill paths).

## Changelog

### 2026-11-11
- Full expansion of all domain skills.
- Consolidated connections and branding.
- Updated READMEs with structure for images/screenshots.
- No breaking changes. No GitHub Actions used.

### 2026-11-10
- Initial repo with edge-communication skill.

## Security

Highly secure by default. Local compute stays local. Do not send lab logs, pinmux, or board files to hosted endpoints.