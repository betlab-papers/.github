# betlab — Internal Paper Dashboard

**AI-Enhanced Academic Writing Workflow**  
_Maintained by Wonjun_

---

## 🚀 Core Infrastructure

### [writing-agent-playbook](https://github.com/betlab-papers/writing-agent-playbook)

The centralized logic core for the Antigravity Agent. It provides a standardized library of **Rules**, **Skills**, and **Workflows** for academic writing.

- **Dual-Format Support**: Full support for both **LaTeX** (`.tex`) and **Typst** (`.typ`).
- **Automated Pipelines**:
  - **Drafting**: `/korean-drafting`, `/translate-to-en`
  - **Review**: `/manuscript-review`, `/review-response-audit`
  - **Submission**: `/pre-submission`, `/resubmission`
- **Quality Assurance**: Automated consistency checks, build safety, and citation audits.

---

## 📂 Key Repositories

| Repository                                                                            | Description                                      |
| :------------------------------------------------------------------------------------ | :----------------------------------------------- |
| **[writing-agent-playbook](https://github.com/betlab-papers/writing-agent-playbook)** | **[Kernel]** Agent rules, skills, and workflows. |
| **.github**                                                                           | Organization profile and global configuration.   |

---

## 🏛️ Managed Paper Repositories

All research papers in this organization follow a strict **Dual-Repository Structure**:

1. **Paper Repository** (`paper-name`): Contains the actual manuscript content (`.tex` / `.typ`), data, and figures.
2. **Agent Logic** (`.agent`): A submodule or subtree of `writing-agent-playbook` that provides the tooling context.

This ensures that every paper project has access to standard writing tools while maintaining content independence.

## 🔗 Quick Documentation

- **[Agent Architecture](https://github.com/betlab-papers/writing-agent-playbook/blob/main/docs/architecture_diagrams.md)**: Visual map of rules, skills, and workflows.
- **[Rule System](https://github.com/betlab-papers/writing-agent-playbook/tree/main/rules)**: Detailed authoring guidelines (Style, BibTeX, Figures).
- **[Workflows](https://github.com/betlab-papers/writing-agent-playbook/tree/main/workflows)**: Automation chain definitions.
