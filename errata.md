---
layout: page
title: Exam Errata
description: Corrections and additional explanations of exam solutions
nav_order: 8
---

# Exam Errata

When the teaching team notices incorrect or unclear answers in earlier exam solutions, we will document them here. This way, the original answer key is left as-is, but we can help guide students around any stumbling blocks.
We will also add comments about ambiguous questions, or any other commentary that might be helpful for students.

## Midterm 1

### MT1 Fall 2018

#### Q2

You can answer parts (a) and (b) by taking a look at the "Q2 Handout"", which was passed out with the Midterm 1 itself (both of these are linked to from the [Resources page]({{ site.baseurl }}/resources/)).

#### Q3.e: 

Solution typo: plot is "dodge" 

### MT1 Fall 2020

#### Q12.5: 

Solution typo: ln(5000) = 8.52. 

#### Q14.4: 

Solution typo: answer is "No Endo"

### MT1 Spring 2021

#### Q4.1: 

Correct answer: B, D

#### Q5i: 

Solution: Age is classified as a continuous variable because the range of possible values is continuous, even though the table does not display decimal values. 

### MT1 Fall 2021

### MT1 Fall 2022

#### Q6: 

Solution typo: D = 85


## Midterm 2

### MT2 Fall 2018

#### Q5:

Solution typo: Binomial equation missing from the prompt. P(X = k) = (n k)(0.67)^k(0.33)^(n-k)

#### Q5.4:

Solution typo: P(X = 5000)

#### Q6.1:

Solution typo: 0.47/√1000 = 0.0149

### MT2 Fall 2020

### MT2 Spring 2021

#### Q4:

Solution typo: n = 3

### MT2 Fall 2021

#### Q1.b:

Complete solution: 
No; if these two events were independent, then we would expect the conditional probability of a randomly chosen person getting Alzheimer's to be the same across all cognitive risk assessment score ranges (the value should just be equal to the probability of choosing a person who develops Alzheimer's, or P(A)). However, as shown below, this is not the case:
 P(A) = 0.42
 P(A | 0-1) = 0
 P(A | 1-2) = 3/17 = 0.176
Note: Students can show independence in multiple ways -- they can compare the probability of developing Alzheimer's across multiple risk score ranges or by comparing one with the probability of getting Alzheimer's.

### MT2 Fall 2022

#### Q12.c: 

Solution: The null value mu_0 = 4 is _not_ contained in the 95% confidence interval (6.5, 7.0), so we have evidence to reject the null hypothesis. The true mean counseling time is likely greater than 4 minutes. 

## Final Exam

### Final Fall 2020

#### Q6: 

Solution: The solution provides the answer for "Chi-sq test for goodness of fit" but the question prompt asks for "Chi-sq test for independence". The correct answer for Chi-square test for independence should be: "Two categorical variables (or K≥2 groups of a categorical explanatory variable and a categorical response variable)"

#### Q7.c: 

Solution: The solution should be 3.766/2. 

#### Q9.4:

Solution: The question asks for: a) mA for people with blonde hair, b) mA for people with brown hair, and c) mA for people with red hair. There is a mismatch in the solution, labeling them as A, B, C and giving them in this order: brown (19.87), blonde (15.25), red (10.02).

#### Q13.4: 

Solution: The 95% CI is (0.81, 1.15), which does NOT contain 0. Therefore, we REJECT the null hypothesis and conclude that there is a significant relationship between BMI and diastolic blood pressure.

### Final Spring 2021 Takehome

#### Q2.1

The answer uses the Wald large-sample confidence interval, but the criteria are not met, since one cell in the table is not >= 10. So the "plus four" method should be used instead.

#### Q5.6

For finding the degrees of freedom for the `Residuals`, termed `BBB` in the problem, there is a typo in the solution. It should be 495, not 195. This found by taking the value of $N_{tot} - k$ . Also acceptable would be 494.06, which, from the lecture on ANOVA, we learned that $df = \frac{\text{sumseq}}{\text{meansq}}$ , and $494.06 = \frac{1042.47}{2.11}$ . The difference between these two answers is likely due to numerical round-off errors.

#### Q8.2

The answer key says the answer is C, Kruskal-Wallis, but the answer should be B, Wilcoxon Sign Rank, because the study design is using paired data to control confounders between men and women.

### Final Fall 2021

#### Q19.3

The answer says that the Wilcoxon Rank Sum test is the most appropriate choice. This may be so, but the stated reason is not correct. The $t$-test works just fine for small data-sets, as long as the assumptions of the $t$-test hold. So the answer is necessary, but by itself, not sufficient. So one's reasoning might be that since the problem doesn't mention anything about symmetry, central peak, lack of outliers, etc. we cannot assume that those conditions for the two-sample $t$-test hold. Thus, you can fall back to using the Wilcoxon Rank Sum test, which makes no such assumptions.

#### Q23

There is an error, in that -23 is declared to have a positive sign ("+"). It should have a negative sign ("-"). In that case, E is 3, F is 12.


### Final Fall 2023

#### Q12

These are proportions, so the answer key should be talking about $\hat{p}$, not $\mu$. Also, for Q12.4, the formula for Wald large-sample confidence intervals should be used, as we're dealing with the sampling distribution, not the population distribution.
