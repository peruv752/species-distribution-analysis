Species Distribution Analysis: Climate Impact on Bird Populations
Author: Purnima Purnima
 Date: October 2025
 Skills Demonstrated: R Programming, Statistical Modeling, Machine Learning, Ecological Data Analysis, Data Visualization

 Project Overview
This project analyzes the relationship between environmental variables and bird species richness across 200 survey sites in North America. Using statistical modeling and machine learning techniques, I identified key climate and habitat factors that predict biodiversity patterns.
Research Question: How do climate variables (temperature, precipitation) and habitat characteristics (forest cover, human disturbance) affect bird species diversity?

 Skills & Tools Used
Programming & Analysis
R Programming: tidyverse, ggplot2, dplyr, data manipulation
Statistical Modeling: Multiple linear regression, model diagnostics
Machine Learning: Random Forest (randomForest, caret)
Data Visualization: ggplot2, corrplot, viridis color palettes
Spatial Analysis: Geographic mapping, spatial distribution patterns
Ecological Methods
Species richness analysis
Environmental variable correlation
Predictive modeling for biodiversity
Variable importance assessment

 Key Findings
Temperature shows a significant positive correlation with species richness (p < 0.001)
Forest cover is the strongest positive predictor of biodiversity
Human disturbance has a significant negative impact on species diversity
Random Forest model achieved R² = 0.85, outperforming linear regression (R² = 0.72)

 Repository Structure
species-distribution-analysis/
│
├── analysis.R                    # Main R script with complete analysis
├── README.md                     # This file
│
└── output/
    ├── ecological_data.csv       # Generated dataset (200 sites)
    ├── 01_species_distribution.png
    ├── 02_temp_species.png
    ├── 03_correlation_matrix.png
    ├── 04_multiple_factors.png
    ├── 05_model_diagnostics.png
    ├── 06_variable_importance.png
    ├── 07_predictions.png
    ├── 08_spatial_map.png
    └── analysis_summary.txt      # Written summary of findings


 How to Run
Prerequisites
Install R and the required packages:
install.packages(c("tidyverse", "ggplot2", "corrplot", "randomForest", 
                   "caret", "viridis", "maps", "RColorBrewer"))

Running the Analysis
Clone this repository:
git clone https://github.com/peru752/species-distribution-analysis.git

cd species-distribution-analysis

Open analysis.R in RStudio


Set your working directory (line 15):


setwd("your/path/to/project")

Run the entire script:
source("analysis.R")

Check the output/ folder for all generated visualizations and reports

 Sample Visualizations
Species Richness Distribution

Temperature vs Species Richness

Variable Importance (Random Forest)

Spatial Distribution Map

 Statistical Results
Linear Regression Model
R-squared: 0.72
Significant Predictors: Temperature (β = 0.50, p < 0.001), Forest Cover (β = 0.30, p < 0.001)
Model p-value: < 0.001
Random Forest Model
RMSE: 5.83
R-squared: 0.85
Most Important Variables: Forest Cover, Temperature, Human Disturbance

 Methodology
Data Generation
Simulated realistic ecological data with known relationships between environmental variables and species richness, mimicking real-world survey data from sources like eBird.
Analysis Pipeline
Exploratory Data Analysis: Summary statistics, distribution checks, missing value assessment
Visualization: Multiple plot types to explore relationships
Statistical Modeling: Multiple linear regression with diagnostics
Machine Learning: Random Forest with cross-validation
Model Comparison: Performance evaluation (RMSE, R²)
Spatial Analysis: Geographic mapping of biodiversity patterns

 Applications
This analysis demonstrates skills applicable to:
Conservation Planning: Identifying critical habitat variables for species protection
Climate Change Research: Predicting biodiversity responses to environmental change
Land Use Planning: Understanding human impact on wildlife diversity
Ecological Monitoring: Establishing baseline biodiversity patterns

 Learning Outcomes
Through this project, I demonstrated:
Proficiency in R programming for ecological data analysis
Understanding of statistical modeling and machine learning techniques
Ability to visualize complex environmental relationships
Skills in interpreting and communicating scientific results
Knowledge of ecological principles and biodiversity patterns

 Future Enhancements
[ ] Integrate real data from Global Biodiversity Information Facility (GBIF)
[ ] Add time-series analysis for temporal trends
[ ] Implement species-specific distribution models
[ ] Include additional predictors (land use, elevation variability)
[ ] Create interactive Shiny dashboard for exploration

 Contact
Purnima Purnima
 Email: purn0005@algonquinlive.com



 License
This project is open source and available for educational purposes.

 Acknowledgments
Environmental data simulated based on patterns from North American Breeding Bird Survey
Statistical methods adapted from ecological modeling literature
Visualization techniques inspired by R for Data Science (Wickham & Grolemund)

Note: This is a demonstration project using simulated data to showcase analytical skills for quantitative ecology positions.

