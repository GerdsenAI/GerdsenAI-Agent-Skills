---
name: edge-communication
description: "Software-defined radio, Meshtastic mesh, network, and edge communication workflows for secure offline and hybrid systems. Use for LoRa, Meshtastic pairing, Tailscale/WireGuard exit nodes, UniFi segmentation, kid-safe communicators, or edge-to-cloud routing. Triggers on SDR, Meshtastic, mesh, LoRa, Tailscale, WireGuard, edge network, communicator."
type: workflow
lifecycle: active
---

# Edge Communication & Meshtastic Skill

Brand: **GRUMMAN AI** / GerdsenAI. Secure by default. No cellular dependency for core messaging.

## When to use
- Setting up Meshtastic nodes or companions.
- Configuring Linux touchscreen communicators with Element/Matrix over Tailscale/WireGuard.
- UniFi network segmentation and parental controls.
- SDR experiments or edge radio links.
- Connecting edge devices (Jetson, Raspberry Pi class) securely without exposing ports.

## Core principles
1. Prefer complete off-the-shelf devices. No custom PCBs unless explicitly approved.
2. Route internet only through controlled exit nodes (Tailscale/WireGuard). Fail closed.
3. Meshtastic for mesh/offline; Element for Wi-Fi messaging. Do not equate LoRa with guaranteed location or emergency comms.
4. Document BOM with US stock/pricing evidence. Flag unknowns.
5. Preserve existing security boundaries from Portal/Grumman work.

## Procedure
1. Inventory current hardware shortlist (SenseCAP T1000-E or equivalent, Linux tablets).
2. Verify Linux viability: touch, cameras, Element, Tailscale, restrictive shell.
3. Test end-to-end: Wi-Fi messaging, exit-node fail-closed, UniFi block, Meshtastic/GPS demo.
4. Record sources and evidence. No guessed inventory.

See Communicator issue for coordination handoff.

## Connections
- Links to Jetson skills for edge compute.
- Cyber defense for network policy.
- Mapping for location reliability notes.
