---
name: edge-communication
description: "Software-defined radio, Meshtastic mesh, network, and edge communication workflows for secure offline and hybrid systems. Use for LoRa, Meshtastic pairing, Tailscale/WireGuard exit nodes, UniFi segmentation, kid-safe communicators, or edge-to-cloud routing. Triggers on SDR, Meshtastic, mesh, LoRa, Tailscale, WireGuard, edge network, communicator."
type: workflow
lifecycle: active
---

# Edge Communication & Meshtastic Skill

Brand: **GRUMMAN AI** / GerdsenAI. Secure by default. No cellular dependency for core messaging. Local-first. No GitHub Actions.

![GRUMMAN AI Logo](https://avatars.githubusercontent.com/u/217308685?s=200&v=4)

## When to use
- Setting up Meshtastic nodes or companions (see Communicator #1 for kid communicator decision).
- Configuring Linux touchscreen communicators with Element/Matrix over Tailscale/WireGuard.
- UniFi network segmentation and parental controls.
- SDR experiments or edge radio links.
- Connecting edge devices (Jetson Orin, Raspberry Pi class) securely without exposing ports.
- Mabry-EMR Jetson appliance shell and Tailscale smoke deploy.

## Core principles
1. Prefer complete off-the-shelf devices. No custom PCBs unless explicitly approved and sourced.
2. Route internet only through controlled exit nodes (Tailscale/WireGuard). Fail closed.
3. Meshtastic for mesh/offline; Element for Wi-Fi messaging. Do not equate LoRa with guaranteed location or emergency comms. Document reliability limits.
4. Document BOM with US stock/pricing evidence. Flag unknowns as "not sourced".
5. Preserve existing security boundaries from Portal/Grumman work. Integrate with cyber-defense.
6. Local compute stays local. Do not send lab logs or board files to hosted endpoints.

## Procedure
1. Inventory current hardware shortlist (SenseCAP T1000-E or equivalent, Linux tablets). Source from vendor pages.
2. Verify Linux viability: touch, cameras, Element, Tailscale, restrictive shell.
3. Test end-to-end: Wi-Fi messaging, exit-node fail-closed, UniFi block, Meshtastic/GPS demo. Capture screenshots of map/UI for README.
4. Record sources and evidence. No guessed inventory. Update changelog if breaking protocol changes.
5. Integrate with Jetson nodes for edge inference over the mesh.

## Example Output
Meshtastic network visualization (branded dark theme, Louisiana region example):

![Meshtastic Mesh Map](https://via.placeholder.com/800x400/000000/00FF00?text=Meshtastic+Mesh+Map+GRUMMAN+AI) <!-- Replace with actual screenshot from app. Generated example available in optimized skills repo. -->

## Connections
- Links to Jetson skills for edge compute and flash/prep (Voice-Assistant OOM, Mabry-EMR).
- Cyber defense for network policy, session invalidation, vaults (Local #457/#447).
- Mapping for location reliability notes and field mapping.
- Communicator repo for kid-safe devices and off-the-shelf decisions.
- Local Portal for shared comms patterns.
- AI-training for any edge inference models.
- Weather-Forecasting for environmental boundary conditions over mesh.

## Breaking Changes
None. Protocol or mesh key changes require explicit changelog notes and migration guidance.
