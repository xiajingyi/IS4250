    ## Warning: package 'MASS' was built under R version 3.2.4

    ## Warning: package 'effects' was built under R version 3.2.4

    ## Warning: package 'vcd' was built under R version 3.2.4

    ## Warning: package 'mlogit' was built under R version 3.2.4

    ## Warning: package 'maxLik' was built under R version 3.2.4

    ## Warning: package 'miscTools' was built under R version 3.2.4

    ## Warning: package 'nnet' was built under R version 3.2.4

    ## 
    ## Call:
    ## glm(formula = LifestyleScoreCategory ~ AGE + OCCUPATION + WORKPLACESCALE + 
    ##     EDUCATIONATTAINMENT + MARITALSTATUS + ACCOMPANYINGCHILDREN + 
    ##     SALARY + NUMBEROFCITIESRESIDEDIN + DAILYWORKINGHOURS + WEEKLYWORKINGDAYS + 
    ##     TYPEOFRESIDENCE + BMI + MENTALHEALTH, data = Female)
    ## 
    ## Deviance Residuals: 
    ##     Min       1Q   Median       3Q      Max  
    ## -1.5984  -0.4616  -0.2455   0.5110   1.7953  
    ## 
    ## Coefficients:
    ##                                                  Estimate Std. Error
    ## (Intercept)                                      1.320702   0.145745
    ## AGE>32                                           0.006449   0.029797
    ## OCCUPATIONConstruction                          -0.021987   0.072999
    ## OCCUPATIONHospitality                            0.147513   0.047052
    ## OCCUPATIONDomestic services                      0.108042   0.039121
    ## OCCUPATIONSmall Business                         0.099319   0.043162
    ## OCCUPATIONRecreation/Leisures                    0.510557   0.045997
    ## WORKPLACESCALEModerate                           0.009764   0.035228
    ## WORKPLACESCALESmall                              0.049802   0.034366
    ## EDUCATIONATTAINMENTJunior high school           -0.014356   0.032163
    ## EDUCATIONATTAINMENTHigh school                  -0.008373   0.040723
    ## EDUCATIONATTAINMENTCollege                      -0.065916   0.064264
    ## MARITALSTATUSSingle                              0.189972   0.050819
    ## MARITALSTATUSCohabitating                        0.097258   0.098883
    ## MARITALSTATUSDivorced or widowed                 0.096586   0.145273
    ## ACCOMPANYINGCHILDRENCohabitating children       -0.014943   0.050197
    ## ACCOMPANYINGCHILDRENChildren residing elsewhere -0.036181   0.048858
    ## SALARY1500-2500RMB                              -0.081510   0.038732
    ## SALARY2500-3500RMB                              -0.066948   0.044016
    ## SALARY>=3500RMB                                  0.151349   0.057936
    ## NUMBEROFCITIESRESIDEDIN>=3                       0.084115   0.031586
    ## DAILYWORKINGHOURS<8                              0.046031   0.080927
    ## DAILYWORKINGHOURS8-11                            0.073464   0.032144
    ## DAILYWORKINGHOURS>=11                            0.046271   0.033985
    ## WEEKLYWORKINGDAYS5                              -0.031169   0.071234
    ## WEEKLYWORKINGDAYS6                               0.001739   0.068115
    ## WEEKLYWORKINGDAYS7                               0.036078   0.067901
    ## TYPEOFRESIDENCERenting with others               0.071352   0.047354
    ## TYPEOFRESIDENCERenting as a family              -0.012920   0.036462
    ## TYPEOFRESIDENCERenting alone                     0.097257   0.045521
    ## TYPEOFRESIDENCEOwning a living place            -0.111225   0.067534
    ## BMI                                              0.002772   0.004965
    ## MENTALHEALTHAbnormal                             0.323680   0.038269
    ##                                                 t value Pr(>|t|)    
    ## (Intercept)                                       9.062  < 2e-16 ***
    ## AGE>32                                            0.216 0.828677    
    ## OCCUPATIONConstruction                           -0.301 0.763289    
    ## OCCUPATIONHospitality                             3.135 0.001737 ** 
    ## OCCUPATIONDomestic services                       2.762 0.005789 ** 
    ## OCCUPATIONSmall Business                          2.301 0.021466 *  
    ## OCCUPATIONRecreation/Leisures                    11.100  < 2e-16 ***
    ## WORKPLACESCALEModerate                            0.277 0.781681    
    ## WORKPLACESCALESmall                               1.449 0.147408    
    ## EDUCATIONATTAINMENTJunior high school            -0.446 0.655379    
    ## EDUCATIONATTAINMENTHigh school                   -0.206 0.837105    
    ## EDUCATIONATTAINMENTCollege                       -1.026 0.305126    
    ## MARITALSTATUSSingle                               3.738 0.000189 ***
    ## MARITALSTATUSCohabitating                         0.984 0.325420    
    ## MARITALSTATUSDivorced or widowed                  0.665 0.506199    
    ## ACCOMPANYINGCHILDRENCohabitating children        -0.298 0.765961    
    ## ACCOMPANYINGCHILDRENChildren residing elsewhere  -0.741 0.459043    
    ## SALARY1500-2500RMB                               -2.104 0.035434 *  
    ## SALARY2500-3500RMB                               -1.521 0.128381    
    ## SALARY>=3500RMB                                   2.612 0.009044 ** 
    ## NUMBEROFCITIESRESIDEDIN>=3                        2.663 0.007790 ** 
    ## DAILYWORKINGHOURS<8                               0.569 0.569545    
    ## DAILYWORKINGHOURS8-11                             2.285 0.022364 *  
    ## DAILYWORKINGHOURS>=11                             1.362 0.173462    
    ## WEEKLYWORKINGDAYS5                               -0.438 0.661746    
    ## WEEKLYWORKINGDAYS6                                0.026 0.979630    
    ## WEEKLYWORKINGDAYS7                                0.531 0.595229    
    ## TYPEOFRESIDENCERenting with others                1.507 0.131994    
    ## TYPEOFRESIDENCERenting as a family               -0.354 0.723106    
    ## TYPEOFRESIDENCERenting alone                      2.137 0.032726 *  
    ## TYPEOFRESIDENCEOwning a living place             -1.647 0.099687 .  
    ## BMI                                               0.558 0.576674    
    ## MENTALHEALTHAbnormal                              8.458  < 2e-16 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## (Dispersion parameter for gaussian family taken to be 0.3678571)
    ## 
    ##     Null deviance: 1220.97  on 2672  degrees of freedom
    ## Residual deviance:  971.14  on 2640  degrees of freedom
    ## AIC: 4947.3
    ## 
    ## Number of Fisher Scoring iterations: 2

    ##                                                       COR     2.5 %
    ## (Intercept)                                     3.7460504 2.8152369
    ## AGE>32                                          1.0064696 0.9493733
    ## OCCUPATIONConstruction                          0.9782531 0.8478416
    ## OCCUPATIONHospitality                           1.1589480 1.0568502
    ## OCCUPATIONDomestic services                     1.1140951 1.0318646
    ## OCCUPATIONSmall Business                        1.1044184 1.0148310
    ## OCCUPATIONRecreation/Leisures                   1.6662198 1.5225766
    ## WORKPLACESCALEModerate                          1.0098114 0.9424415
    ## WORKPLACESCALESmall                             1.0510632 0.9825993
    ## EDUCATIONATTAINMENTJunior high school           0.9857465 0.9255249
    ## EDUCATIONATTAINMENTHigh school                  0.9916615 0.9155868
    ## EDUCATIONATTAINMENTCollege                      0.9362098 0.8254134
    ## MARITALSTATUSSingle                             1.2092159 1.0945769
    ## MARITALSTATUSCohabitating                       1.1021445 0.9079649
    ## MARITALSTATUSDivorced or widowed                1.1014042 0.8284959
    ## ACCOMPANYINGCHILDRENCohabitating children       0.9851679 0.8928584
    ## ACCOMPANYINGCHILDRENChildren residing elsewhere 0.9644659 0.8763932
    ## SALARY1500-2500RMB                              0.9217232 0.8543413
    ## SALARY2500-3500RMB                              0.9352438 0.8579428
    ## SALARY>=3500RMB                                 1.1634020 1.0385190
    ## NUMBEROFCITIESRESIDEDIN>=3                      1.0877542 1.0224565
    ## DAILYWORKINGHOURS<8                             1.0471064 0.8935233
    ## DAILYWORKINGHOURS8-11                           1.0762294 1.0105180
    ## DAILYWORKINGHOURS>=11                           1.0473582 0.9798680
    ## WEEKLYWORKINGDAYS5                              0.9693121 0.8430031
    ## WEEKLYWORKINGDAYS6                              1.0017409 0.8765490
    ## WEEKLYWORKINGDAYS7                              1.0367371 0.9075515
    ## TYPEOFRESIDENCERenting with others              1.0739587 0.9787671
    ## TYPEOFRESIDENCERenting as a family              0.9871630 0.9190787
    ## TYPEOFRESIDENCERenting alone                    1.1021436 1.0080708
    ## TYPEOFRESIDENCEOwning a living place            0.8947370 0.7838090
    ## BMI                                             1.0027759 0.9930651
    ## MENTALHEALTHAbnormal                            1.3822045 1.2823245
    ##                                                    97.5 %
    ## (Intercept)                                     4.9846225
    ## AGE>32                                          1.0669998
    ## OCCUPATIONConstruction                          1.1287238
    ## OCCUPATIONHospitality                           1.2709092
    ## OCCUPATIONDomestic services                     1.2028786
    ## OCCUPATIONSmall Business                        1.2019145
    ## OCCUPATIONRecreation/Leisures                   1.8234146
    ## WORKPLACESCALEModerate                          1.0819972
    ## WORKPLACESCALESmall                             1.1242974
    ## EDUCATIONATTAINMENTJunior high school           1.0498867
    ## EDUCATIONATTAINMENTHigh school                  1.0740571
    ## EDUCATIONATTAINMENTCollege                      1.0618785
    ## MARITALSTATUSSingle                             1.3358615
    ## MARITALSTATUSCohabitating                       1.3378518
    ## MARITALSTATUSDivorced or widowed                1.4642090
    ## ACCOMPANYINGCHILDRENCohabitating children       1.0870209
    ## ACCOMPANYINGCHILDRENChildren residing elsewhere 1.0613894
    ## SALARY1500-2500RMB                              0.9944196
    ## SALARY2500-3500RMB                              1.0195096
    ## SALARY>=3500RMB                                 1.3033025
    ## NUMBEROFCITIESRESIDEDIN>=3                      1.1572221
    ## DAILYWORKINGHOURS<8                             1.2270882
    ## DAILYWORKINGHOURS8-11                           1.1462138
    ## DAILYWORKINGHOURS>=11                           1.1194970
    ## WEEKLYWORKINGDAYS5                              1.1145462
    ## WEEKLYWORKINGDAYS6                              1.1448131
    ## WEEKLYWORKINGDAYS7                              1.1843118
    ## TYPEOFRESIDENCERenting with others              1.1784083
    ## TYPEOFRESIDENCERenting as a family              1.0602909
    ## TYPEOFRESIDENCERenting alone                    1.2049953
    ## TYPEOFRESIDENCEOwning a living place            1.0213642
    ## BMI                                             1.0125816
    ## MENTALHEALTHAbnormal                            1.4898642

    ## 
    ## Call:
    ## glm(formula = LifestyleScoreCategory ~ Marry, data = Female)
    ## 
    ## Deviance Residuals: 
    ##     Min       1Q   Median       3Q      Max  
    ## -1.0851  -0.4881  -0.4881   0.5119   1.5119  
    ## 
    ## Coefficients:
    ##             Estimate Std. Error t value Pr(>|t|)    
    ## (Intercept)  1.48811    0.01470 101.207  < 2e-16 ***
    ## Marryb       0.37718    0.02989  12.618  < 2e-16 ***
    ## Marryc       0.59699    0.09649   6.187 7.07e-10 ***
    ## Marryd       0.23411    0.15480   1.512    0.131    
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## (Dispersion parameter for gaussian family taken to be 0.4274227)
    ## 
    ##     Null deviance: 1221.0  on 2672  degrees of freedom
    ## Residual deviance: 1140.8  on 2669  degrees of freedom
    ## AIC: 5319.6
    ## 
    ## Number of Fisher Scoring iterations: 2

    ##                   2.5 %    97.5 %
    ## (Intercept)  1.45929466 1.5169319
    ## Marryb       0.31859134 0.4357684
    ## Marryc       0.40787638 0.7861098
    ## Marryd      -0.06928632 0.5375042

    ## (Intercept)      Marryb      Marryc      Marryd 
    ##    4.428732    1.458167    1.816648    1.263782

    ##                  COR     2.5 %   97.5 %
    ## (Intercept) 4.428732 4.3029234 4.558219
    ## Marryb      1.458167 1.3751892 1.546151
    ## Marryc      1.816648 1.5036213 2.194841
    ## Marryd      1.263782 0.9330595 1.711729

    ## 
    ## Call:
    ## glm(formula = LifestyleScoreCategory ~ WorkplaceScale1, data = Male)
    ## 
    ## Deviance Residuals: 
    ##      Min        1Q    Median        3Q       Max  
    ## -1.13504  -0.13504   0.05904   0.07521   1.07521  
    ## 
    ## Coefficients:
    ##                  Estimate Std. Error t value Pr(>|t|)    
    ## (Intercept)       1.92479    0.02280  84.405  < 2e-16 ***
    ## WorkplaceScale1b  0.01617    0.03036   0.532    0.594    
    ## WorkplaceScale1c  0.21025    0.03218   6.534 7.55e-11 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## (Dispersion parameter for gaussian family taken to be 0.4425515)
    ## 
    ##     Null deviance: 1266.9  on 2810  degrees of freedom
    ## Residual deviance: 1242.7  on 2808  degrees of freedom
    ## AIC: 5690.7
    ## 
    ## Number of Fisher Scoring iterations: 2

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
