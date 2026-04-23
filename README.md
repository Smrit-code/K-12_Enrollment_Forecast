K–12 Enrollment Modeling & Demographic Analysis (California)
A machine learning + demographic analytics project using Random Forests and county‑level insights.

Project Overview
This project analyzes California K–12 school‑level enrollment data to understand demographic patterns, programmatic needs, and structural drivers of enrollment across counties. Using a Random Forest regression model, combined with county‑level demographic aggregation and visual analytics, the project provides a comprehensive view of how enrollment varies across regions and what factors influence it.

The notebook includes:
Data cleaning and preprocessing
Feature engineering
Random Forest modeling
Model evaluation (R², MAE, scatter plot)
Feature importance analysis
County‑level demographic heatmaps
Programmatic needs comparison
Top 3 counties by demographic enrollment

Dataset Description
The dataset includes:
School-level enrollment counts (TK–12)
Demographic groups:  
Programmatic indicators: English Learner (EL), Students with Disabilities (SWD), Socioeconomically Disadvantaged (SED), Free/Reduced Meal Eligible (FRPM)
County and district identifiers
The dataset represents active California K–12 schools for the 2024–25 academic year.

Machine Learning Model
A Random Forest Regressor was trained to predict total school enrollment using:
Grade-level counts
Demographic distributions
Programmatic needs
County-level characteristics
Model Performance
R² Score: 0.907
MAE: ~96 students
These metrics indicate strong predictive performance across schools of varying sizes and demographic profiles.

Key Insights
Enrollment Patterns
Enrollment is concentrated in a small number of large counties.
Urban counties show higher demographic diversity.
Rural counties tend to have smaller, more homogeneous student populations.
Demographic Insights
Programmatic Needs
SED and FRPM percentages are high across most counties.
SWD percentages remain stable statewide.
EL percentages vary sharply by region.
These features reflect structural community characteristics tied to school size.

Top 3 Counties by Demographic Enrollment
The analysis identifies which counties have the highest enrollment for each demographic group, supporting:
Equity planning
Staffing models
Program funding
County-level comparisons

Visualizations Included
Actual vs Predicted Enrollment scatter plot
Feature importance ranking
County-level demographic heatmap
Programmatic needs comparison
Top 3 counties by demographic group

Methods Used
Random Forest Regression
County-level aggregation
Heatmaps and comparative visualizations
Feature engineering for demographic and programmatic indicators
