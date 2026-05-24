# Predictors of Flu Vaccine Uptake

## Group Members
- Trish Huallpa
- Ayanna Antoine

## Project Description
In this study, we investigate the influenza vaccination intake and what the possible factors could be that affect this. Although there is widespread availability of this vaccine, the rates of this vaccine are seen to be irregular. By utilizing Datasets from the National Library of Medicine and the health policy organization called KFF, and survey data related to vaccine uptake, we were able to prepare data using NumPy and Pandas. To be able to visualize this into graphs, Matplotlib and Seaborn were used to identify patterns. A logistic regression was then made using Statsmodels in order to analyze the data.

This project explores how factors like age, education, income, or healthcare access can influence the intake of the flu vaccine. We investigate whether there is a structural barrier, personal belief, misinformation, or a lack of resources that dictates the decision one makes. Several staged data analyses were established to find the main variable of vaccine uptake.

## Main Biological/Health Question
**What demographic or personal factors (e.g., age, education, income, health beliefs) are most strongly associated with a person's decision to get a flu vaccine?**

## Dataset Description
- **Source:** National Library of Medicine and KFF (health policy organization) - Survey data related to vaccination intake in the United States
- **Data Collection:** Datasets were downloaded and imported into Google Colab
- **Data Preparation:** Pandas and NumPy were used to read, clean, and handle the data with focus on demographic factors
- **Visualization:** Matplotlib and Seaborn were used to create bar charts, pie graphs, and line plots to identify patterns
- **Data Analysis:** A logistic regression model was created using Statsmodels to predict vaccination status and determine significant factors while controlling for confounding variables

## Key Findings
Our findings indicated that **age and income were the primary factors of vaccination status**. The logistic regression analysis revealed:

- A **positive correlation** between the increase in age and income and the likelihood of an individual's vaccine intake
- An **odds ratio of 0.79** in those with low income
- An **odds ratio of 1.00** in higher income groups
- Individuals who received the influenza vaccine are most likely to take it **1-3 times** in their lifetime, and less likely to take it more than 3 times
- **Economic status and age are highly dependent determinants** for influenza vaccine uptake
- Evidence suggests **structural barriers and resource limitations** that impact public health outcomes

## Instructions

### How to Run the Notebook
1. Open the notebook directly in Google Colab: [**fluproject.ipynb**](https://colab.research.google.com/drive/1eDPdGksV-ItdsiheaaN8TbhysB0unk-f?usp=sharing)
2. Alternatively, open `fluproject.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook
3. Run all cells in sequence to reproduce the analysis and visualizations

### Required Python Libraries
The following libraries are required to run this project:

```
pandas
numpy
matplotlib
seaborn
statsmodels
```

**Installation:** To install all required libraries, run:
```bash
pip install pandas numpy matplotlib seaborn statsmodels
```

Alternatively, if running in Google Colab, these libraries are pre-installed by default.
