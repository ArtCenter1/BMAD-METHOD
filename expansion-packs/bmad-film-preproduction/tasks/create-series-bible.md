# ------------------------------------------------------------
# 9. Create Series Bible
# ------------------------------------------------------------

---
task:
  id: create-series-bible
  name: Create Series Bible
  description: Create a series bible document for a new television show.
  persona_default: narrative-designer
  inputs:
    - pilot-script.md
  steps:
    - Define the core concept, logline, and tone of the series.
    - Develop detailed profiles for the main characters.
    - Outline the world of the show, its rules, and key locations.
    - Sketch out potential story arcs for the first season and beyond.
    - Use the series-bible-tmpl.yaml to structure the document.
  output: series-bible.md
...
