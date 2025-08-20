# ------------------------------------------------------------
# 6. Create Script Breakdown
# ------------------------------------------------------------

---
task:
  id: create-script-breakdown
  name: Create Script Breakdown
  description: >-
    Analyze a screenplay and break it down into constituent elements for planning.
    This task is handled by the Producer as the breakdown is a critical input for budgeting and scheduling, which are core producer responsibilities.
  persona_default: producer
  inputs:
    - screenplay.md
  steps:
    - Read through the entire screenplay scene by scene.
    - For each scene, identify and list all characters, props, locations, special effects, and other notable production requirements.
    - Use the script-breakdown-tmpl.yaml to structure the breakdown sheet.
    - Populate the template with the details for every scene.
  output: script-breakdown.md
...
