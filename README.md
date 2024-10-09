# Fast Radio Bursts (FRBs) Analysis

## Overview
Fast Radio Bursts (FRBs) are enigmatic astrophysical phenomena classified into two main categories:

- **Repeating FRBs**: FRBs that have been observed to repeat over time.
- **Apparently Non-Repeating FRBs**: FRBs that appear to be non-repeating, but their true nature is uncertain.

## Objective
This repo aims to disentangle the mystery of FRBs using machine learning methods. Specifically,  we focus on an array of supervised machine learning techniques.

## Methodology
1. **Training Machine Learning Algorithms**:
   - We utilize a fraction of the observed FRBs from the **first CHIME/FRB catalog**.
   - The training data includes labels indicating which FRBs are apparently non-repeating and which are repeating.

2. **Predicting Repetitiveness**:
   - The trained models predict the repetitiveness of the remaining FRB data based on the observed parameters.
   - We compare the model predictions with the actual observed repetitiveness.

## Key Findings
- The models can correctly predict most FRBs, suggesting distinct mechanisms behind repeating and non-repeating FRBs.
- Two critical distinguishing factors between non-repeating and repeating FRBs are identified:
  - **Brightness Temperature**
  - **Rest-Frame Frequency Bandwidth**

## Keywords
- Methods: Data Analysis
- Transients: Fast Radio Bursts

## Data Sources
- **CHIME/FRB Catalog**: [Access the CHIME Catalog](https://www.chime-frb.ca/catalog) for the data used in this analysis.
- **Research Paper**: [Link to Research Pape](#) (https://arxiv.org/pdf/2210.02463).
