# Economics 204 Empirical Paper: Age and the Covid-19 Pandemic’s Impact on Employee Income
## Written by Geoffrey Cho

### Abstract

The Covid-19 pandemic, as well as the mandates and strategies implemented by governments worldwide to curb the spread and risks of the virus, brought about 
one of the most significant economic shortfalls in recent years, specifically regarding employment.
Older people face higher risks of serious complications, including but not limited to: long-lasting side effects even after recovering from the virus (coined “long Covid” by the media), hospitalizations, and even death.
Additionally, every worker in the labor force had to adjust to major work and lifestyle changes as working remotely became the new norm due to stay-at-home mandates enacted all around the world. Due to these factors, older workers could have faced harsher and more negative economic and employment outcomes (especially at the peak of the pandemic) compared to younger workers. So what impact did the age of workers have on their wages before the Covid-19 virus became a pandemic, and has that impact changed as societies and the economies around the world move towards a post-Covid era? The main relationship being examined in this paper is between the age of workers and their annual income, viewed in different years-2019 and 2021 were chosen to differentiate “pre” and “post” Covid years, with 2020 representing the peak of the pandemic’s effects on society-to further and better understand the impact that Covid-19 specifically had on this relationship. 

### Introduction

What impact did the age of workers have on their wages before the Covid-19 virus became a pandemic, and has that impact changed as societies and the economies around the world move towards a post-Covid era? Without question, the Covid-19 pandemic has been and continues to be (at the time this paper was written) one of the most consequential events of the past century; inarguably, very few other events in the 2000’s have had such a paradigm shifting effect on the day to day lives of everyone around the world. One of the biggest changes in the daily lifestyles of people in labor forces was their working situation, as the contagious nature of the Covid-19 virus necessitated working remotely from home or even forcing businesses to lay off a large number of workers. Before Covid-19 even became internationally accepted and recognized as a pandemic (for the purposes of this paper, “pre-Covid” will be designated as the year of 2019 since in March 2020 then-United States president Donald Trump declared Covid to be a nationwide emergency) age was certainly a known impacting factor in income earned by workers. The general thought was that as a worker’s age increased, so too did their income, and Erica York in her article Average Income Tends to Rise with Age supported this notion, stating that “Income tends to exhibit an inverted-U-shape pattern, rising with age and then dropping slightly…[before entering] retirement.” 

However, the National Bureau of Economic Research points out the economic hardship faced by older workers, stating that “employment for [older adults aged 50-70] dropped substantially more” compared to pre-Covid era employment. “For people aged 50-61”, their employment in 2021 dropped 8.3% lower, whereas employment for “those aged 62-70” was 10.7% lower than expected. The National Academy of Elderly Law Attorneys (NAELA) echoed this sentiment, noting that the pandemic was particularly strenuous on older people in the labor force. Older individuals are at higher risk for hospitalization and death due to Covid-19 infections, which worsened age discrimination that typically “increases during times of economic uncertainty, contributing to longer unemployment duration for older workers.” NAELA proposes different challenges that could contribute to the adversity that older workers face, including a difficult transition to remote work, longer periods of unemployment and underemployment compared to younger workers, and increased forced early retirement.

This paper will use multiple regression models to determine if the impact of the age of a worker on their respective annual income is more pronounced and influential in the pre-Covid era or moving towards a post-Covid time.  For the purposes of this paper, “post-Covid” will be designated as the year of 2021 since after the wave of infections caused by the Delta variant of the Covid virus in late November 2021, the Center for Disease Control (CDC) recommended to everyone over the age of 18 to get a vaccination booster shot. 

### Literature Review

The Institute of Labor Economics (IZA) studied the impact of COVID-19 on “how age and income gradients relate to the Covid pandemic”. The dataset used in this study was gathered from “publicly available data that was collected by Belot et al. (2020) between April 15 and April 23” (Belot, 2020) which included “6,082 respondents; roughly 1000 from each of six countries. Three Asian countries (China, Japan, and South Korea) and three western countries (Italy, the United Kingdom, and the United States).” The analysis of the IZA’s paper was primarily based on ordinary least square models, but also incorporated linear probability models when the results were binary. The “right hand side” variables included age and income dummy variables, as well as additional control variables for “gender, a rural-urban indicator, and regional dummies”. Sepulveda and Brooker found “consistent evidence that younger people have been more negatively affected-both economically and psychologically”, which contradicts the assumptions about Covid-19 more negatively affecting older workers than younger workers. What’s even more fascinating is that although their paper mainly focused on “age and income differences”, their data also indicates that “women are disproportionately affected by this economic crisis.” (Sepulveda and Brooker, 2021).

This paper similarly utilizes data made available to the public, but gathered instead from the monthly U.S. labor force survey, called the Current Population Survey (CPS), since it more specifically pertains to and aligns with this paper’s primary focus on the United States. Additionally, the IZA paper studies the impact of Covid itself and the measures taken to contain the disease on different people in different countries, with age and income being quantitative variables to categorize people and their lifestyles, whereas this paper will focus instead on the impact of age on income (of people in the United States only) with Covid serving as timeline benchmark differentiating “pre” and “post” Covid eras. Similar to the IZA paper, however, this paper will also incorporate ordinary least square methods as well as multiple linear regression models as the basis of statistically analyzing the data collected and observed. 

Edgardo Sepulveda and Ann-Sylvia Brooker examined the relationship between income inequality and COVID mortality for Science Direct. Two different datasets from 2021 were used: Johns Hopkins’ dataset on COVID-19 deaths and data gathered by the Organization for Economic Co-operation and Development (OECD) for national populations. Sepulveda and Brooker’s paper uses the Poisson regression model for statistical analysis as they claim this model “is appropriate for discrete, count data”, particularly for datasets that include many zeros. Additionally, they also chose “country-level clustered standard error specifications that, when used with the Poisson model, controls for heteroskedasticity and autocorrelation.” (Sepulveda and Brooker, 2021) Their explained variable was COVID-19 mortality rate, categorized by age groups, and their explained variables were income inequality (specifically, the disposable income Gini coefficient) and income (median per capita income in terms of USD Purchasing Power Parity). Interestingly, the most important fact that the study found was that “income inequality is significantly associated with higher Covid-19 mortality” (Sepulveda and Brooker, 2021) for all age groups (that they used in the paper) which contradicts the findings of the IZA paper.

The National Bureau of Economic Research (mentioned above) conducted a study on how the Covid-19 pandemic impacted older workers’ employment and Social Security spillover. In similar fashion to this paper, “public use microdata from the monthly IPUMS Current Population Survey (CPS) from January 2015 - March 2021” was mainly used as the database in order to “track monthly employment outcomes.” (Goda, Jackson, Nicholas, Stith, 2021) In order to specifically analyze only older workers, the NBER paper limited the scope of analysis to workers “aged 50-70 at the time of survey”. Various main variables were used, such as month indicators, a month-level time trend, state fixed effects, and event time relative to February 2020. Supplementary “demographic controls such as age, race, Hispanic ethnicity, education, a metro area indicator, and household family size” were also utilized as well as controls for “time trends, month and state fixed effects and other control variables”. (Goda, Jackson, Nicholas, Stith, 2021) The study found that for the oldest age group of workers who identified their ethnicity as other than “white”-in the case of the NBER paper, the “oldest” age group was assigned as workers aged 62-70-”...both unemployment and labor market exits for reasons other than retirement and disability” represent a larger share of employment decline starting in April 2020. (Goda, Jackson, Nicholas, Stith, 2021) In general, the NBER paper found that for older workers at the start of April 2020, “employment declines sharply relative to the predicted employment rate to 10-15 percentage points lower than the counterfactual”. 

### Econometric model

Simple population regression model: *incwage = β<sub>1</sub> + β<sub>2</sub>age + e*

Multiple population regression model: *incwage = β<sub>1</sub> + β<sub>2</sub>age + β<sub>3</sub>white + β<sub>4</sub>female + β<sub>5</sub>labforce + e*

Multiple sample regression line:



The econometric models used in this paper were all of the functional forms of simple and multiple regression models which were: linear, quadratic, cubic, log-linear, log-log, and linear-log models. It’s reasonable to predict that income earnings and distributions would not be equal across all ages, and therefore estimating a straight line of best fit on the data would lead to a functional form error. Thus, all functional forms (of simple regression models) were run in order to examine which of the functional forms would be the better fit to the data being analyzed, and this was determined by comparing the sum of squared errors (SSE’s) since lower SSE’s indicate a better fit to the actual data. STATA provides SSE’s but only if the explained y variable (in this case, annual income or incwage) is of the same form so multiple R-squares were calculated for, as higher R-squares can also indicate whether the models are a good fit to the data, and special STATA commands were utilized in order to be able to also compare linear and log-linear models in addition to linear models and log-log models since in both cases, a linear y variable is being compared to a log y variable. Furthermore, multiple hypothesis tests were also conducted to test for statistical significance and data distribution, which included a two-tailed F-test, right and left tailed F-tests, and two other hypothesis tests that tested whether the effect of age on incwage is twice as great as the effect of being white on incwage and whether age is a relevant variable in explaining incwage. 

Additionally, three other models with interaction terms for age and labor force status (age_lab), white and female (white_female), and white and age (white_age) were utilized as well. Interaction terms were introduced because they can reveal if the effect of one variable varies with the level of other variables. The effect of an extra year of age on incwage would probably be different for a white person compared to a non-white person, hence why the interaction term age_white was created. The same logic applies to the creation of age_lab (the effect of an extra year in age would probably be different for someone who is employed as compared to someone who is unemployed, particularly for older people) and white_female (due to gender and race inequalities in workplaces and the labor market, the effect of being white would probably be different for females as compared to males).   

### Data and Descriptive Statistics

The dataset for this paper was extracted from the publicly available Integrated Public Use Microdata Series (IMPUS) harmonized with the Current Population Survey (CPS) of the United States. As mentioned above, the years 2019 and 2021 were chosen to differentiate “pre” and “post” Covid years, with 2020 representing the peak of the pandemic’s effects on society. While the Covid pandemic is still largely impactful even to this day, the advent of Covid vaccines and booster shots marked a shift in moving on from the societal effects of the virus, in terms of how governments dealt with and people viewed the pandemic based on the CDC timeline of COVID-19. The main explanatory x variable was age (in years) and the main explained y variable was incwage, described as “total pre-tax wage and salary income” or “money received as an employee for the previous calendar year”. Additional explanatory x variables included three other dummy variables: white (whether someone’s race was classified as white or non-white), female (whether someone’s identified gender was classified as female or male), and labforce (the labor status of a person, and whether that person was classified as in the labor force or not). 

IMPUS CPS gathered the ages of 343,644 respondents but almost 89,000 observations were dropped (leaving 254,713 observations to be used for this paper) since the data included respondents who were under the age of 18. Although the federal legal working age in the United States technically starts at 14 years, many labor conditions and hours are set for employees under the age of 18, so these data observations were dropped from the dataset for the most accurate representation of data on annual income as most of these respondents were seemingly not yet employed anyways. IMPUS CPS also coded the missing data on annual income for underage, unemployed respondents (these observations were referred to as N.I.U or “Not In Universe”) as “99999999” which seriously skewed and misrepresented the dataset when these values were not dropped. Similarly, IMPUS CPS coded the missing data on labor force status for (presumably) underage people-again, these observations were referred to as N.I.U-as 0, with not being in the labor force coded as 1 and being in the labor force coded as 2. The N.I.U values were dropped, and a revised version of the labforce variable was created as “labforce_rev” with the 1 values indicating a person not being in the labor force being replaced as 0 and the 2 values indicating a person being in the labor force being replaced as 1 in order to remain consistent with dummy variable values that only take 0 or 1 values.

As shown in Table 2, all variables were rounded to three decimal places (or the nearest thousandths place) for the sake of consistency.

### Estimation Results

According to Table 2, the mean annual income from the entire dataset (meaning all three 2019, 2020, 2021 years) was $36,109.94 and the average age of employees was 47.837 years. Due to the COVID-19 pandemic’s far-reaching and devastating ramifications in terms of health and economy/finances, and also given the fact that elder citizens were particularly at risk for serious complications from the virus, it was assumed that annual income earned by employees-especially as age increased-would be negatively affected more so during the peak Covid-19 pandemic year of 2020 compared to the pre-Covid year of 2019, and incwage would increase from 2021 as compared to 2020 as the economy started to recovery and countries around the world began repealing stay-at-home mandates. However, Table 3B shows that incwage actually increased during 2020 compared to 2019 by a mean estimate difference of $2,195.98, from a mean of $34,954.79 in 2019 to a mean of $37,150.77 in 2020-although whether or not employee age factored into this increase or whether this increase in mean annual income differed amongst different ages was unable to be determined. Even more surprising was the fact that incwage appeared to actually decrease in 2021 as compared to 2020; Table 3B shows that incwage decreased by a mean estimate difference of -$786.83 from a mean of $37,150.77 in 2020 to a mean of $36,363.94 in 2021. 

Another fascinating result found in this study was the fact that the mean annual income (across all three years) was much lower for employees whose race/ethnicity was non-white compared to their white colleagues. For non-whites, their mean annual income in this time period was $32,723.720 whereas for white employees, their mean annual income in this time period was $37,113.300; the difference in mean annual income was -$4,389.58. Throughout this Covid-19 pandemic, and even before the pandemic began to truly affect the economy worldwide, it seems clear that white employees were fiscally better off than employees of minority races/ethnicities.

Interpretations for each functional form of the regression models were able to be concluded based on the regression and summary of statistics outputs given by STATA as well as calculations made based on these outputs (for interaction terms). The coefficient of the interaction term “age_lab” was 651.0, as shown in Table 4, and this implies that the effect of age on annual earnings is 651.0 more for people who were in the labor force compared to those who were not in the labor force. The coefficient of the interaction term “white_female” was -5,501, again as shown in Table 4, and this implies that the effect of being white on annual earnings is -5,501 less for females as compared to males. Finally, the coefficient of the interaction term “age_white” was 1.669, implying that the effect of age on annual earnings is 1.669 more for white employees in comparison to those in the labor force who were of non-white ethnicity. 

What these interaction term coefficients can tell us is a better understanding of the true effect of different variables on incwage according to certain characteristics/other variables. For example, the effect of an extra year in age on annual income earned is $247.457 for people who qualified as not being in the labor force, but $54,108.517 for those in the labor force (holding race and sex constant); this is not surprising at all because a person’s labor force status is the biggest and most relevant determining factor in how much annual income that he/she earns. The effect of an employee’s race being white on their annual income earned is $1935.937 if that employee is also a male, but this effect results in a -$10,747.873 decrease if that employee were a female (holding age constant); the difference in income earned between males and females has been well documented and studied by now, and this difference can be further seen considering that even if two employees were of the same race (being white), simply being a female results in an almost devastating negative effect on their yearly income whereas the male employee actually benefits from being his gender alone. The effect of an extra year in the age of a worker on incwage is $247.457 if they are not a white person and $2183.394 if their race is “white”; similar to the pay gap between males and females, a white person evidently earned more in annual income than any other race/nationality.

Some interpretations didn’t make sense given the context of the data, especially when the b1 value (the sample estimator for 1 parameter) indicated a certain estimated annual income if employee age was 0-even though the minimum age for the dataset used was 18- or the  b4 coefficient (the sample estimator for the 4 parameter associated with the female dummy variable) was negative for the linear, quadratic, cubic, and linear-log models, and even the models for the interaction terms. In the linear model, for example, the b1 value was interpreted to mean that when the age of an employee was 0, the estimated annual income earned was -$5,192.909, which doesn’t make sense because a newborn child obviously wouldn’t be able to earn any income whatsoever, in addition to the fact that earning a negative annual income is impossible in the first place. Additionally, although the mean annual income increased from 2019 to 2020 and decreased in 2020 as compared to 2021 (regardless of age), some functional forms signaled that when the age of an employee increased by 1 year, their respective annual income would actually decrease; for example, in the linear-log model, an increase in employee age by 1% lead to a decrease of annual income by  -$48,709.95. 

As previously stated, all functional forms of the simple regression model were run to determine which functional form was the better fit for the data by comparing SSE’s, since lower SSE’s indicate a better fit. (SSE’s for each functional form were given by STATA’s regression output, found by looking at each respective sum of square “Residual” value.) More importantly, the R-squared values were also compared; the closer a R-squared value is to 1.0, the better that specific econometric model fits the data. By this metric, the log-log functional form seems to fit the dataset the best/most accurately because its R-squared value was 0.178; furthermore, the linear quadratic, cubic, and log-lin models all seemed to fit to the data to a very similar degree because their R-squared values only differed slightly from each other. 

### Conclusions

Due to the COVID-19 pandemic’s far-reaching and devastating consequences on peoples’ health and finances and overall on countries’ economies (especially given the fact that an increase in age, regardless of employment status, resulted in an increase in the risk of severe and life-threatening symptoms/reactions to the virus such as hospitalization and even death, as well as the fact that many employees were laid off due to the stay-at-home mandates issued by governments around the world that negatively impacted businesses) it was assumed that annual income would be lower in 2020 compared to 2019 and that incwage would be higher in 2021 compared to 2020. The impact that the age of workers had on their wages before the Covid-19 virus became a pandemic, and the changes/differences that this impact changed as societies and the economies around the world move towards a post-Covid era was the focal point of this paper. However, as mentioned above and in reference to Table 3B, a truly surprising and unforeseen result of this paper was the fact that mean annual income actually increased in 2020-even with economies worldwide suffering tremendously due to the pandemic-from 2019 by a mean estimate difference of $2,195.98. And as the world moved towards a post-Covid era and stay-at-home mandates began to be lifted, economies began to fiscally recover- which makes the finding that annual income earned in 2021 decreased by a mean of  -$786.83, compared to 2020 at the height and peak of Covid-19’s devastating global impact. 

These findings regarding the changes at the mean of annual income earned go against the results of the IZA paper, which found that income level drop offs were experienced across the six countries analyzed, although this drop off differed across various age and income groups. However, these findings and the results found in Tables 3A and 4 echo similar sentiments as the NBER paper in that non-white workers . Unfortunately, it seems that even in the face of a pandemic with once-in-a-century effects on the world, workers who were non-white faced greater unemployment and labor market exits than their white counterparts.

The unexpectedness of the changes at the mean of annual income earned according to the different years and periods in the Covid-19 timeline can probably be attributed to other economic factors outside of just employment levels and statuses. Inflation could definitely have an impact on the reported annual earnings depending on how the economy may be faring (at a given point during the Covid-19 era), which may help to explain why and how annual incomes earned increased in the year of 2020 where economies were universally suffering around the world for every country, as compared to 2019 when the effects and impact of the pandemic were not yet truly realized or felt. Additionally, breaking down the age variable into different age groups, in a similar manner to the IZA paper, would further help to see the true effect of age on incwage during this pandemic era; interpretations of interaction terms between age and labor force status as well as age and race (white vs. non-white) were calculated and presented in this paper but it doesn’t fully help to explain whether older workers financially suffered more compared to younger workers. 

### Apendix

**Table 1: Description of Variables**
| Variable Name  | Variable Description |
| ------------- | ------------- |
| Incwage (USD $)  | Main explained y variable. From IPUMS CPS website: “total pre-tax wage and salary income” or “money received as an employee for the previous calendar year”.  |
| Age  | Main explanatory x variable. From IMPUS CPS website: “Each person’s age at last birthday.”  |
| White| Dummy variable created for White (Americans), assuming the value of 0 for all non-white races and 1 if a person was white.  |
| Female  | Dummy variable created for females, assuming the value of 0 if the person was male and 1 if the person was female. From IMPUS CPS website: “SEX gives each person’s sex.”|
| Labforce_rev  | A revised dummy variable (a revision of the original “labforce” variable) that assumes the value of 0 if a person is not in the labor force and 1 if a person is in the labor force.|

**Table 2: Descriptive Statistics of the Variables**
| Variable Name  | Mean/Average | Standard Deviation | Minimum | Maximum |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Incwage (USD $) | 36109.940  | 65383.750 | 0 | 2099999 |
| Age  | 47.837  | 17.871 | 18 | 85 |
| White | 0.771  | 0.420 | 0 | 1 |
| Female | 0.525  | 0.499 | 0 | 1 |
| Labforce_rev | 0.643 | 0.479 | 0 | 1 |

**Table 3A: Descriptive Statistics according to Race (White vs. Non-white)**
| Variable Name  | Non-white (white = 0) | White (white = 1) | Difference |
| ------------- | ------------- | ------------- | ------------- |
| Incwage (USD $)  | 32723.720 | 37113.300 | -4389.58 |
| Age  | 46.776 | 48.151 | 1.375 |
| Female  | 0.548 | 0.518 | 0.030 |
| Labforce_rev  | 0.618 | 0.650 | -0.032 |

**Table 3B: Descriptive Statistics according to Year (2019, 2020, 2021)**
| Variable Name  | 2019 | 2020 | 2021 |
| -------------- | ---- | ---- | ---- |
| Incwage (USD $)  | 34954.79 | 37150.77 | 36363.94 |
| Age  | 47.40583  | 48.1752 | 47.98116 |
| White  | 0.7729218  | 0.7737673 | 0.767513 |
| Female  | 0.5256887 | 0.5241853 | 0.5239144 |
| Labforce_rev  | 0.6528924 | 0.6413837 | 0.6413837 |

**Table 4: Regression Models**

<img width="501" alt="Screen Shot 2023-05-02 at 2 37 17 AM" src="https://user-images.githubusercontent.com/121268398/235597043-b2f95492-8ce7-45b7-a569-1f87050c30af.png">

 
**Graph 1:**

<img width="499" alt="Screen Shot 2023-05-02 at 2 43 00 AM" src="https://user-images.githubusercontent.com/121268398/235597641-08d36228-a985-4a30-8e30-924a6480bb64.png">

**Graph 2:**

<img width="541" alt="Screen Shot 2023-05-02 at 2 43 32 AM" src="https://user-images.githubusercontent.com/121268398/235597727-dabaacdd-f0af-4bb2-921a-7d65711ea27b.png">

**Graph 3:**

<img width="465" alt="Screen Shot 2023-05-02 at 2 44 03 AM" src="https://user-images.githubusercontent.com/121268398/235597818-5ede76ee-1536-45bc-9d03-005e2169a68b.png">

**Graph 4:**

<img width="505" alt="Screen Shot 2023-05-02 at 2 44 26 AM" src="https://user-images.githubusercontent.com/121268398/235597882-60001a1d-53ab-4fe3-be3e-5a16ae87d4e6.png">

**Graph 5:**

<img width="572" alt="Screen Shot 2023-05-02 at 2 45 15 AM" src="https://user-images.githubusercontent.com/121268398/235597997-a6fb3f34-ce01-407c-ac6b-4df9d9ff5ae9.png">

### Stata Do-File Code

```
* "clear all" command clears data in memory and calls data file again when run
clear all

* "log" command using "paper_logfile1" saves output window results and stores into paper_logfile1
* "replace" command stores new results of do file into same logfile 
log using "/Users/geoffreycho/Downloads/paper_logfile1.log", replace

use "/Users/geoffreycho/Downloads/cps_00007.dta", replace

* "describe" command describes the characteristics of the variables, such as labels, definitions, explanations, etc.
describe

* "label list" command checks the dataset's variable's characteristics
label list

* "browse" command opens the dataset with aforementioned labels
* "nolabel" shows dataset/variable characteristics with codes instead of labels
browse, nolabel

replace age = . if age < 18
replace incwage = . if incwage == 99999999
replace labforce = . if labforce == 0

* "drop" command drops observations with missing values
cap drop if age == .
cap drop if incwage == .
cap drop if labforce == .

cap gen labforce_rev = labforce
replace labforce_rev = 0 if labforce == 1
replace labforce_rev = 1 if labforce == 2

* "female", "white" dummy variables created
* "gen" command generates a new variable
* "cap" command tells STATA not to rerun gen commands if the generated variable already exists, so as to suppress error messages
cap gen female = 0
replace female = 1 if sex == 2

cap gen white = 0
replace white = 1 if race == 100

* "y_2019", "y_2020", "y_2021" dummy variables created
cap gen y_2019 = 0
replace y_2019 = 1 if year == 2019

cap gen y_2020 = 0
replace y_2020 = 1 if year == 2020

cap gen y_2021 = 0
replace y_2021 = 1 if year == 2021

bys y_2019: sum incwage age white female labforce_rev
bys y_2020: sum incwage age white female labforce_rev
bys y_2021: sum incwage age white female labforce_rev
* installing the "outreg2" command
ssc install outreg2

* summary statistics
sum incwage age white female labforce_rev
outreg2 using summary.doc, replace sum(log) keep(incwage age white female labforce_rev)


* creates a histogram for all observations in incwage and saving graph (in same folder)
hist incwage, percent ytitle(Percent) xtitle(Annual Income) title(Histogram of Annual Income)
graph export "income1.png", as(png) replace

***************************
* LINEAR MODEL
***************************
* "reg" command performs ordinary least-squares population regression (in linear terms)
reg incwage age white female labforce_rev
outreg2 using myreg.doc, replace ctitle(Model 1)

* generates predicted values from the regression
cap predict yhat1, xb

* generates residuals from the regression
cap predict ehat1, resid

* "scatter" command generates a scatter plot with first variable listed as y axis and second variable as x axis
twoway(scatter incwage age), ytitle(Annual Income) xtitle(Age in Years) title(Scatterplot between Annual Income and Worker Age, size(medium)) 
graph export "scatter_model1.png", as(png) replace

* creates a histogram of residuals for skewness
hist ehat1, percent ytitle(Percent) xtitle(Predicted errors from Regression of Annual Income on Age) title(Histogram of Predicted Errors)
graph export "ehat1.png", as(png) replace

* summary statistics for annual income (incwage) by race (white or non-white) and sex (female or male)
bys white: sum incwage age female labforce_rev
bys female: sum incwage age white labforce_rev

***************************
* QUADRATIC MODEL
***************************
* "age_sq" variable created for quadratic model, squares age values
cap gen age_sq = age*age
sum age_sq

reg incwage age_sq white female labforce_rev
outreg2 using myreg.doc, append ctitle(Model 2)
cap predict yhat2, xb

* comparison of fitted lines from linear and quadratic models
graph twoway (scatter incwage age)(line yhat1 age)(line yhat2 age), ytitle(Annual Income and Predicted Annual Income) xtitle(Age in Years) title(Scatterplot and Fitted Lines from Linear and Quadratic Models, size(medium))
graph export "fit1.png", as(png) replace

sum ehat1, detail

***************************
* CUBIC MODEL
***************************
* "age_cu" variable created for cubic model, cubes age values
cap gen age_cu = age*age*age
sum age_cu

* regression of annual income (incwage) on age cubed
reg incwage age_cu white female labforce_rev
outreg2 using myreg.doc, append ctitle(Model 3)

***************************
* LOG-LIN MODEL (log(incwage))
***************************
* "lincwage" variable created for log-lin model, log incwage
cap gen lincwage = log(incwage)
sum lincwage

hist lincwage, percent ytitle(Percent) xtitle(Log Annual Income) title(Histogram of Log Annual Income)
graph export "lincwage.png", as(png) replace

* regression of log annual income (lincwage) on age
reg lincwage age white female labforce_rev
outreg2 using myreg.doc, append ctitle(Model 4)

***************************
* LOG-LOG MODEL (log(incwage) on log(age))
***************************
* "lage" variable created for log-log model, log age
cap gen lage = log(age)
sum lage

* regression of log annual income (lincwage) on log age (lage) and other variables
reg lincwage lage white female labforce_rev
outreg2 using myreg.doc, append ctitle(Model 5)

***************************
* LIN-LOG MODEL (incwage on log(age))
***************************
* regression of annual income (incwage) on log(age) 
reg incwage lage white female labforce_rev
outreg2 using myreg.doc, append ctitle(Model 6)

***************************
* INTERACTION TERMS
***************************
* creating an interaction term between "age" and "labforce"
cap gen age_lab = age*labforce_rev
reg incwage age white female labforce_rev age_lab
outreg2 using myreg.doc, append ctitle(Model 7)

* creating an interaction term between "female" and "white" dummy variables
cap gen white_female = white*female
reg incwage age white female white_female labforce_rev
outreg2 using myreg.doc, append ctitle(Model 8)

*creating an interaction term between "age" and "white" variables
cap gen age_white = white*age
reg incwage age white age_white female labforce_rev
outreg2 using myreg.doc, append ctitle(Model 9)

***************************
* HYPOTHESIS TESTING
***************************

* absolute critical value for two-tailed test at 5% significance level, with df = 254,713-2 = 254,711
display "Absolute Critical Value for two-tailed t-test is " invt(254711, 0.975)

* absolute critical value for right-tailed test at 5% significance level, with df = 254,713-2 = 254,711
display "Absolute Critical Value for right-tailed t-test is " invt(254711, 0.95)

* absolute critical value for left-tailed test at 5% significance level, with df = 254,713-2 = 254,711
display "Absolute Critical Value for left-tailed t-test is " invt(254711, 0.05)

* testing whether the effect of age on incwage is twice as much as the effect of being white
* H0: beta2 - 2*beta3 = 0 and H1: beta2 - 2*beta3 ≠ 0
reg incwage age white female labforce_rev
test age - 2*white = 0

* testing whether age is relevant as a variable in explaining incwage
* H0: beta2 = beta6 = 0 and H1: at least one parameter ≠ 0
reg incwage age white female labforce_rev age_sq
test age = age_sq = 0

***************************
* R-SQUARED
***************************
reg incwage age white female labforce_rev
corr incwage age white female labforce_rev
scalar R_sq_corr = r(rho)^2
display R_sq_corr

* Showing that R-squared in a regression model equals the square of correlation between y and yhat1
* "quietly" command suppresses regression output
quietly reg incwage age white female labforce_rev
cap predict yhat1, xb
corr incwage yhat1
scalar R_sq_lin = r(rho)^2
display R_sq_lin

* Making R-squares comparable with the linear and log-linear models
reg lincwage age white female labforce_rev
cap predict lyhat3, xb
cap gen yhat3 = exp(lyhat3)
corr incwage yhat3
scalar R_sq_loglin = r(rho)^2
display R_sq_loglin

* Making R-squares comaparable with the linear and log-log models
reg lincwage lage white female labforce_rev
cap predict lyhat4, xb
cap gen yhat4 = exp(lyhat4)
corr incwage yhat4
scalar R_sq_loglog = r(rho)^2
display R_sq_loglog

save "/Users/geoffreycho/Downloads/cps_paper.dta", replace
log close
```

