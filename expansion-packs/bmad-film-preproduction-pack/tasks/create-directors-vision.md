# ------------------------------------------------------------
# 5. Create Director's Vision
# ------------------------------------------------------------

---
task:
  id: create-directors-vision
  name: Create Director's Vision
  description: Articulate the director's creative vision for the film.
  persona_default: director
  inputs:
    - screenplay.md
  steps:
    - Analyze the script for core themes, tone, and emotional arcs.
    - Define the visual style, including camera language, color palette, and pacing.
    - Use the directors-vision-tmpl.yaml to structure the vision document.
    - Populate the template with detailed descriptions of the artistic approach.
  output: directors-vision.md
...
