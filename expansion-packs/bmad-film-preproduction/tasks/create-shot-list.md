# ------------------------------------------------------------
# 1. Create Shot List
# ------------------------------------------------------------

---
task:
  id: create-shot-list
  name: Create Shot List
  description: Create a detailed shot list for a scene or sequence.
  persona_default: director
  inputs:
    - script.md
  parameters:
    scene_number: integer
  steps:
    - Break down the scene into individual moments and actions.
    - For each moment, define the shot size, angle, and movement.
    - Use the shot-list-tmpl.yaml to format the shot list.
    - Populate the template with all required details for each shot.
    - Run the shot-list-completeness-checklist.md against the output.
  output: scene-{{scene_number}}-shot-list.md
...
