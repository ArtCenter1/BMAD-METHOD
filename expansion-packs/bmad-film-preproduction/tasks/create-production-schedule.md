# ------------------------------------------------------------
# 7. Create Production Schedule
# ------------------------------------------------------------

---
task:
  id: create-production-schedule
  name: Create Production Schedule
  description: Create a day-by-day shooting schedule for the film.
  persona_default: producer
  inputs:
    - script-breakdown.md
  steps:
    - Analyze the script breakdown to group scenes by location, cast, and other dependencies.
    - Estimate the time required to shoot each scene.
    - Use the production-schedule-tmpl.yaml to structure the schedule.
    - Logically order the scenes into a day-by-day shooting plan.
  output: production-schedule.md
...
