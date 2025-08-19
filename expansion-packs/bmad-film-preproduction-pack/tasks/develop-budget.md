# ------------------------------------------------------------
# 2. Develop Budget
# ------------------------------------------------------------

---
task:
  id: develop-budget
  name: Develop Budget
  description: Create a preliminary budget for the film production.
  persona_default: producer
  inputs:
    - script.md
    - production-plan.md
  parameters:
    contingency_percentage: float
  steps:
    - Use the budgeting-checklist.md to identify all potential cost categories.
    - Estimate costs for each "Above the Line" and "Below the Line" item.
    - Use the budget-tmpl.yaml to structure the budget.
    - Calculate sub-totals for each department and phase.
    - Apply the specified contingency percentage to the total.
  output: film-budget-v1.md
...
