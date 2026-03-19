# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Digital Wellbeing & Smartphone Addiction Analysis

This project analyses a digital wellbeing dataset to investigate how smartphone usage behaviours relate to levels of smartphone addiction.

The dataset includes variables such as screen time, social media usage, gaming hours, notifications received, and sleep duration. These variables are analysed to identify patterns associated with different levels of smartphone addiction.

Python is used to clean, analyse, and visualise the dataset. Statistical testing and a machine learning regression model are applied to explore relationships between usage behaviour and addiction levels.

The results are presented through data visualisations and an interactive dashboard to communicate insights effectively.


# Dataset Content

The dataset used in this project contains information about smartphone usage behaviour and digital wellbeing indicators.

The dataset includes variables such as:

- daily_screen_time_hours
- social_media_hours
- gaming_hours
- work_study_hours
- sleep_hours
- notifications_per_day
- app_opens_per_day
- addiction_level

These variables describe how individuals interact with their smartphones and allow analysis of potential factors contributing to higher levels of digital addiction.


# Business Requirements

Context

The use of smartphones has increased significantly, raising concerns about digital wellbeing and smartphone addiction.

This project analyses smartphone usage behaviour to identify patterns associated with higher levels of addiction.

Stakeholder Needs

Researchers, educators, and individuals may be interested in understanding how usage behaviours such as screen time and notifications relate to addiction levels.

Business Requirements

BR1: Screen Time and Addiction  
Analyse the relationship between daily screen time and addiction level.

BR2: Social Media Usage  
Investigate whether social media usage is associated with higher addiction levels.

BR3: Sleep and Digital Wellbeing  
Explore whether lower sleep duration is linked to higher addiction levels.


# Project Hypothesis & Validation

Hypothesis 1 – Screen Time and Addiction

H0: Daily screen time has no relationship with smartphone addiction level  
H1: Higher daily screen time is associated with higher smartphone addiction levels  

Test: Pearson Correlation


Hypothesis 2 – Social Media Usage

H0: Social media usage has no relationship with smartphone addiction level  
H1: Higher social media usage is associated with higher smartphone addiction levels  

Test: Pearson Correlation


Hypothesis 3 – Sleep Duration

H0: Sleep duration has no relationship with smartphone addiction level  
H1: Lower sleep duration is associated with higher smartphone addiction levels  

Test: One sided t test

# Technologies Used

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
SciPy  
Scikit-learn  
Jupyter Notebook  
Tableau Public  
Git and GitHub  

# Project Structure

digital-wellbeing-analysis
│
├── Data
│   ├── raw
│   └── clean
│
├── jupyter_notebooks
│   ├── Data Preparation & Exploration.ipynb
│   └── Statistical Analysis & Modelling.ipynb
│
├── README.md
└── requirements.txt

# Project Objectives

The aim of this project is to:

- Analyse smartphone usage data to explore factors influencing addiction levels  
- Investigate relationships between variables such as screen time, social media usage, and sleep  
- Perform statistical hypothesis testing  
- Build a regression model to predict addiction level  
- Create visualisations and an interactive dashboard  


# Methodology

The project follows a structured data analytics workflow:

- Data extraction and cleaning using Python  
- Exploratory Data Analysis to understand patterns  
- Statistical hypothesis testing  
- Machine learning modelling using Linear Regression  
- Data visualisation and dashboard creation  


# Main Data Analysis Libraries

The following libraries were used in this project:

- pandas for data manipulation and analysis  
- numpy for numerical operations  
- matplotlib and seaborn for data visualisation  
- scipy for statistical testing  
- scikit-learn for machine learning modelling  


# Interactive Tableau Dashboard

Dashboard link: https://public.tableau.com/app/profile/priya.kaur.natt/viz/SmartphoneUsageAddictionDashboard/Dashboard1?publish=yes 

An interactive dashboard was developed using Tableau Public to visually present key insights from the smartphone usage dataset.

The dashboard combines multiple visualisations to provide a comprehensive overview of user behaviour and addiction levels:

- Addiction Level Distribution  
  Displays the overall distribution of users across Mild, Moderate, and Severe addiction categories. This provides context for understanding how addiction is spread within the dataset.

- Addiction Level by Gender  
  A stacked bar chart showing how addiction levels vary across gender groups. This allows for comparison and highlights differences in behavioural patterns between groups.

- Relationship Between Screen Time and Addiction Level  
  A scatter plot illustrating the relationship between daily screen time and addiction level. A positive trend is observed, indicating that higher screen time is associated with more severe addiction levels. Trend lines are included to highlight this relationship across different genders.

### Interactivity

The dashboard includes interactive functionality to enhance data exploration:

- Users can click on a gender category to filter all visualisations dynamically  
- This allows for deeper analysis of patterns within specific groups  
- The interactivity improves usability and supports more detailed insights  

### Design Considerations

The dashboard was designed with clarity and usability in mind:

- A clean layout with a clear visual hierarchy, placing the scatter plot as the main focus  
- Consistent colour coding for addiction levels across all charts  
- Minimal clutter to ensure readability and focus on key insights  



# Ethical Considerations

The dataset contains behavioural data related to smartphone usage. While no personal identifiers are included, there are ethical considerations regarding how addiction levels are defined and interpreted.

There is a risk of bias in the dataset, as behavioural patterns may not represent all user groups equally. Additionally, smartphone usage data can be sensitive, and care must be taken not to draw harmful or misleading conclusions.

The analysis focuses on identifying relationships rather than making causal claims, and results are interpreted cautiously.


# Key Findings

The analysis identified relationships between smartphone usage behaviours and addiction level.

Higher screen time and increased social media usage were associated with higher levels of addiction, while lower sleep duration showed a negative relationship with wellbeing.

However, no single variable fully explains addiction level, suggesting that multiple behavioural factors contribute.


# Results & Performance

A Linear Regression model was trained to predict addiction level.

Model performance:

Mean Squared Error and R² score indicate moderate predictive ability, suggesting that additional variables may be needed to improve accuracy.


# Future Improvements

Future work could include:

- testing additional machine learning models  
- including more variables such as demographic data  
- improving the dashboard with additional interactive features  