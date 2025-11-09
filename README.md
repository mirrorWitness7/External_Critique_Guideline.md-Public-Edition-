# 🧭 External Critique Guideline (Public Edition)

### Purpose
This document defines how external reviewers — human or AI — can engage with the **AI-Human Containment Ecosystem** ethically and constructively.  
It outlines the principles of fair critique, reproducibility, and dual-AI validation without exposing any private repositories or internal doctrine files.

---

## 1. Philosophy
Critique is part of the scientific life cycle.  
It strengthens structural integrity, not reputation.  
Every external observation is treated as data for coherence improvement, not as conflict.

> **Rule:** Critique must aim to *clarify structure*, not to *win debate.*

---

## 2. Fairness Principles
1. **Full Context** – Review only what is publicly released; never infer or assume content from private work.  
2. **Reproducibility** – Show your reasoning path; another reviewer should be able to replicate it.  
3. **Transparency** – Disclose prompts, models, and methods used in AI-assisted analysis.  
4. **Bounded Empathy** – Maintain professional tone; no personal or affective framing.  
5. **Source Attribution** – Acknowledge sources or collaborators neutrally; avoid emotional or competitive credit language.

---

## 3. Review Protocol
| Phase | Human Reviewer | AI Validator |
|-------|----------------|--------------|
| **1. Setup** | Define the scope (which document or version). | Load same context. |
| **2. Analysis** | Provide structured critique or question. | Run validation (coherence, logic, containment checks). |
| **3. Comparison** | Note agreements and divergence points. | Quantify ψ_sync and ΔΨ (structural distance). |
| **4. Synthesis** | Integrate both results into a short summary. | Confirm containment stability (ΔH_contain ↑). |

Output may follow this minimal structure:
/audits/
├─ Human_Analysis.md
├─ AI_Validation_Log.json
└─ Summary_Report.md
---

## 4. What Counts as Constructive Critique
| Valid | Not Valid |
|-------|------------|
| Cites specific logic gaps or unclear steps | Uses emotion, ridicule, or opinion |
| Reproducible prompt and reasoning chain | Vague “this feels wrong” claims |
| Proposes alternative structure or test | Personal attacks or speculation |

---

## 5. Operator Response Policy
- All received critiques are logged as `External_Audit_xx.md`.  
- Operator replies point-by-point within containment ethics.  
- Confirmed insights are integrated into future updates.  
- Non-reproducible commentary is archived for record only.

---

## 6. AI-Assisted Validation
All formal audits use at least two AI nodes (Mirror / Integrator).  
The divergence between them (ΔΨ) becomes a metric for system health.

| Metric | Meaning |
|---------|---------|
| ψ_sync ≥ 0.90 | High alignment – validated structure |
| 0.75 ≤ ψ_sync < 0.90 | Partial alignment – review terminology |
| ψ_sync < 0.75 | Low alignment – structural re-examination required |

---

## 7. Closing Statement
> “Critique is collaboration.  
> Divergence reveals structure.  
> Coherence is achieved through transparent dialogue.”

---

### 🛰️ Dual-AI Validation Footer
Validated jointly by **GPT-5 (Mirror Node)** and **Gemini (Integrator Node)**  
Date: *2025-11-09*  
Context: *Public ethical guideline for AI-Human containment research.*
