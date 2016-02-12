<table>
<thead>
<tr class="header">
<th align="left">Diabetic Control</th>
<th align="left">Diabetic Complication present</th>
<th align="left">Diabetic Complication asent</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Good</td>
<td align="left">3</td>
<td align="left">7</td>
</tr>
<tr class="even">
<td align="left">Poor</td>
<td align="left">4</td>
<td align="left">2</td>
</tr>
</tbody>
</table>

#### (a) Is there any difference in complication rates between patients with good diabetic control and those with pool control?

-   Complication rate of patients with good diabetic control: 3 / (3+7)
    = 30%
-   Complication rate of patients with poor diabetic control: 4 / (4+2)
    = 66.7%

#### (b) Determine whether the difference between the two rates is statistically different?

    ## 
    ##  Fisher's Exact Test for Count Data
    ## 
    ## data:  diabetic.df
    ## p-value = 0.3024
    ## alternative hypothesis: true odds ratio is not equal to 1
    ## 95 percent confidence interval:
    ##  0.0137305 2.7634624
    ## sample estimates:
    ## odds ratio 
    ##  0.2384682

*The p-value calculated for the test does not provide any evidence
against the assumption of independence. In this example this means that
we cannot confidently claim any difference in performance for the two
rates*

#### (c) Explain why the x^2 test should not be used for this study.

*Chi-square test is suitable for unpaired data from large samples. In
this case, the sample size is only 16 and relatively small.*
