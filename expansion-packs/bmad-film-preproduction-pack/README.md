# BMAD Film Pre-Production Expansion Pack

Turn your script into a shoot-ready plan. This expansion pack packages a complete set of film-focused agents, workflows, templates, and checklists that wire the creative process into production-ready deliverables. It builds on the Creative Writing pack (script and story) and adds film production specialists to manage design, camera, budget, and scheduling.

## 🎬 Overview

The Film Pre-Production Expansion Pack is aimed at filmmakers, producers, and production teams who want a repeatable, agent-driven workflow for pre-production. Use it to go from script lock to a locked shot list, budget, and production schedule.

### Key Features

- 🤖 **5 Film-Specific Agents** — Director, Producer, Cinematographer (DP), Production Designer (PD), Storyboard Artist.
- 📝 **Integrated Writing Team** — includes the full Creative Writing pack for script health and story readiness.
- ⚙️ **Workflows for Every Format** — feature, short, TV pilot, and spot workflows tailored to scale and schedule.
- ✅ **Practical Checklists** — readiness checks for budgets, shotlists, safety, and day-of workflows.
- 📋 **Templates & Tasks** — lookbooks, call sheets, stripboards, prop lists, and rental/vendor briefs.

## ✍️ Included Agents

### Core Film Team
1. **Director** — Creative leadership, vision statements, blocking, rehearsal notes.
2. **Producer** — Budgeting, scheduling, vendor/hire briefs, risk registers.
3. **Cinematographer (DP)** — Camera packages, lens choices, lighting plans, shot lists.
4. **Production Designer (PD)** — Lookbooks, set/prop briefs, continuity and build plans.
5. **Storyboard Artist** — Storyboards, animatic blueprints, coverage recommendations.

### Integrated Writing Department
Includes the Creative Writing agents: Plot Architect, Character Psychologist, World Builder, Editor, and other writing specialists to guarantee the script is ready before heavy production planning begins.

## 🚀 Installation

### Via BMad Installer (recommended)

```bash
npx bmad-method install
# Select "Film Pre-Production" from the expansion packs list
```

### Manual Installation

1. Clone or download this expansion pack.
2. Copy the folder into your BMad Method `expansion-packs/` directory:

```bash
cp -r bmad-film-preproduction-pack/ ~/bmad-method/expansion-packs/
```

3. Run the BMad installer or `bmad` CLI to register the pack.

## � Usage

### Quick Start

```bash
# Load the full film pre-production team
bmad load team film-preproduction

# Activate individual agents when needed
bmad activate director
bmad activate producer
bmad activate dp
```

### Available Workflows

- **feature-film-pre-production** — Full-feature workflow: breakdown → budget → schedule → previsualization → readiness checks.
- **short-film-pre-production** — Condensed workflow optimized for small crews and tight budgets.
- **tv-pilot-pre-production** — Series bible + pilot-specific planning.
- **tv-spot-pre-production** — Fast turnaround workflow for commercials and spots.
- **screenplay-development** — Script-first workflow using the Creative Writing pack.

## 📋 Key Components

### Templates (included)
- `director-statement-tmpl.yaml` — one-page creative brief for the director.
- `budget-feature-tmpl.yaml` / `budget-short-tmpl.yaml` — starter budgets by production scale.
- `stripboard-tmpl.yaml` / `day-out-of-days-tmpl.yaml` — scheduling templates.
- `call-sheet-tmpl.yaml` — standardized day-of call sheet.
- `lookbook-tmpl.yaml` — PD & Director visual reference pack.
- `storyboard-tmpl.yaml` — panel and animatic timing template.
- `prop-costume-list-tmpl.yaml` — prioritized list with sourcing notes.

### Featured Checklists
- Pre-Production Readiness Checklist
- Shotlist & Coverage QA
- Budget Sign-off Checklist (scenarios & contingencies)
- Camera & Lighting Safety Checklist

### Tasks & Utilities
- Script breakdown task (auto-extract locations, characters, props)
- Budget scenario generator (low/medium/high)
- Call sheet generator
- Storyboard-to-shotlist mapper

## 🎯 Use Cases

### Feature Film Pre-Production
- Develop a director's vision, create a line-item budget, and produce a locked shooting schedule with a prioritized shot list.

### Television Development
- Assemble a series bible, align visual approach across episodes, and create pilot-specific production plans.

### Short-Form & Commercials
- Rapid planning with compact budgets and focused shot lists for quick turnarounds.

## ✅ Best Practices

1. Lock script first: run the `screenplay-development` workflow from the Creative Writing pack before heavy budgeting.(Check the writing department for more workflows available)
2. Run 3 budget scenarios and mark non-negotiables to guide trade-offs.
3. Use director and PD lookbooks early to avoid late design changes.
4. Map storyboard panels to exact script lines and schedule items for traceability.

## Templates & Examples

The `templates/` folder contains YAML templates referenced by workflows; copy and adapt them per project. Example files include a feature budget, a stripboard, a call sheet, and a storyboard panel template.

## 🤝 Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch
3. Follow BMad Method conventions (see root `CONTRIBUTING.md`)
4. Submit a PR with a clear description and tests/examples when relevant

## 📄 License

This expansion pack follows the same license as the BMAD Method core.

## 🙏 Credits

Created for the BMad Method community.

Special thanks to the authors of the Creative Writing pack for templates and workflow patterns.

---

**Version:** 1.0.0  
**Compatible with:** BMad Method v1.0+  
**Last Updated:** 2025
