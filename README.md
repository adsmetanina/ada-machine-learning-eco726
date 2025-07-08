# Evaluating the Impact of the ADA

Final project code for ECO726 at Hunter College, Program & Policy Evaluation. This repository contains an analysis of the Americans w/ Disabilities Act (ADA) using machine learning tools to assess its impact on the earnings of individuals w/ disabilities. The project replicates and updates the findings of Acemoglu and Angrist (2001) using CPS data from 1988 to 1997. The final project submitted in December 2024.

## File

| File         | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| `main.ipynb` | Complete Google Colab notebook containing all steps of the analysis         |

## Project Overview

- **Goal:** Estimate the effect of the ADA on the weekly earnings of people w/ disabilities.
- **Data Source:** March CPS (1988–1997).
- **Methodology:** Causal forests, covariate balancing, and OLS regression.
- **Treatment Variable:** Disability status.
- **Outcome:** Log of weekly earnings.

## Key Methods

- Data cleaning and treatment/control assignment using CPS variables.
- Weighting of treatment group to national disability rate (19.3%).
- Estimation of Average Treatment Effect (ATE) via causal forests.
- Comparison w/ baseline OLS results.

## Summary of Results

- ATE from causal forests is not statistically significant.
- Subgroup analyses show some heterogeneity across gender, region, and education.
- OLS confirms a significant (~36%) earnings penalty associated w/ disability status.

## Reference

- Acemoglu, D., & Angrist, J. (2001). *Consequences of Employment Protection? The Case of the Americans w/ Disabilities Act.* *Journal of Political Economy*, 109(5), 915–957. [https://doi.org/10.1086/322900](https://doi.org/10.1086/322900)

## License

This project is for academic use only.
