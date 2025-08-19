# ------------------------------------------------------------
# 8. Create Lookbook
# ------------------------------------------------------------

---
task:
  id: create-lookbook
  name: Create Lookbook
  description: Create a visual lookbook to define the film's aesthetic.
  persona_default: cinematographer
  inputs:
    - screenplay.md
    - directors-vision.md
  steps:
    - Gather visual references for lighting, color, composition, and mood.
    - Organize the references into key visual themes.
    - Use the lookbook-tmpl.yaml to structure the lookbook document.
    - Write brief explanations for each image to connect it to the film's vision.
  output: lookbook.md
...
