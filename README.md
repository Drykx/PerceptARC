# A Guide to the Abstraction and Reasoning Corpus (ARC-AGI)

**Semester Project – Mathematics for Data Science Lab, EPFL**  
📅 *23 September 2024 – 3 January 2025*  
📍 *École Polytechnique Fédérale de Lausanne (EPFL)*  
🎓 *10 ECTS project*

---

## 📄 Final Report

You can download the full PDF report from the [Releases page](https://github.com/Drykx/PerceptARC/releases/tag/v1.0).

[![Download PDF](https://img.shields.io/badge/Download-Final_Report-blue)](https://github.com/Drykx/PerceptARC/releases/tag/v1.0)

> ⚠️ As I will be competing this year, I’ve decided not to share my code or final results publicly. However, I’m sharing my notes to help others explore ARC-AGI.  
>  
> 💬 Feel free to reach out if you'd like to discuss the project: **delineauj@gmail.com**

---

## 🔍 Project Overview

This project investigates the limitations of Transformer-based large language models (LLMs) in achieving Artificial General Intelligence (AGI), with a focus on the ARC-AGI benchmark introduced by François Chollet. ARC-AGI is designed to test core human priors such as objectness, numerosity, and compositionality—fundamental capabilities where current LLMs often fall short, particularly in internalizing abstract representations or reasoning symbolically.

We introduce the first mathematical and intuitive framework for analyzing ARC-AGI and survey state-of-the-art approaches aimed at overcoming these limitations, including test-time tuning (TTT) and inference-time strategies like AIRV. Building on this foundation, we propose a classification-based architecture inspired by Gestalt psychology, defining 16 distinct human "perceptions" essential for solving ARC-AGI tasks.

Despite time constraints, we hand-labeled 200 tasks—laying the foundation for a scalable dataset of over 1.2 million examples—and developed an initial neural classification model. Our early findings suggest that solving ARC-AGI may require a two-level cognitive process. We also raise key questions about how LLMs perceive structured reasoning tasks relative to human intuition.

 Ultimately, we argue that abstraction in language models may require mechanisms akin to the quotient operator in mathematics, and propose future directions inspired by DreamCoder-style neural program induction.
 
> I believe this work points toward the need for a new field of mathematics — one that redefines what information is, and the kinds of transformations that preserve it. This new framework may intersect with ideas from physical entropy in physics and informational entropy in computer science. Such a foundation could help explain how intelligent systems represent, compress, and reason about structure and why current models fall short.

---

## 🔒 License

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to share and adapt it with proper attribution.

© 2025 Jean-Sébastien Delineau
