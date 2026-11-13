---
name: cyber-defense
description: "Cyber defense, hardening, secure app interconnection, provenance for GRUMMAN AI. Triggers on security, hardening, Tailscale, mTLS, vault, defense, sessions."
type: workflow
lifecycle: active
---

# Cyber Defense Skill

Brand: **GRUMMAN AI**. Fail closed. Local-first. Sourced claims only. No GH Actions.

## Secure Connections Between Apps
Highly secure means for interconnecting all apps (Local/Portal, Research-Chat, Fleet, Isaac-SHim, Jetson nodes, OSINT, Communicator, Weather-Forecasting, NVMe-RunBox, Agentic-Devtools, CLI):
- Tailscale/WireGuard mesh with fail-closed exit nodes. Prefer loopback + private mesh.
- Local MCP servers and Infisical-style secrets/vaults. No secrets in prompts or repos.
- mTLS where applicable. Session invalidation on password/credential changes (see Local #457).
- UniFi segmentation, no public exposure for sensitive data. Trust path remediation (Local #434 eMudhra).
- Meshtastic fallback for offline/low-bandwidth. Dot-owned receipts for audit and provenance.
- Specific patterns: shared Comms (#437), Portal security composition.

## When to use
- Remediation of security issues across repos (Local, Portal, Fleet, Jetson).
- Designing or auditing inter-app links.
- Hardening Jetson/edge nodes and network policies.
- Coordinating with issue consolidation (Local #474) and branding.

## Connections
- All apps listed above.
- Intelligence for threat awareness and evidence.
- Edge-communication for mesh policy and communicator security.
- Coding for implementation patterns and secure code.
- Jetson and schematics for hardware hardening.
- AI-training for model security and local inference.

## Breaking Changes
None. Changes to mesh keys, vault schemas, or session policies require explicit migration notes in CHANGELOG.
