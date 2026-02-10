  <h1 align="center">
  betlab — Internal Paper Dashboard
</h1>

<p align="center">
  <b>🔒 Internal Use Only</b> • <em>Latex-based Paper Writing Workflow</em>
</p>

---

## 🚀 Quick Start

1.  **New Paper**: Clone [`latex-template`](https://github.com/betlab-papers/latex-template) and start writing in `manuscript/`.
2.  **Agent Setup**: `git clone https://github.com/betlab-papers/paper-agent-rules.git .agent`
3.  **Project Config**: Edit `.agent/project.md` for abbreviations, domain terms, and publisher.
4.  **Environment**: Use `uv` for python dependencies.

## 📝 Active Manuscripts

| Repository                                                                                                                                                   | Description / Note                     |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------- |
| [**Privacy-preserving-transfer-learning**](https://github.com/betlab-papers/Privacy-preserving-transfer-learning)                                            | <em>Under Review</em>. PPTL Framework. |
| [**Contextually-Extended-iTransformer...**](https://github.com/betlab-papers/Contextually-Extended-iTransformer-for-virtual-sensor-networks)                 | Virtual sensor networks paper.         |
| [**Sensing-priorities-for-occupant...**](https://github.com/betlab-papers/Sensing-priorities-for-occupant-centric-comfort-control-under-privacy-constraints) | Occupant-centric comfort control.      |
| [**Annual-Energy-and-Exergy-Analysis-of-ASHP**](https://github.com/betlab-papers/Annual-Energy-and-Exergy-Analysis-of-ASHP)                                  | Heat pump analysis.                    |

## 🛠️ Assets & Tools

| Repository                                                                  | Purpose                                                              |
| :-------------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [**latex-template**](https://github.com/betlab-papers/latex-template)       | LaTeX paper template with `manuscript/` and `submission/` structure. |
| [**paper-agent-rules**](https://github.com/betlab-papers/paper-agent-rules) | AI Agent rules, skills & workflows — clone as `.agent/`.             |
| [**.github**](https://github.com/betlab-papers/.github)                     | Organization profile & global configs.                               |

## 🤖 Agentic Workflow (Gemini)

This organization uses a standardized **Agentic Workflow** for paper writing.

### Directory Structure Standard

```
repo/
├── manuscript/              # Source .tex, .bib, images/
│   ├── manuscript_1st.tex   # Original submission (archived)
│   ├── manuscript_2nd.tex   # Active revision
│   ├── references.bib
│   └── images/
├── submission/              # Submission documents & packaging
│   ├── cover_letter/
│   ├── Highlights/
│   ├── review_response/
│   ├── els_template/        # Publisher style files
│   └── submission_ready/    # Final packaged output
├── .agent/                  # Rules, Skills, Workflows (separate repo)
└── docs/                    # Additional guides (agent-setup.md)
```

### Key Commands (Slash Command)

- `/pre-submission`: Run checks before submission.
- `/post-revision`: Post-revision cleanup and packaging.
- `/bibtex-full-check`: Full BibTeX validation.
- `/bibtex-verify`: Validate references.
- `/table-align`: Auto-format tables.
- `/sync-revisedtext`: Sync reviewer response with manuscript.

---

<p align="center">
  <sub>Maintainer: Wonjun | Last Updated: 2026-02-10</sub>
</p>
