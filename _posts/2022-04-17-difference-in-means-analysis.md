# Difference-in-means Analysis
To determine whether any other variables are having a confounding or significant effect in determining envy-motivated action, a difference-in-means analysis was performed to check for any variables significant at 0.05 level. 
Advantage remained a consistently significant variable at a p-value of almost 0. 
The perceived cause of loss also seems to be a statistically significant determinant of envy-motivated action, particularly if the participant attributed their loss to inequity or bad luck. 
The following tables defines the top 10 lowest p-values in each dataset after the implementation of dummy variables for categorical data.

*Balance Table with Adjusted P-Values for 2-Point Difference*
| Variable                                           | No Advantage | Advantage | p-value      | corrected p-value | reject H0 |
|----------------------------------------------------|--------------|-----------|--------------|-------------------|-----------|
| Advantage                                          | 87.000000    | 70.000000 | 8.327341e-01 | 0.000000          | True      |
| Cause_Of_Loss_The competition was unfair (You h... | 0.034483     | 0.342857  | 1.303993e-07 | 0.000003          | True      |
| Cause_Of_Loss_Bad luck                             | 0.252874     | 0.042857  | 2.925257e-04 | 0.004485          | True      |
| Education_High school degree or equivalent         | 0.264368     | 0.114286  | 1.876221e-02 | 0.215765          | False     |
| Education_Master`s degree (e.g. MA, MS, MEd)       | 0.068966     | 0.185714  | 2.578479e-02 | 0.237220          | False     |
| Religion_None                                      | 0.344828     | 0.200000  | 4.493016e-02 | 0.295255          | False     |
| Age                                                | 40.528736    | 37.314286 | 4.277763e-02 | 0.295255          | False     |
| Religion_Christian (including Church of England... | 0.620690     | 0.742857  | 1.055402e-01 | 0.582471          | False     |
| Employment_Student                                 | 0.000000     | 0.028571  | 1.140053e-01 | 0.582471          | False     |
| Political_Belief_Liberal                           | 0.448276     | 0.571429  | 1.266240e-01 | 0.582471          | False     |

*Balance Table with Adjusted P-Values for 5-Point Difference*
| Variable                                           | No Advantage | Advantage | p-value  | corrected p-value | reject H0 |
|----------------------------------------------------|--------------|-----------|----------|-------------------|-----------|
| Advantage                                          | 82.000000    | 74.000000 | 0.000000 | 0.000000          | True      |
| Political_Belief_Conservative                      | 0.426829     | 0.243243  | 0.015478 | 0.363723          | False     |
| Political_Belief_Liberal                           | 0.365854     | 0.500000  | 0.092116 | 0.766362          | False     |
| Religion_Muslim                                    | 0.036585     | 0.000000  | 0.097833 | 0.766362          | False     |
| Religion_Buddhist                                  | 0.036585     | 0.000000  | 0.097833 | 0.766362          | False     |
| Employment_Self-employed                           | 0.134146     | 0.054054  | 0.091295 | 0.766362          | False     |
| Cause_Of_Loss_The competition was unfair (You h... | 0.060976     | 0.135135  | 0.118174 | 0.793455          | False     |
| Religion_Jewish                                    | 0.000000     | 0.027027  | 0.135785 | 0.797735          | False     |
| Education_Other                                    | 0.012195     | 0.040541  | 0.266272 | 0.829945          | False     |
| Employment_Employed part-time (less than 40 hou... | 0.024390     | 0.054054  | 0.339215 | 0.829945          | False     |

*Balance Table with Adjusted P-Values for Combined Data*
| Variable                                           | No Advantage | Advantage  | p-value      | corrected p-value | reject H0 |
|----------------------------------------------------|--------------|------------|--------------|-------------------|-----------|
| Advantage                                          | 169.000000   | 144.000000 | 4.247233e-01 | 0.000000          | True      |
| Cause_Of_Loss_The competition was unfair (You h... | 0.047337     | 0.236111   | 7.025870e-07 | 0.000018          | True      |
| Cause_Of_Loss_Bad luck                             | 0.171598     | 0.069444   | 6.279959e-03 | 0.104666          | False     |
| Political_Belief_Liberal                           | 0.408284     | 0.534722   | 2.542872e-02 | 0.256427          | False     |
| Age                                                | 39.928994    | 37.270833  | 2.564272e-02 | 0.256427          | False     |
| Education_High school degree or equivalent         | 0.224852     | 0.131944   | 3.384712e-02 | 0.282059          | False     |
| Political_Belief_Conservative                      | 0.343195     | 0.243056   | 5.357724e-02 | 0.382695          | False     |
| Cause_Of_Loss_Differences between you and your ... | 0.526627     | 0.423611   | 6.939746e-02 | 0.433734          | False     |
| Education_Master`s degree (e.g. MA, MS, MEd)       | 0.165680     | 0.243056   | 8.936955e-02 | 0.449997          | False     |
| Employment_Self-employed                           | 0.118343     | 0.062500   | 8.999943e-02 | 0.449997          | False     |
