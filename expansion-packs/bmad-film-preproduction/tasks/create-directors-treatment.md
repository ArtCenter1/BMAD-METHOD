# ------------------------------------------------------------
# 10. Create Director's Treatment
# ------------------------------------------------------------

---
task:
  id: create-directors-treatment
  name: Create Director's Treatment
  description: Create a director's treatment document for a commercial or short-form project.
  persona_default: director
  inputs:
    - ad-script.md
  steps:
    - Summarize the core concept and message of the spot.
    - Describe the visual approach, tone, and style.
    - Use the directors-treatment-tmpl.yaml to structure the document.
    - Include references or a mood board to convey the aesthetic.
  output: directors-treatment.md
...
