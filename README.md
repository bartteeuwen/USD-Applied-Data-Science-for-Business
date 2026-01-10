# Data Science for Business – Agentic AI Final Project

This repository showcases a **complete, end-to-end applied machine learning project** completed as part of the graduate-level course  
**Data Science for Business (ADS 505)** in the M.S. in Applied Data Science program at the University of San Diego.

The project explores whether **agentic AI systems can be deployed safely and reliably** to support real-world CRM workflows, with a focus on precision, control, and decision thresholds rather than full automation.

---

## Project Objective

As CRM platforms increasingly introduce agentic AI capabilities, organizations face a key question:  
*Can AI systems decide when to act—and how to act—without introducing unacceptable risk?*

The goal of this project was to:

- Evaluate whether an agentic AI can reliably decide **when** to invoke a tool in a CRM workflow  
- Assess how accurately the system can select the **correct tool** when action is warranted  
- Design a deployment approach that prioritizes control, interpretability, and risk management  
- Translate model performance into practical guidance for real-world rollout  

---

## What This Repository Contains

- A **fully documented analysis notebook** containing:
  - Data ingestion and preprocessing of conversational logs  
  - Feature engineering from dialog context and prior actions  
  - Exploratory analysis of factors influencing tool invocation  
  - A two-stage classification pipeline (when to act, which tool to call)  
  - Model evaluation using accuracy, F1, confusion matrices, and top-k metrics  
  - Threshold analysis to balance precision, coverage, and safety  

The notebook is written to be readable by both technical and non-technical audiences, with explanations provided alongside code, visualizations, and results.

---

## Dataset Overview

The project uses a **publicly available conversational dataset** designed to simulate CRM-style interactions.

Key characteristics include:

- Multi-turn conversations between users and agents  
- Embedded tool calls representing CRM actions  
- Rich contextual history capturing prior dialogue and tool usage  
- Moderate class imbalance reflecting real-world decision sparsity  

Labels were derived directly from conversation structure to support a two-stage decision framework.

---

## Key Takeaways

- **Separating “when to act” from “how to act” improves control:** A two-stage design enables conservative, interpretable deployment.  
- **Thresholding matters as much as model choice:** Adjusting confidence thresholds provides a clear trade-off between precision and coverage.  
- **The system achieved high accuracy when it chose to act:** At conservative thresholds, tool selection accuracy exceeded 90%, albeit with limited coverage.  
- **Agentic AI is best deployed incrementally:** Precision-first, assistive workflows reduce risk and support safe experimentation.  
- **Decision support beats full automation early:** The strongest use case is augmenting human workflows, not replacing them.

---

## Why This Project Matters

This project demonstrates how applied data science can be used to evaluate **emerging AI capabilities through a business and risk lens**, not just a modeling one.

The workflow reflects challenges commonly faced in:
- AI product evaluation  
- Decision automation under uncertainty  
- Risk-aware deployment of ML systems  
- CRM and workflow intelligence  

Rather than asking whether an AI *can* act, the project focuses on whether it *should*—and under what conditions.

---

## Notes

- This project was completed entirely as part of the USD Applied Data Science program.  
- All data used is publicly available.  
- Reports and presentations associated with this project are available upon request.

---
