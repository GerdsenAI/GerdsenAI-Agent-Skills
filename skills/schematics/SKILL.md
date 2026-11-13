---
name: schematics
description: "Engineering schematics, drawings, renditions, blueprints, CAD, 3D for GRUMMAN AI. Links functional-3d-design. Triggers on schematic, drawing, CAD, blueprint, 3D, Blender, kinematics, DFM."
type: workflow
lifecycle: active
---

# Engineering Schematics / Drawings / Blueprints Skill

Brand: **GRUMMAN AI**. Real millimetre scale. DFM. Headless Blender preferred. Sourced claims only. No GH Actions.

## Rules
- Separate requirements, schematics, and fabrication files. Agents do not fabricate from chat diagrams.
- Source dimensions, materials, loads from datasheets or measurements (follow grumman-research). Pass millimetres only into kit functions.
- Use functional-3d-design skill for kinematics/DFM (see GerdsenAI/functional-3d-design-skills or local skill). Start with function, joints, process before looks.
- Document BOM with evidence. No hot-plug assumptions. Envelope on DIMS via kit.set_dims.
- 1 Blender unit = 1 metre. Do not set scale_length = 0.001.

## Procedure
1. Retrieve selected baseline from Orin-Camera-Lab or hardware docs. Write BRIEF.md from assets.
2. Design order: function/load path, joints (kinematics.md), process/material, envelope, block out with box_mm/cyl_mm, key motion, lights, export.
3. Generate or update drawings in headless Blender at real mm scale. Include kinematics checks and DFM notes.
4. Capture renders (PNG plates, cycle movies if motion) for README. Branded dark theme, rainbow accents.

## Example Output
Jetson carrier chassis schematic/render:

![Chassis Schematic](https://via.placeholder.com/800x400?text=Jetson+Chassis+Schematic+GRUMMAN+AI) <!-- Replace with Blender render -->

## Connections
- Orin-Camera-Lab for hardware baselines.
- functional-3d-design-skills repo (or local).
- Mapping for spatial/field layouts.
- Jetson and edge-communication for deployment context and enclosures.
- Cyber for secure file handling of board files.
- Coding for any associated scripts or issue consolidation.
- AI-training for any simulation-to-real pipelines.

See grumman-research for hardware evidence and sourcing checklist.

## Breaking Changes
None. Unit or DFM process changes require changelog notes.
