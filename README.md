# Evaluating the Effects of the Americans w/ Disabilities Act Using Machine Learning

Final project code for ECO 726: Policy & Program Evaluation at Hunter College. Replication of Acemoglu and Angrist (2001) using machine learning tools in R. This repository contains a set of R codes used to prepare, merge, and analyze labor policy data. It specifically investigates how the Americans w/ Disabilities Act (ADA) impacts the earnings of individuals w/ disabilities. The project constructs an analytic sample using CPS datasets from 1988 to 1997, and performs a final analysis.


## Files

| File         | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| `main.ipynb` | Complete Google Colab notebook containing all steps of the analysis         |

## Project Overview

The final paper submitted in December 2024 summarizes the research findings and methodology. It includes regression results, policy implications, and literature references.

## Data Sources
- [March CPS (1988-1997)]

## Methodology

- **Treatment Variable:** Disability status.
- **Outcome:** Log of weekly earnings.
- Data cleaning and treatment and control assignment using CPS variables.
- Weighting of treatment group to national disability rate (19.3%).
- Estimation of Average Treatment Effect (ATE) via causal forests.
- Comparison w/ baseline OLS results.

## Results

- ATE from causal forests is not statistically significant.
- Subgroup analyses show some heterogeneity across gender, region, and education.
- OLS confirms a significant (~36%) earnings penalty associated w/ disability status.

## Reference

- Acemoglu, D., & Angrist, J. (2001). *Consequences of Employment Protection? The Case of the Americans w/ Disabilities Act.* *Journal of Political Economy*, 109(5), 915–957. [https://doi.org/10.1086/322900](https://doi.org/10.1086/322900)

## Notes

This project demonstrates applied modeling in R. Some minor bugs remain unedited to preserve the submitted version.

## License

This repository is for academic use only.
