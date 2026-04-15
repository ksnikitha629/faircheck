# FairCheck: Bias Detection Tool

## Overview
FairCheck is a tool designed to evaluate whether a predictive model exhibits bias across different groups. AI was used to debug code for this assignment. 

## Features
- Computes fairness metrics:
  - Selection rate
  - Accuracy
  - False positive rate
  - False negative rate
- Visualizes disparities across groups
- Flags potential bias using threshold-based detection

## Dataset
This project uses a simulated dataset to demonstrate how fairness disparities can be detected across groups.

The dataset includes:
- `actual`: true outcome
- `predicted`: model prediction
- `group`: demographic group

## Ethical Framework
This project aligns with the NIST AI Risk Management Framework:

- **Map**: Identifies stakeholders and potential harms
- **Measure**: Quantifies disparities using fairness metrics
- **Manage**: Flags potential bias for further review
- **Govern**: Promotes transparency in AI systems

## Use Case
This tool can be applied to real-world scenarios such as:
- Loan approvals
- Hiring systems
- College admissions

## Limitations
- Fairness metrics may conflict with one another
- Results depend on available group data
- Equal metrics do not guarantee true fairness
- Context is critical when interpreting results

## Author
Snikitha Kassey
