---
name: jetson
description: "Jetson Orin flash, prep, programming, carriers, edge AI. Based on grumman-research and Orin-Camera-Lab. Triggers on Jetson, Orin, flash, BSP, CSI, GMSL, Nano, NX."
type: knowledge
lifecycle: active
---

# Jetson Flash / Prep / Programming Skill

Brand: **GRUMMAN AI**. Follow selected baseline from GrummanAI-Orin-Camera-Lab docs/selected/. Local compute stays local. No GH Actions.

## Rules (from grumman-research)
1. Retrieve latest selected baseline before any claim. Module and architecture follow it.
2. Source every part number, pin, voltage, price, wattage from datasheet, vendor page, or committed measurement. If none, write "not sourced" and stop.
3. No hot-plug. Confirm exact module identity and carrier/BSP. Lab boot on 260-pin allowed only if baseline permits.
4. Local compute stays local. Do not send lab logs, pinmux, or board files to hosted endpoints.
5. Separate requirements notes, schematics, and fabrication files (gerbers/BOM).

## Procedure
1. Fetch baseline from GerdsenAI/GrummanAI-Orin-Camera-Lab `docs/selected/`.
2. Follow official NVIDIA flash guides for exact module (Orin Nano/NX etc.). Document commands and evidence.
3. Document BOM with evidence. Integrate with edge-communication for secure deployment (Tailscale, Meshtastic fallback).
4. Prep: headless setup, CSI/GMSL camera configs as per baseline, power rules (802.3bt PD etc.).
5. Programming: local inference, ROS2 if applicable, secure networking. Capture flash logs/screenshots for docs.

## Example Output
Jetson flash utility terminal (branded):

![Jetson Flash](https://via.placeholder.com/800x400?text=Jetson+Orin+Flash+GRUMMAN+AI) <!-- Replace with actual terminal screenshot -->

## Connections
- Orin-Camera-Lab (selected baseline), Isaac-SHim (simulation), Voice-Assistant repos.
- Edge-communication for mesh/network and secure edge.
- Schematics for carrier chassis and DFM (functional-3d-design).
- Cyber-defense for hardening and vaults.
- AI-training for edge model deployment.
- Coding for implementation patterns and issue links.

Related: GrummanAI-Isaac-SHim research epics, Weather-Forecasting Earth-2 ties.

## Breaking Changes
Baseline updates or BSP changes must be noted with migration steps. No breaking changes in this skill update.
