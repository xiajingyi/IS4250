    ## Warning: package 'MASS' was built under R version 3.2.4

    ## Warning: package 'effects' was built under R version 3.2.4

    ## Warning: package 'vcd' was built under R version 3.2.4

    ## Warning: package 'mlogit' was built under R version 3.2.4

    ## Warning: package 'maxLik' was built under R version 3.2.4

    ## Warning: package 'miscTools' was built under R version 3.2.4

    ## Warning: package 'nnet' was built under R version 3.2.4

    ## 
    ## Call:
    ## glm(formula = LifestyleScoreCategory ~ AGE1 + OCCUPATION1 + WORKPLACESCALE1 + 
    ##     EDUCATIONATTAINMENT1 + MARITALSTATUS1 + ACCOMPANYINGCHILDREN1 + 
    ##     SALARY1 + NUMBEROFCITIESRESIDEDIN1 + DAILYWORKINGHOURS1 + 
    ##     WEEKLYWORKINGDAYS1 + TYPEOFRESIDENCE1 + BMI1 + MENTALHEALTH1, 
    ##     data = Male)
    ## 
    ## Deviance Residuals: 
    ##      Min        1Q    Median        3Q       Max  
    ## -1.51054  -0.35541   0.05747   0.25828   1.30052  
    ## 
    ## Coefficients:
    ##                                                   Estimate Std. Error
    ## (Intercept)                                       1.818357   0.134533
    ## AGE1>32                                           0.075548   0.029329
    ## OCCUPATION1Construction                           0.061433   0.039592
    ## OCCUPATION1Hospitality                            0.152360   0.059894
    ## OCCUPATION1Domestic services                     -0.044515   0.058494
    ## OCCUPATION1Small Business                         0.074207   0.049767
    ## OCCUPATION1Recreation/Leisures                    0.328535   0.053973
    ## WORKPLACESCALE1Moderate                          -0.004100   0.032142
    ## WORKPLACESCALE1Small                              0.115605   0.035593
    ## EDUCATIONATTAINMENT1Junior high school            0.048573   0.038026
    ## EDUCATIONATTAINMENT1High school                   0.104891   0.043263
    ## EDUCATIONATTAINMENT1College                       0.006557   0.060308
    ## MARITALSTATUS1Single                              0.059163   0.050465
    ## MARITALSTATUS1Cohabitating                        0.126653   0.111801
    ## MARITALSTATUS1Divorced or widowed                 0.100202   0.119432
    ## ACCOMPANYINGCHILDREN1Cohabitating children       -0.009185   0.051080
    ## ACCOMPANYINGCHILDREN1Children residing elsewhere  0.003431   0.049214
    ## SALARY11500-2500RMB                               0.024775   0.054414
    ## SALARY12500-3500RMB                               0.053686   0.054518
    ## SALARY1>=3500RMB                                  0.124165   0.059376
    ## NUMBEROFCITIESRESIDEDIN1>=3                      -0.003589   0.026819
    ## DAILYWORKINGHOURS1<8                             -0.026661   0.154712
    ## DAILYWORKINGHOURS18-11                            0.002697   0.030943
    ## DAILYWORKINGHOURS1>=11                            0.109729   0.039474
    ## WEEKLYWORKINGDAYS15                              -0.153728   0.090779
    ## WEEKLYWORKINGDAYS16                              -0.048398   0.088742
    ## WEEKLYWORKINGDAYS17                              -0.112826   0.089954
    ## TYPEOFRESIDENCE1Renting with others               0.007519   0.042985
    ## TYPEOFRESIDENCE1Renting as a family               0.021140   0.034734
    ## TYPEOFRESIDENCE1Renting alone                     0.095243   0.039562
    ## TYPEOFRESIDENCE1Owning a living place            -0.089238   0.067670
    ## BMI1NOrmal Weight                                -0.049054   0.065387
    ## BMI1Overweight                                   -0.053937   0.068110
    ## MENTALHEALTH1Abnormal                             0.358926   0.039953
    ##                                                  t value Pr(>|t|)    
    ## (Intercept)                                       13.516  < 2e-16 ***
    ## AGE1>32                                            2.576  0.01005 *  
    ## OCCUPATION1Construction                            1.552  0.12085    
    ## OCCUPATION1Hospitality                             2.544  0.01102 *  
    ## OCCUPATION1Domestic services                      -0.761  0.44672    
    ## OCCUPATION1Small Business                          1.491  0.13605    
    ## OCCUPATION1Recreation/Leisures                     6.087 1.31e-09 ***
    ## WORKPLACESCALE1Moderate                           -0.128  0.89851    
    ## WORKPLACESCALE1Small                               3.248  0.00118 ** 
    ## EDUCATIONATTAINMENT1Junior high school             1.277  0.20159    
    ## EDUCATIONATTAINMENT1High school                    2.425  0.01539 *  
    ## EDUCATIONATTAINMENT1College                        0.109  0.91343    
    ## MARITALSTATUS1Single                               1.172  0.24115    
    ## MARITALSTATUS1Cohabitating                         1.133  0.25738    
    ## MARITALSTATUS1Divorced or widowed                  0.839  0.40155    
    ## ACCOMPANYINGCHILDREN1Cohabitating children        -0.180  0.85731    
    ## ACCOMPANYINGCHILDREN1Children residing elsewhere   0.070  0.94442    
    ## SALARY11500-2500RMB                                0.455  0.64892    
    ## SALARY12500-3500RMB                                0.985  0.32483    
    ## SALARY1>=3500RMB                                   2.091  0.03660 *  
    ## NUMBEROFCITIESRESIDEDIN1>=3                       -0.134  0.89355    
    ## DAILYWORKINGHOURS1<8                              -0.172  0.86319    
    ## DAILYWORKINGHOURS18-11                             0.087  0.93054    
    ## DAILYWORKINGHOURS1>=11                             2.780  0.00548 ** 
    ## WEEKLYWORKINGDAYS15                               -1.693  0.09049 .  
    ## WEEKLYWORKINGDAYS16                               -0.545  0.58554    
    ## WEEKLYWORKINGDAYS17                               -1.254  0.20985    
    ## TYPEOFRESIDENCE1Renting with others                0.175  0.86114    
    ## TYPEOFRESIDENCE1Renting as a family                0.609  0.54284    
    ## TYPEOFRESIDENCE1Renting alone                      2.407  0.01613 *  
    ## TYPEOFRESIDENCE1Owning a living place             -1.319  0.18737    
    ## BMI1NOrmal Weight                                 -0.750  0.45319    
    ## BMI1Overweight                                    -0.792  0.42848    
    ## MENTALHEALTH1Abnormal                              8.984  < 2e-16 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## (Dispersion parameter for gaussian family taken to be 0.4152831)
    ## 
    ##     Null deviance: 1266.9  on 2810  degrees of freedom
    ## Residual deviance: 1153.2  on 2777  degrees of freedom
    ## AIC: 5542.8
    ## 
    ## Number of Fisher Scoring iterations: 2

    ##                                                        COR     2.5 %
    ## (Intercept)                                      6.1617266 4.7335559
    ## AGE1>32                                          1.0784750 1.0182286
    ## OCCUPATION1Construction                          1.0633597 0.9839652
    ## OCCUPATION1Hospitality                           1.1645792 1.0355880
    ## OCCUPATION1Domestic services                     0.9564617 0.8528591
    ## OCCUPATION1Small Business                        1.0770292 0.9769358
    ## OCCUPATION1Recreation/Leisures                   1.3889312 1.2495065
    ## WORKPLACESCALE1Moderate                          0.9959086 0.9351049
    ## WORKPLACESCALE1Small                             1.1225529 1.0469114
    ## EDUCATIONATTAINMENT1Junior high school           1.0497715 0.9743768
    ## EDUCATIONATTAINMENT1High school                  1.1105896 1.0203014
    ## EDUCATIONATTAINMENT1College                      1.0065781 0.8943613
    ## MARITALSTATUS1Single                             1.0609483 0.9610333
    ## MARITALSTATUS1Cohabitating                       1.1350227 0.9116742
    ## MARITALSTATUS1Divorced or widowed                1.1053947 0.8746945
    ## ACCOMPANYINGCHILDREN1Cohabitating children       0.9908572 0.8964624
    ## ACCOMPANYINGCHILDREN1Children residing elsewhere 1.0034372 0.9111692
    ## SALARY11500-2500RMB                              1.0250848 0.9213887
    ## SALARY12500-3500RMB                              1.0551536 0.9482223
    ## SALARY1>=3500RMB                                 1.1322030 1.0078217
    ## NUMBEROFCITIESRESIDEDIN1>=3                      0.9964174 0.9453945
    ## DAILYWORKINGHOURS1<8                             0.9736909 0.7190023
    ## DAILYWORKINGHOURS18-11                           1.0027011 0.9436974
    ## DAILYWORKINGHOURS1>=11                           1.1159756 1.0328911
    ## WEEKLYWORKINGDAYS15                              0.8575056 0.7177371
    ## WEEKLYWORKINGDAYS16                              0.9527549 0.8006524
    ## WEEKLYWORKINGDAYS17                              0.8933057 0.7489133
    ## TYPEOFRESIDENCE1Renting with others              1.0075478 0.9261411
    ## TYPEOFRESIDENCE1Renting as a family              1.0213645 0.9541458
    ## TYPEOFRESIDENCE1Renting alone                    1.0999264 1.0178601
    ## TYPEOFRESIDENCE1Owning a living place            0.9146279 0.8010206
    ## BMI1NOrmal Weight                                0.9521297 0.8376030
    ## BMI1Overweight                                   0.9474914 0.8290866
    ## MENTALHEALTH1Abnormal                            1.4317911 1.3239500
    ##                                                    97.5 %
    ## (Intercept)                                      8.020794
    ## AGE1>32                                          1.142286
    ## OCCUPATION1Construction                          1.149160
    ## OCCUPATION1Hospitality                           1.309637
    ## OCCUPATION1Domestic services                     1.072649
    ## OCCUPATION1Small Business                        1.187378
    ## OCCUPATION1Recreation/Leisures                   1.543913
    ## WORKPLACESCALE1Moderate                          1.060666
    ## WORKPLACESCALE1Small                             1.203660
    ## EDUCATIONATTAINMENT1Junior high school           1.131000
    ## EDUCATIONATTAINMENT1High school                  1.208868
    ## EDUCATIONATTAINMENT1College                      1.132875
    ## MARITALSTATUS1Single                             1.171251
    ## MARITALSTATUS1Cohabitating                       1.413089
    ## MARITALSTATUS1Divorced or widowed                1.396942
    ## ACCOMPANYINGCHILDREN1Cohabitating children       1.095192
    ## ACCOMPANYINGCHILDREN1Children residing elsewhere 1.105049
    ## SALARY11500-2500RMB                              1.140451
    ## SALARY12500-3500RMB                              1.174144
    ## SALARY1>=3500RMB                                 1.271935
    ## NUMBEROFCITIESRESIDEDIN1>=3                      1.050194
    ## DAILYWORKINGHOURS1<8                             1.318597
    ## DAILYWORKINGHOURS18-11                           1.065394
    ## DAILYWORKINGHOURS1>=11                           1.205743
    ## WEEKLYWORKINGDAYS15                              1.024492
    ## WEEKLYWORKINGDAYS16                              1.133753
    ## WEEKLYWORKINGDAYS17                              1.065537
    ## TYPEOFRESIDENCE1Renting with others              1.096110
    ## TYPEOFRESIDENCE1Renting as a family              1.093319
    ## TYPEOFRESIDENCE1Renting alone                    1.188609
    ## TYPEOFRESIDENCE1Owning a living place            1.044348
    ## BMI1NOrmal Weight                                1.082316
    ## BMI1Overweight                                   1.082806
    ## MENTALHEALTH1Abnormal                            1.548416

    ## 
    ## Call:
    ## glm(formula = LifestyleScoreCategory ~ AGE2 + OCCUPATION2 + WORKPLACESCALE2 + 
    ##     EDUCATIONATTAINMENT2 + MARITALSTATUS2 + ACCOMPANYINGCHILDREN2 + 
    ##     SALARY2 + NUMBEROFCITIESRESIDEDIN2 + DAILYWORKINGHOURS2 + 
    ##     WEEKLYWORKINGDAYS2 + TYPEOFRESIDENCE2 + BMI2 + MENTALHEALTH2, 
    ##     data = Female)
    ## 
    ## Deviance Residuals: 
    ##     Min       1Q   Median       3Q      Max  
    ## -1.6101  -0.4576  -0.2443   0.5101   1.7934  
    ## 
    ## Coefficients:
    ##                                                   Estimate Std. Error
    ## (Intercept)                                       1.335276   0.107772
    ## AGE2>32                                           0.013070   0.029462
    ## OCCUPATION2Construction                          -0.022646   0.072997
    ## OCCUPATION2Hospitality                            0.146563   0.047017
    ## OCCUPATION2Domestic services                      0.108541   0.039096
    ## OCCUPATION2Small Business                         0.098444   0.043165
    ## OCCUPATION2Recreation/Leisures                    0.511222   0.045978
    ## WORKPLACESCALE2Moderate                           0.010878   0.035235
    ## WORKPLACESCALE2Small                              0.051549   0.034353
    ## EDUCATIONATTAINMENT2Junior high school           -0.013732   0.032164
    ## EDUCATIONATTAINMENT2High school                  -0.006093   0.040777
    ## EDUCATIONATTAINMENT2College                      -0.063977   0.064288
    ## MARITALSTATUS2Single                              0.193553   0.050920
    ## MARITALSTATUS2Cohabitating                        0.099820   0.098913
    ## MARITALSTATUS2Divorced or widowed                 0.103567   0.145365
    ## ACCOMPANYINGCHILDREN2Cohabitating children       -0.014140   0.050200
    ## ACCOMPANYINGCHILDREN2Children residing elsewhere -0.036883   0.048885
    ## SALARY21500-2500RMB                              -0.084000   0.038728
    ## SALARY22500-3500RMB                              -0.070769   0.044034
    ## SALARY2>=3500RMB                                  0.149137   0.057864
    ## NUMBEROFCITIESRESIDEDIN2>=3                       0.085063   0.031614
    ## DAILYWORKINGHOURS2<8                              0.044522   0.080925
    ## DAILYWORKINGHOURS28-11                            0.074579   0.032110
    ## DAILYWORKINGHOURS2>=11                            0.046225   0.033988
    ## WEEKLYWORKINGDAYS25                              -0.029190   0.071239
    ## WEEKLYWORKINGDAYS26                               0.002829   0.068111
    ## WEEKLYWORKINGDAYS27                               0.041215   0.067977
    ## TYPEOFRESIDENCE2Renting with others               0.067486   0.047383
    ## TYPEOFRESIDENCE2Renting as a family              -0.014593   0.036468
    ## TYPEOFRESIDENCE2Renting alone                     0.095862   0.045538
    ## TYPEOFRESIDENCE2Owning a living place            -0.113797   0.067525
    ## BMI2NOrmal Weight                                 0.049758   0.043679
    ## BMI2Overweight                                    0.031238   0.051197
    ## MENTALHEALTH2Abnormal                             0.323254   0.038272
    ##                                                  t value Pr(>|t|)    
    ## (Intercept)                                       12.390  < 2e-16 ***
    ## AGE2>32                                            0.444 0.657353    
    ## OCCUPATION2Construction                           -0.310 0.756406    
    ## OCCUPATION2Hospitality                             3.117 0.001845 ** 
    ## OCCUPATION2Domestic services                       2.776 0.005538 ** 
    ## OCCUPATION2Small Business                          2.281 0.022649 *  
    ## OCCUPATION2Recreation/Leisures                    11.119  < 2e-16 ***
    ## WORKPLACESCALE2Moderate                            0.309 0.757562    
    ## WORKPLACESCALE2Small                               1.501 0.133589    
    ## EDUCATIONATTAINMENT2Junior high school            -0.427 0.669452    
    ## EDUCATIONATTAINMENT2High school                   -0.149 0.881235    
    ## EDUCATIONATTAINMENT2College                       -0.995 0.319746    
    ## MARITALSTATUS2Single                               3.801 0.000147 ***
    ## MARITALSTATUS2Cohabitating                         1.009 0.312985    
    ## MARITALSTATUS2Divorced or widowed                  0.712 0.476241    
    ## ACCOMPANYINGCHILDREN2Cohabitating children        -0.282 0.778219    
    ## ACCOMPANYINGCHILDREN2Children residing elsewhere  -0.754 0.450623    
    ## SALARY21500-2500RMB                               -2.169 0.030175 *  
    ## SALARY22500-3500RMB                               -1.607 0.108142    
    ## SALARY2>=3500RMB                                   2.577 0.010009 *  
    ## NUMBEROFCITIESRESIDEDIN2>=3                        2.691 0.007176 ** 
    ## DAILYWORKINGHOURS2<8                               0.550 0.582251    
    ## DAILYWORKINGHOURS28-11                             2.323 0.020276 *  
    ## DAILYWORKINGHOURS2>=11                             1.360 0.173934    
    ## WEEKLYWORKINGDAYS25                               -0.410 0.682019    
    ## WEEKLYWORKINGDAYS26                                0.042 0.966874    
    ## WEEKLYWORKINGDAYS27                                0.606 0.544361    
    ## TYPEOFRESIDENCE2Renting with others                1.424 0.154483    
    ## TYPEOFRESIDENCE2Renting as a family               -0.400 0.689065    
    ## TYPEOFRESIDENCE2Renting alone                      2.105 0.035378 *  
    ## TYPEOFRESIDENCE2Owning a living place             -1.685 0.092059 .  
    ## BMI2NOrmal Weight                                  1.139 0.254735    
    ## BMI2Overweight                                     0.610 0.541814    
    ## MENTALHEALTH2Abnormal                              8.446  < 2e-16 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## (Dispersion parameter for gaussian family taken to be 0.3678274)
    ## 
    ##     Null deviance: 1221.0  on 2672  degrees of freedom
    ## Residual deviance:  970.7  on 2639  degrees of freedom
    ## AIC: 4948
    ## 
    ## Number of Fisher Scoring iterations: 2

    ##                                                        COR     2.5 %
    ## (Intercept)                                      3.8010436 3.0772833
    ## AGE2>32                                          1.0131557 0.9563088
    ## OCCUPATION2Construction                          0.9776081 0.8472846
    ## OCCUPATION2Hospitality                           1.1578477 1.0559184
    ## OCCUPATION2Domestic services                     1.1146509 1.0324288
    ## OCCUPATION2Small Business                        1.1034523 1.0139383
    ## OCCUPATION2Recreation/Leisures                   1.6673280 1.5236466
    ## WORKPLACESCALE2Moderate                          1.0109370 0.9434784
    ## WORKPLACESCALE2Small                             1.0529005 0.9843420
    ## EDUCATIONATTAINMENT2Junior high school           0.9863617 0.9261014
    ## EDUCATIONATTAINMENT2High school                  0.9939257 0.9175817
    ## EDUCATIONATTAINMENT2College                      0.9380265 0.8269767
    ## MARITALSTATUS2Single                             1.2135538 1.0982864
    ## MARITALSTATUS2Cohabitating                       1.1049719 0.9102412
    ## MARITALSTATUS2Divorced or widowed                1.1091199 0.8341497
    ## ACCOMPANYINGCHILDREN2Cohabitating children       0.9859597 0.8935706
    ## ACCOMPANYINGCHILDREN2Children residing elsewhere 0.9637888 0.8757314
    ## SALARY21500-2500RMB                              0.9194311 0.8522234
    ## SALARY22500-3500RMB                              0.9316770 0.8546405
    ## SALARY2>=3500RMB                                 1.1608318 1.0363716
    ## NUMBEROFCITIESRESIDEDIN2>=3                      1.0887861 1.0233697
    ## DAILYWORKINGHOURS2<8                             1.0455280 0.8921802
    ## DAILYWORKINGHOURS28-11                           1.0774304 1.0117125
    ## DAILYWORKINGHOURS2>=11                           1.0473104 0.9798161
    ## WEEKLYWORKINGDAYS25                              0.9712315 0.8446647
    ## WEEKLYWORKINGDAYS26                              1.0028328 0.8775109
    ## WEEKLYWORKINGDAYS27                              1.0420765 0.9120888
    ## TYPEOFRESIDENCE2Renting with others              1.0698155 0.9749374
    ## TYPEOFRESIDENCE2Renting as a family              0.9855126 0.9175305
    ## TYPEOFRESIDENCE2Renting alone                    1.1006069 1.0066304
    ## TYPEOFRESIDENCE2Owning a living place            0.8924395 0.7818102
    ## BMI2NOrmal Weight                                1.0510165 0.9647837
    ## BMI2Overweight                                   1.0317312 0.9332270
    ## MENTALHEALTH2Abnormal                            1.3816167 1.2817718
    ##                                                     97.5 %
    ## (Intercept)                                      4.6950284
    ## AGE2>32                                          1.0733818
    ## OCCUPATION2Construction                          1.1279770
    ## OCCUPATION2Hospitality                           1.2696164
    ## OCCUPATION2Domestic services                     1.2034212
    ## OCCUPATION2Small Business                        1.2008690
    ## OCCUPATION2Recreation/Leisures                   1.8245586
    ## WORKPLACESCALE2Moderate                          1.0832189
    ## WORKPLACESCALE2Small                             1.1262341
    ## EDUCATIONATTAINMENT2Junior high school           1.0505431
    ## EDUCATIONATTAINMENT2High school                  1.0766217
    ## EDUCATIONATTAINMENT2College                      1.0639885
    ## MARITALSTATUS2Single                             1.3409187
    ## MARITALSTATUS2Cohabitating                       1.3413620
    ## MARITALSTATUS2Divorced or widowed                1.4747317
    ## ACCOMPANYINGCHILDREN2Cohabitating children       1.0879011
    ## ACCOMPANYINGCHILDREN2Children residing elsewhere 1.0607005
    ## SALARY21500-2500RMB                              0.9919389
    ## SALARY22500-3500RMB                              1.0156574
    ## SALARY2>=3500RMB                                 1.3002386
    ## NUMBEROFCITIESRESIDEDIN2>=3                      1.1583840
    ## DAILYWORKINGHOURS2<8                             1.2252334
    ## DAILYWORKINGHOURS28-11                           1.1474171
    ## DAILYWORKINGHOURS2>=11                           1.1194540
    ## WEEKLYWORKINGDAYS25                              1.1167634
    ## WEEKLYWORKINGDAYS26                              1.1460527
    ## WEEKLYWORKINGDAYS27                              1.1905897
    ## TYPEOFRESIDENCE2Renting with others              1.1739268
    ## TYPEOFRESIDENCE2Renting as a family              1.0585317
    ## TYPEOFRESIDENCE2Renting alone                    1.2033567
    ## TYPEOFRESIDENCE2Owning a living place            1.0187233
    ## BMI2NOrmal Weight                                1.1449568
    ## BMI2Overweight                                   1.1406326
    ## MENTALHEALTH2Abnormal                            1.4892392

    ## [1] TRUE

    ## Call:
    ## polr(formula = Score ~ Occupation, data = Male, weights = N, 
    ##     method = "logistic")
    ## 
    ## Coefficients:
    ##                      Value Std. Error t value
    ## Occupation2Moderate -1.425     0.1280 -11.133
    ## Occupation3Small    -1.089     0.1219  -8.933
    ## 
    ## Intercepts:
    ##                              Value    Std. Error t value 
    ## Healthy|Relatively Healthy    -1.3372   0.1117   -11.9669
    ## Relatively Healthy|Unhealthy   0.9681   0.1089     8.8903
    ## 
    ## Residual Deviance: 4365.54 
    ## AIC: 4373.54

    ##                         2.5 %    97.5 %
    ## Occupation2Moderate 0.1868933 0.3087360
    ## Occupation3Small    0.2648106 0.4270955

    ##                                   Value Std. Error    t value      p value
    ## Occupation2Moderate          -1.4252998  0.1280223 -11.133219 8.645606e-29
    ## Occupation3Small             -1.0889654  0.1219090  -8.932610 4.160757e-19
    ## Healthy|Relatively Healthy   -1.3371541  0.1117380 -11.966873 5.298833e-33
    ## Relatively Healthy|Unhealthy  0.9681238  0.1088968   8.890284 6.095274e-19

    ##                         2.5 %     97.5 %
    ## Occupation2Moderate -1.676219 -1.1743808
    ## Occupation3Small    -1.327903 -0.8500282

    ## Occupation2Moderate    Occupation3Small 
    ##           0.2404364           0.3365645

    ##                           COR     2.5 %    97.5 %
    ## Occupation2Moderate 0.2404364 0.1868933 0.3087360
    ## Occupation3Small    0.3365645 0.2648106 0.4270955
