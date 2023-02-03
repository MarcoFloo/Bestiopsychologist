---
title: Hierarchical Regression
summary: Hierarchical regression is a way to show if variables of your interest explain a statistically significant amount of variance in your Dependent Variable (DV) after accounting for all other variables.
tags:
  - 
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---
**Hierarchical Regression: Background**

Human resource management is one of the key aspects of an organization's success, and statistical analysis plays a crucial role in understanding and predicting employee behavior. Hierarchical regression is one of the most widely used statistical techniques for analyzing employee data in human resources.

**What is Hierarchical Regression?**

Hierarchical regression is a statistical model that analyzes the relationship between a dependent variable and several independent variables, taking into account the relationship between these variables. It is a type of multiple regression that allows for the examination of complex relationships between variables, taking into account their hierarchical nature. The hierarchical nature of the model allows researchers to identify the unique impact of each predictor on the dependent variable, while controlling for the effects of other predictors.

**Why Use Hierarchical Regression in Human Resources?**

In human resources, hierarchical regression can be used to study employee attitudes, behaviors, and outcomes. For example, it can be used to understand the relationship between job satisfaction and job performance. Hierarchical regression can also be used to study the impact of organizational factors, such as leadership style, on employee attitudes and behaviors. Additionally, hierarchical regression can be used to analyze the impact of individual characteristics, such as personality and motivation, on employee attitudes and behaviors.

**Steps in Conducting a Hierarchical Regression Analysis**

Conducting a hierarchical regression analysis in human resources requires several steps:


1.Define the dependent variable and independent variables: The dependent variable is the outcome that the researcher wants to explain, and the independent variables are the predictors of the dependent variable.


2.Collect the data: Employee data can be collected through surveys, interviews, or observation.


3.Clean the data: The data collected must be cleaned to ensure that it is accurate and usable for analysis.


4.Choose the appropriate hierarchical model: A hierarchical model must be chosen based on the nature of the data and the research questions.


5.Conduct the regression analysis: The regression analysis is performed using statistical software, such as SPSS or R.


6.Interpret the results: The results of the regression analysis must be interpreted to understand the relationship between the dependent variable and the independent variables.

**My Experience**

I conducted three-stage hierarchical multiple regression was conducted with job performance as the dependent variable. Critical thinking score was entered at stage one of the regression (i.e., Model 1), conscientiousness score at stage two (i.e., Model 2), and a work sample at stage three (i.e., Model 3), based on the correlations between the three predictors and job performance.  

**The Data:**

| C_ID | PM   | CONS | INT  | WS   |
|------|------|------|------|------|
| 103  | 3.07 | 2.75 | 3.38 | 3.1  |
| 104  | 3.53 | 3.79 | 3.58 | 3.3  |
| 108  | 4.07 | 3.67 | 3.52 | 3.56 |
| 110  | 3.87 | 3.67 | 4.23 | 4    |
| 111  | 3.27 | 2.17 | 3.31 | 2.9  |
| 112  | 3.67 | 3.33 | 3.12 | 2.8  |
| 114  | 3.4  | 2.38 | 2.92 | 2.8  |
| 115  | 4.47 | 3.13 | 4.08 | 3.4  |
| 116  | 3.13 | 2.17 | 3.83 | 3.3  |
| 117  | 2.93 | 2.88 | 3.35 | 2.8  |
| 118  | 3.47 | 3.08 | 3.38 | 3.7  |
| 123  | 3.73 | 2.75 | 3.88 | 3.1  |
| 124  | 2.93 | 3.04 | 3    | 3.1  |
| 125  | 3.8  | 3.5  | 3.27 | 3    |
| 127  | 2.87 | 2.25 | 3.12 | 2.8  |
| 128  | 4.07 | 2.79 | 3.2  | 2.8  |
| 129  | 3.87 | 3.63 | 3.38 | 3.4  |
| 167  | 3.67 | 2.71 | 3.5  | 3.1  |
| 168  | 4.07 | 3.75 | 3.73 | 4    |
| 174  | 3.73 | 2.96 | 3.62 | 3.7  |
| 175  | 3.67 | 2.88 | 3.38 | 3.2  |
| 176  | 3.73 | 2.71 | 3.58 | 3.2  |
| 177  | 3.27 | 2.58 | 2.81 | 2.7  |
| 178  | 3.8  | 3.21 | 3.85 | 3.6  |
| 180  | 3.53 | 2.21 | 2.88 | 2.6  |
| 181  | 3.73 | 2.04 | 2.85 | 2.6  |
| 182  | 2.67 | 3    | 3.54 | 3.3  |
| 183  | 3.47 | 2.71 | 3.13 | 2.5  |
| 186  | 3.4  | 1.88 | 3.15 | 2.6  |
| 187  | 3.47 | 2.38 | 3.35 | 3.1  |
| 189  | 3.53 | 3.42 | 3.21 | 3.6  |
| 190  | 3.4  | 3    | 3.12 | 3    |
| 191  | 3.4  | 3.04 | 3.54 | 3.4  |
| 192  | 3.13 | 2.75 | 3.77 | 3.8  |
| 193  | 3    | 2.38 | 3.77 | 3.3  |
| 194  | 3.33 | 3.29 | 3.69 | 3.4  |
| 195  | 3.27 | 2.67 | 2.96 | 3.1  |
| 196  | 3.27 | 2.38 | 3    | 2.2  |
| 197  | 2.67 | 2.88 | 3.44 | 3.3  |
| 198  | 3.13 | 3    | 3.04 | 2.9  |
| 200  | 3.6  | 2.75 | 3.35 | 3.1  |
| 201  | 3.47 | 3.04 | 3.27 | 3.3  |
| 203  | 2.8  | 2.63 | 3.46 | 3.6  |
| 206  | 2.93 | 2.71 | 3.81 | 3.7  |
| 208  | 3.8  | 3.75 | 3.76 | 3.8  |
| 213  | 3.8  | 3.21 | 3.46 | 3.6  |
| 214  | 2.07 | 3.21 | 3.88 | 3.4  |
| 215  | 3.4  | 1.96 | 3.81 | 3.1  |
| 217  | 4    | 3    | 3.38 | 2.9  |
| 220  | 3.53 | 1.96 | 3.36 | 2.1  |
| 221  | 3.6  | 3.67 | 3.25 | 3.4  |
| 222  | 3.93 | 3.71 | 2.65 | 3.5  |
| 223  | 3.73 | 3.42 | 4.54 | 4.2  |
| 224  | 3.6  | 2.83 | 3.38 | 3    |
| 225  | 3.27 | 2.13 | 3.04 | 2.8  |
| 226  | 3.67 | 2.54 | 4    | 2.8  |
| 227  | 3.6  | 3.38 | 3.65 | 3.7  |
| 230  | 3.27 | 3    | 3.96 | 3.6  |
| 231  | 4    | 2.92 | 3.46 | 3.3  |
| 233  | 3.93 | 3.88 | 4.19 | 3.6  |
| 235  | 4    | 3.5  | 3.65 | 3.4  |
| 236  | 4.47 | 3.21 | 3.56 | 3.1  |
| 237  | 2.47 | 1.92 | 3.31 | 2.9  |
| 238  | 3.8  | 3.54 | 3.27 | 3.2  |
| 239  | 3.27 | 2.46 | 2.68 | 2.9  |
| 240  | 2.93 | 3    | 3.52 | 3.7  |
| 262  | 3.07 | 3.13 | 3.6  | 3.4  |
| 263  | 3.4  | 2.58 | 3.46 | 3    |
| 264  | 3.67 | 2.96 | 3.5  | 3.4  |
| 266  | 3.53 | 2.63 | 3.27 | 3    |
| 267  | 3.33 | 4.17 | 3.31 | 3.5  |
| 268  | 4    | 3    | 3.42 | 3.2  |
| 269  | 4.4  | 2.79 | 3.54 | 3.7  |
| 270  | 3.4  | 3.17 | 4.19 | 3.9  |
| 300  | 3.2  | 3.54 | 3.46 | 3.5  |
| 301  | 3.67 | 2.54 | 3.69 | 2.9  |
| 302  | 2.6  | 2.04 | 3.38 | 3.2  |
| 303  | 3    | 2.92 | 3    | 3.1  |
| 306  | 4.2  | 3.42 | 3.38 | 3.2  |
| 307  | 2.6  | 3.46 | 2.58 | 2.6  |
| 308  | 3.6  | 3.58 | 3.92 | 3.4  |
| 309  | 3    | 2.46 | 3.08 | 3    |
| 310  | 3.87 | 3.54 | 2.87 | 3.3  |
| 311  | 3.4  | 3.08 | 3.92 | 3.5  |
| 312  | 4    | 3.54 | 3.69 | 3.1  |
| 313  | 3.2  | 3.13 | 3.62 | 3.6  |
| 314  | 3.27 | 2.38 | 3.38 | 2.6  |
| 316  | 2.93 | 3.63 | 3.54 | 3.6  |
| 317  | 3.93 | 3.25 | 3.65 | 3.4  |
| 318  | 4.07 | 3.42 | 3.44 | 3.6  |
| 319  | 2.07 | 2.67 | 2.77 | 2.2  |
| 320  | 3.07 | 3.67 | 2.96 | 3.1  |
| 321  | 4.07 | 2.96 | 3.58 | 3.2  |
| 322  | 3.67 | 3.17 | 3.65 | 3.1  |
| 324  | 4.13 | 2.5  | 3.54 | 3.5  |
| 326  | 3.87 | 3.08 | 3.88 | 2.7  |
| 327  | 3.73 | 2.21 | 4.31 | 3.1  |
| 328  | 3.27 | 2.5  | 3.19 | 2.8  |
| 329  | 3.6  | 2.71 | 3.12 | 2.8  |
| 330  | 4.2  | 3.17 | 4.19 | 3.7  |
| 333  | 3.4  | 3.33 | 3.88 | 3.4  |
| 334  | 2.47 | 2.96 | 2.69 | 3    |
| 337  | 2.93 | 2.83 | 3.27 | 3.4  |
| 338  | 3.13 | 3.67 | 4.54 | 3.8  |
| 339  | 3.07 | 2.04 | 3.15 | 3.2  |
| 340  | 3.6  | 2.79 | 2.92 | 2.9  |
| 341  | 3.47 | 3.13 | 3.12 | 2.9  |
| 343  | 3.4  | 2.67 | 3.15 | 3    |
| 344  | 3.47 | 2.92 | 3.04 | 3.1  |
| 345  | 3.4  | 2.88 | 3.08 | 3.3  |
| 347  | 2.8  | 3.33 | 3    | 2.8  |
| 349  | 2.47 | 3    | 2.15 | 2.6  |
| 350  | 3.47 | 1.92 | 4.08 | 3.2  |
| 351  | 3.73 | 3.54 | 3.35 | 3    |
| 352  | 4.07 | 3.29 | 3.56 | 3.4  |
| 353  | 3.27 | 3.33 | 2.77 | 2.7  |
| 354  | 3.2  | 3.08 | 3.23 | 2.9  |
| 355  | 3.53 | 2.63 | 3.19 | 2.7  |
| 356  | 3.53 | 2.63 | 3.35 | 3.5  |
| 358  | 3.73 | 3.38 | 4    | 3.5  |
| 361  | 3.47 | 3.25 | 3.23 | 3.3  |
| 362  | 3.4  | 2.5  | 3.2  | 2.9  |
| 363  | 4    | 2.88 | 3.38 | 3    |
| 364  | 3.93 | 3.21 | 3.38 | 3.1  |
| 365  | 3.67 | 2.38 | 3.15 | 2.8  |
| 366  | 3.4  | 3.58 | 3.85 | 3.9  |
| 368  | 3.2  | 3.04 | 2.33 | 3.17 |
| 369  | 3.73 | 3.04 | 3.67 | 3    |
| 370  | 3.4  | 2.83 | 4    | 3.5  |
| 371  | 3.13 | 2.79 | 2.88 | 2.7  |
| 372  | 3.13 | 3.25 | 3.27 | 3.1  |
| 373  | 3.4  | 2.75 | 3.19 | 2.9  |
| 374  | 3.2  | 3.17 | 3.2  | 3    |
| 377  | 2.6  | 2.58 | 3.12 | 3.1  |
| 378  | 3    | 3.08 | 3.23 | 3.5  |
| 394  | 3.2  | 1.67 | 2.62 | 2.3  |
| 395  | 3.47 | 2.58 | 3.04 | 2.9  |
| 397  | 4.6  | 3.5  | 3.92 | 3.4  |
| 398  | 3.67 | 2.54 | 2.64 | 2.7  |
| 404  | 3.07 | 3.25 | 3.54 | 3.8  |
| 406  | 3    | 2.38 | 3.19 | 2.9  |
| 408  | 3.67 | 2.29 | 3.27 | 2.7  |
| 409  | 3.73 | 2.92 | 3.65 | 3.2  |
| 484  | 3.27 | 3.21 | 3.81 | 3.4  |
| 485  | 3.13 | 2.63 | 3.54 | 2.8  |
| 486  | 3.4  | 3.17 | 3.69 | 3.3  |
| 487  | 3.07 | 2.92 | 3.96 | 3.4  |
| 489  | 2.47 | 1.58 | 3.85 | 3    |
| 498  | 3.73 | 3.13 | 3.12 | 3.1  |
| 500  | 3.93 | 3.21 | 4.12 | 4.2  |
| 502  | 3.8  | 2.96 | 3.85 | 2.8  |
| 504  | 2.8  | 3.25 | 3.54 | 3.4  |
| 506  | 3.47 | 3.33 | 4.12 | 3.7  |
| 508  | 3.07 | 2.96 | 3.27 | 2.9  |
| 509  | 2.27 | 3.17 | 2.81 | 3.3  |
| 510  | 3.6  | 3.17 | 3.35 | 3    |
| 511  | 3.33 | 3.13 | 4.38 | 3.8  |
| 512  | 2.93 | 2.67 | 3.04 | 2.6  |
| 513  | 3    | 3.08 | 3.73 | 3.7  |
| 514  | 3.4  | 2.96 | 3.38 | 3.6  |
| 519  | 2.73 | 3.33 | 3.5  | 3.5  |
| 520  | 3.8  | 3.58 | 4    | 3.7  |
| 533  | 3.87 | 3.21 | 3.19 | 3.1  |
| 534  | 3.73 | 3.33 | 4.04 | 3.7  |
| 536  | 3.2  | 2.58 | 2.92 | 2.6  |
| 537  | 3.33 | 2.29 | 2.81 | 3.2  |
| 539  | 3.87 | 2.88 | 3.88 | 3.5  |
| 540  | 3.47 | 2.83 | 2.92 | 3    |
| 541  | 3.47 | 2.46 | 3.35 | 3.3  |
| 545  | 3.53 | 1.96 | 3.58 | 3.1  |
| 546  | 2.67 | 2.92 | 2.96 | 2.9  |
| 547  | 3.87 | 4.04 | 4.08 | 3.9  |
| 550  | 3.2  | 3.54 | 3.35 | 3.6  |
| 553  | 3.47 | 2.17 | 3.92 | 3.2  |
| 556  | 3.67 | 3.67 | 3.4  | 3.1  |
| 557  | 2.73 | 2.96 | 3.15 | 3.2  |

Prior to conducing the hierarchical multiple regression, the relevant assumptions of this 
statistical analysis were tested.  As the collinearity statistic (i.e., VIF) was within accepted limits, 
the assumption of multicollinearity was deemed to have been met (Coakes, 2005; Hair et al., 
1998).  Residual and scatter plots indicated the assumptions of normality, linearity and 
homoscedasticity were all satisfied (Hair et al., 1998; Pallant, 2001).

![screen reader text](QQ.jpg "Normality Test")


The regression statistic in Table 1. Model 1 was significant: F(1,174)=19.50. p<.001. Adding conscientiousness (i.e., Model 2) to the regression model explained 4% of the variance, which is the incremental validity of CONS. The change in R^2 was significant F(1, 173)= 7.85,p=.01. Adding a work sample (i.e model 3) did not contribute a significant change in R^2, and therefore did not contribute to significant incremental validity. Model 2 showed the smallest AIC and BIC, meaning this was the best model. 


Model 2 explained a significant amount of variance in job performance F(2,173)=14.00, p<.001. The two predictors are significant; structured interview, β = .27, t(173)=3.74,p<.001; CON, β =.20 t(173)=2.80, p=.01. The R^2 is 0.14 meaning that both predictors accounted for 14% of the variance in the job performance.


As the work sample did not provide significant incremental validity, it should not be used in the selection procedure. Structured interview had the largest beta weight, making it the best predictor of the two assessment tools.

**This project was run in {{< icon name="r-project" pack="fab" >}} R (a programming language for statistical computing and graphics) using the following code:**


```R
dat1<-Data_A7

cor(dat1[, 2:5], use="pairwise.complete.obs")

options(scipen=15)

m1 <- lm(PM ~ INT, data=dat1)                       # Model 1

m2 <- lm(PM ~ INT + CONS, data=dat1)                  # Model 2

m3 <- lm(PM ~ INT + CONS + WS, data=dat1)           # Model 3

vif(m3)                                                      ## VIF should be less than 10
plot(m3)

anova(m1, m2, m3)

glance(m1)                                     # To see AIC & BIC for model 1
glance(m2)                                     # To see AIC & BIC for model 2
glance(m3)

summary(m1)                                                  ## show the result
summary(m2)                                                  ## show the result
summary(m3)                                                  ## show the result

RS_change<-(summary(m2)$r.squared)-(summary(m1)$r.squared)
RS_change

dat2 <- scale(dat1[, 2:5])                                    ## transform to z-scores

dat2 <- data.frame(dat2)

m2S <- lm(PM ~ INT + CONS, data=dat2)
summary(m2S)
```


**Conclusion**

Hierarchical regression is a powerful statistical technique for analyzing employee data in human resources. By taking into account the relationship between variables, it allows researchers to identify the unique impact of each predictor on the dependent variable, while controlling for the effects of other predictors. When conducting a hierarchical regression analysis in human resources, it is important to define the dependent and independent variables, collect accurate data, choose the appropriate hierarchical model, and interpret the results appropriately
