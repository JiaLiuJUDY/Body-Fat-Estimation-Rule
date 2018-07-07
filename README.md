# Body-Fat-Estimation-Rule
This repo shows a simple, robust, accurate and precise  “rule-of-thumb” method to estimate percentage of body fat using clinically available measurements. 

To accurately estimate bodyfat, several criterions were used to select important variables. After model diagonsis, we transformed independent variables to better satisfy linear model assumptions. It was found out that among all 14 variables, the linear function of WEIGHT, WEIGHT transformation, ABDOMEN, FOREARM, and WRIST can best interpret bodyfat.

This repo contains all of the data analysis for the mentioned Body Fat data. It is consisted of six main parts:

* data folder: includes the raw data (BodyFat.csv) and the cleaned data (clean.csv)
* code folder: includes all the code for our analysis
* figure folder: includes all figures/images/tables produced in our analysis
* summary folder: a Jupyter Notebook summary and its html file for our analysis.
* slide folder: a Jupyter Notebook slide and its html file for presetation.

This project came up with a simple principle to calculate body fat given weight & abdomen:

    *BodyFat (%) = -50 + 0.3Weight(kg) + Abdomen(cm)*

with an Residual Mean Square Error equals to 22.1.
