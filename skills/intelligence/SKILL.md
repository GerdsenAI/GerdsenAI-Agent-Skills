---
name: intelligence
description: "Intelligence gathering, OSINT, research pipelines, evidence grounding for GRUMMAN AI. Triggers on OSINT, research, intelligence, evidence, provenance, fact-check."
type: workflow
lifecycle: active
---

# Intelligence Gathering Skill

Brand: **GRUMMAN AI**. Evidence first. No invented facts. Local-first preferred. No GH Actions.

## Procedure
1. Source every claim (URL or document path, date read, exact sentence/quote). If none, "not sourced" and stop.
2. Prefer local tools and private data sources. Ground in project repos (Research-Chat, OSINT-Fusion, Weather-Forecasting).
3. Version sources and track contradictions. Do not average disagreements; quote both.
4. For research passes: fact-check against primary sources before recommending. Link to open research issues.
5. Capture screenshots of research outputs or dashboards for READMEs where applicable.

## Connections
- Research-Chat (large backlog), Weather-Forecasting research issues (Earth-2, NIM fact-checks), OSINT-Fusion.
- Mapping for geo-intel and field data.
- Cyber for secure collection and provenance.
- Coding for pipeline implementation and issue consolidation.
- AI-training for dataset provenance in research.
- Isaac-SHim for simulation-based intelligence.

Related open issues: Weather #31-#37 research tracking, Isaac research epics.

## Breaking Changes
None. Source format or provenance rules changes require changelog notes.
