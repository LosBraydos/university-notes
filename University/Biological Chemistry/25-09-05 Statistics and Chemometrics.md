
### Statistics 

Univariate Statistical Analysis
- Introduction to statistics
- Probability, Hypothesis (significance) testing
- Confidence intervals

Why Statistics?
- To validate experimental results
- To distinguish between true effects and random noise
- To construct working models for monitoring, control, diagnosis, and prognosis
- To screen for important variables in large multivariate data sets
	- Metabolomics, Genomics, Proteomics
	- Processes, Finance, Clinical Analysis

Important:
- Statistics can *not* be used as a substitute for knowledge. Should be used as a complement in order to make experimentation efficient and reliable
- Careless use of statistical methods lead to results based on chance/random correlations
- Properly used, statistics provide a set of powerful and reliable methods for data analysis in multiple fields

Why such a bad reputation?
- Hard to distinguish between correlation and causation
- Correlation between two variables often occurs because they are both associated with a third factor. They are correlated, but do not cause each other
- Look for causations nor for correlations!

Example: Coffee
Positive:
- Decrease risk of age related diabetes
- Positive effect on asthma
- Decreases risk for migraine
- Works as painkiller in women
- Decrease risk for skin cancer
Negative:
- Large amounts of acrylamide - carcinogenic
- Miscarriage

Contradictions?
- Aftonbladet writes acrylamide in coffee increases cancer risk.
- Next year they claim acrylamide in chips lowers cancer risk


Differences between groups can be due to...:
- Real differences
	What's really interesting!
- Systematic errors
	Fools us to fins "true" relationships that don't exist (must be minimised)
- Random variations
	Can be estimated by means of *confidence intervals* and be tested by means of *significance analysis*

How to know if the difference between averages of groups is caused by real effect or pure chance
	Significance testing (hypo test)


Null hypothesis (H0): Assume no significant difference
	H0: x1(average) = x2(average)

Alt hypo (HA): Assumes significant difference
	H0: x1(average) =/= x2(average)
	
Probability (p) value:
	Calculated giving the probability to get the observed measure values if H0 was true
If not enough evidence to reject H0, we can *not* assume that H0 is true.
Significance analysis can never tell that a certain treatment lacks effect, it can only tell that we haven't succeeded to prove that the treatment has got a significant effect

Example:
- Assumption: Vitamin C lowers bp significantly in patient group A compared to patient group B treated with a placebo
	H0: No significant difference
		xA(average) = xb(average)
	HA: Assume significant difference
		xA(average) =/= xb(average)
	P = 0.02: 2% chance that HA is wrong => HA is accepted with 98% significance
		Significant difference in bp between A and B
	P= 0.2: 20% chance that HA is wrong
	H0 is retained, no significant difference between A and B


Choosing the right test is important!
	The wrong test can lead to obviously (or not) wrong results.
	- Independent test vs Dependent test (test for average of difference for all groups)

Dependent test
	ex: H0: delta(average) = 0
	HA: delta(average) =/= 0


Type I and II errors:

|             | H0 false      | H0 true      |
| ----------- | ------------- | ------------ |
| H0 reject   | OK            | Type I error |
| H0 accepted | Type II error | OK           |
Type I: false negative
Type II: false positive

Type I dangerous when:
	Does a drug have an effect on a certain disease state?
	Significant analysis says Yes, the truth says No
Type II dangerous when:


Confidence intervals:
	A measure of uncertainty occurring from chance when we try to estimate the average of the studied population
	All values within a confidence interval are equally probable based on a chosen level of significance (often 95%)
		- If all values between groups are equally probable on a 95% level, the difference xA(average) - xB(average) is equally likely to be 0 as any other value within the interval

Size of confidence interval is decided by...
- The confidence level (99% give wider interval than 95%)
- Random variation present
	- Large amount of random variation gives high standard error (SE) leading to wider interval
- Number of samples

Summary:
- Statistics is powerful i fu sed correctly. Also dangerous if used incorrectly
- Hypothesis testing were used to look for significant difference between group averages (independent) or effects different from zero (dependent)
- Confidence intervals


### Chemometrics
Maps to understand and optimise (chemical) processes
	Combines Math, Statistics, and Chemistry
	Well used in industry such as Pharma, Pulp/Paper, Food, etc. Also in Biology and Medicine

Models:
	How to understand complicated mathematical models in a simple way?
	Experiment -> Data -> Model (equation) -> Model (map) -> Experiment

