# Investigating-The-Factors-Influencing-Student-s-Choice-of-Program-of-Study-A-Case-Study-of-KNUST

📄 Full Report: [View Analysis](Investigating The Factors Influencing Student’s Choice of Program of Study_ A Case Study of KNUST.pdf)

## Overview
This project investigates the factors shaping undergraduate program choices among 194 students at Kwame Nkrumah University of Science and Technology (KNUST) in Ghana, based on a 2025 survey. Key drivers include personal passion/interest (51.6%), job opportunities (28%), and family influence (80.2% influential), with significant program-specific variations (e.g., higher family role in Architecture, p<0.001). Career focus (mean=0.505) and academic alignment (mean=0.565) dominate, while EFA identifies seven latent factors explaining 73% of variance. High satisfaction (91.4%) prevails, but 30.1% reconsider choices due to job prospects concerns (56.5%). Findings underscore intrinsic motivations and family roles, informing targeted recruitment and support strategies for diverse student demographics in STEM programs.

## Objectives
- Investigate factors influencing students in selecting undergraduate programs at KNUST.
- Understand the role of family members in selecting undergraduate programs.
- Determine the primary personal and career-related factors influencing students’ choice of program of study at KNUST.

## Dataset Summary
- **Source**: Primary survey data from KNUST undergraduate students in planning and related programs (2025).
- **Sample Size**: 194 respondents.
- **Key Variables**: Demographics (age, gender, employment, income, marital status, program); motivational factors (passion, job opportunities, family influence, scholarships); concerns (job prospects, academic difficulty, costs); information sources (internet, university website, alumni); satisfaction/reconsideration levels.

## Methods
- Descriptive statistics (means, frequencies, percentages) and visualizations (bar plots, box plots, heatmaps) for profiling demographics and factor distributions.
- Inferential tests including chi-square for associations (e.g., gender vs. program, p<0.001) and ANOVA/Tukey HSD for group differences (e.g., family influence by program, F=10.619, p<0.001).
- Exploratory factor analysis (EFA) for latent structures (KMO=0.74, 7 factors explaining 73% variance); K-means clustering for influence patterns; linear/logistic regression for predictors (e.g., family influence on satisfaction, β=-1.416, p<0.001); mediation analysis for indirect effects.

## Key Findings
- Demographics: Youthful (mean age=22.26), female-majority (56.7%), with Development Planning dominant (47.4%); significant gender-program association (χ²=34.20, p<0.001), e.g., no females in Land Economy.
- Motivational factors: Passion/interest (51.6%) leads, followed by job opportunities (28%); significant program variations (e.g., passion χ²=46.40, p<0.001); family influential for 80.2%, with career concerns dominant (87.6%).
- Personal/career factors: Academic alignment (mean=0.565) and career focus (mean=0.505) key; EFA reveals 7 factors (e.g., passion-driven, career growth) explaining 73% variance; high satisfaction (91.4%), but 30.1% reconsider due to job prospects (56.5% concern).
- Family role: Supportive (82.8% full support), but pressure moderate (6.5% strong); clusters show high influence in Architecture/Settlement Planning; mediation: family influence reduces satisfaction via personal interest (ACME=-1.178, p<0.001).
- Correlations: Academic alignment vs. career focus (r=0.322); family influence negatively correlates with job/salary importance (r=-0.409/-0.610).


## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr, psych (for EFA), cluster (for K-means), lavaan (for mediation), car (for ANOVA)

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "psych", "cluster"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). Investigating The Factors Influencing Student’s Choice of Program of Study: A Case Study of KNUST.
