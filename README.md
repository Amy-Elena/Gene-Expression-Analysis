# Gene-Expression-Analysis  

This project investigates the association between **SALL1 gene expression** and **sex** using data from the Genotype-Tissue Expression (GTEx) project. The analysis focuses on understanding whether gene expression levels of **SALL1** differ significantly between males and females by performing a linear regression analysis.

## Project Overview

The dataset used in this project consists of three main files:
1. **Adipose_subcutaneous.csv**: Contains expression data of multiple genes, including SALL1, for various subjects.
2. **GTEx_phenotypes.csv**: Includes phenotypic information such as sex, age, and death history for each subject.
3. **gencode26.csv**: Provides additional metadata about each gene, including chromosome position and gene type.

### Objective
The goal is to run a linear regression model to test the association between **SALL1 gene expression** and **sex**. The project aims to identify whether the gene's expression is significantly influenced by sex and assess the strength of this association.

## Key Steps
1. **Data Preparation**:
   - Loaded the three data files and merged them based on subject ID and gene.
   - Filtered the data to focus on the **SALL1** gene.

2. **Exploratory Data Analysis (EDA)**:
   - Examined the distribution of gene expression levels for **SALL1**.
   - Analyzed summary statistics, visualized expression distributions, and identified potential outliers.

3. **Linear Regression**:
   - Ran a linear regression with **SALL1 expression** as the dependent variable and **sex** as the independent variable.
   - Extracted key results: p-value, beta (effect size), R-squared, and F-statistic.

4. **Model Assumptions**:
   - Checked assumptions of linearity, normality, and homoscedasticity.
   - Conducted the Breusch-Pagan test to assess homoscedasticity.

## Results
The regression analysis revealed a significant association between **SALL1 expression** and **sex**:
- **P-value**: < 0.001, indicating a statistically significant difference in **SALL1** expression between males and females.
- **Beta (Effect Size)**: The effect size (0.920) indicates a positive relationship, with females having higher **SALL1** expression compared to males.

## Conclusion
The analysis demonstrates that **SALL1 gene expression** is significantly associated with sex, with females showing higher average expression levels. The model’s results provide valuable insights into the potential role of sex in gene expression for **SALL1**.

