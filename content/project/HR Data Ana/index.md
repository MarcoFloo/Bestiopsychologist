---
title: HR Data Analytics
summary: Logistic Regression is a type of machine learning algorithm that is used to predict/forecast variables that are categorical in nature. It is used to solve classification tasks.
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

**My Start**: I am a beginner to the world of people analytics. As someone
exploring the capabilities of R and Tableau, I hope this marks the beginning of a journey
where I can share my abilities and learn from others. Feel free to write to me if you have
suggestions or you would like to see something added!

**Background Info About The Project:**


-Descriptive and Inferential Data Analysis: I am passionate about using the story telling
of data to better explain HR metrics. Although there might be trends or eye-catching
numbers at first glance, my goal is to dig deeper and understand what our data is really
showing. You cannot improve what you do not measure.

-Model with Machine Learning: The ultimate goal is to create a model to predict
whether an employee will quit or stay. Logistic regression is a statistical technique that
can differentiate which factors are more impactful towards a dichotomous outcome (e.g.,
to leave or to stay). Adding machine learning techniques then allows us to understand the
strength of our predictive model.

-Recommendations: How can the organization reduce turnover? This step is arguably the
most important since it connects data to organizational policy.
About this data set: IBM HR Analytics Attrition Data set is an excellent dataset to demonstrate
logistic regression and better understand attrition. Attrition is simply the turnover rate of
employees. This data is publicly available here.
Exploratory Analysis
What does our data show at a glance? We can make some interesting observations without using
advanced methods. Although Excel and R can be used for this process, Tableau produces
dynamic data visualizations. These analyses will also help us determine how we should work
with our data throughout the project.

-Overall, about 84% of the workforce stayed while about 16% left. We can visually see
this is a moderately imbalanced dataset. Knowing our dataset is skewed (not normally
distributed) helps us determine what further analyses we can conduct.

-Is there a wage gap? It seems both overall and among departments that there are no
major differences of the monthly average income between genders. This is good news for
both our employees and the organization!

-Here’s where things get interesting...

o Age cohorts: Gen-Z workers show the highest frequency of turnover rate at
around 36%- most likely to pursue other career opportunities. Boomers have the
next highest proportion of employees leaving at 17%- most likely to retire.

o Income: It seems that employees who left were paid less on average than those
who stayed. These differences were most significant within the HR and Research
and Development departments. (HR should know better!)

{{< figure src="download.jpg" caption="A caption" numbered="true" >}}


-What factors significantly relate to each other? A correlation matrix displays correlations
between 2 variables. Although this analysis can be conducted in Excel, R can sort the
significant correlations together! This feature can help us quickly visualize the strongest
relationships, rather than having to look around the entire visual.
What we see:



o The higher the job level, the higher the monthly income (r=.95).

o The higher the job level, the higher the total working years (r=.78).

o The higher the percent salary hike, the higher the performance (rating r=.77).

o The higher the total working years, the higher the monthly income (r=.77).

-Logistic Regression:
Logistic regression is a specialized linear model where regression weights (our input variables)
are interpreted on a log odds scale for a dichotomous outcome. We can use this technique to
calculate fit statistics and model evaluations.

-VIF: After categorizing and splitting our data, we should check if multicollinearity is
occurring between our input variables. The Variance Inflation Factor is a technique
which creates a linear model with 1 dependent variable against multiple independent
variables.

-We can see that “Job Level” produces the highest VIF score of 8.45, so we should
eliminate it. Normally a VIF score of 10 or higher serves as the cutoff. However, this
removal will increase the precision of our other independent variables and increases the
overall statistical power of our model.

-After removing “Job Level” from the data set, we can now see that none of our VIF
scores are close to approaching 10. Let’s create our final model!

-Interpreting the Model:

Let’s use machine learning to further evaluate our logistic regression model.
A Confusion Matrix is a classification model, using supervised learning, that allows us to
evaluate our linear model’s performance. The number of predicted and actual values are
displayed in the chart below. The top left corner shows the number of true positives, the top right
corner shows the number of false positives (Type 1 error) the bottom left corner shows the
number of false negatives (Type 2 Error), and the bottom right corner shows the number of true
negatives.

Overall, our model shows that from 294 example cases, 237 were correctly predicted to stay and
14 were correctly predicted to leave. 36 were falsely predicted to stay and 7 were falsely
predicted to leave. Compared to the dataset, our produced, linear model holds an impressive 85%
accuracy rating.

Since the data set is moderately imbalanced, relying on a model’s accuracy measure is
insufficient. Receiver Operating Characteristic Curve (ROC curves) plot true positive rates
[TP/(TP + FN)], which is the percentage of terms who were accurately classified as such, and we
want to maximize (i.e., sensitivity), against false positive rates [FP/(TN + FP)], which is the
percentage of non-terms who were classified as terms, and we want to minimize. We can
determine its strength by looking at the are under the ROC curve or AUC. The higher our AUC,
the better our model is classifying turnover as staying (1 as 1) and leaving (0 as 0).

-Top Reasons For Leaving:

-Monthly income.

-Longer Hours

-Lack Of Tenure


Recommendations:

-Incomes can be increased to increase retention. Although we don’t know this
organization’s overtime policy, either limiting the amount of overtime or increasing its
incentive could decrease turnover.

-If dates were provided for when employees started and left the organization, a survival
analysis could have been conducted to predict not only what causes an employee to leave,
but also when.

-While understanding why employees leave an organization is a great start, it is equally
important to understand why employees stay. Deploying an engagement survey can
provide additional insight for which factors keep employees at the organization.


-Why does this matter?:

HR professionals, managers, and C-Suite members generally believed seeking a higher income
was the key motivator, for employees quitting, during the Great Resignation. Our exploratory
visualizations seemed to support this belief, but analyzing our data tells a deeper story. In this
organization’s case, working overtime was the most impactful reason! Increasing salaries could
decrease the number of employees working overtime, but what if the organization is financially
constrained? Addressing the other significant variables could provide a more cost-effective and
personalized approach. Overall, using advanced, statistical models created a better judgment of
employees’ behavior to predict attrition.
