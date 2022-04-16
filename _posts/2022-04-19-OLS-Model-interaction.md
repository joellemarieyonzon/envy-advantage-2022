# OLS Model Interacting Advantage and Cause of Loss
The difference-in-means analysis implies that an individual’s perceived cause of loss and advantage are both significant determinants in envy-motivated behavior. 
The following models interact the two variables to show that an advantage causes malicious behavior when an individual perceives the situation as unfair or due to bad luck.

*Model Interacting Advantage and Cause of Loss for 2-Point Difference*
```text
==========================================================================================================================================
Dep. Variable:        Train_Or_Delete   R-squared:                       0.302
Model:                            OLS   Adj. R-squared:                  0.288
Method:                 Least Squares   F-statistic:                     22.03
Date:                Fri, 15 Apr 2022   Prob (F-statistic):           6.53e-12
Time:                        20:33:14   Log-Likelihood:                -73.816
No. Observations:                 157   AIC:                             155.6
Df Residuals:                     153   BIC:                             167.9
Df Model:                           3                                         
Covariance Type:            nonrobust                                         
==========================================================================================================================================
                                                                             coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------------------------------------------------------------------
Intercept                                                                  0.2486      0.048      5.177      0.000       0.154       0.343
Advantage                                                                 -0.1419      0.071     -2.004      0.047      -0.282      -0.002
Q("Cause_Of_Loss_The competition was unfair (You had a disadvantage)")     0.7294      0.091      7.999      0.000       0.549       0.910
Q("Cause_Of_Loss_Bad luck")                                                0.0084      0.090      0.094      0.925      -0.169       0.186
==========================================================================================================================================
```


*Model Interacting Advantage and Cause of Loss for 5-Point Difference*
```text
==========================================================================================================================================
Dep. Variable:        Train_Or_Delete   R-squared:                       0.225
Model:                            OLS   Adj. R-squared:                  0.217
Method:                 Least Squares   F-statistic:                     29.85
Date:                Fri, 15 Apr 2022   Prob (F-statistic):           5.69e-17
Time:                        16:21:34   Log-Likelihood:                -161.10
No. Observations:                 313   AIC:                             330.2
Df Residuals:                     309   BIC:                             345.2
Df Model:                           3                                         
Covariance Type:            nonrobust                                         
==========================================================================================================================================
                                                                             coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------------------------------------------------------------------
Intercept                                                                  0.2447      0.034      7.213      0.000       0.178       0.312
Advantage                                                                 -0.0978      0.048     -2.020      0.044      -0.193      -0.003
Q("Cause_Of_Loss_The competition was unfair (You had a disadvantage)")     0.6678      0.071      9.439      0.000       0.529       0.807
Q("Cause_Of_Loss_Bad luck")                                                0.1137      0.071      1.600      0.111      -0.026       0.253
==========================================================================================================================================
```

*Model Interacting Advantage and Cause of Loss for Combined Data*
```text
======================================================================================================================================================================
Dep. Variable:        Train_Or_Delete   R-squared:                       0.281
Model:                            OLS   Adj. R-squared:                  0.264
Method:                 Least Squares   F-statistic:                     17.00
Date:                Fri, 15 Apr 2022   Prob (F-statistic):           5.88e-19
Time:                        16:21:34   Log-Likelihood:                -149.37
No. Observations:                 313   AIC:                             314.7
Df Residuals:                     305   BIC:                             344.7
Df Model:                           7                                         
Covariance Type:            nonrobust                                         
======================================================================================================================================================================
                                                                                                         coef    std err          t      P>|t|      [0.025      0.975]
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Cause_Of_Loss[Bad luck]                                                                                0.3448      0.073      4.701      0.000       0.200       0.489
Cause_Of_Loss[Differences between you and your opponent in effort during the exercise]                 0.2558      0.060      4.246      0.000       0.137       0.374
Cause_Of_Loss[Differences between you and your opponent in intelligence]                               0.2921      0.042      6.977      0.000       0.210       0.375
Cause_Of_Loss[The competition was unfair (You had a disadvantage)]                                     0.3750      0.140      2.685      0.008       0.100       0.650
Advantage                                                                                             -0.0448      0.145     -0.309      0.757      -0.330       0.240
Advantage:Cause_Of_Loss[T.Differences between you and your opponent in effort during the exercise]    -0.0315      0.169     -0.186      0.852      -0.364       0.301
Advantage:Cause_Of_Loss[T.Differences between you and your opponent in intelligence]                  -0.1981      0.159     -1.246      0.214      -0.511       0.115
Advantage:Cause_Of_Loss[T.The competition was unfair (You had a disadvantage)]                         0.6110      0.212      2.878      0.004       0.193       1.029
======================================================================================================================================================================
```
