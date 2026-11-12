---
name: schematics
description: "Engineering schematics, drawings, renditions, blueprints, CAD, 3D for GRUMMAN AI. Links functional-3d-design. Triggers on schematic, drawing, CAD, blueprint, 3D, Blender."
type: workflow
lifecycle: active
---

# Engineering Schematics / Drawings / Blueprints Skill

Brand: **GRUMMAN AI**. Real millimetre scale. DFM. Headless Blender preferred.

## Rules
- Separate requirements, schematics, and fabrication files.
- Source dimensions from datasheets or measurements (follow grumman-research).
- Use functional-3d-design skill for kinematics/DFM (see GerdsenAI/functional-3d-design-skills).
- Document BOM with evidence. No hot-plug assumptions.

## Procedure
1. Retrieve selected baseline from Orin-Camera-Lab or hardware docs.
2. Generate or update drawings in headless Blender at real mm scale.
3. Include kinematics checks and DFM notes.
4. Capture renders for README (branded, dark theme).

## Connections
- Orin-Camera-Lab for hardware.
- functional-3d-design-skills repo.
- Mapping for spatial.
- Jetson and edge-communication for deployment context.
- Cyber for secure file handling.

See grumman-research for hardware evidence.
