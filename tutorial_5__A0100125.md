    ## 
    ## Call:
    ## lm(formula = lifeexpf ~ birthrat, data = country)
    ## 
    ## Residuals:
    ##      Min       1Q   Median       3Q      Max 
    ## -17.3110  -2.6524  -0.0768   3.1784  18.1892 
    ## 
    ## Coefficients:
    ##             Estimate Std. Error t value Pr(>|t|)    
    ## (Intercept) 89.58892    1.31645   68.05   <2e-16 ***
    ## birthrat    -0.74471    0.03878  -19.20   <2e-16 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## 
    ## Residual standard error: 5.619 on 119 degrees of freedom
    ##   (1 observation deleted due to missingness)
    ## Multiple R-squared:  0.756,  Adjusted R-squared:  0.754 
    ## F-statistic: 368.8 on 1 and 119 DF,  p-value: < 2.2e-16

-   As p-value: \< 2.2e-16 (less than 0.05) is small, we cannot reject
    null hypothesis. Thus, there is a linear relationship between the
    two variables.

-   R-square is 0.756 close to 1, showing a relatively strong linear
    relationship between the two variables.

![](tutorial_5__A0100125_files/figure-markdown_strict/unnamed-chunk-2-1.png)<!-- -->

-   The two variables are negatively corelated (as seen from the graph -
    downward slope). The higher the birth rate, the lower the life
    expectancy.

-   Simple linear equation: lifeexpf = 89.58892 - 0.74471 \* birthrat;
    lifeexpf = 89.58892 - 0.74471 \* 25 = 70.97117
