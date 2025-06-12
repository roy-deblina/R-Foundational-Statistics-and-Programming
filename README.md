# Foundational Statistics and Programming in R

## Project Overview
This project serves as a comprehensive demonstration of fundamental statistical concepts and their practical implementation in R. It covers a wide range of topics, from probability distributions and hypothesis testing to correlation and the Central Limit Theorem. A key component of this project is not just applying built-in R functions, but also manually calculating statistical metrics and building user-defined functions from scratch to showcase a deep, first-principles understanding of the underlying theory.

## Key Concepts & Skills Demonstrated
### 1. Probability Distributions & Approximations
#### Binomial, Poisson, and Normal Distributions:

Calculated exact probabilities using dbinom(), pbinom(), dpois(), and ppois().

Applied the Poisson distribution to approximate binomial probabilities, validating the conditions (n > 20, np < 7).

Used the Normal distribution to approximate binomial probabilities, correctly applying the continuity correction.

### Discrete Probability Distributions:

Manually calculated the Expected Value and Variance for a custom discrete probability distribution.

Computed and plotted cumulative probabilities to determine the median of the distribution.

### 2. Hypothesis Testing & Statistical Inference
#### Correlation Analysis (Kendall's Tau):

Tested the hypothesis of independence between consecutive waiting times in the faithful dataset using Kendall's rank correlation coefficient (cor.test()).

#### Two-Sample T-Test:

Compared the mean weights of two different chick diets (ChickWeight dataset) using a two-sided t-test, assuming equal variances.

#### Paired T-Test (from Scratch):

Manually calculated the test statistic, critical value, p-value, and a one-sided 95% confidence interval for paired data (chick weight gain) without using the built-in t.test() function.

#### Chi-Squared Test for Independence:

Performed a Chi-squared test on a contingency table (warpbreaks dataset) to test for independence between categorical variables.

Manually calculated the Chi-squared statistic and p-value to replicate the results of the built-in function.

### 3. Central Limit Theorem (CLT)
#### Demonstration of the CLT:

Generated thousands of random samples from the Nile river dataset with different sample sizes (n=16 and n=64).

Visualized the sampling distributions of the sample mean, showing convergence towards a normal distribution as the sample size increases.

Compared the histograms of the sample means to their corresponding normal density curves.

### 4. R Programming & Function Development
#### Data Manipulation:

Utilized subsetting, filtering, and data restructuring techniques (e.g., using matrix() to create paired data).

#### Data Visualization:

Created a variety of plots to explore data and present results, including bar plots, histograms with density overlays, QQ plots, boxplots, and scatterplots using Base R.

#### Custom Function Development:

Built a user-defined function from scratch to perform a Chi-Squared test, demonstrating the ability to translate statistical formulas into reusable R code.

### Datasets Used
faithful

ChickWeight

Nile

warpbreaks

### Tools Used
R & RMarkdown

Packages: datasets, moments
