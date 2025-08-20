# ------------------------------------------------------------
# 3. Design Production
# ------------------------------------------------------------

---
task:
  id: design-production
  name: Design Production
  description: Create the production design brief for the film.
  persona_default: production-designer
  inputs:
    - script.md
    - director-vision.md
  parameters:
    key_scenes: array
  steps:
    - Analyze the script and director's vision for visual themes and motifs.
    - Create mood boards for the overall look, key locations, and characters.
    - Use the production-design-brief-tmpl.yaml to structure the design document.
    - Detail the design approach for sets, costumes, and key props.
    - Run the production-design-consistency-checklist.md against the output.
  output: production-design-brief.md
...
