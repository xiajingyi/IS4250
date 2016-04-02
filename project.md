    ## Warning: package 'MASS' was built under R version 3.2.4

    ## Warning: package 'effects' was built under R version 3.2.4

    ## Warning: package 'vcd' was built under R version 3.2.4

    ## Warning: package 'mlogit' was built under R version 3.2.4

    ## Warning: package 'maxLik' was built under R version 3.2.4

    ## Warning: package 'miscTools' was built under R version 3.2.4

    ## Warning: package 'nnet' was built under R version 3.2.4

    ##       Gender
    ## Age    Male Female
    ##   <=32 1237   1408
    ##   >32  1574   1265

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  Age
    ## X-squared = 41.241, df = 1, p-value = 1.346e-10

    ##                     Gender
    ## Occupation           Male Female
    ##   Manufacturing      1406   1107
    ##   Construction        677     92
    ##   Hospitality         148    237
    ##   Domestic service    144    430
    ##   Small business      232    403
    ##   Recreation/leisure  204    404

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  Occupation
    ## X-squared = 752.52, df = 5, p-value < 2.2e-16

    ##               Gender
    ## WorkplaceScale Male Female
    ##       Large     851    649
    ##       Moderate 1101    841
    ##       Small     859   1183

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  WorkplaceScale
    ## X-squared = 110.02, df = 2, p-value < 2.2e-16

    ##                      Gender
    ## EducationalAttainment Male Female
    ##   Elementary or lower  393    611
    ##   Junior high school  1409   1380
    ##   High school          777    543
    ##   College              232    139

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  EducationalAttainment
    ## X-squared = 109.03, df = 3, p-value < 2.2e-16

    ##                      Gender
    ## MaritalStatus         Male Female
    ##   Married             2042   1977
    ##   Single               700    631
    ##   Cohabitating          39     47
    ##   Divorced or widowed   30     18

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  MaritalStatus
    ## X-squared = 4.9029, df = 3, p-value = 0.179

    ##                              Gender
    ## AccompanyingChildren          Male Female
    ##   No children                  849    796
    ##   Cohabitating children        878    968
    ##   Children residing elsewhere 1084    909

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  AccompanyingChildren
    ## X-squared = 18, df = 2, p-value = 0.0001234

    ##               Gender
    ## Salary         Male Female
    ##   <1500RMB      168    317
    ##   1500-2500RMB 1036   1492
    ##   2500-3000RMB 1071    628
    ##   >=3500RMB     536    236

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  Salary
    ## X-squared = 356.87, df = 3, p-value < 2.2e-16

    ##                        Gender
    ## NumberOfCitiesResidedIn Male Female
    ##                     1-2 1859   2207
    ##                     >=3  952    466

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  NumberOfCitiesResidedIn
    ## X-squared = 193, df = 1, p-value < 2.2e-16

    ##                  Gender
    ## DailyWorkingHours Male Female
    ##              <8     18     62
    ##              8    1273   1310
    ##              8-11 1066    615
    ##              >=11  454    686

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  DailyWorkingHours
    ## X-squared = 189.59, df = 3, p-value < 2.2e-16

    ##                  Gender
    ## WeeklyWorkingDays Male Female
    ##               <=4   57     99
    ##               5    805    759
    ##               6   1046   1201
    ##               7    903    614

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  WeeklyWorkingDays
    ## X-squared = 74.984, df = 3, p-value = 3.652e-16

    ##                        Gender
    ## TypeOfResidence         Male Female
    ##   Collective dormitory  1040    515
    ##   Renting with others    324    312
    ##   Renting as a family    897   1400
    ##   Renting alone          430    324
    ##   Owning a living place  120    122

    ## 
    ##  Pearson's Chi-squared test
    ## 
    ## data:  TypeOfResidence
    ## X-squared = 299.26, df = 4, p-value < 2.2e-16

    ## # weights:  21 (12 variable)
    ## initial  value 2936.590648 
    ## iter  10 value 2369.263164
    ## iter  20 value 2338.615808
    ## final  value 2338.613660 
    ## converged

    ## Call:
    ## multinom(formula = LifestyleScoreCategory ~ occ, data = Female)
    ## 
    ## Coefficients:
    ##   (Intercept)       occb      occc      occd      occe     occf
    ## 2  -0.6165651  0.1356141 0.2562971 0.4288389 0.3428716 1.279892
    ## 3  -2.7769841 -0.1318940 1.5532499 0.5525024 0.7479265 3.371316
    ## 
    ## Std. Errors:
    ##   (Intercept)      occb      occc      occd      occe      occf
    ## 2  0.06425061 0.2274230 0.1567793 0.1186064 0.1224575 0.1481678
    ## 3  0.15717490 0.6134105 0.2483505 0.2662140 0.2551708 0.2072738
    ## 
    ## Residual Deviance: 4677.227 
    ## AIC: 4701.227

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
