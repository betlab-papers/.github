<h1 align="center">
  BET Lab — Internal Paper Dashboard
</h1>

<p align="center">
  <b>🔒 Internal Use Only</b> • <em>Latex-based Paper Writing Workflow</em>
</p>

---

## 🚀 Quick Start

1.  **New Paper**: Copy a template from `Journal-templates`.
2.  **Agent Setup**: Ensure your repo has the `.agent` folder from `paper-agent-rules`.
3.  **Environment**: Use `uv` for python dependencies.

## 📝 Active Manuscripts

| Repository | Description / Note |
|:-----------|:-------------------|
| [**Privacy-preserving-transfer-learning**](https://github.com/betlab-papers/Privacy-preserving-transfer-learning) | <em>Under Review</em>. PPTL Framework. |
| [**Contextually-Extended-iTransformer...**](https://github.com/betlab-papers/Contextually-Extended-iTransformer-for-virtual-sensor-networks) | Virtual sensor networks paper. |
| [**Sensing-priorities-for-occupant...**](https://github.com/betlab-papers/Sensing-priorities-for-occupant-centric-comfort-control-under-privacy-constraints) | Occupant-centric comfort control. |
| [**Annual-Energy-and-Exergy-Analysis-of-ASHP**](https://github.com/betlab-papers/Annual-Energy-and-Exergy-Analysis-of-ASHP) | Heat pump analysis. |

## 🛠️ Assets & Tools

| Repository | Purpose |
|:-----------|:--------|
| [**Journal-templates**](https://github.com/betlab-papers/Journal-templates) | Elsevier, IEEE, and other LaTeX templates. |
| [**paper-agent-rules**](https://github.com/betlab-papers/paper-agent-rules) | Source of truth for Agent rules & skills. |
| [**.github**](https://github.com/betlab-papers/.github) | Organization profile & global configs. |

## 🤖 Agentic Workflow (Gemini)

This organization uses a standardized **Agentic Workflow** for paper writing.

### Directory Structure Standard
```
repo/
├── .agent/              # Rules, Skills, Workflows
├── Submission/          # Clean LaTeX for submission
├── nomenclature_example/ # Nomencl logic
└── figures/             # Source figures
```

### Key Commands (Slash Command)
- `/pre-submission`: Run checks before submisison.
- `/bibtex-verify`: Validate references.
- `/table-align`: Auto-format tables.

---

<p align="center">
  <sub>Maintainer: Wonjun | Last Updated: 2026-02-09</sub>
</p>
