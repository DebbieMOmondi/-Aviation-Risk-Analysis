# Aircraft Safety Analysis for Fleet Investment Decisions

## Overview
This project analyzes historical aircraft incident and survivability data to help a company considering expansion into the aviation sector. Using data science methods, we evaluate operational risks and recommend the safest aircraft models for investment. The project includes data preparation, visualization, and generation of actionable insights, supported by an interactive dashboard.

## Business Understanding
As the company diversifies into aviation, safety becomes a critical concern, especially for a new entrant with limited industry experience. The goal is to identify aircraft models that minimize operational risk, ensuring strong safety performance and protecting the company's reputation and assets.

**Key Stakeholder Questions:**
- Which aircraft models have the lowest rates of fatal incidents?
- Which aircraft models show the highest passenger survivability rates?
- How can we prioritize aircraft purchases based on historical safety performance?

## Data Understanding and Analysis

**Source of Data:**
- The dataset comes from the National Transportation Safety Board (NTSB) and includes records of civil aviation accidents and selected incidents in the United States and international waters from 1962 to 2023.

**Description of Data:**
- Aircraft make and model
- Counts of accidents categorized by severity (Destroyed, Substantial, Minor)
- Total fatalities, serious injuries, and number of uninjured passengers
- Calculated safety scores based on survivability rates and severity profiles

**Three Key Visualizations:**

1. **Damage Frequency and Severity by Aircraft Model**  
   - Visualization of how many incidents resulted in Destroyed, Substantial, or Minor damage for each aircraft model.
   ![Graph Description](images/Aircraft_Damage_Comparison_by_Make_and_Model.png)


2. **Total Fatal Injuries vs Total Uninjured Passengers**  
   - Scatter plot showing the balance between fatalities and survivability across different aircraft models.
   ![Graph Description](images/Fatalities_vs_Uninjured_Passengers_per_Event.png)

3. **Aircraft Safety Scores**  
   - Bar chart ranking aircraft models by overall calculated safety score, combining fatality rates, injury rates, and uninjured passenger counts.
   ![Graph Description](images/Aviation-Risk-Analysis\Images\Top_10_Safest_Aircraft_Models.png)

## Conclusion

Through careful analysis, two major findings were reached:

- The **Boeing 777** stands out as the safest aircraft across all evaluated metrics, showing extremely low fatality rates and high survivability.
- The **Boeing 747-400** and **Boeing 767** also demonstrate strong performance, making them good secondary options for expanding the fleet safely.


Overall, this analysis provides a clear, evidence-based recommendation to prioritize newer, proven aircraft models that enhance passenger safety and reduce operational risks for the company.

## Project Files
 
[Aviation Safety Analysis Dashboard](https://public.tableau.com/app/profile/deborah.omondi/viz/AviationRiskAnalysis-Dashboard/Dashboard1?publish=yes)

[View My Full Jupyter Notebook as a PDF](Aircraft_Safety_Analysis_ipynb.pdf)

[View My Powerpoint Presentation](presentation.pdf)
