# From Structural Mapping to Intention Reasoning: A Review of LLM-based Mobile Test Migration

[![Report](https://img.shields.io/badge/Document-10--Page_Report-blue)]()
[![Presentation](https://img.shields.io/badge/Slides-Available-success)]()
[![Institution](https://img.shields.io/badge/Institution-TUM-orange)]()

## 📌 Project Overview
This repository contains the comprehensive Bachelor Seminar Report and associated presentation materials exploring the application of Large Language Models (LLMs) in automating the migration of mobile application test scripts. 

Testing mobile applications across heterogeneous Android devices remains challenging due to ecosystem fragmentation and the brittleness of UI-dependent automation techniques[cite: 5]. This project examines how recent LLM-based approaches address this limitation by shifting test migration from structure-level mapping to intention-level reasoning[cite: 5].

## 🎯 Key Research Questions
* **The Paradigm Shift:** How do LLMs overcome the limitations of traditional, static UI attribute-based migration frameworks (e.g., CraftDroid, AppFlow) when facing structurally dissimilar applications?
* **Pipeline Mechanics:** How can the complex process of LLM-driven test migration be standardized into a unified operational pipeline?[cite: 5]
* **Reliability & Evaluation:** Why is the conventional "success rate" metric insufficient for evaluating test migration, and how do issues like semantic drift and visual grounding errors threaten execution stability?[cite: 4, 5]

## 💡 Core Findings & Contributions
* **Unified Three-Stage Pipeline:** Synthesized a unified framework categorizing the LLM migration process into three stages: Abstraction of test intent, Planning of execution strategies, and Grounding of abstract actions onto concrete UI elements[cite: 5].
* **Identification of Critical Bottlenecks:** Identified that while natural language Intermediate Representations (IRs) improve cross-app generalization, they introduce risks of "semantic drift" where target execution deviates from the original test objective[cite: 4, 5]. Furthermore, visual grounding (via Vision-Language Models) remains highly fragile in non-standard UIs[cite: 4, 5].
* **The Evaluation Crisis:** Highlighted a fundamental mismatch in current benchmarking: reaching a final UI state does not guarantee the preservation of step-level test intent[cite: 4, 5].
* **Future Industrial Trajectory:** Concluded that future reliable deployment at scale requires hybrid neuro-symbolic architectures that combine LLM reasoning with traditional verification mechanisms[cite: 5].

## 📂 Repository Contents
* `docs/`: 
  * `Report_10_Pages.pdf` - The final 10-page academic report[cite: 4, 5].
  * `Presentation_Slides.pdf` - The slide deck used for the seminar presentation[cite: 4, 5].
* `latex_source/`: The complete LaTeX source code used for typesetting the report, including figures and `.bib` references.

## 🛠️ Tools & Technologies
* **Research Focus:** Large Language Models (LLMs), Vision-Language Models (VLMs), Mobile App GUI Testing, Automated Test Migration[cite: 4, 5]
* **Analysis Methodology:** Literature Review, Meta-analysis, Pipeline Synthesis[cite: 4, 5]
* **Typesetting:** LaTeX, BibTeX

---
*This project was completed as a Bachelor Seminar by Tian Gan at the Technical University of Munich (TUM), School of CIT, in January 2026[cite: 4, 5].*
