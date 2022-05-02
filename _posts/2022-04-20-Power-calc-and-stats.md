# Power Calculations
Due to the few numbers of observations in the data, power calculations were performed to determine the standardized effect size for the number of observations at hand. Effect sizes were calculated at the 5% significant level and 90% power. For all three forms of data, we can only find a small effect size. 
For the 5 and 2-point data, only a 0.37 effect size is possible. For the combined data, we can only estimate an effect size of about 0.26.

# Statistical Testing
Initial statistical testing to determine a difference of choice for between the group assigned a partner with an advantage and the group where the participant was assigned a partner without an advantage shows no statistically significant difference in choices between perceived advantage.

*Statistical Testing for 2-Point Difference*

| Action                | T-stat    | P-Value  |
|-----------------------|-----------|----------|
| Benign or Malicious  | -1.089707 | 0.525154 |
| Benign or Nothing     | 0.071133  | 0.943384 |
| Malicious or Nothing  | 0.209982  | 0.833957 |

*Statistical Testing for 5-Point Difference*

| Action                | T-stat    | P-Value  |
|-----------------------|-----------|----------|
| Benign or Malicious  | 0.636872  | 0.525154 |
| Benign or Nothing     | -0.151144 | 0.880060 |
| Malicious or Nothing  | -1.039266 | 0.300310 |

*Statistical Testing for Combined Data*

| Action                | T-stat    | P-Value  |
|-----------------------|-----------|----------|
| Benign or Malicious  | -0.318193 | 0.750552 |
| Benign or Nothing     | -0.111300 | 0.911450 |
| Malicious or Nothing  | -0.609381 | 0.542717 |

However, it may be the case that participants who were not motivated to perform well in the Raven’s Matrices were not treating the experiment seriously. 
This possibility was investigated by subsetting the data by performance in the first set of matrices to gauge effort. 
Statistical testing of this data showed that those who scored 7 or higher out of the total of 17 possible points in a 5-point difference chose differently between benign or malicious action.

*Statistical Testing for 5-Point Data Subset by Performance*

| Score  | Choice               | T-stat | P-Value | Reject H0 (95%) |
|--------|----------------------|--------|---------|-----------------|
| 3+     | Benign or Malicious  | -0.788 | 0.432   | False           |
|        | Benign or Nothing    | 0.333  | 0.740   | False           |
|        | Malicious or Nothing | 1.012  | 0.313   | False           |
| 4+     | Benign or Malicious  | -0.734 | 0.464   | False           |
|        | Benign or Nothing    | 0.343  | 0.732   | False           |
|        | Malicious or Nothing | 1.021  | 0.309   | False           |
| 5+     | Benign or Malicious  | -1.015 | 0.312   | False           |
|        | Benign or Nothing    | 0.842  | 0.402   | False           |
|        | Malicious or Nothing | 0.623  | 0.534   | False           |
| 6+     | Benign or Malicious  | -0.913 | 0.364   | False           |
|        | Benign or Nothing    | 1.749  | 0.083   | False           |
|        | Malicious or Nothing | 1.510  | 0.134   | False           |
| 7+     | Benign or Malicious  | -1.789 | 0.078   | False           |
|        | Benign or Nothing    | 2.189  | 0.032   | True            |
|        | Malicious or Nothing | 2.366  | 0.020   | True            |
| 8+     | Benign or Malicious  | -1.241 | 0.220   | False           |
|        | Benign or Nothing    | 1.018  | 0.314   | False           |
|        | Malicious or Nothing | 2.031  | 0.048   | True            |
| 9+     | Benign or Malicious  | -0.178 | 0.860   | False           |
|        | Benign or Nothing    | 0.671  | 0.507   | False           |
|        | Malicious or Nothing | 1.757  | 0.088   | False           |
| 10+    | Benign or Malicious  | 0.309  | 0.760   | False           |
|        | Benign or Nothing    | -0.075 | 0.941   | False           |
|        | Malicious or Nothing | 0.250  | 0.805   | False           |
| 11+    | Benign or Malicious  | -0.398 | 0.699   | False           |
|        | Benign or Nothing    | -0.398 | 0.699   | False           |
|        | Malicious or Nothing | 0.000  | 1.000   | False           |
| 12+    | Benign or Malicious  | 0.516  | 0.633   | False           |
|        | Benign or Nothing    | 0.000  | 1.000   | False           |
|        | Malicious or Nothing | 0.516  | 0.633   | False           |
| 13+    | Benign or Malicious  | 1.000  | 0.423   | False           |
|        | Benign or Nothing    | 0.000  | 1.000   | False           |
|        | Malicious or Nothing | 0.000  | 1.000   | False           |

A difference-in-means analysis of this subset showed that only advantage is statistically significant. 
Simple regression shows a negative relationship between advantage and choice, which implies that perceiving an advantage in an opponent makes one more likely to act in accordance with malicious envy.

*Balance Table with Adjusted P-Values for 5-Point Difference Subset Score of 7+*

| Variable                                           | No Advantage | Advantage | p-value  | corrected p-value | reject H0 |
|----------------------------------------------------|--------------|-----------|----------|-------------------|-----------|
| Advantage                                          | 82.000000    | 74.000000 | 0.000000 | 0.000000          | True      |
| Delete_Or_Nothing                                  | 0.390244     | 0.472973  | 0.020489 | 0.420030          | False     |
| Train_Or_Nothing                                   | 0.609756     | 0.621622  | 0.031582 | 0.431624          | False     |
| Train_Or_Delete                                    | 0.317073     | 0.270270  | 0.077567 | 0.602084          | False     |
| Political_Belief_Liberal                           | 0.365854     | 0.500000  | 0.088110 | 0.602084          | False     |
| Unconditional_Self_Acceptance_Score                | 3.670732     | 3.559459  | 0.075579 | 0.602084          | False     |
| Religion_Buddhist                                  | 0.036585     | 0.000000  | 0.113068 | 0.662253          | False     |
| Religion_Muslim                                    | 0.036585     | 0.000000  | 0.199884 | 0.682936          | False     |
| Political_Belief_Conservative                      | 0.426829     | 0.243243  | 0.199884 | 0.682936          | False     |
| Religion_Christian (including Church of England... | 0.719512     | 0.729730  | 0.177896 | 0.682936          | False     |

*OLS Model for 5-Point Difference Subset Score of 7+*

```text
==============================================================================
Dep. Variable:        Train_Or_Delete   R-squared:                       0.039
Model:                            OLS   Adj. R-squared:                  0.027
Method:                 Least Squares   F-statistic:                     3.199
Date:                Fri, 15 Apr 2022   Prob (F-statistic):             0.0776
Time:                        16:21:36   Log-Likelihood:                -51.228
No. Observations:                  80   AIC:                             106.5
Df Residuals:                      78   BIC:                             111.2
Df Model:                           1                                         
Covariance Type:            nonrobust                                         
==============================================================================
                 coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------
Intercept      0.4091      0.070      5.837      0.000       0.270       0.549
Advantage     -0.1869      0.104     -1.789      0.078      -0.395       0.021
==============================================================================
```





