# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: [ICE CREAM DOESN’T CAUSE DROWNING: BENCH-MARKING LLMS AGAINST STATISTICAL PITFALLS IN CAUSAL INFERENCE]

  - **[https://openreview.net/attachment?id=MGMG7yQ18v&name=supplementary_material]()**
  - **Objective**: Evaluate the reliability of LLMs in statistical causal inference and identify common causal reasoning pitfalls.
  - **Methods**: Introduces the CausalPitfalls benchmark with 75 datasets and questions across six causal inference categories, comparing direct and code-assisted prompting
  - **Outcomes**: Reveals substantial reliability gaps in LLM causal reasoning; code-assisted prompting improves performance but models remain unreliable on complex tasks.
  - **Relation to the Project**: Presents the CausalPitfalls data suite, which includes a dedicated challenge on mediator–outcome confounding, which is used for this project. Explains mediation analysis and mediator-outcome confounding.

- **Source 2**: [Dealing with complex problems of confounding in mediation analysis]

  - **[https://www.sis-statistica.it/old_upload/contenuti/2013/09/RS12-Dealing-with-complex-problems-of-confounding.pdf]()**
  - **Objective**: Address mediation analysis under mediator–outcome confounding, especially when confounders are affected by the exposure.
  - **Methods**: Counterfactual framework, identification of natural and controlled direct/indirect effects, G-formula, inverse probability weighting, and G-estimation.
  - **Outcomes**: Provides identification and estimation strategies for direct and indirect effects in the presence of intermediate confounding.
  - **Relation to the Project**: Covers mediator–outcome confounding.

- **Source 3**: [Confounding in Statistical Mediation Analysis: What It Is and How to Address It]

  - **[https://pmc.ncbi.nlm.nih.gov/articles/PMC5726285/]()**
  - **Objective**: Explain how confounding affects mediation analysis and present methods to obtain more valid causal mediation estimates.
  - **Methods**: Reviews design-based approaches (double randomization), statistical adjustment methods (IPW, sequential G-estimation, ANCOVA), and sensitivity analysis (L.O.V.E.).
  - **Outcomes**: Adjusting for mediator–outcome confounders can substantially change mediation effect estimates and improve causal interpretation.
  - **Relation to the Project**: Focuses on identifying, adjusting for, and assessing mediator–outcome confounding in mediation analysis.
