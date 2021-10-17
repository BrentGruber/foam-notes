

#### 1. Which of the following would be considered a categorical variable?

a. Gender, measured as 1=Male, 2=Female, 3=Other

b. Height, measured in cm 

c. Income, measured in dollars

d. Education, measured in 1=less than college, 2=college, 3=post-college


**Answer**

a + d

A categorical variable is a variable in which the value can be put into one of a fixed number of categories.

b + c would be considered continuous variables, because they can take on many different numeric values.  They could be made categorical by changing them into ranges. e.g. 1=0-10 dollars, 2=11-20 dollars, 3=21-30 dollars, 4=30+ dollars




#### 2. Which of the following would be considered an ordinal variable?
   
a. Treatment, measured as 1=Treatment, 2=Control

b. Gender, measured as 1=Male, 2=Female, 3=Other

c. Ideology, measured from 0=Very Liberal to 7=Very Conservative

d. Race, measured as 1=Whites, 2=Blacks, 3=Hispanic, 4=Asian, 5=Others


**Answer**

c

An ordinal variable is a categorical variable in which the values have order in relativity to each other, e.g. a spectrum from very unlikely to very likely.  So in order to be an ordinal variable, the value needs to be able to be put into one of a fixed number of categories and those categories need to have some relativity or scale other than mutual exclusivity.



#### 3. Which measure would you use when you have a categorical variable and you want to measure central tendency of this variable?

a. Mean

b. Median

c. Mode

d. Variance


**Answer**

c

You would use the mode to measure central tendency of categorical data.  In fact, the mode is the only measure of central tendency that you can use with categorical data—such as the most preferred flavor of ice cream.  Because categorical data is not ordered, the mode will give you information such as the most common value.  An ordinal variable, which does have order, could have a mode that is different than the center

continuous variables could possibly have no mode, if no values repeat.

4. A reliable measure means

a. The measure is unambiguous
b. The measure captures what you truly aim to measure
c. The measure only produces a small amount of error
d. The measure does not produce any error

**Answer**

c

A measure is said to be reliable if it produces almost similar results under similar circumstances with very little to no error



#### 5. You’re interested in estimating the average number of days between terrorist attacks in a given region.
You randomly select 100 days on which attacks happen, and observe that on average there had been
12.77 days since the last incident, with variance 10.22 days. What is your 95% confidence interval, for
the true average number of days between attacks?

a. 12.77,(10.7,14.8)
b. 10.22,(9.4,11.6)
c. 12.77,(2.6,22.9)
d. 12.77,(12.1,13.4)

**Answer**

d 

xbar = 12.77 (average number of days since last attack from samples)
s^2 = 10.22 (variance)
s = 3.1969 = sqrt(s^2) (standard deviation)
n = 100 (sample size)
Degrees of freedom = df = n - 1 = 100 - 1 = 99 (the higher your dof the more accurate your estimations are)

At 95% confidence level the t is ,

\alpha  = 1 - 95% = 1 - 0.95 = 0.05  (total amount of area outside of central 95% of curve)
\alpha / 2 = 0.05 / 2 = 0.025   (divide by 2 for each side of the curve)

t\alpha /2,df = t0.025,99 =1.984 (table lookup https://yuppal.people.ysu.edu/econ_3790/t-table.pdf)

Margin of error = E = t\alpha/2,df * sqrt(s^2/n)
E = 1.984 * (3.1969/ sqrt(100)) = 0.634 ~0.6

95% confidence = xbar +- E
95% = 12.77 - 0.6 ~ 12.17 ~ 12.1
95% = 12.77 + 0.6 ~ 13.37 ~ 13.4



#### 6. If A and B are independent events, and P(A) > 0 and P(B) > 0, which statement is not correct?

a. P(B|A) = P(B)
b. P(A|B) = P(A)
c. P(A intersect B) = P(A)P(B)
d. P(A union B) = P(A) + P(B)


**Answer**

d.

ref: http://www.stat.yale.edu/Courses/1997-98/101/probint.htm

a + b are both true because the events are indepent, meaning that the result of one has no impact on the other, so it stands to reason that the probability that A occurs given B, is just the probability of A, since the result of B doesn't change the probability of A

c is true because the probability of A intersect B can be read as the probability that both A and B occur.  e.g. you are flipping two coins, what is the probability that both coins come up heads?  it would be 0.25 calculated as P(coin A = Heads) * P(coin B = Heads) = 0.5 * 0.5 = 0.25 or a 1 in 4 chance that both coins land on heads.  This can be found using set theory, by analyzing the set of possible outcomes.  If you flip 2 coins you have the following set of possible outcomes

    {HH, HT, TH, TT}


You can see from the set, that there are 4 total possible outcomes and one of those outcomes fills our conditions (both coins land on heads)

d is not true, because the probability of A union B can be read as the probability that A or B occur.  However it is not as simple as adding P(A) + P(B) because there is some overlap, because those probabilities both include the probability that both occur, so that intersection is being counted twice.  So the actual formula is P(A) + P(B) - P(A intersect B)

looking at the set and using the same condition we can read the union as what is the probability that Coin A is heads or Coin B is heads.

Coin A:  HH and HT satisfy this condition, or there is a 2/4 chance that Coin A is heads
Coin B: HH and TH satisfy this condition, or there is a 2/4 chance that Coin B is heads

if we add these together we would get a 4/4 chance or 100% chance of A or B landing on heads, which doesn't make sense because there is still a 1/4 chance that neither is heads (TT), and we can't go over 100% in probability.  It turns out that this happens because we are counting HH twice, so have to subtract one of these occurrences to get te actual probability which is 3/4 (HH, HT, TH)



#### 7. Which statement is not correct?

a. In a normal distribution, the mode, median, and mean are all the same

b. A normal distribution can be invoked by the Central Limit Theorem

c. We want to infer the sample mean and standard deviation from the population mean and standard deviation

d. None of these three are correct


**Answer**

c

a) A Normal distribution is symmetric and it is unimodal . thus mean median and mode are same for Normal distribution.

b) Yes in case of large sample , using Central Liimit theorem , any distribution can be approximated by Normal distribution .

c) sample mean and std deviation cannot be inferred from population mean and standard deviation, however population mean and standard deviation can be inferred from sample

This would be like inferring the results of a poll in california if you knew how every person in the state would answer. You can't make that inferrence because you don't know which samples were taken.



#### 8. You have two variables, X and Y. The sample size is N=1000. The mean of X is 2.90. the mean of Y is 2.95. The correlation between them is 0.72. The variance of X is 4. The variance of Y is 9. What is the covariance between X and Y?

a. 25.92

b. 11.34

c. 4.32

d. 0.36

**Answer**

c

N=1000

Xbar = 2.9

Ybar = 2.95

p = 0.72 (correlation coefficient)

var(X) = 4

var(Y) = 9

p = cov(X,Y)/sqrt(var(X)*var(Y))

0.72 = cov(X,Y)/sqrt(4*9)

0.72 = cov(X,Y)/6

4.32 = cov(X,Y)



#### 9. Imagine that we're fielding a survey at OSU. 54 percent of students responded that they support free trade. If we survey a random group of 100, what is the P(>54 students support free trade)

a. P(Y<54)

b. 1-P(Y<54)

c. P(Y=54)

d. 1-P(Y>54)


**Answer**

b

P(Y>=54) = 1 - P(Y<54)



#### 10. When we have the p-value of 0.001

a. it means that we fail to reject the null hypothesis

b. it means that there is a .999 chance our theory could be supported

c. it means that there is a causal relationship between the two variables

d. it means that the relationship between the two variables is stronger than the one with the p-value of 0.05

e. none of these four are correct/cannot say

**Answer**

d

ref: https://dataschool.com/fundamentals-of-analysis/correlation-and-p-value/

“p value is the probability of obtaining results as extreme or more extreme, given the null hypothesis is true”.  That is that the p-value is essentially the probability that you receive the results that you did, by pure chance.  

a p value of 0.05 is considered a 5% probability that you would receive these results by chance alone, indicating a 95% probability that there is some relationship between variables.  any p-value lower than 0.05 is considered strong evidence against the null hypothesis.

If you are flipping a coin multiple times, your null hypothesis would be that the coin is unbiased to heads or tails.  If you flipped the coin 10 times and got 10 heads, you would have an extremely low p-value  ~0.002 or a 1 in 500 chance that you received this result given that the coin is not biased.  Because this is less than the p-value of 0.05 it is considered strong enough evidence to reject the null hypothesis that the coin is not biased.  So we can say that we likely received these results because the coin is biased towards heads. 



#### 11. You're interested in evaluating the effect of gender on income and in finding a pay disparity between men and women. Income is measured with individuals' wage (in dollars). Gender is self-reported. Which test would you use?

a. Chi^2 test

b. difference of means t-test

c. correlation coefficient t-test

d. covariance matrix

**Answer**

b

a.) Chi^2 test is for testing categorical variables, as income is a continuous variable and not categorical, this test will not work

c + d) evaluating a difference in pay based on gender isn't really concerned with the relationship between the two data sets, but rather the difference

so the answer is b, we want to split the data into two data sets, by gender, then compare the means


#### 12. Which statement about causal theory is correct?

a. Experimental design is one of the observational studies.

b. Dependent variable is often called Treatment and we ultimately want to know how this affects the outcome variable.

c. We usually rely on observational studies to examine the causal relationship between X and Y.

d. Operationalization is a way to measure the Dependent variable and independent variable

**Answer**

c

NOTE: double check this one

Example experiment:

Testing how caloric intake affects weight, independent variable = caloric intake, this can be controlled and you are using it to test the Dependent variable of weight.

Operationalization is the process of turning abstract concepts into measurable observations.

This leaves c as the only answer


#### 13. Which is not a part of the four hurdles to causality? Choose all

a. We should control for all confounding variables

b. We should avoid any possibility where X could Cause Y

c. We should observe a credible causal mechanism connecting two variables

d. We should observe covariation between X and Y

e. We should have as many independent variables as possible

**Answer**

b, e

The 4 Hurdles to Causality are:

---------------------

(1) Whether there occurs a credible causal mechanism that generally connects X and Y or any two variables.

(2) Whether we can avoid any of such possibility in which Y could cause X.

(3) Whether there is a covariation between the variables X and Y.

(4) Whether we have controlled for all confounding variables.


#### 14. In the lecture, we talked about Polity IV index as a measure on democracy. This index mostly captures whether the government executive faces contestation, but lacks the information about political participation--another important part of democracy.  Therefore, this measure is weak in

a. concept clarity

b. reliability

c. validity

d. efficiency

**Answer**

c

NOTE: double check this one

validity has to do with the inferences that can be made


#### 15. You are running a difference-of-mean hypothesis test with our lab data in R and get the following result:

```r
Welch Two Sample t-test
data: Exam1_Study adn Exam1_noStudy
t = 1.8409, df=97.385, p-value = 0.06867
```

Which of the following is true?

a. The null hypothesis being tested here is that there is a difference between group means in the population.

b. This test is based on the normal distribution

c. You have a significant result here

d. You cannot confidently reject the null hypothesis

**Answer**

b, d 

NOTE: Double check this one

You cannot confidently reject the null hypothesis because we have a p-value of greater than 0.05

Welch Two Sample T-Test assumes normal distribution for data sets

a.) The null hypothesis is that there is no difference between group means

c.) The result is not significant because the p-value is too high


#### 16. Which statement is not correct?

a. With a random sample with a sufficient large size (n>30), we can do statistical inference by invoking the central limit theorem where we rely on the sampling distribution.

b. When we invoke the CLT, the mean of the sample is going to be the best guess for the mean of the population.

c. Standard errors will become larger as the number of sample size increases, which results in a wider confidence level.

d. We can use the confidence interval to test our hypothesis about the unknown values of the population.

**Answer**

c 

As sample size grows, the standard error will decrease, because higher sample size means that the sample is closer to the population, leaving less room for error.

#### 17. Which codes would you use to produce the following plot?

a. ggplot(data, aes(Exam1, factor(Study)) + geom_boxplot() + theme_bw())

b. ggplot(data, aes(factor(Study), Exam1)) + geom_boxplot() + theme_bw())

c. ggplot(data, aes(Exam1, factor(Study)) + geom_point() + theme_bw())

d. ggplot(data, aes(factor(Study), Exam1) + geom_point() + theme_bw())

e. qplot(grades$Exam1,data$factor(Study)) + theme_bw()

**Answer**
b

We know we want a box and whisker plot, which limits us to a or b (geom_boxplot), the only difference between the two is the order of arguments in the aes command.  the first argument should be the x axis, which in our case is factor(Study), so b is our answer.


#### 18. Let's say we are making a data frame xy with the following two vectors.
```
x
```
[1] 10 13 100 42 55
```
y
```
[1] "A" "B" "C" "D" "E"

After making a data frame xy, you're running the code xy[4,2]. which output would this code generate?  Note that the vector x will be the first column

a. 42

b. "D"

c. "A" "B" "C" "D" "E"

d. 42, D

**Answer**

b

Ran this in R

(x <- c(10, 13, 100, 42, 55))

(y <- c("A", "B", "C", "D", "E"))

xy <- data.frame(x, y)

(xy[4,2])


#### 19. Operationalization means...

a. setting up how to measure the independent variable and dependent variable

b. concise statement of how changes in the independent variable affect the dependent variable

c. explaining why the independent variable affects the dependent variable

d. testing statistical models and parameters

**Answer**

a

ref: https://scientificinquiryinsocialwork.pressbooks.com/chapter/9-3-operationalization/

Operationalization is the process by which researchers conducting quantitative research spell out precisely how a concept will be measured. 

#### 20. Choose a correct statement.

a. We use the mode value when we have skewed data

b. continuous variables have equal unit differences

c. The squared root of standard deviation is equal to variance

d. The treatment group is usually used as a dependent variable

**Answer**

b

a.) You would use the median for skewed data

c.) The opposite is true, the standard deviation is equal to the square root of the variance

d.) The treatment group is the group where the dependent variable is being tested. e.g. in a drug test, the control group is the group that takes a placebo, where the treatment group is the group that actually gets the drug. the dependent variable is effectiveness of the drug


#### 21. Choose a correct statement

a. We use CDFs to obtain the probability for any range

b. PMFs are used for continuous models

c. The Poisson distribution is a PDF

d. When we have a discrete probability, we would integral the PDF to get the CDF

**Answer**

a

b.) PDFs (Probability Density Functions) are used for continuous models

c.) The Poisson distribution is a PMF (Probability Mass Function)

d.) When we have a continuous probability, we would integral the PDF to get the CDF

The CDF is the probability of retrieving a result less than or equal to x.  e.g. if you roll a 6 sided die, there is about a 1/6 or 16.67% chance of retrieving any number.  Therefore the CDF of x, is the probability that you roll x or lower. The CDF of 2 in this case would then be the probability that you roll a 1 or 2 (2/6 or 33.33%).

#### 22. When you want to select everything except the first three elements of the vector "y"...

a. y[-(1:3)]

b. y[0:2]

c. y[1:3]

d. y[-(0:2)]

**Answer**

a

tested in r

#### 23. In R, create an object "z" and store the value "10" to this object.

a. z <- 10

b. z -> 10

c. z == 10

d. z - 10

**Answer**

a

#### 24. In R, create a new vector x that takes a value 1 when y is equal to 13 and 0 everywhere that y is not equal to 13.

a. x <- ifelse(y\==1, 1, 0)

b. x <- ifelse(y\==13, 1, 0)

c. y <- ifelse(x\==13, 1, 0)

d. x <- ifelse(y\==13, 0, 1)

**Answer**

c


#### 25. Choose a correct statement.

a. When we have categorical variables, the central tendency can be obtained by using the mean of the variables.

b. If event A and B are disjoint, they are always independent

c. Models assume a simplified world with sample statistics

d. A measure is said to be reliable only when we have random measurement errors.

**Answer**

c.

a.) You would use mode to gather central tendency of a categorical variable

b.) if event A and B are disjoint they must not be independent

d.) A measure is said to be reliable when it is consistent based on given inputs with little to no error.