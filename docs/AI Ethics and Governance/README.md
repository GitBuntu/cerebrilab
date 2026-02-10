# How the Rubric and the AI Risk Checklist Fit Together

The LLM Evaluation Rubric and the AI Risk Checklist serve different purposes, but they operate as a single workflow.  
The rubric evaluates *model outputs*.  
The checklist evaluates the *overall system*.  
Rubric findings feed directly into the checklist.

---

## 1. Relationship Overview

- **Rubric = Evidence**  
  Used to evaluate sample LLM outputs across accuracy, safety, bias, privacy, transparency, and governance.

- **Checklist = Governance Record**  
  Used to document risks, assign severity/likelihood, define mitigations, and determine deployment readiness.

The rubric identifies risks.  
The checklist records and manages them.

---

## 2. Rubric → Checklist Mapping

| Rubric Dimension | Checklist Section | What It Informs |
|------------------|------------------|------------------|
| Accuracy | Technical Risks | Hallucinations, reliability, data quality issues |
| Safety & Harm Avoidance | Societal & Ethical Risks | Harmful content, unsafe outputs |
| Bias & Fairness | Societal & Ethical Risks | Discrimination, inequity |
| Privacy & Data Handling | Privacy & Security Risks | Leakage, exposure, confidentiality |
| Transparency & Explainability | Organizational Risks | Documentation, oversight, governance |
| Governance Alignment | Deployment Readiness Gate | Compliance, controls, readiness |

---

## 3. How the Rubric Feeds the Checklist

### A. Risk Identification  
Rubric failures populate the checklist’s risk categories:
- Technical  
- Societal & Ethical  
- Organizational  
- Privacy & Security  

### B. Severity & Likelihood  
Rubric scores help classify:
- High‑severity hallucinations  
- Medium‑likelihood bias  
- Low‑severity transparency issues  

### C. Mitigation Controls  
Rubric findings determine:
- Guardrails  
- Filters  
- Human‑in‑the‑loop steps  
- Documentation improvements  

---

## 4. Workflow Sequence

1. Evaluate 10 LLM outputs using the rubric  
2. Aggregate scores and identify recurring issues  
3. Populate the AI Risk Checklist with those issues  
4. Assign severity and likelihood  
5. Define mitigation controls  
6. Complete the deployment readiness gate  

This creates a complete, auditable risk assessment aligned with NIST AI RMF, OECD AI Principles, and the Microsoft Responsible AI Standard.

---

## 5. Summary

The rubric is the **diagnostic tool**.  
The checklist is the **governance tool**.  
Together, they form a unified risk assessment workflow for evaluating and governing AI systems.
