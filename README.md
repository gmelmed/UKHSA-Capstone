# UKHSA-Capstone
This project is part of the capstone for the **MPA Data Science for Public Policy program - LSE**, hosted by the UK Health Security Agency (UKHSA).

## Overview
This repository contains the code and data used to analyze National Action Plans (NAPs) on antimicrobial resistance (AMR) using Large Language Models (LLMs). The project explores how GPT-4o-mini model can be leveraged to annotate policy documents, identify key policy elements, and compare AMR strategies across different countries.

## Key Findings
- **High Accuracy**: GPT-4o-mini achieved an overall accuracy exceeding 89% in annotating NAPs.
- **Whole-Document Approach**: Outperformed the chunking approach in precision and F1-score.
- **Language-Based Performance**: Higher accuracy on English-language NAPs than Spanish-language NAPs.
- **Regional Disparities**: Latin America had the lowest alignment with WHO’s Global Action Plan.

## Repository Contents
```plaintext
📂 data/              # NAPs and table results
📂 notebooks/           # Python scripts for processing and analysis
📂 viz/           # Figures results
```

## Methodology
1. **Whole-Document Approach**: The model analyzes entire NAPs in a single prompt.
2. **Chunking Approach**: NAPs are divided into smaller segments for analysis.
3. **Performance Evaluation**: Accuracy, precision, recall, and F1-score are calculated by comparing model outputs to human annotations.
4. **Policy Insights**: Unvalidated annotations on a larger dataset help identify global trends in AMR policy.

## Policy Implications
- **AI-assisted Policy Analysis**: LLMs can enhance policy document evaluation with human oversight.
- **Standardization**: Establishing structured policy document formats can improve AI-driven assessments.
- **International Collaboration**: Strengthening partnerships can improve AMR strategies globally.

## Contributors
- [Betzabé Soria]()
- [Gabriel Melmed]()
- [Giovana De La Cruz]()
- [Shashank Srivastava]()
