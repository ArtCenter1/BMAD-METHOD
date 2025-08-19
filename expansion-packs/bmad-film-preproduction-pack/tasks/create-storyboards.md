# ------------------------------------------------------------
# 4. Create Storyboards
# ------------------------------------------------------------

---
task:
  id: create-storyboards
  name: Create Storyboards
  description: Create storyboards for a scene or sequence.
  persona_default: storyboard-artist
  inputs:
    - script.md
    - shot-list.md
  parameters:
    scene_number: integer
  steps:
    - Review the shot list and script for the specified scene.
    - For each shot, sketch a panel that clearly shows the composition, characters, and key action.
    - Use the storyboard-tmpl.yaml to format the storyboard sequence.
    - Add notes for camera movement, SFX, or dialogue as needed for each panel.
  output: scene-{{scene_number}}-storyboards.md
...
