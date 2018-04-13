
<!--

https://www.checkmarket.com/blog/how-to-estimate-your-population-and-survey-sample-size/

How to determine population and survey sample size?

A survey can only be truly valuable when it’s reliable and representative for your business. However, determining the ideal survey sample size and population can prove tricky. In other words, who will you be surveying and how many people? No idea? No worries. We’re here to help!

Say you’re a market research manager at a furniture company and you are planning to launch a new furniture line by the end of 2016. However, before you launch the new line you wish to conduct an online survey on whether your line ‘Fall – 2016’ is more or less likely to be a hit or miss on the European Union (EU) market. So far, so good. Yet, the following question will almost instantly arise: “What is the population that I would like to survey?”. Or, who do you need to survey to gain valuable insights in the success of your new furniture line? In this case the answer is rather straightforward. Assuming that you are launching the new line on the European market, that minors do not buy furniture and that your furniture is reasonably priced, your population consists of all adults in the EU.

What is the survey sample size?
For obvious reasons it is impossible to survey those (roughly) 400 million adults in the EU. A sample of adults living in the EU offers the solution for this issue. A sample is a selection of respondents chosen in such a way that they represent the total population as good as possible. However, instantly a new question comes to the forefront: “How many people should my sample consist of?”. Using a correct survey sample size is crucial for your research. After all, a sample that is too big will lead to the waste of precious resources such as time and money, while a sample that is too small will not allow you to gain reliable insights.

So, how large should your sample be? Should you survey 1%, 5%, 10%, … of the adult citizens in the EU? Well, this depends largely on how accurate you want your survey data to be. In other words, how closely you want your results to match those of the entire population. There are two measures that affect the accurateness of the data.

First of all there is the margin of error (or confidence intervals). In short, this is the positive and negative deviation you allow on your survey results for the sample. Or, in other words, the deviation between the opinions of your respondents and the opinion of the entire population. An example will shed some light on this statistical explanation. Suppose you set your margin of error on 5%. If – let’s hope so! – 90% of your survey respondents like the ‘Fall 2016’ line, a 5% margin of error means that you can be ‘sure’ that between 85% (90%-5) and 95% (90%+5) of the entire population actually likes the ‘Fall 2016’ line.
Second there is the confidence level. This tells you how often the percentage of the population that likes the ‘Fall 2016’ line actually lies within the boundaries of the margin of error. Or, following on our previous example, it tells you how sure you can be that between 85% and 95% of the population likes the ‘Fall 2016’ campaign. Suppose you chose the 95% confidence level – which is pretty much the standard in quantitative research1 – then in 95% of the time between 85% and 95% of the population likes the ‘Fall 2016’ line2.
How many respondents does your survey require?
Once you have decided how accurate you want your sample data to be, you can start calculating how many respondents (people who have completely filled in the survey or completes as we call them at CheckMarket) you actually need.

Below you find an indicative table on how to calculate your number of completes. Remember that your population consist of approximately 400 million adults in the EU. As a consequence, the appropriate number of completes will be found on the last row of the table below. Depending on the confidence level and the margin of error, the number of completes will vary. As we chose a margin of error of 5% and a confidence level of 95% for our ‘Fall 2016’ campaign, you need approximately 400 completes (it is advisable to round to the nearest hundred) for your sample.

Alternatively, on the CheckMarket website, you find an easy sample size calculator to calculate the number of completes…

![](https://www.checkmarket.com/wp-content/uploads/2013/02/estimate_population_survey_sample.gif)

What about response rate?
Before you start sending out your survey to 400 respondents, remember there is such a thing as response rate. Response rate is the ratio of respondents that fill in the questionnaire they received compared to the total number of surveys you send out. For instance, if you send out your survey to 400 people and you receive 200 filled in surveys, your response rate is 50%.

For an online survey, conventionally, a response rate of 20% is considered as a good response rate, while a 30% response rate is considered to be really really good. As we calculated that we need 400 completes, this means that you will definitely have to send the survey to more than 400 people in order to reach those 400 completes. Obviously, you cannot predict beforehand what response rate you will achieve. However, assuming that your survey will achieve a response rate of 20%, we divide the objective of 400 completes by a response rate of 20%. As a consequence, you will have to send your survey to approximately 2.000 adults in the EU.

1 In some quantitative research, stricter confidence levels are used (e.g. the 99% confidence level)
2 To put it more precisely: 95% of the samples you pull from the population.

-->

<!--
https://onlinecourses.science.psu.edu/stat500/book/export/html/29

Lesson 6 - Confidence Intervals for Population Proportions and Population Means
This lesson starts with the basic concept of using confidence intervals to understand and perform inference. We then talk about how to find confidence intervals for one population proportion. The important issue of determining the required sample size to estimate a population proportion will also be discussed in detail in this lesson.

Estimating the population mean is one of the most common and important questions one comes across in practice. In this lesson, we will also talk about the confidence interval for a population mean when the population standard deviation is unknown. We will also explain how to determine the number of observations to be included in the sample.

Lesson 6 Objectives

Upon successful completion of this lesson, you will be able to:

understand the reason for estimating with confidence interval.
calculate confidence intervals for population proportions.
interpret a confidence interval.
know the meaning of margin of error and its use.
compute sample sizes for different experimental setting.
know when and how to use t-interval to estimate the population mean.
compute sample sizes for estimating the population mean.
6.1 - Inference for the Binomial Parameter: Population Proportion
Unit Summary

Introduction to Inferences
Estimation
Properties of 'Good' Estimators
General Format and Interpretation of a Confidence Interval
Inferences on the Binomial Parameter p
Confidence Interval for Binomial Parameter, p
Assumptions to be Checked When Using the Z-interval for Estimating Binomial Parameter
The Derivation of the Confidence Interval
When Conditions are NOT satisfied
More on the Interpretation of a Confidence Interval
reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (see Course Schedule).

 

Introduction to Inferences
The real power of statistics comes from applying the concepts of probability to situations where you have data. The results, called statistical inference, give you probability statements about the population of interest based on that set of data.

There are two types of statistical inferences:

1. Estimation

Use information from the sample to estimate (or predict) the parameter of interest.

Using the result of a poll about the president's current approval rating to estimate (or predict) his or her true current approval rating nationwide.

2. Statistical Test

Use information from the sample to determine whether a certain statement about the parameter of interest is true.

Think about the following, then click on the icon to the left to display an answer.


  Give an example about statistical test:

Estimation
We begin our discussion on inference with estimation.  Two common estimation methods are point estimates (e.g. sample proportion or sample mean), and confidence intervals.  The latter is a new concept which be the focus of this lesson.  Such intervals are built around point estimates which is why understanding point estimates is important to understanding confidence intervals.

 

Properties of 'Good' Estimators
In determining what makes a good estimator, there are two key features.

1. The center of the sampling distribution for the estimate is the same as that of the population.  When this property is true, the estimate is said to be unbiased.  The most often-used measure of the center is the mean.

2. Smallest standard error when compared to other estimators.  For example, in the normal distribution the mean and median are essentially the same.  However, the standard error of the median is about 1.25 times that of the standard error of the mean.  We know the standar error of the mean is \(\sigma / \sqrt{N}\).  Therefore in a normal distribution, the SE(median) is about 1.25 times \(\sigma / \sqrt{N}\).  This is why the mean is a better estimator than the median when the data is normal (or approximately normal). 

 

General Format and Interpretation of a Confidence Interval
In putting the two proporties together, the center using the point estimate and the standard error of this estimate, we can include a measure of confidence to our error to form a margin of error.  This you may have readily seen whenever you have heard or read a sample survey result (e.g. a survey of current approval rating of the President, or attitude citizens have on some new policy).  In such surveys you may hear reference to the "44% of those surveyed approved of the President's reaction" (this is the sample proportion), "and the survey had a 3.5% margin or error, or ± 3.5%." This latter number is the margin of error.  In putting these two together, we have an interval for which the group conducting the survey is confident the parameter value falls (i.e. the proportion of U.S. citizens who approve of the President's reaction).  In this example, that interval would be from 40.5% to 47.5%  This example provides the general construction of a confidence interval:

sample statistic ± margin of error

The margin of error will consist of two pieces.  One is the standard error of the sample statistic.  The other is some multiplier of this standard error based on how confident we want to be in our estimate.  This multiplier will come from the same distribution as the standard error; for example, as we will see with the sample proportion this multiplier will come from the standard normal distribution.  Some might say, "Why not just be 100% confident?", but that does not make practical sense.  For instance, what value comes from me saying I am 100% confident that the approval rating for the President is from 0% to 100%.  That is the only interval in which one can be truly confident will capture the actual proportion.  Similarly, if you were to ask your professor what they think your score will be on an exam and they reply, "zero to one hundred" what would you think of that answer? 

However, one does want to be as confident as reasonable possible.  Most confidence levels used range from 90% confidenct to 99% confidence, with 95% being the most widely used.  In fact, when you read a resport that includes a margin of error, you can usually assume this has a 95% confidence attached to it unless otherwise stated. 



The interpretation of a confidence interval has the basic template of: "We are 'some level of percent confident' that the 'population of interest' is from 'lower bound to upper bound'.  The phrases in single quotes are replaced with the specific language of the problem.  For instance, see point 4 in the first example.





Inferences on the Binomial Parameter p 
The point estimate of p is:

\[\hat{p}=\frac{\mbox{# of success in the sample}}{\mbox{# of samples}}= \frac{y}{n}\]

If one wants to know how accurate the sample proportion is to estimate the population proportion, we need some probability statement and thus we want to know the sampling distribution of \(\hat{p}\). From this distribution, we can get a confidence interval.  Such an interval provides a range of value for which the parameter value is believed to fall.  An interval is more likely to be "correct" than a point estimate.

Useful Notation

\(Z_\alpha\) is the z-value having a tail area of \(\alpha\) to its right. With some calculation, one can use Standard Normal Cumulative Probability Table to find the value.



Z0.15 = 1.04
Z0.08 = 1.40
Z0.02 = 2.05

Some commonly used \(\alpha\) values are (0.1, 0.05, and 0.01, 0.005, 0.001). and from the Standard Normal Table we to find \(Z_\alpha\) to be:



Z0.1 = 1.28
Z0.05 = 1.645
Z0.01 = 2.326



Confidence Interval for the Binomial Parameter
 A confidence interval is an interval of values computed from sample data that is likely to cover the true parameter of interest.

Recall the important fact:

If \(n p\geq 5\) and \(n (1-p)\geq 5\) then \(\hat{p}\) is approximately normal with mean π and standard deviation \(\sqrt{\frac{p (1-p)}{n}}\) .   

NOTE: This topic refers back to the lesson on Sampling Distribution of the Sample Proportion.  We listed '5' as the minimal accepted value, with more conservative values now in practice of 10 or 15. 



Assumptions to be Checked when using the Z-interval for Estimating Binomial Parameter
One-sample Z-interval for the population proportion, p.

Assumptions needed to check before one can use the one-sample z-interval for π :
\(n \hat{p}\geq 5\) ; \(n (1-\hat{p})\geq 5\) (i.e. number of successes and number of failures both greater than or equal to 5)

\((1 - \alpha )\) 100% confidence interval for \(\pi\) is :
\(\hat{p} \pm z_{\alpha/2} \sqrt{\frac{\hat{p}\cdot (1-\hat{p})}{n}}\), where \(Z_{\alpha/2}\) represents a z-value with \(\alpha/2\) area to the right of it.

NOTE: Previously we used the population proportion p instead of \(\hat{p}\).  Why?  Because then we had an idea what that parameter was.  Now, however, we are trying to estimate that value; that is, we do not know the population proportion.  We need to adjust by using the estimate, in this case the sample proportion.

 

Where did this \(Z_\alpha\) come from? The Derivation of the Confidence Interval
The confidence interval can be derived from the following fact:

\[P\left(-z_{\alpha/2} \leq \frac{\hat{p}-p}{\sqrt{\frac{\hat{p}(1-\hat{p})}{n}}} \leq z_{\alpha/2}\right)=1-\alpha\]

After some algebraic manipulations:

\[P\left(\hat{p}-z_{\alpha/2} \cdot \sqrt{\frac{\hat{p}\cdot (1-\hat{p})}{n}} \leq p \leq \hat{p}+z_{\alpha/2} \cdot \sqrt{\frac{\hat{p}\cdot (1-\hat{p})}{n}} \right)=1-\alpha\]

 



Example:  Presidential Approval Rating
image of the seal of the President of the United StatesA random sample of 1500 U.S. adults is taken.  They are asked whether they approve or disapprove of the current president's performance so far (i.e. an approval rating).  Of the 1500 surveyed, 660 respond with "approve".  Calculate a 95% confidence interval for the overall approval rating of the the president.

1. Check conditions.  Since a confidence interval, we can examine the number of "successes" and the number of "failures".  In this example there were 660 successes and 840 failures (found by N - number of successes).  With both successes and failures being at least 5, the condition to use the z-method to calculate the interval is acceptable.

2. Find the \(Z_{\alpha/2}\) multiplier for the level of confidence.  For 95% confidence, the alpha value is 5% or 0.05  The multiplier would be a z-value with α/2, or 0.025 area to the right of it.  Examining the standard normal table, we find that this corresponds to a z-value of 1.96

3. Complete the formula for the confidence interval.  In this example, we have a sample proportion, \(\hat{p}, of 660/1500 = 0.44 and a sample size, n, of 1500. 

\[\hat{p} \pm z_{\alpha/2} \sqrt{\frac{\hat{p}\cdot (1-\hat{p})}{n}} = 0.44 \pm 1.96 \sqrt{\frac{0.44\cdot (1-0.44)}{1500}}= 0.44 \pm 0.025 = 0.415 \leq p \leq 0.465\]

4. Provide an interpretation of the interval.  "We are 95% confident that the overall U.S. adult approval rating for the current  president is from 41.5% to 46.5%."  You could also see this written as, "The current U.S. approval rating for the president is 44% with a 95% margin of error of 2.5%."  Commonly, the standard level of confidence is 95% so that reference is often left out as that is the assumed level of confidence unless otherwise stated.  Also, the method calculates a proportion but often the reported values are converted to percentages.  If you use the decimal formal (e.g. 0.415 and 0.465) then reference these as proportion and not percentage.

Here is Dr. Bulathsinhala reviewing the correct interpretation of a confidence interval for this example.





We want to know the proportion of graduate students at Penn State who are Democrats.

To answer the question, we give out the following survey:

Are you a Democrat? Please circle one answer.

Yes	No
Suppose that we get 10 people that circled Yes and 20 people that circled No (that includes the case when people don't know whether they are Democrats!!)

Let X = the number of successes (number of students who chose Yes) = 10

n = number of trials = 30

\[\hat{p}=\frac{10}{30}=0.33\]

Now, compute a 90% confidence interval for p .

Checking assumptions?
A 90% confidence interval for p is?
What is the interpretation of this interval?
Work out your answer first, then click the graphic to compare answers.

What Can One Do if the Conditions are NOT Satisfied? 
For a confidence interval for a proportion, there is a technique called exact methods.  These methods can be used if the software offers it.  These exact methods are more complicated and are based on the a relationship between the binomial and another distrubution we will later learn called the F-distribution.  The Z-method is much simpler and fairly easy to compute.  In fact if you ever come across a published random survey (e.g. a Gallup poll) you can use the methods in this lesson to construct a reliable proportion confidence interval rather quickly.

 

More on the Interpretation of a Confidence Interval 
In the graph below, we draw 10 replications (for each replication, we sample 30 students and ask them whether they are Democrats) and compute an 80% Confidence Intervals each time. We are lucky in this set of 10 replications and get exactly 8 out of 10 intervals that contain the parameter. Due to the small number of replications (only 10), it is quite possible that we get 9 out of 10 or 7 out of 10 that contain the true parameter. On the other hand, if we try it 10,000 (a large number of) times, the percentage that contains the true porportions will be very close to 80%.



If we repeatedly draw random samples of size n from the population where the proportion of success in the population is π and calculate the confidence interval \(\hat{\pi} \pm z_{\alpha/2}\sqrt{\frac{\hat{\pi}\cdot (1-\hat{\pi})}{n}}\) each time, we would expect that 100(1 - α)% of the intervals would contain the true parameter, π .

 

6.2 - Sample Size Computation for Population Proportion Confidence Interval
Unit Summary

Margin of Error
Determining the Required Sample Size
Cautions About Sample Size Calculations
reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (See Course Schedule).

 
Margin of Error
Note: The margin of error E is half of the width of the confidence interval.

\[E=z_{\alpha/2}\sqrt{\frac{\hat{p}\cdot (1-\hat{p})}{n}}\]

Confidence and precision (we call wider intervals as having poorer precision): Note that the higher the confidence level, the wider the width (or equivalently, half width) of the interval and thus the poorer the precision.

 

 One television poll stated that the recent approval rating of the president is 72%; the margin of error of the poll is plus or minus 3%. [For most newspapers and magazine polls, it is understood that the margin of error is calculated for a 95% confidence interval (if not stated otherwise). A 3% margin of error is a popular choice.]

If we want the margin of error smaller (i.e., narrower intervals), we can increase the sample size. Or, if you calculate a 90% confidence interval instead of a 95% confidence interval, the margin of error will also be smaller. However, when one reports it, remember to state that the confidence interval is only 90% because otherwise people will assume a 95% confidence.

Determining the Required Sample Size
If the desired margin of error E is specified and the desired confidence level is specified, the required sample size to meet the requirement can be calculated by two methods:

a. Educated Guess

\[n=\frac {(z_{\alpha/2})^2 \cdot \hat{p}_g \cdot (1-\hat{p}_g)}{E^2}\]

Where \(\hat{p}_g\) is an educated guess for the parameter π.

b. Conservative Method

\[n=\frac {(z_{\alpha/2})^2 \cdot \frac{1}{2} \cdot \frac{1}{2}}{E^2}\]

This formula can be obtained from part (a) using the fact that:

For 0 ≤ p ≤ 1, p (1 - p) achieves its largest value at \(p=\frac{1}{2}\).

The sample size obtained from using the educated guess is usually smaller than the one obtained using the conservative method. This smaller sample size means there is some risk that the resulting confidence interval may be wider than desired. Using the sample size by the conservative method has no such risk.

 For the next poll of the president's approval rating, we want to get a margin of error of 1% with 95% confidence. How many individuals should we sample? (In the last poll his approval rate was 72%).

a. Educated Guess (use if it is relatively inexpensive to sample more elements when needed.)

Z0.025 = 1.96, E = 0.01

Therefore, \(n=\frac{(1.96)^2 \cdot 0.72\cdot 0.28}{(0.01)^2}=7744.66\) .

The sample size needed is 7745 people (we always need to round up to the next integer when the result is not a whole number).  Why?  Because we are estimating the smallest sample size needed to produce the desired error.  Since we cannot sample a portion of a subject - e.g. we cannot take 0.66 of a subject - we need to round up to guarantee a large enough sample).

b. Conservative Method (use if the start-up cost of sampling is expensive and thus it is not economical to sample more elements later).

\(n=\frac{(1.96)^2 \cdot 0.5\cdot 0.5}{(0.01)^2}=9604\)

The sample size is 9604 people.

Cautions About Sample Size Calculations
1. Why do we need to round up?  Because we are estimating the smallest sample size needed to produce the desired error.  Since we cannot sample a portion of a subject - e.g. we cannot take 0.66 of a subject - we need to round up to guarantee a large enough sample.

2. Remember that this is the minimal sample size needed for our study.  If we encounter a situation where the response rate is not 100% then if we just sample the calculated size, in the end we will end up with a less than desired sample size.  To counter this, we can adjust the calculated sample size by dividing by an anticipated response rate.  For instance, using the above example if we expected about 40% of the those contacted to actually participate in our survey (i.e. a 40% response rate) then we would need to sample 7745/0.4=19,362.5 or 19,363.  In other words, our actually sample size would need to be 19,363 given the 40% response rate.

Minitab logo
Minitab Commands to Find the Confidence Interval for a Population Proportion
Stat > Basic Statistics > 1 proportion.
Select the Summarized data option button.
Enter the Number of trials and Number of successes (events).
Click the Options button and type the confidence level.
If you want to use normal approximation, check the box. The exact interval is always appropriate. Under the conditions that: \(n \hat{\pi}\geq 5\), \(n (1-\hat{\pi})\geq 5\), one can also use the z-interval to approximate the answers. The exact interval and the z-interval should be very similar when the conditions are satisfied.
Minitab Movie icon Click on the 'Minitab Movie' icon to display a walk through of 'Find a Confidence Interval for a Population Proportion in Minitab'.

 At the Centre Community Hospital is State College, Pennsylvania, it is observed that 185 out of 360 babies born last year were girls. If we assume that this situation is representative of birth gender in the United States, give a 95% confidence interval for the true proportion of baby girls in the United States.

try it! Try to figure out your answers first, then click the graphic to compare answers.

 a. Hand Computation. 

b. Use Minitab to obtain the exact interval:

The exact interval is (0.4609, 0.5666).

We can see that the two intervals found in (a) and (b) are quite close to each other.

try it!
If 3 out 5 randomly sampled premature babies survived, obtain a 95% confidence interval for the survival rate of premature babies at the Center Community Hospital.

 

6.3 - Inference for the Population Mean
Unit Summary

Inferences for the Population Mean When the Population Standard Deviation is Unknown
t-Distribution
General Comments About Confidence Intervals
reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (See Course Schedule).

 

Inferences for the Population Mean When the Population Standard Deviation is Unknown
Note: This case is realistic whereas the \(\sigma\) known case is unrealistic.

It is true that when population is normal or when the sample size is large,

\[\frac{\bar{X}-\mu}{\sigma/\sqrt{n}}=Z\]

where Z has a standard normal distribution.

Usually, we don't know \(\sigma\), what can one do then? One way is to estimate \(\sigma\) by s (the standard deviation of the sample) and replace \(\sigma\) by s in the above equation . However, this new quotient no longer has a z-distribution.  Intead it has a t-distribution. We call the following a studentized version of \(\bar{X}\):

\[\frac{\bar{X}-\mu}{s/\sqrt{n}}=t\]

t-Distribution
In 1908, Gosset from Guiness Breweries discovered the t-distribution. His pen-name was Student and thus it is called the "Student's t-distribution".

Note: The t-distribution is different for different sample size, n. Thus, tables as detailed as the standard normal table are not provided in usual statistics books. A more concise table is provided for various degrees of freedom.



Properties of the t-distribution:

t is symmetric about 0
t distribution is more variable than the z distribution
t distributions are different for different degrees of freedom (d.f.), in this case d.f. = n - 1.
As n → \(\infty\) , t → z
The meaning of \(t_\alpha\) is the t-value having area "\(\alpha\)" to the right of it.

How do we use the t-table? (We include a similar table, T Table here so that you can print the table out and refer to it easily when working on the homework.)


Try to figure out your answer first, then click the graphic to compare answers.

try it!
Find t0.05 where the degree of freedom is 20 (recall that the degree of freedom = n - 1). 

 

try it!
Find t0.05 where the degree of freedom is 34. 

When the corresponding degree of freedom is not given in the table, you can use the value for the closest degree of freedom that is smaller than the given one. We use this approach since it is better to err in a conservative manner (get a t-value that is slightly larger than the precise t-value). For a precise t-value, use Minitab as indicated below.

Using Minitab to Find t-values When df NOT Found on Table
When the degrees of freedom are on the t-table we can use the table to find the t-value to use as the multiplier in our calculation of a confidence interval for a population mean.  But what do we do when the degrees of freedom are not on the table?  The t-table degrees of freedom run continuously from 1 to 30, then go by intervals after 30 (e.g. after 30 we have 35).  In such cases we can use software such as Minitab to find a more exact value for the multiplier opposed to using a degrees of freedom that is "close". 

Also, when the sample size is larger than 30, the t-values are not that different from the z-values. Thus, a crude estimate for t0.05 with 34 degrees of freedom is z0.05 = 1.645.

Minitab logo How to use Minitab to obtain t0.05 with degrees of freedom not on table
For this example we will use DF of 34.  Then using the Minitab we select:

Calc > Probability Distributions > t...

Choose Inverse cumulative probability and enter the degree of freedom and also the input constant as 1 - 0.05 which is 0.95.

Minitab t distribution dialog box

The output of the Minitab will give the value:

Inverse Cumulative Distribution Function

Student's t distribution with 34 DF

P ( X ≤ x )
x
0.9500
1.69092
Thus, t0.05 = 1.69092

The one sample t-interval for \(\mu\) when \(\sigma\) is unknown:

If:

Normal population or large sample
\(\sigma\) is unknown
A 100 (1 - α)% CI for μ is: 

\[\bar{x} \pm t_{\alpha/2}\cdot \frac{s}{\sqrt{n}}\]

where the t-distribution has df = n - 1.

(Recall that the Central Limit Theorem implies that \(\bar{X}\) is normal (even though X is not normal)when \(n \geq 30\). Thus, for a large sample, there is no need to check normality of X.)

image of a hospital bedExample: Emergency Room Wait Time
You are interested in the average emergency room (ER) wait time at your local hospital.  You take a random sample of 50 patients who visit the ER over the past week.  From this sample, the mean wait time was 30 minutes and the standard deviation was 20 minutes.  Find a 95% confidence interval for the average ER wait time for the hospital.

To begin, first check conditions:

1. Is the population data normal?  We don't know.  However, recalling the Empirical Rule (the 68-95-99.7% Rule) we know that if the data were bell shaped that about 95% of the observations would fall within two standard deviations of the mean.  With out sample mean of 30 and SD of 20, for this rule to apply then 95% of the observed wait times would have to fall from negative 10 minutes to positive 70 minutes.  Since one cannot experience a negative wait time, there can be no wait times less than zero.  This would indicate that the data would not come from a normal distribution.  However, the sample size is 50 which exceeds our minimal requirement of 30 in order to use the t-interval.

2. The population standard deviation is unknown; we only know the sample standard deviation. 

Having satisfied the conditions we proceed by finding the proper multiplier from the T-table.  With n of 50 the d.f. are 49, and for 95% confidence the alpha value is 5% or 0.05.  From the T-table under the column 0.025 (remember we use α/2) and a d.f. of 40 (since 49 is not on table), we arrive at a t-value of 2.021  Completing our confidence interval formula,

\(\bar{x} \pm t_{\alpha/2}\cdot \frac{s}{\sqrt{n}}\) = \(30 \pm 2.021\cdot \frac{20}{\sqrt{50}}\) = \(30 \pm 5.72\)= \(24.28 \leq μ \leq 35.72\)

Interpreting our interval: We are 95% confident that mean emergency room wait time at our local hospital is from 24.28 minutes to 35.72 minutes. 

Reflecting back on on interpretation of a proportion interval, we see the same basic structure: level of confidence, parameter of interest, lower and upper bounds.



The mean length of certain construction lumber is supposed to be 8.5 feet. A random sample of 81 pieces of such lumber gives a sample mean of 8.3 feet and a sample standard deviation of 1.2 feet.

\(\bar{X}\) = 8.3, s = 1.2

Try to figure out your answer first, then click the graphic to compare answers.

try it!
What is the 95% CI for "mean length of such lumber?" 

 

try it!
What is the 99% CI for "mean length of such lumber?" 

General Comments About Confidence Intervals
Confidence and precision (we call wider intervals having poorer precision): Note that the higher the confidence level, the wider the width of the interval and thus less precision.  As you consider confidence intervals think about how they are affected by changes in level of confidence, sample size, standard deviation.  In essence, you want to consider how such changes would affect the standard error.  If they would increase the error, the interval would widen; if decrease error, the interval narrows.

6.4 - Sample Size Computation for the Population Mean
Unit Summary

Margin of Error: Half Width of the Interval
Sample Size Computation for Population Mean
 

reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (See Course Schedule).

 

Margin of Error: Half Width of the Interval
A \(100(1 - \alpha)%\) CI for \(\mu\) is:

 \[\bar{x}-t_{\alpha/2}\cdot \frac{s}{\sqrt{n}},\ \bar{x}+t_{\alpha/2}\cdot \frac{s}{\sqrt{n}}\]

where the t-distribution has df = n - 1.

Thus, margin of error, sometimes denoted as E, is equal to:

\[E=\frac{t_{\alpha/2}\cdot s}{\sqrt{n}}\]

Sample Size Computation for Population Mean
How many graduate students should one sample if one wants to estimate the average height of PSU graduate students?

To determine the sample size, one first decides the confidence level and the half width of the interval one wants. Then we can find the sample size to yield an interval with that confidence level and with a half width not more than the specified one.

 The cruder method to find the sample size:

\[n=(\frac{z_{\alpha/2}\cdot \sigma}{E})^2\]

rounded up to the next whole integer.

Try to figure out your answer first, then click the graphic to compare answers.

try it!
A marketing research firm wants to estimate the average amount a student spends during the Spring break. They want to determine it to within \$120 with 90% confidence. One can roughly say that it ranges from \$100 to \$1700. How many students should they sample?  

Margin of error = E = ?
\(\sigma\) ≈ ?
Sample size needed is ?

Note: In homework and exams, it is fine if you simply use the cruder method. A more accurate method is provided in the following for your reference only.

 A more accurate method to estimate the sample size: iteratively evaluate the formula since the t value also depends on n.

\[n=(\frac{t_{\alpha/2}\cdot s}{E})^2\]

Start with an initial guess for n, plug in the formula, and iteratively solve for n.

If the initial guess for n is 20, t0.05 = 1.729 for degree of freedom = 19, then

\[n=\frac{(t_{\alpha/2})^2 \cdot s^2}{E^2}=\frac{(1.729)^2\cdot {400}^2}{(120)^2}=33.21\]

For n = 34, degree of freedom = 33, and t0.05 = 1.697

\[n=\frac{(t_{\alpha/2})^2 \cdot s^2}{E^2}=\frac{(1.697)^2\cdot {400}^2}{(120)^2}=31.95\]

If we use n = 32, the result is the same. Thus, the more accurate answer to the example is to sample 32 students.

6.5 - Conditions to Check Before One Can Use the t-Interval
Unit Summary

Conditions When One Can Use t-Procedure for Population Mean
Using Normal Probability Plot to Check Normality
What to Do If One Cannot Use the t-Procedure
reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (See Course Schedule).

 

Conditions When One Can Use t-Procedure for Population Mean
When the population standard deviation is unknown, one uses s to estimate the population standard deviation. The resulting interval is the one sample t-interval. Conditions to use the t-interval are:

When sample size is less than 15, use t-interval procedure only when population is very close to normal.
When sample size is between 15 and 30, it can be used if the variable is not far from normal.
When sample size is large, we can always use t-interval if there are no extreme outliers that cannot be removed.
Using Normal Probability Plot to Check Normality
For small sample size, if the distribution is not normal or if there are outliers, then one needs to use other procedures such as nonparametric methods.

Thus, if sample size is less than 30, one needs to use normal probability plot to check whether the sample may come from a normal distribution and then follow the above guideline to determine whether one can use the t-interval.

image of a rattlesnakeExample: Rattlesnake Lengths
It is very time consuming to find rattlesnakes and nerve racking to measure them. A scientist randomly finds 12 snakes from the Central Pennsylvania area and measures their length (snakes.txt). The following twelve measurements in inches are obtained:

40.2	43.1	45.5	44.5	39.5	38.5
40.2	41.0	41.6	43.1	44.9	42.8
Using the above data, find a 90% confidence interval for the mean length of rattlesnakes in the Central Pennsylvania area.

Think about what conditions you need to check.

Answer: The sample size is only 12. Let's do a normal probability plot to check whether the data may come from a normal distribution.

Minitab logoCreating a Normal Probability Plot in Minitab
With the data from the snakes.txt input into a Minitab worksheet, from the main menu in Minitab select:

Minitab > Graph > probability plot

According to the Help in Minitab associated with the Normal Probability plot, "If the points fall within the confidence limits, then the data may come from a normal distribution.".

Here is the normal probability plot for the rattlesnake data. What do you conclude about whether they may come from a normal distribution?

Probability plot using snake length data

Since the points all fall within the confidence limits, there is no evidence to suggest that the data do not come from a normal distribution.

Now, we can proceed to find the 90% t-interval for the mean length of rattlesnakes in the Central Pennsylvania area since even though the sample size is less than 30, the normality plot shows that the data may come from a normal distribution. In the following, we show how to use Minitab to find the t-interval:

Enter the twelve measurements into one column (name it length for this example)
Stat > Basic Statistics > 1-Sample t
Click in the variable (length for this example) and change the confidence level to the desired level
Minitab Movie icon Click on the 'Minitab Movie' icon to view a walk through of 'Finding a 90% Confidence Interval for a Continuous Data in Minitab'.

The output is given in the window session. (You can highlight the part you want to copy and then choose Edit > copy and then paste that to your document.)

T Confidence Intervals

Variable	
N
Mean
StDev
SE Mean
90.0 % CI
length	
12
42.075
2.257
0.652
(40.905, 43.245)
Example: CD Player Lifetime
To obtain the lifetime of his new CD player, a manufacturer uses 10 randomly selected CD players and he obtains the following data in hours (CD_lifetime.txt):

230	4122	4135	4356	3987
4562	3578	4598	3789	4397
Using the above data, find a 90% confidence interval for the mean lifetime for this model of CD player.

Think about what conditions you need to check.

Answer: The sample size is only 10.

Use the normal probability plot to determine whether one can use the t-interval to find the confidence interval. What is your conclusion?

CD lifetime probability plot

Since some points do fall outside the confidence limits, the plot suggests that the data do not come from a normal distribution.

What to Do If One Cannot Use the t-Procedure
What will you do if you cannot use the t-interval?

You should at least develop a healthy skepticism about the validity of the t-interval to be used for this problem. You may look for a more robust procedure such as the one-sample Wilcoxon procedure.

6.6 - Using Software for Confidence Intervals
Minitab logo Minitab Commands to Find the Confidence Interval for a Population Proportion
Stat > Basic Statistics > 1 proportion.
From the  drop down box select the Summarized data option button.  (If you have the raw data you would use the default drop down of One or more samples, each in a column.)
Enter the number of successes in the Number of Events text box, and the sample size in the Number of Trials text box.
Click the Options button. The default confidence level is 95.  If your desire another confidence level edit appropriately. 
To use the z- interval method choose Normal Approximation from the Method text box.  The exact interval is always appropriate and is the default. Under the conditions that: \(n \hat{p}\geq 5\), \(n (1-\hat{p})\geq 5\), one can also use the z-interval to approximate the answers. The exact interval and the z-interval should be very similar when the conditions are satisfied.
Click OK and OK again.
Minitab Movie icon Click on the 'Minitab Movie' icon to display a walk through of 'Find a Confidence Interval for a Population Proportion in Minitab'.

image of the seal of the President of the United StatesExample: Presidential Approval Rating
Referring to our presidential approval rating example at the beginning of this lesson, we will use Minitab to verify our by-hand results.  Recall in that example a random sample of 1500 was taken from the population of U.S. adults, with 660 responding with a positive approval.   In Minitab and following the steps above, we would enter 660 for the Number of Events and 1500 for the Number of Trials.  The confidence level was 95% and we satisfied the necessary conditions to use the Normal Approximation (or z-interval) method.  The results are:

Test and CI for One Proportion

Sample    X     N    Sample p            95% CI
1          660   1500  0.440000   (0.414880, 0.465120)

Using the normal approximation.

These results closely match our by-hand interval of 0.415 to 0.465

What if we had calculated the exact confidence interval (i.e. did not choose Normal Approximation as the method)?  With the exact method the interval is (0.414685, 0.465550).  Consistent to three decimal places in this case.  You will notice that in the output Minitab does provide a notification that the normal approximation was used.

How different can the normal approximation and exact intervals be when conditions are not satisfied?  Consider this example: In estimating the proportion of premature babies born at the local hospital, a random sample of 10 newborn babies was taken in which 3 were born prematurely.  Find a 90% confidence interval for the true proportion of premature babies born at the hospital. 

As we can see the conditions to use normal approximation method is not satisfied; we only have 3 successes and we need at least 5.  If we used normal approximation methods (note that we are constructing 90% intervals now), Minitab produces an interval of (0.061638, 0.538362).  If the exact method were used, the interval is (0.087264, 0.606624).  The intervals are nearly as close as in the first example.

Also note how wide the intervals are in this second example.  This is a direct result of the small sample size.  The smaller n produces a much a larger error which increases the width of an interval. 

Minitab logoMinitab Commands to Find the Confidence Interval for a Population Mean (sigma unknown)
Stat > Basic Statistics > 1-Sample t.
From the  drop down box select the Summarized data option button.  (If you have the raw data you would use the default drop down of One or more samples, each in a column.)
Enter the sample size, sample mean, and sample standard deviation in their respective text boxes. 
Click the Options button. The default confidence level is 95.  If your desire another confidence level edit appropriately. 
Click OK and OK again.
image of a hospital bedExample: Emergency Room Wait Time
Referring to our prior example of average emergency room wait time from our discussion on confidence intervals for a population mean, our by-hand calculations produced a 95% confidence interval of 24.28 to 35.72 minutes.  Recall the following for that example: sample size 50, sample mean 30, and sample standard deviation 20.  In Minitab following the above steps, we get a 95% confidence interval:

One-Sample T 
 N   Mean  StDev  SE Mean      95% CI
50  30.00  20.00     2.83       (24.32, 35.68)

The slight discrepancy between the estimates is due to our by-hand calculation using the t-value associated with 40 degrees of freedom since the table did not include a d.f. of 49.  Minitab used a t-value for the actually 49 degrees of freedom. With the larger degrees of freedom comes a smaller t-value.  This would result in a smaller margin of error and a narrower interval - precisely what we have here.

Minitab logoUsing Minitab to Check Normality
This Minitab process was presented in the lesson for finding confidence intervals for a population mean.  It is repeated here for convenience.  For small sample size, if the distribution is not normal or if there are outliers, then one needs to use other procedures such as nonparametric methods.  Thus, if sample size is less than 30, one needs to use normal probability plot to check whether the sample may come from a normal distribution and then follow the above guideline to determine whether one can use the t-interval.

Graph > Probability Plot > Simple (note: if we have summarized data only we cannot plot the data!)
Select the column that contains the data you want to graph. 
Click OK.
image of a rattlesnakeExample: Rattlesnake Lengths
It is very time consuming to find rattlesnakes and nerve racking to measure them. A scientist randomly finds 12 snakes from the Central Pennsylvania area and measures their length (snakes.txt). The following twelve measurements in inches are obtained:

40.2	43.1	45.5	44.5	39.5	38.5
40.2	41.0	41.6	43.1	44.9	42.8
The sample size is only 12. Let's do a normal probability plot to check whether the data may come from a normal distribution.  What do you conclude about whether they may come from a normal distribution?

Probability plot using snake length data

Since the points all fall within the confidence limits, there is no evidence to suggest that the data do not come from a normal distribution.



-->

<!--
https://www.itl.nist.gov/div898/handbook/prc/section2/prc263.htm

 
7. Product and Process Comparisons 
7.2. Comparisons based on data from one process 
7.2.6. What intervals contain a fixed percentage of the population values? 

7.2.6.3.
Tolerance intervals for a normal distribution
Definition of a tolerance interval	A confidence interval covers a population parameter with a stated confidence, that is, a certain proportion of the time. There is also a way to cover a fixed proportion of the population with a stated confidence. Such an interval is called a tolerance interval. The endpoints of a tolerance interval are called tolerance limits. An application of tolerance intervals to manufacturing involves comparing specification limits prescribed by the client with tolerance limits that cover a specified proportion of the population.
Difference between confidence and tolerance intervals	Confidence limits are limits within which we expect a given population parameter, such as the mean, to lie. Statistical tolerance limits are limits within which we expect a stated proportion of the population to lie.
Not related to engineering tolerances	Statistical tolerance intervals have a probabilistic interpretation. Engineering tolerances are specified outer limits of acceptability which are usually prescribed by a design engineer and do not necessarily reflect a characteristic of the actual measurements.
Three types of tolerance intervals	Three types of questions can be addressed by tolerance intervals. Question (1) leads to a two-sided interval; questions (2) and (3) lead to one-sided intervals.
What interval will contain p percent of the population measurements?
What interval guarantees that p percent of population measurements will not fall below a lower limit?
What interval guarantees that p percent of population measurements will not exceed an upper limit?
Tolerance intervals for measurements from a normal distribution	For the questions above, the corresponding tolerance intervals are defined by lower (L) and upper (U) tolerance limits which are computed from a series of measurements Yn,…,YN:
YL=Y¯−k2s;YU=Y¯+k2s
YL=Y¯−k1s
YU=Y¯+k1s where the k factors are determined so that the intervals cover at least a proportion p of the population with confidence, γ.
Calculation of k factor for a two-sided tolerance limit for a normal distribution	If the data are from a normally distributed population, an approximate value for the k2 factor as a function of p and γ for a two-sided tolerance interval (Howe, 1969) is
k2=ν(1+1N)z2(1−p)/2χ21−γ,ν−−−−−−−−−−−−−−−⎷,
where χ21−γ,ν is the critical value of the chi-square distribution with degrees of freedom ν that is exceeded with probability γ, and z(1−p)/2 is the critical value of the normal distribution associated with cummulative probability (1−p)/2.
The quantity ν represents the degrees of freedom used to estimate the standard deviation. Most of the time the same sample will be used to estimate both the mean and standard deviation so that ν=N−1, but the formula allows for other possible values of ν.
Example of calculation	For example, suppose that we take a sample of N = 43 silicon wafers from a lot and measure their thicknesses in order to find tolerance limits within which a proportion p = 0.90 of the wafers in the lot fall with probability γ = 0.99. Since the standard deviation, s, is computed from the sample of 43 wafers, the degrees of freedom are ν=N−1.
The reader can download the data as a text file.

Use of tables in calculating two-sided tolerance intervals	Values of the k2 factor as a function of p and γ are tabulated in some textbooks, such as Dixon and Massey (1969). To use the normal and chi-square tables in this handbook to approximate the k2 factor, follow the steps outlined below.
Calculate: (1−p)/2=(1−0.9)/2=0.05 and ν=N−1=43−1=42.
Go to the page describing critical values of the normal distribution. In the summary table under the column labeled 0.05, find
z(1−p)/2=z0.05=−1.645.
Go to the table of lower critical values of the chi-square distribution. Under the column labeled 0.01 in the row labeled degrees of freedom = 42, find
χ21−γ,ν=χ20.01,42=23.650.
Calculate
k2=ν(1+1N)z2(1−p)/2χ21−γ,ν−−−−−−−−−−−−−−−⎷=42(4443)(−1.645)223.650−−−−−−−−−−−−−−−√=2.217.
The tolerance limits are then computed from the sample mean, Y¯, and standard deviation, s, according to case(1).

Important notes	The notation for the critical value of the chi-square distribution can be confusing. Values as tabulated are, in a sense, already squared; whereas the critical value for the normal distribution must be squared in the formula above.
Some software is capable of computing a tolerance intervals for a given set of data so that the user does not need to perform all the calculations. All the tolerance intervals shown in this section can be computed using both Dataplot code and R code. In addition, R software is capable of computing an exact value of the k2 factor thus replacing the approximation given above. R and Dataplot examples include the case where a tolerance interval is computed automatically from a data set.

Calculation of a one-sided tolerance interval for a normal distribution	The calculation of an approximate k factor for one-sided tolerance intervals comes directly from the following set of formulas (Natrella, 1963):
k1ab===zp+z2p−ab−−−−−−√a1−z2γ2(N−1)z2p−z2γN.
A one-sided tolerance interval example	For the example above, it may also be of interest to guarantee with 0.99 probability (or 99 % confidence) that 90 % of the wafers have thicknesses less than an upper tolerance limit. This problem falls under case (3). The calculations for the k1 factor for a one-sided tolerance interval are:
abk1===1−12(43−1)(2.3263)2=0.9356(1.2816)2−143(2.3263)2=1.51651.2816+(1.2816)2−(0.9356)(1.5165)−−−−−−−−−−−−−−−−−−−−−−√0.9356=1.8752.
Tolerance factor based on the non-central t distribution	The value of k1 can also be computed using the inverse cumulative distribution function for the non-central t distribution. This method may give more accurate results for small values of N. The value of k1 using the non-central t distribution (using the same example as above) is:
δk1==zpN−−√=1.281643−−√=8.4037tγ,N−1,δN−−√=12.2883443−−√=1.8740,
where δ is the non-centrality parameter.
In this case, the difference between the two computations is negligble (1.8752 versus 1.8740). However, the difference becomes more pronounced as the value of N gets smaller (in particular, for N≤ 10). For example, if N = 43 is replaced with N = 6, the non-central t method returns a value of 4.4111 for k1 while the method based on the Natrella formuals returns a value of 5.2808.
The disadvantage of the non-central t method is that it depends on the inverse cumulative distribution function for the non-central t distribution. This function is not available in many statistical and spreadsheet software programs, but it is available in Dataplot and R (see Dataplot code and R code). The Natrella formulas only depend on the inverse cumulative distribution function for the normal distribution (which is available in just about all statistical and spreadsheet software programs). Unless you have small samples (say N≤ 10), the difference in the methods should not have much practical effect.



-->

<!--


https://onlinecourses.science.psu.edu/stat500/book/export/html/38


Lesson 7 - Hypothesis Testing
As mentioned before, methods of making inferences about parameters is either estimating the parameter or testing a hypothesis about the value of the parameter. In this lesson we will introduce the concepts of hypothesis testing and then talk about the test for population proportion (instead of following the order of our textbook to talk first about hypothesis testing for population mean).

This lesson introduces the rejection region approach to hypothesis testing and compares it to the p-value approach. One sample t-test for population mean is introduced. The lesson is concluded by a discussion of computation of power and sample size for one sample t-test.

Lesson 7 Objectives

Upon successful completion of this lesson, you will be able to:

understand the concepts of hypothesis testing.
learn how to set up hypotheses.
learn how to perform hypothesis testing for population proportion by the p-value approach.
perform statistical test for population mean.
use confidence interval to draw conclusion about two-sided test.
learn how to calculate power and to choose the sample size for testing the population mean.
7.1 - Introduction to Hypothesis Testing
Unit Summary

Hypothesis Testing
Hypotheses and Test Statistics
The Null and Alternative Hypothesis
Choosing the Null and Alternative Hypotheses
The Logic of Hypothesis Testing
reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (See Course Schedule).

 

Hypothesis Testing
The second type of inference method - confidence intervals was the first, is hypothesis testing.  A hypothesis, in statistics, is a statement about a population where this statement typically is represented by some specific numerical value.  In testing a hypothesis, we use a method where we gather data in an effort to gather evidence about the hypothesis.  In hypothesis testing there are certain steps one must follow.  Below these are summarized into six such steps to conducting a test of a hypothesis.

1. Setting up two competing hypotheses - Each hypothesis test includes two hypothesis about the population.  One is the null hypothesis, notated as Ho, which is a statement of a particular parameter value.  This hypothesis is assumed to be true until there is evidence to suggest otherwise.  The second hypothesis is called the alternative, or research, hypothesis, notated as Ha.  The alternative hypothesis is a statement of a range of alternative values in which the parameter may fall.  One must also check that any assumptions (conditions) needed to run the test have been satisfied e.g. normality of data, independence, and number of success and failure outcomes.

2. Set some level of significance called alpha.  This value is used as a probability cutoff for making decisions about the null hypothesis.  As we will learn later, this alpha value represents the probability we are willing to place on our test for making an incorrect decision in regards to rejecting the null hypothesis.  The most common alpha value is 0.05  or 5%. Other popular choices are 0.01 (1%) and  0.1 (10%).

3. Calculate a test statistic. Gather sample data and calculate a test statistic where the sample statistic is compared to the parameter value.  The test statistic is calculated under the assumption the null hypothesis is true, and incorporates a measure of standard error and assumptions (conditions) related to the sampling distribution.  Such assumptions could be normality of data, independence, and number of success and failure outcomes.

4. Calculate probability value (p-value), or find rejection region - A p-value is found by using the test statistic to calculate the probability of the sample data producing such a test statistic or one more extreme.  The rejection region is found by using alpha to find a critical value; the rejection region is the area that is more extreme than the critical value.

5. Make a test decision about the null hypothesis -  In this step we decide to either reject the null hypothesis or decide to fail to reject the null hypothesis.  Notice we do not make a decision where we will accept the null hypothesis. 

6. State an overall conclusion - Once we have found the p-value or rejection region, and made a statistical decision about the null hypothesis (i.e. we will reject the null or fail to reject the null).  Following this decision, we want to summarize our results into an overall conclusion for our test.

 

Hypotheses and Test Statistics
We will continue our discussion by considering two specific hypothesis tests: a test of one proportion, and a test of one mean.  We will provide the general set up of the hypothesis and the test statistics for both tests.  From there, we will branch off into specific discussions on each of these tests.

In order to make judgment about the value of a parameter, the problem can be set up as a hypothesis testing problem.

 

The Null and Alternative Hypothesis
We usually set the hypothesis that one wants to conclude as the alternative hypothesis, also called the research hypothesis.

There are three types of alternative hypotheses:

1. The population parameter is not equal to a certain value.  Referred to as a "two-sided test".

2. The population parameter is less than a certain value.  Referred to as a "left-tailed test"

3. The population parameter is greater than a certain value.  Referred to as a "right-tailed test".

For all three alternatives, the null hypothesis is the population parameter is equal to that certain value.

Since hypothesis tests are about a parameter value, the hypotheses use parameter notation - p for proportion or \(\mu\) for mean - in their arrangement.  For tests of a proportion or a test of a mean, we would choose the appropriate alternative based on our research question.  Below are the possible alternative hypothesis from which we would select only one of them based on the research question.  The symbols \(p_0\) and \(\mu_0\) are just used in these general statements.  In practice, these get replaced by the parameter value being tested.  The examples following will illustrate.

1. The population parameter is not equal to a certain value.  Referred to as a "two-tailed test".

\(H_a: p \ne p_0\), or \(H_a: \mu \ne \mu_0\)

2. The population parameter is less than a certain value.  Referred to as a "left-tailed test"

\(H_a: p < p_0\), or \(H_a: \mu < \mu_0\)

3. The population parameter is greater than a certain value.  Referred to as a "right-tailed test".

\(H_a: p > p_0\), or \(H_a: \mu > \mu_0\)

 

The null hypothesis in each case would be:

\(H_0: p = p_0\), or \(H_0: \mu = \mu_0\)

 

 When debating the State Appropriation for Penn State, the following question is asked: "Are the majority of students at Penn State from Pennsylvania?" To answer this question, we can set it up as a hypothesis testing problem and use data collected to answer it. This example is about a population proportion and thus we set up the hypotheses in terms of p.  Here the value \(p_0\) is 0.5 since more than 0.5 constitute a majority.  The hypthoses set up would be a right-tailed test:

\(H_0: p = 0.5\) vs. \(H_a: p > 0.5\)

 A consumer test agency wants to see the whether the mean lifetime of a brand of tires is less than 42,000 miles as the tire manufacturer advertises that the average lifetime is at least 42,000 miles.  In this example, we are discussing a mean and therefore set up the hypotheses in terms of \(\mu\).  Here the value of \(\mu_0\) is 42,000.  With the consumer test agency wanting to research that the mean lifetime is below 42,000, we would set up the hypotheses as a left-tailed test:

\(H_0: \mu = 42,000\) vs. \(H_a: \mu < 42,000\)

 The length of a certain lumber from a national home building store is supposed to be 8.5 feet. A builder wants to check whether the shipment of lumber she receives has a mean length different from 8.5 feet.  In this example, we are discussing a mean and therefore set up the hypotheses in terms of \(\mu\).  Here the value of \(\mu_0\) is 8.5.  With the builder wanting to check if the mean length is different from 8.5, she would set up the hypotheses as a two-tailed test:

\(H_0: \mu = 8.5\) vs. \(H_a: \mu \ne 8.5\)

 A political news company believes the national approval rating for the current president has fallen below 40%.  In this example, we are discussing a proportion and therefore will set up the hypothesis in terms of p.  Here is the \(p_0\) value is 0.4 and the hypotheses would be set up as a left-tailed test:

\(H_0: p = 0.4\) vs. \(H_a: p < 0.4\)

 

Choosing the Null and Alternative Hypothesis
If the conditions necessary to conduct the hypothesis test are satistified, then we can use the formulas below to calculate the appropriate test statistic from our sample data.  These assumptions and test statistics are as follows:

Test of One Proportion: the conditions are that \(np_0\) and \(n(1- p_0\)) are at least 5.  If so, then the one proportion test statistic  is:

\[Z^{*} = \frac{\hat{p}-p_0}{\sqrt{\frac{p_0 (1-p_0)}{n}}}\]

Test of One Mean: the condition is that the data satisfies the conditions similar to those used for constructing a t-confidence interval for the mean.  Those were either the data comes from an approxmately normal distribution, or the sample size is large enough (at least 30), or a small sample size (less than 30) the data is not skewed or has outliers.  If any of these conditions are satisfied, the we can calculate the following test statistic:

\[t^{*} = \frac{\bar{x}-\mu_0}{S/\sqrt{n}}\]

NOTE - do not get too hung up on symbols.  We just want to use a notation that helps to remind us that these values are a test statstic.

 

The Logic of Hypothesis Testing
How do we decide whether to reject the null hypothesis?

If the sample data are consistent with the null hypothesis, then we do not reject it.
If the sample data are inconsistent with the null hypothesis, but consistent with the alternative, then we reject the null hypothesis and conclude that the alternative hypothesis is true.
 Referring back to the first example above, say we take a random sample of 500 Penn State students and find that 278 are from Pennsylvania. Can we conclude that the proportion is larger than 0.5?

Is 278/500 = 0.556 much bigger than 0.5? What is much bigger? This depends on the standard deviation of \(\hat{p}\) under the null hypothesis.

\[\hat{p}-{p}_0 =0.556-0.5=0.056\]

The standard deviation of  \(\hat{p}\), if the null hypotheses is true (e.g. when \(p_0 = 0.5\)) is:

\[\sqrt{\frac{p_0 (1-p_0)}{n}}=\sqrt{\frac{0.5 \cdot (1-0.5)}{n}}=\sqrt{\frac{0.5 \cdot (1-0.5)}{500}}\]

We can compare them by taking the ratio.

\[Z^{*} = \frac{\hat{p}-p_0}{\sqrt{\frac{p_0 (1-p_0)}{n}}}=\frac{0.556-0.5}{\sqrt{\frac{0.5 \cdot (1-0.5)}{n}}}=2.504\]

 In the lumber example above, the mean length of the lumber is supposed to be 8.5 feet. A builder wants to check whether the shipment of lumber she receives has a mean length different from 8.5 feet. If the builder observes that the sample mean of 61 pieces of lumber is 8.3 feet with a sample standard deviation of 1.2 feet. What will she conclude?

Is 8.3 very different from 8.5? This depends on the standard deviation of  \(\bar{X}\):

\[t^{*} = \frac{\bar{x}-\mu_0}{S/\sqrt{n}}=\frac{8.3-8.5}{1.2/\sqrt{61}}=-1.3\]

Thus, we are asking if -1.3 is very far away from zero, since that corresponds to the case when \(\bar{X}\) is equal to \(\mu_0\). If it is far away, then it is unlikely that the null hypothesis is true and one rejects it. Otherwise, one cannot reject the null hypothesis.

How do we determine whether to reject the null hypothesis? It depends on the level of significance \(\alpha\) (step 2 of conducting a hypothesis test), and the probability the sample data would produce the observed result.

7.2 - Terminologies, Type I and Type II Errors for Hypothesis Testing
Unit Summary

Type I and Type II Errors and the Setting Up of Hypotheses
A Fictitious Example on Hypothesis Testing
reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (See Course Schedule).

 

Type I and Type II Errors and the Setting Up of Hypotheses
How do we determine whether to reject the null hypothesis? It begins the level of significance α, which is the probability of the Type I error.

What is Type I error and what is Type II error?

When doing hypothesis testing, two types of mistakes may be made and we call them Type I error and Type II error.

Decision
Reality
\(H_0\) is true
\(H_0\) is false
Reject \(H_0\)
Type I error
Correct
Fail to Reject \(H_0\)
Correct
Type II error
If we reject \(H_0\) when \(H_0\) is true, we commit a Type I error. The probability of Type I error is denoted by: \(\alpha\).

If we fail to reject \(H_0\) when \(H_0\) is false, we commit a Type II error. The probability of Type II error is denoted by: \(\beta\).

Our convention is to set up the hypotheses so that Type I error is the more serious error.

image of a derelict houseExample: Building Inspections
An inspector has to choose between certifying a building as safe or saying that the building is not safe. There are two hypotheses:

Building is safe
Building is not safe
How will you set up the hypotheses? Remember to set it up so that Type I error is more serious.

\(H_0\) : Building is not safe
\(H_a\) : Building is safe

Decision
Reality
\(H_0\) is true
\(H_0\) is false
Reject \(H_0\)
Reject "building is not safe" when it is not safe (Type I error)
Correct
Fail to Reject \(H_0\)
Correct
Accept "building is not safe" when it is safe (Type II error)
image of a gavelA Fictitious Example on Hypothesis Testing
A man goes to trial and is tried for the murder of his ex-wife. He is acquitted in the criminal trial by the jury, but convicted in a subsequent civil lawsuit based on the same evidence. Does it make any statistical sense?

We can put it in a hypothesis testing framework. The hypotheses being tested are:

The man is guilty
The man is not guilty
First, let's set up the null and alternative hypotheses.

\(H_0\): Mr. Orangejuice is not guilty
\(H_0\): Mr. Orangejuice is guilty

Here we put "the man is not guilty" in \(H_0\) since we consider false rejection of \(H_0\) a more serious error than failing to reject \(H_0\).

Type I error is committed if we reject \(H_0\) when it is true. In other words, when the man is not guilty but found guilty.

\(\alpha\) = probability (Type I error)

Type II error is committed if we accept \(H_0\) when it is false. In other words, when the man is guilty but found not guilty.

\(\beta\) = Probability (Type II error)

What is the relationship between \(\alpha\) and \(\beta\) here? 

The smaller we specify the significance level, \(\alpha\) , the larger will be the probability, \(\beta\), of accepting a false null hypothesis.

 try it! Determine your answer first, then click the graphic to compare answers.

Why is there a discrepancy in the verdicts between the criminal court case and the civil court case? 

7.3 - Decision Making in Hypothesis Testing
Unit Summary

Two Methods for Making a Statistical Decision
Steps in a Conducting a Hypothesis Test
Rejection Region Approach to Hypothesis Testing for One Proportion Problem
P-value Approach to Hypothesis Testing
Comparing the P-Value Approach to the Rejection Region Approach
reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (See Course Schedule).

 

Two Methods for Making a Statistical Decision
There are two approaches for making a statistical decision regarding a null hypothesis.  One is the rejection region approach and the second is the p-value (or probability value) approach.  Of the two methods, the latter is more commonly used and provided in published literature.  However, understanding the rejection region approach can go a long way in one's understanding of the p-value method.  Regardless of method applied, the conclusions from the two approaches are exactly the same.  In explaining these processes in this section of the lesson, we will build upon the prior steps already discussed (i.e. setting up hypotheses, stating the level of significance α, and calculating the appropriate test statistic).

Let's start out here by having Dr. Wiesner walk through a comparison of the p-value approach with the rejection region approach to hypothesis testing.





Test statistic: The sample statistic one uses to either reject Ho (and conclude Ha) or not to reject Ho.

Critical values: The values of the test statistic that separate the rejection and non-rejection regions.

Rejection region: the set of values for the test statistic that leads to rejection of Ho.

Non-rejection region: the set of values not in the rejection region that leads to non-rejection of Ho.

P-value: The p-value (or probability value) is the probability that the test statistic equals the observed value or a more extreme value under the assumption that the null hypthothesis is true.

As mentioned previously in this lesson, the logic of hypothesis testing is to reject the null hypothesis if the sample data are not consistent with the null hypothesis. Thus, one rejects the null hypothesis if the observed test statistic is more extreme in the direction of the alternative hypothesis than one can tolerate. The critical values are the boundary values obtained corresponding to the preset α level. 

Steps in a Conducting a Hypothesis Test 
Although we listed these at the beginning of the lesson, we reiterate them here for convenience plus we are building on them.

Step 1. Check the conditions necessary to run the selected test and select the hypotheses for that test.:

If Z-test for one proportion: \(np_0 \geq 5\) and \(n(1 - p_0) \geq 5\)
If a t-test for one mean: either the data comes from an approximately normal distribution or the sample size is at least 30.  If neither, then the data is not heavily skewed and without outliers.
If One Proportion Z-test:

Two-tailed	 	Right-tailed	 	Left-tailed
\(H_0 : p = p_0\)	
OR
\(H_0 : p = p_0\)	
OR
\(H_0 : p = p_0\)
\(H_a : p \ne p_0\)	 	\(H_a : p > p_0\)	 	\(H_a : p< p_0\)
If One Mean t-test

Two-tailed	 	Right-tailed	 	Left-tailed
\(H_0 : \mu = \mu_0\)	
OR
\(H_0 : \mu = \mu_0\)	
OR
\(H_0 : \mu = \mu_0\)
\(H_a : \mu \ne \mu_0\)	 	\(H_a : \mu > \mu_0\)	 	\(H_a : \mu < \mu_0\)
Step 2. Decide on the significance level, \(\alpha\).

Step 3. Compute the value of the test statistic:

If One Proportion Z-test: \(Z^{*}=\frac{\hat{p}-p_0}{\sqrt{\frac{p_0(1-p_0)}{n}}}\)

If One Mean t-test: \(t^{*} = \frac{\bar{x}-\mu_0}{S/\sqrt{n}}\)

Rejection Region Approach to Hypothesis Testing
Step 4. Find the appropriate critical values for the tests using the Z-table for test of one proportion, or the t-table if a test for one mean.  REMEMBER: for the one mean test the degrees for freedom are the sample size minus one (i.e. n - 1). Write down clearly the rejection region for the problem.

One Proportion Z-test	One Mean t-test
two tailed Z test
Two-Tailed
Reject \(H_0\) if \(|Z^*| \geq Z_{\alpha/2}\)

two tailed t test
Two-Tailed
Reject \(H_0\) if \(|t^*| \geq t_{\alpha/2}\)

left-tailed z test
Left-Tailed
Reject \(H_0\) if \(Z^* \leq Z_{\alpha}\)	left-tailed t test
Left-Tailed
Reject \(H_0\) if \(t^* \leq t_{\alpha}\)
right-tailed z test
Right-Tailed
Reject \(H_0\) if \(Z^* \geq Z_{\alpha}\)

right-tailed t test
Right-Tailed
Reject \(H_0\) if \(t^* \geq t_{\alpha}\)
Step 5. Check to see if the value of the test statistic falls in the rejection region. If it does, then reject \(H_0\) (and conclude \(H_a\)). If it does not fall in the rejection region, do not reject \(H_0\).

Step 6. State the conclusion in words.

 

P-value Approach to Hypothesis Testing
Steps 1- Step 3. The first few steps (Step 0 - Step 3) are exactly the same as the rejection region approach.

Step 4. In Step 4, we need to compute the appropriate p-value based on our alternative hypothesis:

If \(H_a\) is right-tailed, then the p-value is the probability the sample data produces a value equal to or greater than the observed test statistic.

If \(H_a\) is left-tailed, then the p-value is the probability the sample data produces a value equal to or less than the observed test statistic.

If \(H_a\) is two-tailed, then the p-value is two times the probability the sample data produces a value equal to or greater than the absolute value of the observed test statistic.

Right-tailed	 	Left-tailed	 	Two-tailed
\(P(Z > Z*)\)	
OR
\(P(Z < Z*)\)	
OR
\(2 \times P(Z > |Z*|)\)
\(P(t > t*)\) at df = n-1	 	\(P(t < t*)\) at df = n-1	 	\(2 \times P(t > |t*|)\) at df = n-1
Step 5. Check to see if the p-value is less than the stated alpha value.  If it is, then reject \(H_0\) (and conclude \(H_a\)). If it is not less than alpha, do not reject \(H_0\).

Step 6. Conclusion in words.

Here is Dr. Wiesner working through an example that will help you understand what p-value is:



image of a map of pennsylvania with centre county highlightedExample:  Penn State Students from Pennsylvania
Continuing with our one-proportion example at the beginning of this lesson,  say we take a random sample of 500 Penn State students and find that 278 are from Pennsylvania. Can we conclude that the proportion is larger than 0.5 at a 5% level of significance?

A: Using the Rejection Region Approach
Step 1. Can we use the one-proportion z-test?

The answer is yes since the hypothesized value \(p_0\) is 0.5 and we can check that:

\(np_0 = 500 \times 0.5 = 250 \geq 5\),
\(n(1 - p_0) = 500 \times (1 - 0.5) = 250 \geq 5\).

Set up the hypotheses.  Since the research hypothesis is to check whether the proportion is greater than 0.5 we set it up as a one(right)-tailed test:

\(H_0: p = 0.5\)
\(H_a: p > 0.5\)

Step 2. Decide on the significance level, \(\alpha\).

According to the question, \(\alpha\) = 0.05.

Step 3. Compute the value of the test statistic:

\[\begin{align} Z^{*} &= \frac{\hat{p}-p_0}{\sqrt{\frac{p_0 (1-p_0)}{n}}}\\
&=\frac{0.556-0.5}{\sqrt{\frac{0.5 \cdot (1-0.5)}{500}}}\\
&=2.504\\
\end{align}\]

Step 4. Find the appropriate critical values for the test using the z-table. Write down clearly the rejection region for the problem. We can use the standard normal table or the last row of our t-table to find the value of Z0.05 since that last row for df = \(\infty\) (infinite) refers to the z-value.

From the table, \(Z_0.05\) is found to be 1.645 and thus the critical value is 1.645. The rejection region for the right-tailed test is given by:

\(Z* > 1.645\)

Step 5. Check whether the value of the test statistic falls in the rejection region. If it does, then reject \(H_0\) (and conclude \(H_a\)). If it does not fall in the rejection region, do not reject \(H_0\).

The observed Z-value is 2.504 - this is our test statistic.  Since Z* falls within the rejection region, we reject \(H_0\).

Step 6. State the conclusion in words.

With a test statistic of 2.504 and critical value of 1.645 at a 5% level of significance, we have enough statistical evidence to reject the null hypothesis.  We conclude that a majority of the students are from Pennsylvania.

B: Using the P-value Approach
Steps 1- Step 3. The first few steps (Step 1 - Step 3) are exactly the same as the rejection region approach.

Step 4. In Step 4, we need to compute the appropriate p-value based on our alternative hypothesis.  With our alternative hypothesis being right-tailed:

\[\begin{align}\\
p-value &= P(Z > Z^{*})\\
&= P \left( Z > \left|\frac {\hat{p}-p_0}{\sqrt{\frac{p_0 (1-p_0)}{n}}}\right| \right) \\
&= P \left( Z > \left|\frac{0.556-0.5}{\sqrt{\frac{0.5(1-0.5)}{500}}}\right| \right) \\
&= P(Z > 2.50)\\
&=0.0062\\
\end{align}\]

Step 5. Since p-value = 0.0062 < 0.05 (the α value), we reject the null hypothesis.

Step 6. Conclusion in words:

With a test statistic of 2.504 and p-value of 0.0062, we reject the null hypothesis at a 5% level of significance.  We conclude that a majority of the students are from Pennsylvania.

image of a stack of lumberExample: Length of Lumber
Continuing with our one mean lumber example from the beginning of this lesson, the mean length of the lumber is supposed to be 8.5 feet. A builder wants to check whether the shipment of lumber she receives has a mean length different from 8.5 feet. If the builder observes that the sample mean of 61 pieces of lumber is 8.3 feet with a sample standard deviation of 1.2 feet. What will she conclude?  Conduct this test at a 1% level of significance.

A: Using the Rejection Region Approach
Step 1. Can we use the one-mean t-test?

The answer is yes since the sample size of 61 is sufficiently large (greater than 30):

Set up the hypotheses (since the research hypothesis is to check whether the proportion is different from 0.25, we set it up as a two-tailed test):

\(H_0: \mu = 8.5\)
\(H_a: \mu \ne 8.5\)

Step 2. Decide on the significance level, \(\alpha\).

According to the question, \(\alpha\) = 0.01.

Step 3. Compute the value of the test statistic:

\[t^{*} = \frac{\bar{x}-\mu_0}{S/\sqrt{n}}=\frac{8.3-8.5}{1.2/\sqrt{61}}=-1.3\]

Step 4. Find the appropriate critical values for the test using the t-table. Write down clearly the rejection region for the problem. 

From the table and with degrees of freedom of 60 from 61 - 1, that the critical value at \(t_{\alpha/2} = t_{0.005}\) is found to be 2.660 and thus the critical value 2.660. The rejection region for the two-tailed test is given by:

\(t* < - 2.660\),  or \(t* > 2.660\)

Step 5. Check whether the value of the test statistic falls in the rejection region. If it does, then reject \(H_0\) (and conclude \(H_a\)). If it does not fall in the rejection region, do not reject \(H_0\).

The observed t-value is -1.3 - this is our test statistic.  Since t* does not fall within the rejection region, we fail to reject \(H_0\).

Step 6. State the conclusion in words.

With a test statistic of -1.3 and critical value of ± 2.660 at a 1% level of significance, we do not have enough statistical evidence to reject the null hypothesis.  We conclude that there is not enough statistical evidence that indicates that the mean length of lumber differs from 8.5 feet.

B: Using the P-value Approach
Steps 1- Step 3. The first few steps (Step 1 - Step 3) are exactly the same as the rejection region approach.

Step 4. In Step 4, we need to compute the appropriate p-value based on our alternative hypothesis:

\[\begin{align}p-value &= 2\times P(t > |t^{*}|) \\
&= 2\times P \left(t > \left|\frac{\bar{x}-\mu_0}{S/\sqrt{n}}\right| \right) \\
&= 2\times P \left(t > \left|\frac{8.3-8.5}{1.2/\sqrt{61}}\right| \right)  \\
&= 2\times P(t > |-1.3|) \\
&= 2\times P(t > 1.3)\\
\end{align}\]

Step 5. From the t-table going across the row for 60 degrees of freedom, we do not find a value equal to 1.3. Without software to find a more exact probability, the best we can do from the t-table is find a range.  We do see that the value falls between 1.296 and 1.671.  These two t-values correspond to right-tail probabilies of 0.1 and 0.05, respectively.  Since 1.3 is between these two t-values, then it stands to reason that the probability to the right of 1.3 would fall between 0.05 and 0.1.  Therefore, the p-value would be = \(2\times (0.05)\) and \(0.1)\) or from 0.1 to 0.2  With this range of possible p-values exceeding our 1% level of signficance for the test, we fail to reject the null hypothesis. 

Step 6. Conclusion in words:

With a test statistic of - 1.3 and p-value between 0.1 to 0.2, we fail to reject the null hypothesis at a 1% level of significance since the p-value would exceed our significance level.  We conclude that there is not enough statistical evidence that indicates that the mean length of lumber differs from 8.5 feet.

Comparing the P-Value Approach to the Rejection Region Approach
Both approaches will ensure the same conclusion and either one will work. However, using the p-value approach has the following advantages:

Using the rejection region approach, you need to check the table for the critical value every time people give you a different α value.
In addition to just using it to reject or not reject \(H_0\) by comparing p-value to α value, p-value also gives us some idea of the strength of the evidence against \(H_0\).
7.4 - Statistical Test Examples
Unit Summary

Statistical Test for Population Proportion and Population Mean
Statistical and Practical Significances
Using a Confidence Interval to Draw a Conclusion About a Two-tailed Test
reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (See Course Schedule).

 

Six Steps to Conducting a Statistical Test
The null and alternative hypotheses
Level of significance \(\alpha\)
Test statistics
Compute the p-value
Check whether to reject the null hypothesis by comparing p-value to \(\alpha\)
Conclusion in words
 A reminder of what is a p-value in hypothesis testing:  P-value is a probability of obtaining a value of the test statistic or a more extreme value of the test statistic assuming that the null hypothesis is true.

 Caution: Sometimes p-value is also referred to as the level of significance. One should be aware that \(\alpha\) (alpha) is also called level of significance. This makes for a confusion in terminology. α is the preset level of significance whereas p-value is the observed level of significance.  The p-value, in fact, is a summary statistic which translates the observed test statistic's value to a probability which is easy to interpret.

woman using a laptopExample:  Online Purchases
An e-commerce research company claims that 60% or more graduate students have bought merchandise on-line. A consumer group is suspicious of the claim and thinks that the proportion is lower than 60%. A random sample of 80 graduate students show that only 22 students have ever done so. Is there enough evidence to show that the true porportion is lower than 60%?  Conduct the test at 10% Type I error rate, and use the p-value and rejection region approaches.

Work out your answers to the questions below and then click on the icon to compare answers.

try it!
Set up the hypotheses for the consumer advocate, described above. Specify whether it is a left-tailed test, right-tailed test, or a two-tailed test. 

Now at this point we want to check whether the sample size is large enough so that we can use the one-proportion z-test.

try it!
Check the conditions below now.  1)  \(np_0 \geq 5\), and 2)   \(n(1 - p_0) \geq 5\)

Next, we can calculate the test statistic.

\[\hat{p} = \frac{22}{80} = 0.275\] \[Z^{*} = \frac{\hat{p}-p_{o}}{\sqrt\frac{p_{o}\times(1-p_{o})}{n}} = \frac{0.275-0.6}{\sqrt\frac{0.6\times0.4}{80}}=-5.93\]

try it!
Next find the rejection region for the level of significance and also the p-value for the test statistic. 

 

try it!
Finally, use the test statistic and p-value to make decision and overall conclusion. 

 

To determine whether the probability is small, we will compare it to the preset level of significance, which is the probability of Type I error. Recall that Type I error is the more serious error  - to reject the null hypothesis when that null hypothesis is true.  Think of finding guilty a person who is actually innocent.

When we specify our hypotheses, we should have some idea of what size Type I error we can tolerate. It is denoted as \(\alpha\). A conventional choice of \(\alpha\) is 0.05. Values ranging from 0.001 to 0.1 are also common and the choice of \(\alpha\) depends on the problem one is working on.

Or we can summarize the data by reporting the p-value and let the users decide to reject \(H_0\) or not to reject \(H_0\) for their subjectively chosen \(\alpha\) values. The p-value can also be called the observed level of significance and our book just sometimes refers to it as the level of significance. That may cause confusion and thus we recommend always calling it the p-value and reserve the term level of significance to represent the preset \(\alpha\) value.

image of a hospital bedExample: Emergency Room Wait Time
The administrator at your local hospital states that on weekends the average wait time for emergency room visits is 10 minutes.  Based on discussions you have had with friends who have complained on how long they waited to be seein in the ER over a weekend, you dispute the administrator's claim.  You decide to test you hypothesis.  Over the course of a few weekends you record the wait time for 40 randomly selected patients.  The average wait time for these 40 patients is 11 minutes with a standard deviation of 3 minutes.  Do you have enough evidence to support your hypothesis that the average ER wait time exceeds 10 minutes?  You opt to conduct the test at a 5% level of significance.

Work out your answers to the questions below and then click on the icon to compare answers.

try it!
Set up the hypotheses for the example described above. Specify whether it is a left-tailed test, right-tailed test, or a two-tailed test. 

At this point we want to check whether the data is approximately normal so we can use the one-mean t-test.

try it!
Check the condition.

Next, we can calculate the test statistic. 

\[t^{*}=\frac{\bar{x}-\mu_{0}}{S/\sqrt{n}}=\frac{11-10}{3/\sqrt{40}}=2.11\]

try it!
Next find the rejection region for the level of significance and also the p-value for the test statistic.  

try it!
Finally, use the test statistic and p-value to make decision and overall conclusion. 

  Statistical and Practical Significances
Our decision in this last example was to reject the null hypothesis and conclude that the average wait time exceeds 10 minutes.  However, our sample mean of 11 minutes wasn't too far off from 10.  So what do you think of our conclusion?  Yes, statistically there was a difference at the 5% level of significance, but are that "impressed" with the results?  That is, do you think 11 minutes is really that much different from 10 minutes?  Since we are sampling data we have to expect some error in our results therefore even if the true wait time was 10 minutes it would be extremely unlikely for our sample data to have mean of exactly 10 minutes. This is the difference between statistical significance and practical significance. The former is the result produced from the sample data while the latter is the practical application of those results.

Words of Caution
Critics of hypothesis-testing procedures have observed that a population mean is rarely exactly equal to the value in the null hypothesis and hence, by obtaining a large enough sample, virtually any null hypothesis can be rejected. Thus, it is important to distinguish between statistical significance and practical significance.

Statistical significance is concerned with whether an observed effect is due to chance and practical significance means that the observed effect is large enough to be useful in the real world.

To determine whether the probability is small, we will compare it to the preset level of significance, which is the probability of Type I error. Recall that Type I error is the more serious error  - to reject the null hypothesis when that null hypothesis is true.  Think of finding guilty a person who is actually innocent.

When we specify our hypotheses, we should have some idea of what size Type I error we can tolerate. It is denoted as \(\alpha\) . A conventional choice of \(\alpha\) is 0.05. Values ranging from 0.001 to 0.1 are also common and the choice of \(\alpha\) depends on the problem one is working on. Or we can summarize the data by reporting the p-value and let the users decide to reject \(H_0\) or not to reject \(H_0\) for their subjectively chosen α values.

Another one-proportion example - this example uses \(\pi\) in place of p to represent the proportion.  Note this changes nothing in the overall testing process.

A pharmaceutical company claims that a new treatment is successful in reducing fever in more than 60% of the cases. The treatment was tried on 40 randomly selected cases and 11 were successful. Do you think the company's claim is valid? (Can you reject the company's claim)

Work this our yourself and then review the video (no sound) below:



Using a Confidence Interval to Draw a Conclusion About a Two-tailed Test
The primary purpose of a confidence interval is to estimate some unknown parameter.  A secondary use of confidence intervals is to support decisions in hypothesis testing, especially when the test is two-tailed.  The essence of this method is to compare the hypothesized value to the confidence interval.  If the hypothesized value falls within the interval we fail to reject the null hypothesis.  If the hypothesized value falls outside the interval we reject the null hypothesis.  Let's look at a couple of examples.

For the two-tailed test:

\(H_0: \mu = \mu_0\)
\(H_a: \mu \ne \mu_0\)

The null hypothesis will be rejected at level α if and only if the value \(\mu_0\) does not fall within the (1 - \(\alpha\)) confidence interval for \(\mu\) .

 Recall our lumber example from the lesson on confidence intervals to show how to use a confidence interval to draw a conclusion about a two-tailed test. A 95% confidence interval for the mean lumber length was 8.03 feet to 8.57 feet.

For our two-tailed test the hypotheses were:

\(H_0: \mu = 8.5\)
\(H_a: \mu \ne 8.5\)

Since 8.5 falls within the 95% confidence interval, we cannot reject the null hypothesis at level 0.05.  In general, if the null value falls within the confidence interval we fail to reject the null hypothesis.  If the null value falls outside the confidence interval then we would reject the null hypothesis.

It is possible to use a one-sided confidence bound to draw a conclusion about a one-sided test, but you have to be very careful about obtaining the one-sided confidence bound.

7.5 - Power and Sample Size Determination for Testing a Population Mean
Unit Summary

Why Do We Need to Compute the Power of a Test?
Power and Type II Error of a Test
Choosing the Sample Size for Testing Population Mean
Using Minitab to Perform a One-Sample t-Test and to Compute Power
Last Words About Using Minitab's Power & Sample Size Tools
reading assignmentReading Assignment
An Introduction to Statistical Methods and Data Analysis, (See Course Schedule).

 

Why Do We Need to Compute the Power of a Test?
When the data indicate that one cannot reject the null hypothesis, does it mean that one can accept the null hypothesis? For example, when the p-value computed from the data is 0.12, one fails to reject the null hypothesis at \(\alpha\) = 0.05. Can we say that the data support the null hypothesis?

Answer: When you perform hypothesis testing, you only set the size of Type I error and guard against it. Thus, we can only present the strength of evidence against the null hypothesis. One can sidestep the concern about Type II error if the conclusion never mentions that the null hypothesis is accepted. When the null hypothesis cannot be rejected, there are two possible cases: 1) one can accept the null hypothesis, 2) the sample size is not large enough to either accept or reject the null hypothesis. To make the distinction, one has to check \(\beta\). If \(\beta\) at a likely value of the parameter is small, then one accepts the null hypothesis. If the \(\beta\) is large, then one cannot accept the null hypothesis.

The relationship between \(\alpha\) and \(\beta\) :

If the sample size is fixed, then decreasing α will increase \(\beta\) . If one wants both to decrease, then one has to increase the sample size.

 

Power and Type II Error of a Test
Power = the probability of correctly rejecting a false null hypothesis = \(1 - \beta\) .

 

Choosing the Sample Size for Testing Population Mean
 Refer to page 218 (edition 5) or pg 243 (edition 6) of our textbook to see the graphs that show the probability of Type II error.

Usually, acceptable values of power are larger than 0.7. One usually sets the power to be 0.8 or 0.85. Again, the acceptable values of power depend on the problem just as the value of α depends on the problem.

The following are interrelated: Power (which is \(1 - \beta\)), sample size, α , and the distance between the actual mean and the mean specified in the null hypothesis.

 

Using Minitab to Perform a One-Sample t-Test and to Compute Power
To calculate the smallest sample size needed for specified \(\alpha\) , \(\beta\) , \(\mu_a\) (\(\mu_a\) is the likely value of \(\mu\) at which you want to evaluate the power; \(\mu_a\) is chosen subjectively to reflect the likely value of \(\mu\) from the user's prior knowledge):

One-Tailed test:

\[n=\sigma^2 \frac{(t_\alpha + t_\beta)^2}{(\mu_0-\mu_a)^2}\]

Two-Tailed test:

\[n=\sigma^2 \frac{(t_{\alpha/2 }+ t_\beta)^2}{(\mu_0-\mu_a)^2}\]

Note: The above two formulas are included for your reference only. When you need to compute the sample size, you can simply use Minitab. The formula given in our book are the approximation to the above formula, replacing t by z.

Minitab logo Using Minitab to Compute the Sample Size or the Power
In the main menu in Minitab select:

Stat > power and sample size > 1-sample t

Note: The minimum difference referred to in Minitab is the difference between \(\mu_0\) and \(\mu_a\).

Note: One-sample t-tests are used to perform hypothesis tests of the mean.  To calculate power or sample size for these tests, you need to determine the minimum difference (effect) that you consider to be meaningful.  Then, you can determine the power or the sample size you need to be able to refhect the null hypothesis when the true value differs from the hypothesized value by this minimum difference.

Power and sample size for 1-Sample t Minitab Help

image of feet on a bathroom scaleExample: Weight Change
Weight change in pounds of 14 female subjects after taking an exercise program for six weeks are recorded:

17
7
-4
-18
2
9
12
9
-12
-9
-18
-14
-18
-20
Is there sufficient evidence that the average weight change is different from 0? (set \(\alpha\) = 0.05)

a. State the null and alternative hypothesis:

\(H_0 : \mu = 0\)
\(H_a : \mu \ne 0\)

b. Use Minitab to check whether the one-sample t-test may be used.

Now, the sample size is only 14 and thus we need to use the normal probability plot to check whether the data may come from a normal distribution.

With the 14 data points entered into Minitab, from the menu we can select Graph > probability plot

probability plot of data

We can see that we can use the t-test since the normal probability plot indicates that there is no evidence to suggest that the data do not come from a normal distribution.

c. Use Minitab to perform the test and draw a conclusion using the p-value.

From the Minitab menu select: Stat > Basic Statistics > 1-Sample t

Dialog box items:

Variables: Select the column(s) containing the variable(s) that you want to perform the hypothesis test.
Test mean: Choose to perform a one-sample t-test by checkind the box for Perform hypothesis test; then specify the null hypothesis test value by entering this value into the text box for Hypothesized mean.  For this example, enter the value 0
Click on Options... in the Confidence Level text box, type your desired confidence level (for this example, use 95). In the Alternative hypothesis text box, select the desired alternative hypothesis from: mean ≠ hypothesized mean, mean < hypothesized mean, mean > hypothesized mean. For this example, select mean ≠ hypothesized mean.

Here is the resulting output:

One-Sample T: C1

Test of μ = 0 vs ≠ 0

Variable	
N
Mean
StDev
SE Mean
C1	
14
-4.07
13.08
3.50
 	 	 	 	 
Variable	
95.0% CI
T
P
C1	
( -11.62, 3.48)
-1.16
0.265
Using Minitab, we see that the observed t-value is -1.16 and the p-value is 0.265 which is greater than \(\alpha\) = 0.05. We conclude that we cannot reject the null hypothesis.

There are two possible reasons for the failure of rejection of the null hypothesis:

the null hypothesis is reasonable, or
there's an insufficient sample size to achieve a powerful test.
We do not yet know which one is the real reason and thus proceed to compute the power of the test.

d. Use Minitab to compute the power \((1 - \beta)\) of the test at the likely value \(\mu_a = -5.0\).

Based on the computed power, would you accept the null hypothesis?

n = 14, \(\alpha\) = 0.05

Difference to detect is = 0 - (-5) = 5.

Using Minitab > Stat > power and sample size, we enter our sample information.  We had a sample size of 14 and the true difference we want to be able to detect is 5.  The sample standard deviation was 13.08.  Click Options to select the alternative of interest (Not Equal) and enter our Significance level (this is our alpha value).  When finished, click OK for the Options and OK again.  We find that power = 0.2635 which is the probability that we correctly reject the null hypothesis when the difference is truly at least 5.  This is not very good!  A common power value is 0.8 or 80 percent. The power is very low and we cannot accept the null hypothesis since the possible Type II error is \(\beta\) = 1 - power or 1 - 0.2635 = 0.7365. The possible Type II error is too high.  The most likely reason is that our sample size is too small to detect this difference with any reasonable power. [NOTE: The choice of '5' for the difference was a "researcher's decision".  There is specific reason we selected 5 other than for illustrative purposes in this example.  The difference one selects is just the smallest (minimum) difference the researcher wants to detect between the hypothesized population value and the actual value.]

power

e. Use Minitab to find how large a sample size is needed.

Suppose we want α = 0.05, power = 0.8, and the minimum detectable difference = 5?

From the Minitab output of the one-sample t-test, we see that the standard deviation is 13.08. We can thus estimate \(\sigma\) by 13.08 for the sample size computation problem:

Mintab dialog box for Power and Sample size for 1-sample t

Minitab gives us the following results:

Power and Sample Size

1-Sample t Test

Testing mean = null (versus no = null)
Calculating power for mean = null + difference
Alpha = 0.05 Sigma = 13.08

 	
Sample
Target
Actual
Difference
Size
Power
Power
5
56
0.8000
0.8024
Thus, we see that 56 samples need to be collected in order to draw meaningful results about this hypothesis testing problem.

Last Words About Using Minitab's Power & Sample Size Tools   
Gathering data is like tasting fine wine—you need the right amount. With wine, too small a sip keeps you from accurately assessing a subtle bouquet, but too large a sip overwhelms the palate.

We can’t tell you how big a sip to take at a wine-tasting event, but when it comes to collecting data, Minitab Statistical Software’s Power and Sample Size tools can tell you how much data you need to be sure about your results.  

7.6 - Using Software for Hypothesis Testing
Unit Summary

Conducting a One-Proportion Z-test in Minitab
Conducting a One-Mean t-test in Minitab
Finding Exact Critical Value for a One-Mean t-test in Minitab
Note about Software
In general, as we will learn, software usually performs tests using the p-value method.  That is, the output from software will provide the test statistic and the p-value, along with some other general information e.g. a confidence interval.  To perform rejection region tests you would need to find the critical values from the tables.  However, at the end of this lesson we do demonstrate how to find the correct critical value from the t distribution, i.e. the t-value that corresponds to the degrees of freedom when not on the table.

Minitab logoConducting a One-Proportion Z-test
Note: these steps are very similar to those for one-proportion confidence interval.  The differences occur in steps 4 and 5b.
Click Stat > Basic Stat > 1 Proportion.
In the drop-down box use "One or more samples, each in a column" if you have the raw data, otherwise select "Summarized data" if you only have the sample statistics.
If using the raw data enter the column of interest into the blank variable window below the drop down selection.  If using summarized data enter the number of successes for "Events" and the sample size for "Trials".
Click the check box for "Perform hypothesis test" and enter the null hypothesis value.
Click Options.
Enter the confidence level associated with alpha (e.g. 95% for alpha of 5%).
From the drop down list for "Alternative hypothesis" select the correct alternative.
If conditions are satisfied to perform a z-test for one proportion, select from the "Method" field "normal approximation"
Click OK and OK.
image of a map of pennsylvania with centre county highlightedExample:  Penn State Students from Pennsylvania
Recall our one-proportion example at the beginning of this lesson on whether the a majority of Penn State students are from Pennsylvania.  In that example, we took a random sample of 500 Penn State students and find that 278 are from Pennsylvania. Can we conclude that the proportion is larger than 0.5 at a 5% level of significance?  Also recall in that example we found by hand a test statistic of Z* = 2.504 and p-value of 0.0062.

Our hypotheses were: \(H_0: p = 0.5\) and \(H_a: p > 0.5\)

Using Minitab, we would select Stat > Basic Stat > 1 Proportion.  Choose the summarized data option and enter 278 for "Events" and 500 as the "Trials".   Check the box for Perform Hypothesis Test and enter the null value of 0.5  Click Options.  With our stated alpha value of 5% we keep the default confidence level of 95.  Select "Proportion > hypothesized proportion" from the Alternative Hypothesis list.  Since we verified the the conditions were satisfied, select Normal Approximation under Method.  Click OK and OK again.  The output is:

Test and CI for One Proportion 
Test of p = 0.5 vs p > 0.5

Sample    X    N     Sample p    95% Lower Bound  Z-Value  P-Value
1           278  500     0.556000         0.519451             2.50       0.006
Using the normal approximation.

As the output indicates, our by-hand calculations were very accurate!

Minitab logo
Conducting a One-Mean t-test
Note that these steps are very similar to those for one-mean confidence interval.  The differences occur in steps 4 and 5b

Click Stat > Basic Stat > 1 Sample t.
In the drop-down box use "One or more samples, each in a column" if you have the raw data, otherwise select "Summarized data" if you only have the sample statistics.
If using the raw data enter the column of interest into the blank variable window below the drop down selection.  If using summarized data enter the sample size, sample mean, and sample standard deviation in their respective fields.
Click the check box for "Perform hypothesis test" and enter the null hypothesis value.
Click Options.
Enter the confidence level associated with alpha (e.g. 95% for alpha of 5%).
From the drop down list for "Alternative hypothesis" select the correct alternative.
Click OK and OK.
image of a hospital bedExample: Emergency Room Wait Time
Recall our emergency room wait time example where an administrator at your local hospital states that on weekends the average wait time for emergency room visits is 10 minutes.  From our random sample of 40 patients, the average wait time for these 40 patients was 11 minutes with a standard deviation of 3 minutes.  We conducted the test at a 5% level of significance and wante to demonstrate that the average time exceeded 10 minutes.  Also recall in that example we found by hand a test statistic of  t* = 2.11 and p-value with a range between 0.01 to 0.025

Our hypotheses were: \(H_0: \mu = 10\) and \(H_a: \mu > 10\)

Using Minitab, we would select Stat > Basic Stat > 1 Sample t.  Choose the summarized data option and enter 40 for "Sample size", 11 for the "Sample mean", and 3 for the "Standard deviation".   Check the box for Perform Hypothesis Test and enter the null value of 10  Click Options.  With our stated alpha value of 5% we keep the default confidence level of 95.  Select "Mean> hypothesized mean" from the Alternative Hypothesis list.  Click OK and OK again.  The output is:

One-Sample T 
Test of μ = 10 vs > 10

 N     Mean   StDev  SE Mean   95% Lower Bound     T      P
40    11.000  3.000    0.474               10.201               2.11  0.021

Again, as the output indicates, our hand calculations were quite good.  Notice that Minitab provides a more exact p-value of 0.021 which corresponds to our results as it falls within our calculated range of 0.01 to 0.025.

Minitab logo
Finding Exact Critical Value for a One-Mean t-test
Since the t-table is not as detailed as the z-table, we can only estimate the critical value when the degrees of freedom are not found on the table.  In order to obtain the exact critical value to use in order to conduct the rejection region approach we can use a statistical package such as Minitab.

 Minitab commands to obtain critical value:

Calc > Probability Distributions > t-distribution
Choose the radio button for Inverse Cumulative Distribution (this finds the t-value that produces the entered probability to the left of it).
Enter the correct degrees of freedom
Choose the radio button for "Input constant" and enter the alpha value (if one-side alternative) or alpha/2 (if two-sided alternative).
Click Ok
Example: Emergency Room Wait Time
Find the exact critical value for our emergency room example.  Recall by hand that we had to use the row with 35 degrees of freedom instead of the correct df of 39.  In that example our critical value for alpha of 5% was 1.69.

Go to Calc > Probability Distributions > t-distribution.  Choose radio button for Inverser Cumulative Distribution.  Enter 39 for degrees of freedom.  Click radio button for Input Constant and enter 0.05  The output is as follows:

Inverse Cumulative Distribution Function 
Student’s t distribution with 39 DF
P( X ≤ x )         x
    0.05      -1.68488

This is where you need to be a little careful.  Remember that our alternative was "greater than" or a right-tailed test.  The output is the critical value for a left-tailed test.  However, since the t-distribution is symmetrical, the area to the left of -1.68488 would be the same as the area to the right of 1.68488.  Therefore, the critical value for out test with 39 degrees of freedom would be 1.68488, which doesn't differ much from the 1.69 we estimated using 35 degrees of freedom.  This is why the table skips going one by one after 30; there is little difference between the values when increasing by only one degree of freedom.

-->


### Determination of a 'Representative Sample'

%% {[NOT YET INTEGRATED]} %%

The total number of villages in MTB in the year 2010 is being used as a proxy measure to establish a representative sample within the project's 'social area of impact'.  The client acknowledges that it will be a project of regional significance, and definition of 'area of influence' will continue to be reformulated and refined during the process of social impact assessment.  The significance of this measurement is to establish an appropriate survey size.

FIGURE: 1
%%{[ADJUST TABLE]}%%

----

	Population Size	Confidence Level	Degree of Accuracy	Target Sample Size
MTB total # villages*	72	45%	0.05	28

----

To help ensure that the survey team interacts directly with a 'representative sample' of the regional area of influence, Consultancy grouped villages according to arithmetic quartiles by population and sought to balance site selection accordingly.

FIGURE: 2
%%{[ADJUST TABLE]}%%

----
Calculation of [MTB quartiles](https://docs.google.com/spreadsheets/d/1cZLdBOF8MAJGKAAxh2nlVLznIrmXUX2CRCbkDPKGgLc/edit?pli=1#gid=1619742010)

MTB kabupaten population, mean: 105,341/71 = 1483.676 [1484]

No. MTB villages above mean =  28

//  re-factored mean for top half = 71,232=/28 [2,544]

* top [\geq 2,544] = 5 villages
* mid-top [2,544 - 1,484] = 23 villages

No. MTB villages below mean = 43

//  re-factored mean for top half (mean re-factored) = 34,809/43 [793]

* mid-bottom  [1,483 - 793] = 18 villages
* bottom = [\leq 792] = 26 villages

----

This methodology extends the number of study villages to achieve a more balanced and representative sample, as well as to better demonstrate how the project is attending to the IFC prescript to ensure that the impact assessment process accounts especially for 'vulnerable communities' (i.e., by giving suitable weighting to the representation of small and isolated communities that may be exposed to project-induced indirect impacts, such as price inflation).

{[ADJUST STATEMENT]}
As calculated in the table above and reflected in the graphics below, the distribution of ESMS social baseline study locations achieves a rough approximation of regional composition with respect to population size.

FIGURE: 2
{[INSERT EXCEL IMAGE]}

Primary baseline data collection in each village sets numerical targets for the number of survey participants according to confidence values of 80% and margin of error calculations varying between 0.25 and 0.5. Consultancy will use a combination of household questionnaire surveys, key informant interviews, and focus group discussions to effect a rapid rural appraisal that reaches representative sample population targets //%%{[SECTION]}%%//.  The target number of participants for FGD sessions is calculated according to MTB 2010 village population quartile values. ESMS supplementary social baseline implementation schedules were created by calculating village days according to the estimated number of FGDs that can be completed in one day (6 total; refer to //%%{[SECTION]}%%//).

ANNEX 1:
%%{INSERT: [Sample Definition]}%%


### Selection of Study Sites

Consultancy and client agreed to the following parameters for supplementary baseline site selection:

   * sample size should seek to achieve a defensible statistical representation of the social field; no less than 35% confidence level for regional "area of influence" (minimum of 17 villages)
   * full representation of directly affected communities [equivalent to 'priority directly-affected communities' (PDAC)in the terminology of the client *Public Consultation and Disclosure Plan* (PCDP)]
   * partial representation (ca. 40% - 80%) of areas likely to be exposed to project-induced direct and indirect socio-economic impacts ('directly-affected communities' DAC)
   * partial representation (ca. 10% - 40%) of areas that may indirectly be affected by project-induced socio-economic change, or those area where there is a vocal stakeholder perception or belief that such changes may occur ('indirectly-affected communities' IAC)

Additional parameters influencing Consultancy' proposed field sites selection include:

  - proximity and distance from key project activity zones, especially the administrative and economic center of Saumlaki, the capital of MTB, as well as the planned on-shore LSB site and port facilities in neighboring Olilit Village.
  - distances from port facilities / accessibility by regular forms transportation [proximity to transportation hubs affects the likelihood a village will experience in-migration]
  - distance from healthcare and treatment facilities [availability of, and access to, health and educational services affect the extent to which communities' vulnerability may be impacted by the project]
  - available production land in village [derived from BPN statistics, this measurement indicates the potential of a village community to expand agricultural output in response to added population pressures]
 - due consideration of existing social, demographic, linguistic, geographical and economic data [MTB has several distinctive language groups, the number of which is a matter of scholarly debate; at least five major groups can be distinguished]
 - due consideration of timing, capacity constraints and the logistics of access

Consultancy' proposed selection criteria seeks to extend the geographic coverage of study sites to better account for potential project-induced changes in northern parts of MTB and other more distant villages--such as those that may be affected by speculative flows of immigrants or particularly remote and impoverished villages that are relatively more vulnerable to shocks of regional economic change.  We recognize, however, that  much of the west coast of MTB's Yamdena Island is not accessible by road, and a number of populated islands in the northwest and northeast of Yamdena cannot be readily reached by means of sea transport meeting client' quality, health and safety standards.  Consultancy will work with client to revise and finalize final field site selection.

Following the above parameters and considerations, the Consultancy team recommends selection of the below villages for village-level collection of supplementary baseline data:

ID#	Village	Kecamatan


81-01-43-006	Adaut	Selaru
81-01-54-005	Alusi Kelaan	Kormomolin
81-01-42-003	Batu Putih	Wer Maktian
81-01-40-017	Bomaki	Tanimbar Selatan
81-01-43-004	Kandar	Selaru
81-01-50-029	Kelaan	Tanimbar Utara
81-01-50-026	Keliober	Tanimbar Utara
81-01-40-002	Latdalam	Tanimbar Selatan
81-01-50-022	Lelingluan	Tanimbar Utara
81-01-40-001	Lermatang	Tanimbar Selatan
81-01-43-003	Lingat	Selaru
81-01-41-001	Tumbur	Wer Tamrian
81-01-54-001	Lorwembun	Kormomolin
81-01-40-016	Matakus	Tanimbar Selatan
81-01-54-007	Mayano Raya	Kormomolin
81-01-40-010	Olilit	Tanimbar Selatan
81-01-50-024	Ridool	Tanimbar Utara
81-01-50-023	Ritabel	Tanimbar Utara
81-01-50-002	Rumngeur	Yaru
81-01-41-006	Sangliat Dol	Wer Tamrian
81-01-40-009	Saumlaki	Tanimbar Selatan
81-01-40-009	Sifnana	Tanimbar Selatan
81-01-52-009	Tutukembong	Wuar Labobar
81-01-50-025	Watidal	Tanimbar Utara
81-01-53-001	Waturu	Nirunmas
81-01-43-001	Werain	Selaru
81-01-42-004	Wermatang	Wer Maktian
81-01-40-015	Wowonda	Tanimbar Selatan

For a detailed explication of rationale for the selection of each village, as well as a list of target stakeholders for FGD questions per village, please refer to **ANNEX 2**.

----

ANNEX 2:
%%{INSERT: [Site Selection and Lines of Focused Inquiry]}%%

----

<!--

https://datascience.stackexchange.com/questions/19943/what-is-a-large-enough-sample-size/19946

What is a large enough sample size?

It highly depends, If you want to make inferences on the total population you need to determine what margin of error and what confidence level you can allow for. These will then help you determine the needed sample size. 

If we would want to estimate the population mean $\mu$. The maximum difference between the sample mean $\bar x$ and $\mu$ is given by: 

$$ \epsilon = z_{\frac{\alpha}{2}}\frac{\sigma}{\sqrt{n}}  $$

Where $n$ is the sample size, $\sigma$ is the population standard deviation and $z_{\frac{\alpha}{2}}$ is commonly called the critical value which is derived from the standard normal distribution. These values can be found in tables or using r or python, e.g 1.96 corresponds to a 95% confidence level. 

Knowing $\sigma$ (you usually don't) will allow you to determine the sample size needed to approximate $\mu$ within $\pm \epsilon $ with a confidence level of $1-\alpha$. You can try using $\sigma =  \frac{1}{2}$ which is usually enough. There exists methods for determining $\sigma$ as well. Anyhow, you may rearrange the above relation as follows: 

$$ n = \bigg ( \frac{z_\frac{\alpha}{2}\sigma }{\epsilon}  \bigg )^2 $$

In fact, this question is quite hard to answer. There are many factors that determine the sample size needed for your study. You should definitely go through some material on basic statstics starting with 
[Awesome probability theory][1] and go on studying inferential statistics.    

It is worth taking some time to understand what the total population is in your case and with regard to the inferential question, does the sample include enough relevant observations? I do not feel that enough info is given in your question to provide a good answer.  

You may look at similar surveys conducted and see what sample sizes they have used. 

Another common approach, when you don't know much about your population is using *Slovin's formula* : 

$$n = \frac{N}{(1+N \epsilon ^2)}$$

Where $N$ is the total population. As an example given a confidence level of 98% $\rightarrow \epsilon = 0.02$  and a total population of 600. we would get  

$$n = \frac{600}{1+600\times0.02^2} = 484.$$

Note that *Slovin's formula*  is easily misused but can give you a good starting point. 

I would highly recommend studying statistics if you are planning to continue working with DS.

Hope this provided some help at least. 
  

 


  [1]: https://www.youtube.com/watch?v=KbB0FjPg0mw&list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo

-->

<!--

https://towardsdatascience.com/inferential-statistics-series-t-test-using-numpy-2718f8f9bf2f



T-test using Python and Numpy

Although popular statistics libraries like SciPy and PyMC3 have pre-defined functions to compute different tests, to understand the maths behind the process, it is imperative to understand whats going on in the background. This series will help you understand different statistical tests and how to perform them in python using only Numpy.

A t-test is one of the most frequently used procedures in statistics. But even people who frequently use t-tests often don’t know exactly what happens when their data are wheeled away and operated upon behind the curtain using software like Python and R.

What is t-test?
The t test (also called Student’s T Test) compares two averages (means) and tells you if they are different from each other. The t test also tells you how significant the differences are; In other words it lets you know if those differences could have happened by chance.


t-distribution
A very simple example: Let’s say you have a cold and you try a naturalistic remedy. Your cold lasts a couple of days. The next time you have a cold, you buy an over-the-counter pharmaceutical and the cold lasts a week. You survey your friends and they all tell you that their colds were of a shorter duration (an average of 3 days) when they took the homeopathic remedy. What you really want to know is, are these results repeatable? A t test can tell you by comparing the means of the two groups and letting you know the probability of those results happening by chance.

Another example: Student’s T-tests can be used in real life to compare means. For example, a drug company may want to test a new cancer drug to find out if it improves life expectancy. In an experiment, there’s always a control group (a group who are given a placebo, or “sugar pill”). The control group may show an average life expectancy of +5 years, while the group taking the new drug might have a life expectancy of +6 years. It would seem that the drug might work. But it could be due to a fluke. To test this, researchers would use a Student’s t-test to find out if the results are repeatable for an entire population.

What is t-score?
The t score is a ratio between the difference between two groups and the difference within the groups. The larger the t score, the more difference there is between groups. The smaller the t score, the more similarity there is between groups. A t score of 3 means that the groups are three times as different from each other as they are within each other. When you run a t test, the bigger the t-value, the more likely it is that the results are repeatable.

A large t-score tells you that the groups are different.
A small t-score tells you that the groups are similar.
What are T-Values and P-values?
How big is “big enough”? Every t-value has a p-value to go with it. A p-value is the probability that the results from your sample data occurred by chance. P-values are from 0% to 100%. They are usually written as a decimal. For example, a p value of 5% is 0.05. Low p-values are good; They indicate your data did not occur by chance. For example, a p-value of .01 means there is only a 1% probability that the results from an experiment happened by chance. In most cases, a p-value of 0.05 (5%) is accepted to mean the data is valid.

Types of t-tests?
There are three main types of t-test:
1. An Independent Samples t-test compares the means for two groups.
2. A Paired sample t-test compares means from the same group at different times (say, one year apart).
3. A One sample t-test tests the mean of a single group against a known mean.

How to perform a 2 sample t-test?
Lets us say we have to test whether the height of men in the population is different from height of women in general. So we take a sample from the population and use the t-test to see if the result is significant.

Steps:-

Determine a null and alternate hypothesis.
In general, the null hypothesis will state that the two populations being tested have no statistically significant difference. The alternate hypothesis will state that there is one present. In this example we can say that:

2. Collect sample data
Next step is to collect data for each population group. In our example we will collect 2 sets of data, one with the height of women and one with the height of men. The sample size should ideally be the same but it can be different. Lets say that the sample sizes are nx and ny.

3. Determine a confidence interval and degrees of freedom
This is what we call alpha (α). The typical value of α is 0.05. This means that there is 95% confidence that the conclusion of this test will be valid. The degree of freedom can be calculated by the the following formula:


4. Calculate the t-statistic
t-statistic can be calculated using the below formula:


where, Mx and My are the mean values of the two samples of male and female.
Nx and Ny are the sample space of the two samples
S is the standard deviation

5. Calculate the critical t-value from the t distribution
To calculate the critical t-value, we need 2 things, the chosen value of alpha and the degrees of freedom. The formula of critical t-value is complex but it is fixed for a fixed pair of degree of freedom and value of alpha. We therefore use a table to calculate the critical t-value:


In python, rather than looking up in the table we will use a function from the sciPy package. (I promise u, its the only time we will use it!)

6. Compare the critical t-values with the calculated t statistic
If the calculated t-statistic is greater than the critical t-value, the test concludes that there is a statistically significant difference between the two populations. Therefore, you reject the null hypothesis that there is no statistically significant difference between the two populations.

In any other case, there is no statistically significant difference between the two populations. The test fails to reject the null hypothesis and we accept the alternate hypothesis which says that the height of men and women are statistically different.

Lets Code:

```
## Import the packages
import numpy as np
from scipy import stats


## Define 2 random distributions
#Sample Size
N = 10
#Gaussian distributed data with mean = 2 and var = 1
a = np.random.randn(N) + 2
#Gaussian distributed data with with mean = 0 and var = 1
b = np.random.randn(N)


## Calculate the Standard Deviation
#Calculate the variance to get the standard deviation

#For unbiased max likelihood estimate we have to divide the var by N-1, and therefore the parameter ddof = 1
var_a = a.var(ddof=1)
var_b = b.var(ddof=1)

#std deviation
s = np.sqrt((var_a + var_b)/2)
s



## Calculate the t-statistics
t = (a.mean() - b.mean())/(s*np.sqrt(2/N))



## Compare with the critical t-value
#Degrees of freedom
df = 2*N - 2

#p-value after comparison with the t 
p = 1 - stats.t.cdf(t,df=df)


print("t = " + str(t))
print("p = " + str(2*p))
#Note that we multiply the p value by 2 because its a twp tail t-test
### You can see that after comparing the t statistic with the critical t value (computed internally) we get a good p value of 0.0005 and thus we reject the null hypothesis and thus it proves that the mean of the two distributions are different and statistically significant.


## Cross Checking with the internal scipy function
t2, p2 = stats.ttest_ind(a,b)
print("t = " + str(t2))
print("p = " + str(2*p2))

```

-->

<!--

https://help.surveymonkey.com/articles/en_US/kb/How-many-respondents-do-I-need


Calculating the Number of Respondents You Need
The number of respondents you need depends on your survey goals and how confident you want to be in your results. The more confident you want to be, the less of a margin of error you should accept.

To calculate the number of respondents you need (known as your sample size), use our sample size calculator.

TIP! If you need a guaranteed number of respondents, buy survey responses from SurveyMonkey Audience. You specify the number of responses you need and we'll use your targeting criteria to find you respondents.
Definitions
To calculate your sample size, you'll need to know the following information:

Your population size is the size of the entire population you wish to represent.

Population: The entire group you're interested in making conclusions about.
Sample: The group you're surveying.
Think about the potential size of your target population. For example, if you're sending a survey to male iPhone users in California, you may need to do some research to determine how many total men fit that criteria.

Margin of error tells you how much error surrounds a measure. It's a percentage that describes how much the opinions and behavior of the sample you survey is likely to deviate from the total population. To calculate your margin of error, use our margin of error calculator.

The smaller the margin of error is, the closer you are to having the exact answer at a given confidence level.

In general, the larger your sample size, the lower the margin of error. The closer your sample is in size to your population, the more representative your results are likely to be. And that’s why you’ll notice that the recommended sample size in the table below gets smaller as your tolerance for error gets larger.

For example, let's say we asked 400 people if they have a favorable or unfavorable opinion of Barack Obama and 55% say favorable. Using a 95% confidence level and ±5% margin of error, if we repeated this survey 100 times under the same conditions, 95 out of 100 times, the response would be somewhere between 50% and 60%.

A confidence level tells you how reliable a measure is. Common standards used by researchers are 90%, 95%, and 99%.

A 95% confidence level means if the same survey were to be repeated 100 times under the same conditions, 95 times out of 100 the measure would lie somewhere within the margin of error.

When calculating your sample size, you'll use the z-score for your confidence level. The z-score is the number of standard deviations a given proportion is away from the mean.

Confidence Level
z-score
90%	1.65
95%	1.96
99%	2.58
 
 
 Sample size requirements vary based on the percentage of your sample that picks a particular answer. For example, if in a previous survey you found that 75% of your customers said yes they are satisfied with your product and you are looking to conduct that survey again, you can use p = 0.75 to calculate your needed sample size.

If you're running a survey for the first time, and since most surveys have more than one question (and therefore more than one percentage value to evaluate), we recommend using p = 0.5 to calculate your optimum sample size. This produces a sample size estimate that is neither too conservative nor too loose.

Calculating Sample Size
Calculate the number of respondents you need in seconds using our sample size calculator. If you’d like to do the sample size calculation by hand, use the following formula:

![](https://help.surveymonkey.com/servlet/servlet.ImageServer?id=01530000003EKKb&oid=00D30000001HuKJ)


tatistic
Description
N	Population Size
e	Margin of Error (as a decimal)
z	Confidence Level (as a z-score)
p	Percentage Value (as a decimal)

Suggested Sample Sizes
Below is a table with suggested population sizes by margin of error at a 95% confidence level. We used the above formula to calculate the suggested sample sizes. In some cases, we rounded the sample sizes up to the nearest 5 or 10. For a more exact calculation, use our sample size calculator.

Population Size	Sample Size per Margin of Error
 	
±3%
±5%
±10%
500
345
220
80
1,000
525
285
90
3,000
810
350
100
5,000
910
370
100
10,000
1,000
385
100
100,000+
1,100
400
100

Example Sample Size
You're sending a survey with a Yes or No question asking if parents of children at your school are in favor of an extended school day.

The total number of parents (your population size) is 10,000 and you're comfortable with a ±10% margin of error. Using the table above, you can see you'll need at least 100 people to take your survey.

70% of the 100 parents surveyed answered that they are in favor of an extended school day. This means you can assume that if all 10,000 parents answered the survey, between 60% to 80% of people would be in favor of an extended school day.

How many people should I ask to take my survey?
Your response rate may affect the number of people you send your survey to. The higher the response rate, the fewer people you need to ask to take your survey.

For example, if you need 100 respondents and you expect 25% of the people invited to take your survey will actually respond, then you need to invite 400 people to take your survey.

To calculate the number of people you need to invite to take your survey based on your expected response rate, use the following equation:

# of respondents you need
 x 100
expected % response rate

-->

<!--


http://veekaybee.github.io/2015/08/04/how-big-of-a-sample-size-do-you-need/

Vicki Boykis Data, tech, and sometimes Nutella
About Twitter GitHub Personal RSS

How large should your sample size be?
Aug 4, 2015


I read a recent interview with Hadley Wickham. Two things stood out to me.

The first is how down-to-earth he seems, even given how well-known he is in the data science community.

The second was this quote:

Big data problems [are] actually small data problems, once you have the right subset/sample/summary. Inventing numbers on the spot, I’d say 90% of big data problems fall into this category.

##The technical side of sampling

Even if you don’t have huge data sets (defined for me personally as anything over 10GB or 5 million rows, whichever comes first), you usually run into issues where even a fast computer will process too slowly in memory (especially if you’re using R). It will go even slower if you’re processing data remotely, as is usually the case with pulling down data from relational databases (I’m not considering Hadoop or other NoSQL solutions in this post, since they’re a different animal entirely.)

In the cases where pulling down data takes longer than running regressions on it, you’ll need to sample.

But how big a sample is big enough? As I’ve been working through a couple of rounds of sampling lately, I’ve found that there’s no standard rule of thumb, either in the data science community or in specific industries like healthcare and finance. The answer is, as always, “It depends.”.

Before the rise of computer-generated data collection, statisticians used to have to work up to a large-enough sample. The question was, “I have to collect a lot of data. The process of collecting data, usually through paper surveys, will take a long time and be extremely expensive. How much data is enough to be accurate?”

Today, the question is the opposite: “How much of this massive amount of data that we’ve collected can we throw out and still be accurate?”

That was the question I was trying to answer a couple weeks ago when I was working with a SQL table that had grown to 1+ billion rows.

The business side of sampling
To understand the relationship between an entire population and a subset, let’s take a step back to see why someone might ask.

Let’s say you’re the data scientist at a start-up - Goatly - that sells artisanal handcrafted medicine boxes monthly to owners of narcoleptic goats (this is a real thing and I could watch this video over and over again.

Goatly has ~ 100,000 farms already in your system (who knew America had a narcoleptic goat problem?) and the CEO wants to buy a share in a private jet, so she needs the company to keep growing very quickly. A startling number of goats get much better after taking your medicine and hence, the farm leaves your service. The CEO needs you to figure out what makes these goats better and see if you can predict how many farms will be the next to leave, and as a result, how much business she needs to replace them.

You think you might be able to use logistic regression to predict whether the farm will cancel Goatly (number of goats, size of goats, color of goats, how much of the pills they buy in a month, how many pills they use in a month, ratio of narcoleptic to regular goats, etc.) But when you try to run the regression on the entire data set, it fails because it’s simply too much.

So you need to sample. How many farms do you need to pick to make sure that they accurately represent the total population of farms? There are some smaller farms, some larger farms, some farms with more narcoleptic goats, some farms where the farmers are more aggressive in giving the goats the medicine, etc. If you pick the wrong sample, it won’t be the same as the population, and then all the tests you plan to do later will fail.

Determining sample size
Here’s the standard equation used to calculate error. It’s often the precursor to testing the power of a test (that is, if this equation works in your favor, then you can use power of a test to figure out whether logistic regression or most other tests you use actually work on your sample). More on that at the bottom of the post.

You need to know:

Population size - The entire population you’re sampling (in our case, 100,000.)
Margin of error/confidence interval - How far away are you willing to be from the population statistic?
Confidence level - How confident do you want to be that your sample statistic (the mean, for example) matches your population?
The two things you have to pass judgment on are:

how large you want your confidence level to be: i.e. do you want to be 90% sure that you found all the farms that will cancel Goatly and leave your CEO traveling coach with the peons? 95% or 99%? In settings where you’re dealing with medical data, you want this to be 99%. Elsewhere, 95%, or even 90%, depending on what you’re doing is good enough. I asked around the Data Science Slack and the general consensus was most business settings can do with 95%, again, depending on context.

margin of error By what percent the sample deviates from the population. This is the number you usually see in polls: 43% of people voted Yes on this issue, +/- 3%. Again, you’ll need to use your judgment. There is no standard of error. It’s usually anything between 1 to 4%. Let’s pick 2% for now. Just keep in mind that sample size and margin of error are related: the larger margin of error you pick, the smaller sample size you’ll need.

##Putting it all together:

Interpreting the results of the four stats you need for the entire equation: If we have a population size of 100,000, what number of farms can we sample and be sure that they are representative of all of the farms using Goatly 95% of the time, where our sample statistic is at most 2% below or 2% above the population mean?

Calculating sample size with Python
There are a couple ways to run a quick calculation. The fastest is probably this site. I use it a lot for quick back of the envelope calculations. Normally I would be wary of using a site whose code and methods I didn’t know, but this site is generally well-documented, and we’ll be cross-checking this value against another method.

Putting in our numbers there, we get:

2,345 as the sample size.

image

There is also a really nice Python script that does the same thing.

Adjusted for my sample size and confidence interval (see my Github):

def main():
  sample_sz = 0
  population_sz = 100000
  confidence_level = 95.0
  confidence_interval = 2.0
It also returns the same number:

vicki$ python samplesize.py 
SAMPLE SIZE: 2345
There are a couple of ways to get close to it in R, but I haven’t found anything in the pwr library so far that only requires those three things: margin of error, confidence level, and population. I also haven’t found anything in either SciPy or NumPy that does exactly this, although if I do, I’ll be sure to change the post.

Wrapping up
If you want to select a sample of farms that are representative of the whole Goatly population, you’d need to pick about 2.5k, which is much more manageable than looking at 100,000, and will allow you to get your CEO the results much more quickly. You’re happy, she’s happy, and the narcoleptic goats (the ones that are getting treated, anyway), are also happy.

##Post-script on the Power of a Test

Something you might often come across while reading up on picking the right sample size is “power of test.” (This can be performed once)[https://en.wikipedia.org/wiki/Statistical_power] you actually have your sample size. The power for a test gives you an acceptable Type I error. A Type I error is a false positive, or saying that a farm will leave the Goatly platform when they really won’t. What you’re really testing for is whether the sample size you’re taking matches the population.

Thanks to Sandy and @perfectalgo for editing.


-->

<!--

http://www.tools4dev.org/resources/how-to-choose-a-sample-size/

How to choose a sample size (for the statistically challenged)
One of the most common questions I get asked by people doing surveys in international development is “how big should my sample size be?”. While there are many sample size calculators and statistical guides available, those who never did statistics at university (or have forgotten it all) may find them intimidating or difficult to use.

If this sounds like you, then keep reading. This guide will explain how to choose a sample size for a basic survey without any of the complicated formulas. For more easy rules of thumb regarding sample sizes for other situations, I highly recommend Sample size: A rough guide by Ronán Conroy and  The Survey Research Handbook by Pamela Alreck and Robert Settle.

This advice is for:

Basic surveys such as feedback forms, needs assessments, opinion surveys, etc. conducted as part of a program.
Surveys that use random sampling.
This advice is NOT for:

Research studies conducted by universities, research firms, etc.
Complex or very large surveys, such as national household surveys.
Surveys to compare between an intervention and control group or before and after a program (for this situation Sample size: A rough guide).
Surveys that use non-random sampling, or a special type of sampling such as cluster or stratified sampling (for these situations see Sample size: A rough guide and the UN guidelines on household surveys).
Surveys where you plan to use fancy statistics to analyse the results, such as multivariate analysis (if you know how to do such fancy statistics then you should already know how to choose a sample size).
The minimum sample size is 100
Most statisticians agree that the minimum sample size to get any kind of meaningful result is 100. If your population is less than 100 then you really need to survey all of them.

A good maximum sample size is usually 10% as long as it does not exceed 1000
A good maximum sample size is usually around 10% of the population, as long as this does not exceed 1000. For example, in a population of 5000, 10% would be 500. In a population of 200,000, 10% would be 20,000. This exceeds 1000, so in this case the maximum would be 1000.

Even in a population of 200,000, sampling 1000 people will normally give a fairly accurate result. Sampling more than 1000 people won’t add much to the accuracy given the extra time and money it would cost.

Choose a number between the minimum and maximum depending on the situation
Suppose that you want to survey students at a school which has 6000 pupils enrolled. The minimum sample would be 100. This would give you a rough, but still useful, idea about their opinions. The maximum sample would be 600, which would give you a fairly accurate idea about their opinions.

Choose a number closer to the minimum if:

You have limited time and money.
You only need a rough estimate of the results.
You don’t plan to divide the sample into different groups during the analysis, or you only plan to use a few large subgroups (e.g. males / females).
You think most people will give similar answers.
The decisions that will be made based on the results do not have significant consequences.
Choose a number closer to the maximum if:

You have the time and money to do it.
It is very important to get accurate results.
You plan to divide the sample into many different groups during the analysis (e.g. different age groups, socio-economic levels, etc).
You think people are likely to give very different answers.
The decisions that will be made based on the results of the survey are important, expensive or have serious consequences.
In practice most people normally want the results to be as accurate as possible, so the limiting factor is usually time and money. In the example above, if you had the time and money to survey all 600 students then that will give you a fairly accurate result. If you don’t have enough time or money then just choose the largest number that you can manage, as long as it’s more than 100.

If you want to be a bit more scientific then use this table
While the previous rules of thumb are perfectly acceptable for most basic surveys, sometimes you need to sound more “scientific” in order to be taken seriously. In that case you can use the following table. Simply choose the column that most closely matches your population size. Then choose the row that matches the level of error you’re willing to accept in the results.

Sample size table

You will see on this table that the smallest samples are still around 100, and the biggest sample (for a population of more than 5000) is still around 1000. The same general principles apply as before – if you plan to divide the results into lots of sub-groups, or the decisions to be made are very important, you should pick a bigger sample.

Note: This table can only be used for basic surveys to measure what proportion of the population have a particular characteristic (e.g. what proportion of farmers are using fertiliser, what proportion of women believe myths about family planning, etc). It can’t be used if you are trying to compare two groups (e.g. control versus intervention) or two points in time (e.g. baseline and endline surveys). See Sample size: A rough guide for other tables that can be used in these cases.

Relax and stop worrying about the formulas
It’s a dirty little secret among statisticians that sample size formulas often require you to have information in advance that you don’t normally have. For example, you typically need to know (in numerical terms) how much the answers in the survey are likely to vary between individuals (if you knew that in advance then you wouldn’t be doing a survey!).

So even though it’s theoretically possible to calculate a sample size using a formula, in many cases experts still end up relying rules of thumb plus a good deal of common sense and pragmatism. That means you shouldn’t worry too much if you can’t use fancy maths to choose your sample size – you’re in good company.

Once you’ve chosen a sample size, don’t forget to write good survey questions, design the survey form properly and pre-test and pilot your questionnaire.

Photo by James Cridland

-->

<!--

Sample Size Calculator
How many people do you need to take your survey? Even if you’re a statistician, determining survey sample size can be tough.

Want to know how to calculate it? Our sample size calculator makes it easy. Here’s everything you need to know about getting the right number of responses for your survey.

Calculate Your Sample Size:
Population Size:	
Confidence Level (%):	
Margin of Error (%):	
CALCULATE	
Sample Size:
—
What is sample size?
Sample size is the number of completed responses your survey receives. It’s called a sample because it only represents part of the group of people (or target population) whose opinions or behavior you care about. For example, one way of sampling is to use a “random sample,” where respondents are chosen entirely by chance from the population at large.

Understanding sample sizes
Here are two key terms you’ll need to understand to calculate your sample size and give it context:

Population size: The total number of people in the group you are trying to study. If you were taking a random sample of people across the U.S., then your population size would be about 317 million. Similarly, if you are surveying your company, the size of the population is the total number of employees.

Margin of error: A percentage that tells you how much you can expect your survey results to reflect the views of the overall population. The smaller the margin of error, the closer you are to having the exact answer at a given confidence level.

If you want to calculate your margin of error, check out our margin of error calculator.

How to calculate sample size
Wondering how to calculate sample size? If you’d like to do the calculation by hand, use the following formula:

Sample Size   =

Population Size = N  |   Margin of error = e  |   z-score = z

e is percentage, put into decimal form (for example, 3% = 0.03).

The z-score is the number of standard deviations a given proportion is away from the mean. To find the right z-score to use, refer to the table below:

Desired Confidence Level	z-score
80%	1.28
85%	1.44
90%	1.65
95%	1.96
99%	2.58
 

Things to watch for when calculating sample size
If you want a smaller margin of error, you must have a larger sample size given the same population.
The higher the confidence level you want to have, the larger your sample size will need to be.
Does having a statistically significant sample size matter?
Generally, the rule of thumb is that the larger the sample size, the more statistically significant it is—meaning there’s less of a chance that your results happened by coincidence.

But you might be wondering whether or not a statistically significant sample size matters. The truth is, it’s a case-by-case situation. Survey sampling can still give you valuable answers without having a sample size that represents the general population. Customer feedback is one of the surveys that does so, regardless of whether or not you have a statistically significant sample size. Listening to customer thoughts will give you valuable perspectives on how you can improve your business.

On the other hand, political pollsters have to be extremely careful about surveying the right sample size—they need to make sure it’s balanced to reflect the overall population. Here are some specific use cases to help you figure out whether a statistically significant sample size makes a difference.

 

The Effect Survey Values have on the Accuracy of its Results

Value Increased	Value Decreased
Population Size	Accuracy Decreases	Accuracy Increases
Sample Size	Accuracy Increases	Accuracy Decreases
Confidence Level	Accuracy Increases	Accuracy Decreases
Margin of Error	Accuracy Decreases	Accuracy Increases

Employee and Human Resources Surveys:
Working on an employee satisfaction survey? All HR surveys provide important feedback on how employees feel about the work environment or your company. Having a statistically significant sample size can give you a more holistic view on employees in general. However, even if your sample size isn’t statistically significant, it’s important to send the survey anyway. HR-related surveys can give you important feedback on how you should improve the workplace.

Customer Satisfaction Surveys:
Like we said earlier, customer satisfaction surveys don’t necessarily have to rely on having a statistically significant sample size. While it’s important that your responses are accurate and represent how customers feel, you really should be taking a closer look on each answer in a customer satisfaction survey. Any feedback, positive or negative, is important.

Market Research:
When conducting a market research survey, having a statistically significant sample size can make a big difference. Market research surveys help you discover more information about your customers and your target market. That means a statistically significant sample size can easily help you discover insights on your overall target market. It also assures you’re getting the most accurate information.

Education Surveys:
For education surveys, we recommend getting a statistically significant sample size that represents the population. If you’re planning on making changes in your school based on feedback from students about the institution, instructors, teachers, etc., a statistically significant sample size will help you get results to lead your school to success. If you’re planning on just receiving feedback from students for the sake of seeing what they think—and not necessarily making a change in the system—a statistically significant sample size might not be as important.

Healthcare Surveys:
When conducting healthcare surveys, a statistically significant sample size can help you find out what health issues are a greater concern for your patients over others. It can also help you come to conclusions in medical research. However, if you’re using Healthcare Surveys for Patient Satisfaction reasons or questioning patients about their regular care, a statistically significant sample size might not be as important. Without it, you’re still able to get valuable information from individual patients about their needs and experience.

Casual surveys:
On a day-to-day basis, you might want to send surveys to friends, colleagues, family, etc. In this case, it really depends on what you’re looking for from your survey. If you’d like your results to be used as evidence, a statistically significant sample size is important. If not, and you’re just using SurveyMonkey for fun, sending your survey to just a few people won’t hurt.

Do you need more responses?
Don’t just take a guess at how many people should take your survey and don’t get bogged down in probability sampling or probability distribution models—use our sample size calculator. Get familiar with sample bias, sample size, statistically significant sample sizes, and how to get more responses. Soon you’ll have everything you’ll need to get better data for your survey.

If the sample size calculator says you need more respondents, we can help. Tell us about your population, and we’ll find the right people to take your surveys. With millions of qualified respondents, SurveyMonkey Audience makes it easy to get survey responses from people around the world instantly, from almost anyone.

-->
