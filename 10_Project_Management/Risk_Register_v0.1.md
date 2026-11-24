# Project Risk Register
## Laboratory Data Governance, Quality and Interoperability Programme

**Document Version:** 0.1  
**Document Status:** Draft  
**Prepared by:** Project Manager / Business Analyst

---

## 1. Purpose

This document identifies potential risks that may affect project delivery, data quality, interoperability, timelines and expected outcomes.

Each risk is assessed based on its likelihood and impact. Mitigation actions are proposed to reduce the probability or consequences of each risk.

## 2. Risk Assessment Scale

### Likelihood

| Score | Description |
|---|---|
| 1 | Rare |
| 2 | Unlikely |
| 3 | Possible |
| 4 | Likely |
| 5 | Almost certain |

### Impact

| Score | Description |
|---|---|
| 1 | Negligible |
| 2 | Minor |
| 3 | Moderate |
| 4 | Major |
| 5 | Severe |

**Risk Score = Likelihood × Impact**

### Risk Priority

| Score | Priority |
|---|---|
| 1–5 | Low |
| 6–12 | Moderate |
| 13–25 | High |

## 3. Risk Register

| ID | Identified Risk | Likelihood | Impact | Score | Priority | Mitigation Strategy |
|---|---|---:|---:|---:|---|---|
| R01 | Missing or incomplete laboratory observations | 4 | 4 | 16 | High | Perform completeness profiling and document missing-data patterns |
| R02 | Inconsistent laboratory test names across sources | 4 | 4 | 16 | High | Establish terminology standardisation and LOINC governance rules |
| R03 | Inconsistent measurement units | 4 | 5 | 20 | High | Define unit validation and standardisation rules before analysis |
| R04 | Incorrect or incomplete reference ranges | 3 | 4 | 12 | Moderate | Assess reference-range availability and document limitations |
| R05 | Duplicate laboratory records | 3 | 3 | 9 | Moderate | Define duplicate detection rules and investigate possible duplicates |
| R06 | Dataset does not contain all required fields | 3 | 4 | 12 | Moderate | Verify dataset structure early and revise project scope if needed |
| R07 | Incorrect LOINC terminology mapping | 3 | 5 | 15 | High | Review mappings using authoritative terminology resources and clinical input |
| R08 | OMOP mapping incompatibility | 3 | 4 | 12 | Moderate | Review target CDM requirements and document mapping assumptions |
| R09 | Dashboard indicators are misunderstood by stakeholders | 2 | 3 | 6 | Moderate | Use clear definitions, labels and explanatory documentation |
| R10 | Project activities exceed the planned six-week timeline | 3 | 4 | 12 | Moderate | Review progress weekly and prioritise essential deliverables |
| R11 | Limited stakeholder availability for review and UAT | 3 | 3 | 9 | Moderate | Plan review sessions in advance and provide structured feedback templates |
| R12 | Dataset licensing or usage restrictions | 2 | 5 | 10 | Moderate | Review the dataset licence and attribution requirements before publication |

*Note: Likelihood and impact scores are initial planning estimates. They must be reassessed as the project progresses.*

## 4. Risk Ownership

| Risk Category | Proposed Risk Owner |
|---|---|
| Project timeline and scope | Project Manager |
| Laboratory data quality | Quality Manager |
| Clinical terminology and LOINC | Clinical Informatics Lead |
| Technical and OMOP mapping | Clinical Informatics Lead / Data Analyst |
| Dashboard and technical feasibility | IT Manager / Data Analyst |
| Stakeholder engagement | Project Manager |
| Licensing and data usage | Project Manager |

## 5. Risk Monitoring Plan

- Review the risk register weekly.
- Reassess likelihood and impact when new information becomes available.
- Record newly identified risks.
- Assign an owner to each high-priority risk.
- Document mitigation actions and their status.
- Escalate risks that threaten project objectives or delivery milestones.

## 6. Key Project Risks Requiring Early Attention

The following risks require particular attention:

1. Measurement-unit inconsistencies.
2. Incomplete or missing laboratory data.
3. Incorrect terminology mapping.
4. Limitations in available dataset fields.
5. Dataset licensing and attribution requirements.

## 7. Important Assumptions

- This is a portfolio project using a publicly available dataset.
- Risk scores are preliminary estimates, not measured probabilities.
- Stakeholder roles and ownership are proposed for a hypothetical hospital network.
- Mitigation actions will be refined after dataset assessment.
- No real hospital deployment or patient-care impact is claimed.