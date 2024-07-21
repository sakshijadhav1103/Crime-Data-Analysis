# Crime-Data-Analysis
This project involves an analysis of crime data using exploratory data analysis (EDA), ANOVA analysis, and Gaussian Naive Bayes classification. The dataset includes information on victims, suspects, and crimes, allowing for an investigation into patterns and factors associated with different types of crimes.

## Data Collection

The data for this project was collected in person by visiting police stations. It was initially obtained in the form of First Information Reports (FIRs), which were then converted into structured data for use in this project.

## Project Structure

- **`CRIME2.csv`**: The dataset used for analysis.
- **`analysis.py`**: The Python script containing the code for data analysis, including EDA, ANOVA analysis, and Naive Bayes classification.

## Data Description

The dataset contains the following columns:
- `Victim_age`: Age of the victim
- `Victim_gender`: Gender of the victim
- `Suspect_age`: Age of the suspect
- `Suspect_gender_identified`: Gender identified for the suspect
- `Suspect_known_status`: Known status of the suspect
- `Suspect_count`: Number of suspects
- `Victim_religion`: Religion of the victim
- `Police_station`: Police station handling the case
- `Crime`: Type of crime

## Analysis Overview

### Exploratory Data Analysis (EDA)

1. **Histograms**: Distribution of victim age.
2. **Bar Charts**: Distribution of victim gender.
3. **Box Plots**: Distribution and outliers of victim age.
4. **Cross-tabulations**: Relationship between victim gender and type of crime.
5. **Correlation Heatmap**: Correlation between numeric variables.
6. **Pivot Tables**: Average victim age by crime and suspect gender.
7. **Scatter Plots**: Relationship between victim age and suspect age.
8. **Count Plots**: Crime distribution by police station and victim religion.

### ANOVA Analysis

1. **Victim Age by Victim Gender**: Analysis of variance to see if victim age varies by gender.
2. **Victim Age by Crime Type**: Analysis of variance to determine if victim age varies by crime type.
3. **Victim Age by Crime and Suspect Count**: Combined effect of crime type and suspect count on victim age.
4. **Victim Age by Police Station**: Analysis of variance to see if victim age varies by police station.
5. **Suspect Count by Crime Type**: Analysis of variance to determine if suspect count varies by crime type.
6. **Suspect Count by Police Station**: Analysis of variance to see if suspect count varies by police station.

### Naive Bayes Classification

1. **Data Preparation**: Handling missing values and encoding categorical variables.
2. **Model Training**: Training a Gaussian Naive Bayes model to classify whether the suspect's known status is unknown based on other features.
3. **Model Evaluation**: Assessing model performance and making predictions.

## Installation

Ensure you have the required Python libraries installed. You can install them using pip:

```bash
pip install pandas numpy seaborn scikit-learn matplotlib statsmodels
