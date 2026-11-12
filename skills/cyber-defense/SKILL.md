---
name: cyber-defense
description: "Cyber defense, hardening, secure app interconnection, provenance for GRUMMAN AI. Triggers on security, hardening, Tailscale, mTLS, vault, defense."
type: workflow
lifecycle: active
---

# Cyber Defense Skill

Brand: **GRUMMAN AI**. Fail closed. Local-first.

## Secure Connections Between Apps
- Tailscale/WireGuard mesh with fail-closed exit nodes.
- Local MCP + Infisical-style secrets.
- Session invalidation on password/credential changes (see Local #457).
- UniFi segmentation, no public exposure.
- Meshtastic fallback for offline.
- Dot-owned receipts for audit.
- Specific apps: GerdsenAI-Local (Portal), Research-Chat, Fleet, Isaac-SHim, Jetson nodes (Orin-Camera-Lab, Voice-Assistant), Communicator, Weather-Forecasting, NVMe-RunBox, Agentic-Devtools.

## When to use
- Remediation of security issues across repos (Local, Portal, Fleet).
- Designing inter-app links.
- Hardening Jetson/edge nodes.
- Coordinating with issue consolidation (Local #474).

## Connections
- All apps listed above.
- Intelligence for threat awareness.
- Edge-communication for mesh policy.
- Coding for implementation patterns.
