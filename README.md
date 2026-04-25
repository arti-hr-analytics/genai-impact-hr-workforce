# The Gen AI Workforce Shift: Which HR Roles Are Most at Risk?
### A Skills-Based Analysis Using O*NET Data and Python

**Author:** Arti Sharma  
**Date:** April 2026  
**Tools:** Python, Pandas, Matplotlib, Google Colab  
**Data Source:** O*NET 30.2 Database, U.S. Department of Labor  

---

## Research Question
To what extent are HR occupations exposed to Generative AI automation, and which specific task clusters drive that exposure?

---

## Key Findings
- **HR Assistants** are most at risk (AI Exposure Score: 3.95/5.0) — 58% of their tasks are highly automatable
- **Education Administrators** are most resilient (Score: 3.00/5.0) — only 22% high-risk tasks
- **Active Listening and Speaking** (score: 4.08) are the most important AND most AI-resistant HR skills
- **38% of all HR tasks** analyzed are highly automatable by Gen AI

---

## Visualizations
| Figure | Description |
|--------|-------------|
| Figure 1 | HR Occupations Ranked by Gen AI Exposure Score |
| Figure 2 | Task Risk Composition by HR Occupation |
| Figure 3 | Top HR Skills by Importance — Which Will Survive Gen AI? |

---

## Repository Contents
| File | Description |
|------|-------------|
| `HR_GenAI_Research.ipynb` | Full Python analysis notebook |
| `HR_GenAI_Exposure_Results.xlsx` | Final occupation scores |
| `HR_Tasks_Scored.xlsx` | All 180 HR tasks with AI exposure scores |
| `Figure1_AI_Exposure_by_HR_Role.png` | Bar chart — occupation ranking |
| `Figure2_Task_Breakdown_by_Role.png` | Stacked bar — task composition |
| `Figure3_Surviving_Skills.png` | Skills survival analysis |

---

## Methodology
1. Downloaded O*NET 30.2 task and skills data for 8 HR occupations
2. Filtered 18,796 tasks to 180 HR-specific tasks across 8 SOC codes
3. Scored each task 1–5 for Gen AI exposure using keyword-based rubric
4. Calculated weighted average exposure score per occupation
5. Cross-referenced with O*NET skills importance ratings

---

## HR Recommendations
1. **Reskill HR Assistants** in data literacy and AI tool management
2. **Redesign recruiting roles** around AI augmentation not replacement
3. **Invest in human skills** — social perceptiveness, negotiation, coaching
4. **CHROs should audit** their HR task portfolio for automation exposure
5. **Build AI literacy** across all HR functions regardless of risk level

---

## Connect
- LinkedIn: [Arti Sharma](#)
- Email: artisharmaresume26@gmail.com# genai-impact-hr-workforce
A skills-based analysis of Gen AI exposure across HR occupations using O*NET data and Python
