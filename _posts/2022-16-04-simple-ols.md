# Simple OLS models
For analysis, an initial simple OLS regression model was run for all three datasets that took advantage as the sole determinant of envy-motivated action. 
The best performing model was created with the 2-point difference data at 0.008 r-squared, while the model created with the combined data exhibited almost no explanatory power with no consistency in sign. 
The models for the 2-point and combined data show a positively signed coefficient, meaning that when one perceives an opponent as having an advantage, they are more likely to exhibit envy-motivated malicious behavior.  
In all models, advantage held no statistical significance at even the 0.10 significance level. 
Additionally, Breusch-Pagan testing showed no homoskedasticity in the models.

*Simple OLS Model for 2-Point Difference*
------------------------------------------------------------------------------
Dep. Variable:        Train_Or_Delete   R-squared:                       0.008
Model:                            OLS   Adj. R-squared:                  0.001
Method:                 Least Squares   F-statistic:                     1.187
Date:                Fri, 01 Apr 2022   Prob (F-statistic):              0.278
Time:                        23:22:49   Log-Likelihood:                -101.40
No. Observations:                 157   AIC:                             206.8
Df Residuals:                     155   BIC:                             212.9
Df Model:                           1                                         
Covariance Type:            nonrobust                                         
------------------------------------------------------------------------------
                 coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------
Intercept      0.2759      0.050      5.539      0.000       0.177       0.374
Advantage      0.0813      0.075      1.090      0.278      -0.066       0.229
------------------------------------------------------------------------------


*Simple OLS Model for 5-Point Difference*                       
| Dep. Variable:    | Train_Or_Delete | R-squared:          | 0.003   |
|-------------------|-----------------|---------------------|---------|
| Model:            | OLS             | Adj. R-squared:     | -0.004  |
| Method:           | Least Squares   | F-statistic:        | 0.4056  |
| No. Observations: | 156             | Prob (F-statistic): | 0.525   | 
| Df Residuals:     | 154             | Log-Likelihood:     | -98.643 |
| Df Model:         | 1               | AIC:                | 201.3   |
| Covariance Type:  | nonrobust       | BIC:                | 207.4   |
|                   |                 |                     |         |         |        |        |
|                   | coef            | std err             | t       | P>\|t\| | [0.025 | 0.975] |
| Intercept         | 0.3171          | 0.051               | 6.264   | 0.000   | 0.217  | 0.417  |
| Advantage         | -0.0468         | 0.073               | -0.637  | 0.525   | -0.192 | 0.098  |
|                   |                 |                     |         |         |        |        |


*Simple OLS Model for Combined Data*
------------------------------------------------------------------------------
Dep. Variable:        Train_Or_Delete   R-squared:                       0.000
Model:                            OLS   Adj. R-squared:                 -0.003
Method:                 Least Squares   F-statistic:                    0.1012
Date:                Fri, 15 Apr 2022   Prob (F-statistic):              0.751
Time:                        16:21:31   Log-Likelihood:                -200.87
No. Observations:                 313   AIC:                             405.7
Df Residuals:                     311   BIC:                             413.2
Df Model:                           1                                         
Covariance Type:            nonrobust                                         
------------------------------------------------------------------------------
                 coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------
Intercept      0.2959      0.035      8.340      0.000       0.226       0.366
Advantage      0.0166      0.052      0.318      0.751      -0.086       0.120
------------------------------------------------------------------------------

