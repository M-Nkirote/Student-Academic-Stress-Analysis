# ${\textsf{\color{#C25A7C}📊 Academic Stress Analysis}}$ 

## ${\textsf{\color{#FFC0CB}📖 Introduction}}$
Academic stress has become a pressing issue among students globally, with profound impacts on their mental health and academic outcomes.
This project analyzes a real-world dataset on student academic stress to:

*  Identify key factors contributing to stress.
*  Evaluate their relationships with student well-being.
*  Support data-driven research, mental health evaluation, and the development of informed educational policies.

## ${\textsf{\color{#FFC0CB}📂 Dataset}}$
**Data Source :** https://www.kaggle.com/datasets/poushal02/student-academic-stress-real-world-dataset

| Column Name | Data Type | Description
|----------|-------------|-------------|
| Timestamp | DateTime | The date and time when the student completed the survey. |
| Your Academic Stage | Categorical (['undergraduate', 'high school', 'post-graduate']) | The student’s level of education, useful for comparing stress across academic stages. |
| Peer pressure | Numerical (1–5 scale) | Degree of influence from peers through competition, comparison, or social expectations. |
| Academic pressure from your home | Numerical (1–5 scale) | Level of academic expectations or pressure experienced from family or household members. |
| Study Environment | Categorical (['Noisy', 'Peaceful', 'disrupted', nan]) | The quality of the student’s study environment, affecting focus and learning productivity. |
| What coping strategy you use as a student? | Categorical (['Analyze the situation and handle it with intellect','Social support (friends, family)', 'Emotional breakdown (crying a lot)']) | The primary coping mechanism students adopt when dealing with academic stress. |
| Do you have any bad habits like smoking, drinking on a daily basis? | Categorical(['No', 'prefer not to say', 'Yes']) | Indicates whether the student engages in potentially harmful daily habits as a response to stress. |
| What would you rate the academic  competition in your student life | Numerical (1–5 scale) | The student’s perception of competition intensity within their academic environment. |
| Rate your academic stress index | Numerical (1–5 scale) | The student’s self-reported overall academic stress level (dependent variable). |


## ${\textsf{\color{#FFC0CB}🔎 Analysis Strategy}}$

**1. Data Preparation**
  - Data Cleaning
  - Feature Engineering

**2. Descriptive Statistics & Exploration**
  - Summary Statistics: Mean, median, and distribution of all numerical variables (peer pressure, home pressure, academic competition, stress index).
  - Categorical Insights: Frequency counts for academic stage, coping strategies, study environment, bad habits.
  - Stress by Group: Compare mean stress index across:
    - Academic stages (high school vs undergraduate vs postgraduate).
    - Study environment (peaceful vs noisy/disrupted).
    - Coping strategies.

**3. Visualization**
  - Univariate: Histograms for numerical variables, bar plots for categorical variables.
  - Bivariate:
    - Boxplots: Stress index by academic stage / study environment / coping strategy.
    - Heatmap: Correlation matrix for numerical variables.

**4. Inferential Analysis**
  - Correlation Tests: Pearson/Spearman correlations between stress index and numerical predictors.

**5. Predictive Modeling**
  - Regression Analysis:
    - Multiple Linear Regression (predicting stress index from peer pressure, home pressure, academic competition, categorical predictors).
    - Cross-validation for model reliability.

**6. Interpretation & Reporting**
  - Identify the strongest predictors of stress.
  - Highlight which pressures (social, environmental, performance) matter most.
  - Compare across educational stages (who is most vulnerable and why).
  - Translate results into insights for educational policy and student support programs.
















