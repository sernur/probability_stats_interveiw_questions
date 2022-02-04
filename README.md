# Repo name is probability_stats_interveiw_questions, but it includes all ML, SQL and product questions as well.
<img width="631" alt="Screen Shot 2021-03-05 at 2 59 24 PM" src="https://user-images.githubusercontent.com/42751574/110178339-877ad180-7dc3-11eb-8687-842d0b9126a6.png">


In this repository, I will try to solve interview questions that are mostly about probability theory, statistics, ML/DL/RL, SQL and Products and mostly asked by FAANGM(T) and some other big companies.  
1. Minimum of two uniform random variables
2. Detecting Unfair coin
3. Can you form a triangle ?
4. Expected Number of flips until N heads
5. Simulating a Fair Coin with a Biased Coin
6. Which game you would choose?
7. Is the coin biased?
8. Fair coins and double headed coin

## Probability
#### Difficulties: Easy, Medium, Hard, Extremely Hard.
1. Minimum of two uniform random variables:
   
    This problem was asked by Google. Probability, Medium

   Say we have X ~ Uniform(0, 1) and Y ~ Uniform(0, 1). What is the expected value of the minimum of X and Y?

2. Is this coin biased ?

    This problem was asked by Google. Probability, Medium.

    A coin was flipped 1000 times, and 550 times it showed heads. Do you think the coin is biased? Why or why not?

3. Forming a triangle

   This problem was asked by Google. Probability, Medium.

   Assume you have a stick of length 1 and you break it uniformly at random into three parts. What is the probability that the three parts form a triangle?

4. Flip until 2 heads

    This problem was asked by Lyft. Probability, Medium. 

    What is the expected number of coin flips needed to get two consecutive heads?


5. Fair odds from unfair coin

   This problem was asked by Airbnb. Probability, Medium.

   Say you are given an unfair coin, with an unknown bias towards heads or tails. How can you generate fair odds using this coin?



6. Ant collision

    This problem was asked by Facebook. Probability, Medium.

    Three ants are sitting at the corners of an equilateral triangle. Each ant randomly picks a direction and starts moving along the edge of the triangle. What is the probability that none of the ants collide? Now, what if it is k ants on all k corners of an equilateral polygon?


7. Number of cards before an Ace

    This problem was asked by Lyft. Probability, Medium. 

    How many cards would you expect to draw from a standard deck before seeing the first ace?

8. First to roll side K

    This problem was asked by Lyft. Probability, Medium.

    A and B are playing the following game: a number k from 1-6 is chosen, and A and B will toss a die until the first person sees the side k, and that person gets $100. How much is A willing to pay to play first in this game?

9. Flipping game

    This problem was asked by Facebook. Probability, Easy.

     You and your friend are playing a game. The two of you will continue to toss a coin until the sequence HH or TH shows up. If HH shows up first, you win. If TH shows up first, your friend wins. What is the probability of you winning?

10. Labeling content

    This problem was asked by Facebook. Probability, Easy.

    Facebook has a content team that labels pieces of content on the platform as spam or not spam. 90% of them are diligent raters and will label 20% of the content as spam and 80% as non-spam. The remaining 10% are non-diligent raters and will label 0% of the content as spam and 100% as non-spam. Assume the pieces of content are labeled independently from one another, for every rater. Given that a rater has labeled 4 pieces of content as good, what is the probability that they are a diligent rater?
11. Max dice roll

    This problem was asked by Spotify. Probability, Medium.

    A fair die is rolled n times. What is the probability that the largest number rolled is r, for each r in 1..6?

12. Mutual best friends

    This problem was asked by Snapchat. Probability, Hard.

    There are two groups of n Snapchat users, A and B, and each user in A is friends with those in B and vice versa. Each user in A will randomly choose a user in B as their best friend and each user in B will randomly choose a user in A as their best friend. If two people have chosen each other, they are mutual best friends. What is the probability that there will be no mutual best friendships?

13. Increase dice order

    This problem was asked by Uber. Probability, Medium.

    Say you roll three dice, one by one. What is the probability that you obtain 3 numbers in a strictly increasing order?

14. First toss

    This problem was asked by Lyft. Probability, Medium.

    A fair coin is tossed n times. Given that there were k heads in the n tosses, what is the probability that the first toss was heads?


15. Coin recursion
    
    This problem was asked by Robinhood. Probability, Medium
    A biased coin, with probability p of landing on heads, is tossed n times. Write a recurrence relation for the probability that the total number of heads after n tosses is even.

16. Random testing

    This problem was asked by Lyft. Probability, Easy.

    Say that you are pushing a new feature X out. You have 1000 users and each user is either a fan or not a fan of X, at random. There are 50 users out of 1000 that do not like X. You will decide whether to ship the feature or not, based on sampling 5 users independently and if they all like the feature, you will ship it. What is the probability that you will ship the feature?

17. Game series
    
    This problem was asked by Facebook. Probability, Medium.

    Alice and Bob are playing a new Facebook game together. They play a series of rounds until one of them wins two more rounds than the other. With probability p, Alice will win each round. What is the probability that Bob wins the overall series?

18. User virality

    This problem was asked by Snapchat. Probability, Medium

    You are analyzing the probability of failure or success of a small social media app competitor. Using some initial data, you estimate that at any step, if there is 1 user then after a day there is a 1/12 chance there will be 0 users, 5/12 chance there will be 1 user, and 1/2 chance there will be 2 users. Say the app starts with one user on day 1. What is the probability that the app will eventually have no users?

19. Replacement frequence.
    
    This problem was asked by Tesla. Probability, Hard.

    Suppose there is a new vehicle launch upcoming. Initial data suggests that any given day there is either a malfunction with some part of the vehicle or possibility of a crash, with probability p which then requires a replacement. Additionally, each vehicle that has been around for n days must be replaced. What is the long-term frequency of vehicle replacements?


20. Favorite show

    This problem was asked by Disney. Probability, Medium

    Alice and Bob are choosing their top 3 shows from a list of 50 shows. Assume that they choose independently of one another. Being relatively new to Hulu, assume also that they choose randomly within the 50 shows. What is the expected number of shows they have in common, and what is the probability that they do not have any shows in common?
21. Different Dice rolls

    This problem was asked by Facebook. Probability, Easy.

    Say you roll three dice and observe the sum of the three rolls. What is the probability that the sum of the outcomes is 12, given that the three rolls are different?

22. Mean roll times

     This problem was asked by Lyft. Probability, Medium

     Suppose you roll a fair die n times, where n is very large. What is the average time between occurrences of a given number?
23. Fan groups
    
    This problem was asked by Snapchat. Probability, Easy.

    You are testing a new feature with various sample groups of three people. Assume that each person is equally likely to be a fan or not a fan of the feature. What is the probability that a randomly chosen group has exactly one fan, given that there is a fan among the three?
24. Waiting time
    
    This problem was asked by Twilio. Probability, Easy.

    You are modeling the wait time a customer has for a support call as exponentially distributed with a mean of 10 minutes. Suppose a customer calls in and is told that all lines are currently busy, and the most recent last spot was occupied 5 minutes ago. What is the probability that the current customer will need to wait no more than another 5 minutes?
    


25. Hit shows
    
    This problem was asked by Netflix. Probability, Hard.

    Before a show is released, it is shown to several in-house raters. You assume there are two types of shows: hits, which have an 80% chance of being liked by any viewer, and misses, which have a 20% chance of being liked by any viewer. There is currently a new show which you believe has a prior distribution of 60% being a hit, and 40% being a miss. Given that 8 raters rated the show and 6 of the 8 liked the show, what is the new posterior distribution of being a hit or miss?
26. Random groups
    
    This problem was asked by Snapchat. Probability, Easy.

    Say we have M users and N groups that we want to assign users into. Define a group as having at least one or more users. How many N-user groups can be made using the M users?

27. First to pick
    
    This problem was asked by Facebook. Probability, Medium.

    Two people are picking random numbers among a set of M odd numbers and N even numbers without replacement. The first person to pick an even number wins. What is the probability that the first person who picks wins?

28. API availability
    
    This problem was asked by Twilio. Probability, Easy.

    Say we have N servers running to serve APIs, each of which has an uptime with probability p at any given time. Assume each server is up independently of other servers. A customer will always get an eventually valid API response if there are at least M of the N servers up. What is the probability that at any given time, a customer will not get an eventually valid API response?

    

29. Card colors

    This problem was asked by Facebook. Probability, Easy.

    Say you have a deck of 50 cards with 5 different colors, and 10 cards of each color. What is the probability that two cards you pick at random do not have the same color and are also not the same number?
30. Default time

    This problem was asked by Stripe. Probability, Easy.

    You are modeling time until default as an exponentially distributed random variable on a weekly basis. Say you have a given customer where you determine their chance of default within the next week is 0.4. What is that customer's probability of default within the next two weeks?

31. Monthly actives

    This problem was asked by Snapchat. Probability, Easy.

    Say you are analyzing the current set of monthly active users (MAUs). Suppose that if a user is currently a MAU, then the probability they will be a MAU next month is 0.9. Additionally, if a user is not currently a MAU then the probability that they will not be one next month is 0.7. In the long fraction what fraction of the current MAUs will still be MAUs?

32. Back and forth

    This problem was asked by Lyft. Probability, Easy.
    A and B are playing a game where they take turns flipping a biased coin, with the probability of landing on heads (and winning) as p. Player A starts the game and they pass the coin back and forth until one person flips heads and wins. What is the probability that A wins?

33. Filtering normal

     This problem was asked by Quora. Probability, Medium.

     Say you have N i.i.d. draws of a normal distribution with parameters μ and σ. What is the probability that k of those draws are larger than some value Y?


34. More likely outcome
    
    This problem was asked by Uber. Probability, medium
    
    A fair coin is tossed twice, and you have to decide whether it is more likely that two heads showed up given that either a) at least one toss was heads, and b) the second toss was heads. Does your answer change if the coin is unfair?


35. Full delivery

    This problem was asked by DoorDash. Probability, Medium.

    There are n of the same meals to be delivered at k delivery spots. Each meal is assigned a delivery spot at random, and the delivery driver will only stop at a delivery spot if there is a meal to be delivered there. What is the probability that the delivery driver will make a full k stops?

36. User threshold

    This problem was asked by Snapchat. Probability, Medium.

    Suppose that you are monitoring the number of daily active users (DAUs) on a daily basis. You determine that on any given day, that population follows a binomial random variable with a certain mean and variance and the population on each day is independent of other days. You set an alert threshold for this week whereby you want to be notified if the population falls below 0.9 * its mean. What is the probability that your alert will go off?

37. Empty topic

    This problem was asked by Twitter. Probability, Medium.

    There are n users and there are k topics. Assume that they select independently, and select a topic completely at random. What is the probability that exactly one topic will have nobody choosing it?




38. Political groups

    This problem was asked by Twitter.  Probability, Medium.

    Say you have a large group of people, each is affiliated as either a Republican or a Democrat. Specifically, there are k groups and each group has R Republicans and D Democrats. At random, a person from group 1 is chosen and sent to group 2, then a person from group 2 is chosen and sent to group 3, etc. Finally, a random person is chosen from group k. What is the probability that the given person is a Republican?

39. Dice re-roll

    This problem was asked by JP Morgan. Probability, Easy.

    Say you are playing a game where you roll a 6-sided dice up to two times, where you can choose to stop at the end of first roll if you wish. You will get a dollar amount equal to the final rolled amount. How much are you willing to pay to play this game?

40. Going to 7.

    This problem was asked by Google. Probability, Easy.

    Say that two teams are playing a series in which each team has a 50% chance of winning any given round. What is the probability that the series will go to 7 games?

41. Gender guess

    This problem was asked by D.E. Shaw. Probability, Easy.

    Suppose you call a random person and ask if they have two children. The person says yes they have two children. You find out that one of their children is a boy - what is the probability that the second child is also a boy?

42. Chance of rain
    This problem was asked by Microsoft. Probability, easy
    Three friends in Seattle each told you it’s rainy, and each person has a 1/3 probability of lying. What is the probability that Seattle is rainy? Assume the probability of rain on any given day is 0.25.



41. Amoeba Survival

    This problem was asked by Goldman Sachs. Probability, easy
    Say you have a jar and it has a single amoeba in it to begin. At every minute, the amoeba has a 1 in 4 chance of doing one of four things: 1) dying out, 2) doing nothing, 3) splitting into 2. What is the probability that there will no amoeba eventually?
42.  Counting paths
     This problem was asked by JP Morgan. Probability, easy
     Imagine you are in a 3D space. From (0,0,0) to (3,3,3), how many paths are there if you can only move up, right, and forward?

43. User transition
    This problem was asked by Pinterest. Probability, easy
    Suppose that you are modeling the monthly active status of a user. At every month, with probability p if the user was a monthly active, then the user will not monthly active user the next month. What is the probability that an arbitrary user will be a monthly active user after two months?

44. Subsequence chance.
    
    This problem was asked by Lyft. Probability, medium
    What is the probability that in a random sequence of H's and T's that HHT shows up before HTT?

45. Double draw
    
    This problem was asked by Zenefits. Probability, easy
    Say that you have a deck of 100 cards with values from 1 to 100, and draw two cards at random without replacement. What is the probability that one card is exactly double the other?

    
46. Consecutive sixes
    
    This problem was asked by JP Morgan. Probability, easy
    Say you roll a dice three times. What is the probability of getting two sixes in a row?

47. Colored Cubes
    
    This problem was asked by SIG. Probability, medium
    Suppose you are given a white cube that is broken into 3x3x3 = 27 pieces. However, before doing so, all 6 faces of the cube were painted green. You randomly pick a small cube and see that 5 faces are white. What is the probability that the bottom face is also white?

48. Random drawer
    
    This problem was asked by J.P. Morgan. Probability, easy
    There are 8 drawers. With probability 1/2, somebody put a letter in one of the drawers. With probability 1/2, that person did not don't put a letter in any drawer. You open the first 7 drawers, and find that they are all empty. What is the probability the 8th drawer has a letter in it?


## Statistics


1. Unfair Coin:
   This problem was asked by Facebook. Statistics,  Medium

   There is a fair coin (one side heads, one side tails) and an unfair coin (both sides tails). 
   You pick one at random, flip it 5 times, and observe that it comes up as tails all five times. What is the chance that you are flipping the unfair coin?

2. Ranking List of shows:

   This problem was asked by Netflix. Product/Statistics, Medium
   How would you design a metric to compare rankings of lists of shows for a given user?

3. Unbaised and consistency
    This problem was asked by Google. Statistics
    What does it mean for an estimator to be unbiased? What about consistent? Give examples of an unbiased but not consistent estimator, as well as a biased but consistent estimator.

4. p-value 

    This problem was asked by Airbnb. Statistics
    
    How can you decide how long to run an experiment? What are some problems with just using a fixed p-value threshold and how do you work around them?


5. Picking between two dice games
   This problem was asked by Facebook., Statistics, hard
   There are two games involving dice that you can play. In the first game, you roll two die at once and get the dollar amount equivalent to the product of the rolls. In the second game, you roll one die and get the dollar amount equivalent to the square of that value. Which has the higher expected value and why?


6. Correlated predictors
    
    This problem was asked by Google. Statistics , medium
    Say you are running a multiple linear regression and believe there are several predictors that are correlated. How will the results of the regression be affected if they are indeed correlated? How would you deal with this problem?

7. MLE vs MAP
    
    This problem was asked by Netflix. Statistics, hard.
    What are MLE and MAP? What is the difference between the two?

8. Improving signups
    
    This problem was asked by Quora. Product/statistics, easy
    Assume you want to test whether a new feature increases signups to the site. How would you run this experiment? What statistical test(s) would you use?

9. Independent and uncorrelated.
    
    This problem was asked by Stripe. Statistics hard
    Say we have two random variables X and Y. What does it mean for X and Y to be independent? What about uncorrelated? Give an example where X and Y are uncorrelated but not independent.

10. A/B testing in streaming
    
    This problem was asked by Netflix. Product/statistics, medium,
    In the streaming context, for A/B testing, what are some metrics and data to track, and what are some differences versus more traditional A/B testing?




11. One extra coin toss
    This problem was asked by Robinhood. Statistics, Medium
    A and B are playing a game where A has n+1 coins, B has n coins, and they each flip all of their coins. What is the probability that A will have more heads than B?

12. Linear regression assumptions
    
    This problem was asked by Google. Statistics, easy
    What are the assumptions behind linear regression? How do you diagnose if any of these assumptions are violated?

13. Covariance of uniforms
    This problem was asked by Netflix. Statistics, hard
    Say we have X ~ Uniform(-1, 1) and Y = X^2. What is the covariance of X and Y?

14. Coin flips needed to detect bias
    This problem was asked by Lyft. Statistics, medium
    Say you have an unfair coin which will land on heads 60% of the time. How many coin flips are needed to detect that the coin is unfair?

15. Area of the circle
    This problem was asked by Lyft. Statistics , medium
    Say you pick the radius of a circle from a uniform distribution between 0 and 1. What is the probability density of the area of the resulting circle?


16. Customer churn MLE
    
    This problem was asked by Airbnb. Statistics, medium
    Say you model the lifetime for a set of customers using an exponential distribution with parameter λ, and you have the lifetime history (in months) of n customers. What is the MLE for λ?
17. Server wait time
    This problem was asked by Dropbox. Statistics, Medium
    Dropbox has just started and there are two servers that service users: a faster server and a slower server. When a user is on the website, they are routed to either server randomly, and the wait time is exponentially distributed with two different parameters. What is the probability density of a random user's waiting time?

18. Clicking variances
    This problem was asked by Google. Statistics, easy,
    Say you have two countries of interest and want to compare variances of clicking behavior from users (i.e. total distribution of clicks). How would you do this comparison, and what assumptions need to be met?

19.  Uncorrelated condition
    
    This problem was asked by Airbnb. Statistics, medium
    Suppose we have two random variables X and Y. Under what condition are X+Y and X-Y uncorrelated?
82. Bernoulli samples
    This problem was asked by Stripe. Statistics, medium
    Consider a Bernoulli random variable with parameter p. Say you observe the following samples: [1, 0, 1, 1, 1]. What is the log likelihood function for p and what is the MLE of p?

20. Bernoulli samples
    This problem was asked by Stripe. Statistics, medium
    Consider a Bernoulli random variable with parameter p. Say you observe the following samples: [1, 0, 1, 1, 1]. What is the log likelihood function for p and what is the MLE of p?




20. Minimum dice roll
    
    This problem was asked by Uber. Stats, hard,
    A fair die is rolled n times. What is the expected value and the standard deviation of the smallest number rolled?

21. expected swaps
    
    This problem was asked by Robinhood. Stats medium
    Say you have n integers 1...n and take a random permutation. For any integers i, j let a swap be defined as when the integer i is in the jth position, and vice versa. What is the expected value of the total number of swaps?

22. Lifetime likelihood
    This problem was asked by Snapchat. Stats, medium
    Say you have a large amount of user data that measures the lifetime of each user. Assume you model each lifetime as exponentially distributed random variables. What is the likelihood ratio for assessing two potential λ values, one from the null hypothesis and the other from the alternative hypothesis?
23. Lifetime difference
    
    This problem was asked by Tesla. Stats medium
    Say that the lifetime of electric vehicles are modeled using a Gaussian distribution. Each type of electric vehicle has an expected lifetime and a lifetime variance. Say you chose two different types of electric vehicles at random. What is the probability that the two lifetimes will be within n time units?

24. Conditional Expectation
    
    This problem was asked by Robinhood. Stats hard
    Say X and Y are independent and uniformly distributed on (0, 1). What is the expected value of X, given that X > Y?


25. Geometric expectation
    This problem was asked by Facebook. Stats hard
    Derive the expectation for a geometric distributed random variable.

26.  Roll correlation
    
    This problem was asked by Robinhood. Stats hard
    Say you roll a fair dice 5 times. Let X be the number of times a 2 was rolled, and Y the number of times a 3 was rolled. What is the correlation coefficient between X and Y?

27. Conditional roll
    This problem was asked by Tesla. Stats medium
    Say you roll a fair dice repeatedly. Let X be the number of rolls until a 1 is rolled, and Y the number of rolls until a 4 is rolled. What is E[X|Y=2]?

28. CDF distribution
    
    This problem was asked by Square. Stats hard
    Say we have a random variable X ~ D, where D is an arbitrary distribution. What is the distribution of F(X) where F is the CDF of X?


29. Customer credits
    
    This problem was asked by Slack. Stats medium
    Suppose that there is a new service with an API offering with credits where by each credit is capped to a certain amount of API usage. Each customer can use a credit and the lifetime of the credit can be modeled as exponentially distributed with an expectation of 2 days. A particular customer will need the API's capabilities for 60 days. How many credits should they purchase so that the probability of API shortage during the 60 days is no more than 1 percent?


30. Exponential conditional
    This problem was asked by Tesla. Stats hard
    Let X and Y be i.i.d exponentially distributed random variables. What is the expectation of X given that X > Y?


31. Uniform distribution
    This problem was asked by Apple. Stats medium
    Derive the mean and variance of the uniform distribution U(a, b).

32. Poisson MLE
    This problem was asked by Google. Stats hard
    Say you have N independent and identically distributed draws of a Poisson random variable. What is the best estimator for the parameter λ? What properties does this estimator have?

33. Uniform draws
    
    This problem was asked by Quora. Stats, medium
    
    Suppose you independently sample three values X ~ U(0, 1). What is the probability that the first value will be larger than the sum of the other two?


34. Joint density
    This problem was asked by Square. Stats hard
    Assume that you have two continuous random variables X and Y that have a joint density function of f(x, y) = x-y when 0 < y < x < 1 and 0 otherwise. What is the covariance of X and Y?





35. Normal mgf
    This problem was asked by Stripe. Stats hard
    Describe what a moment generating function (MGF) is. Derive the MGF for a normally distributed random variable X.

36. Lognormal mean.
    This problem was asked by Slack. Stats, hard
    Assume that log X ~ N(0, 1). What is the expectation of X?

37. Remaining politics
    This problem was asked by Twitter. Stats, easy
    Say you have two groups of random users for surveying, one side Democratic (with D total people) and the other side Republican (with R total people). At each time step, you remove a user randomly and survey them. You stop as soon as all of the Democratic side has been surveyed. At that point, how many Republican people do you expect to still be surveyed?

38.  Summation Odds
    
    This problem was asked by Robinhood. Stats, hard
    Say you take N independent draws of a random variable X ~ Uniform(0, 1). What is the probability that the sum of those N draws is less than or equal to 1? Hint: try looking at N=2 and N=3.


39. Square root of uniform
    This problem was asked by Quora. Stats, medium.
    Let X be uniformly distributed between -1 and 1, i.e. X ~ U(-1, 1). Find the expectation of the square root of |X|.


40. Poisson sum
    This problem was asked by Twilio. Stats, hard
    Say you have two independent Possion random variables X and Y. What is the distribution of X+Y?

41. Central Limit Theorem
    This problem was asked by Uber. Stats, medium
    Explain the Central Limit Theorem and why it is useful.

42.  Variance Bounds
    
    This problem was asked by Akuna Capital. Stats, medium
    Say you have two random variables X and Y, each with a standard deviation. What are the bounds on the variance of aX + bY for constants a and b?

43. Blended statistics
    This problem was asked by Google. Stats, hard
    Say you have two distinct subsets of a dataset for which you know their means and standard deviations. How do you calculate the blended mean and standard deviation of the total dataset? Can you extend it to K subsets?

44. Max of two rolls
    
    This problem was asked by Morgan Stanley. Stats, medium
    What is the expected value of the max of two dice rolls?

45. Confidence Intervals
    This problem was asked by Overstock. Stats, easy
    How would you explain a confidence interval to a non-technical audience?
46. Increasing rolls
    This problem was asked by Robinhood. Stats, hard
    Say you have an n-sided die. You keep rolling and sum the values as long as the current roll is larger than the previous. For example, if n = 6 then you might roll 1, 3, 2 and stop or 1, 4, 5, 3 and stop. In the first case, your total sum is 1 + 3 = 4, and in the second case your total sum if 1 + 4 + 5 = 10. What is the expected value of the sum?

47. Statistical power
    This problem was asked by Microsoft. Stats, easy
    Explain the statistical background behind power.

48. Random normal

This problem was asked by Stripe. Stats, medium
Say you have X ~ N(0, 1). Let Z = XY, where Y takes on two values, -1 and 1 equally with probability 0.5 each. What is the distribution of Z?

49. Monotonically increasing
    
    This problem was asked by Google. Stats, hard
    Assume you are drawing from an infinite set of iid random variables that are uniformly distributed from (0, 1). You keep drawing as long as the sequence you are getting is monotonically increasing. What is the expected length of the sequence you draw?
50. two fives
    
    This problem was asked by Akuna Capital. Stats, medium
    Say you’re rolling a fair six sided dice. What is the expected number of rolls until you roll two consecutive 5s?
51. hypothesis testing and p-value
    This problem was asked by Overstock. Stats, easy
    Describe hypothesis testing and p-values in layman's terms.

52. A/B testing
    This problem was asked by Overstock. Stats, easy,
    Describe some common pitfalls of A/B testing?

53. Type 1 and type 2 errors
    
    This problem was asked by Overstock, Stats, easy
    Describe what type I and type II errors are, and the tradeoffs between them.

54. Sampling from circle
    
    This problem was asked by Lyft. Stats hard,
    How do you uniformly sample points at random from a circle with radius R?


## Machine Learning 

1. Fraud detection trade offs:
   This problem was asked by Affirm. Machine Learning. Medium
   Assume we have a classifier that produces a score between 0 and 1 for the probability of a particular loan application being fraudulent. In this scenario: a) what are false positives, b) what are false negatives, and c) what are the trade-offs between them in terms of dollars and how should the model be weighted accordingly?

2. Classification metrics
   This problem was asked by Uber. Machine Learning, medium
   Say you need to produce a binary classifier for fraud detection. What metrics would you look at, how is each defined, and what is the interpretation of each one?

3. Estimation of fraud
   This problem was asked by Affirm. Machine learning, Medium
   Assume we have some credit model, which has accurately calibrated (up to some error) score of how credit-worthy any individual person is. For example, if the model’s estimate is 92% then we can assume the actual score is between 91 and 93. If we take 92 as a score cutoff and deem everyone above that score as credit-worthy, are we overestimating or underestimating the actual population’s credit score?

4. Identifying synonyms
   This problem was asked by Google. ML . Medium,
   Say you are given a very large corpus of words. How would you identify synonyms?

5. L1 and L2 regularization
   This problem was asked by Uber. ML, Medium,
   What is L1 and L2 regularization? What are the differences between the two?

6. Square root of model squares
   This problem was asked by Affirm. ML, medium
   Assume we have a classifier that produces a score between 0 and 1 for the probability of a particular loan application behind a fraud. Say that for each application’s score, we take the square root of that score. How would the ROC curve change? If it doesn’t change, what kinds of functions would change the curve?

7. Bias -Variance Tradeoff

This problem was asked by Microsoft., ML. Medium
What is the bias-variance tradeoff? How is it expressed using an equation?

8. Modeling listing revenue
   This problem was asked by Airbnb. ML, medium
   Say you are modeling the yearly revenue of new listings. What kinds of features would you use? What data processing steps need to be taken, and what kind of model would run?

9. Recommending similar listings
   This problem was asked by Airbnb. ML, medium
   Say you are tasked with producing a model that can recommend similar listings to an Airbnb user when they are looking at any given listing. What kind of model would you use, what data is needed for that model, and how would you evaluate the model?

10. Adding noise
    This problem was asked by Google., ML, hard,
    Say we are running a probabilistic linear regression which does a good job modeling the underlying relationship between some y and x. Now assume all inputs have some noise ε added, which is independent of the training data. What is the new objective function? How do you compute it?

11. Item propensity modeling
    This problem was asked by Stitch Fix. ML, medium,
    How would you build a model to calculate a customer's propensity to buy a particular item? What are some pros and cons of your approach?

12. K-means clustering update
    This problem was asked by Netflix. ML, hard,
    What is the loss function used in k-means clustering for k clusters and n sample points? Compute the update formula using 1) batch gradient descent, 2) stochastic gradient descent for the cluster mean for cluster k using a learning rate ε.

13. Sensor sensitivity
    This problem was asked by Tesla. ML, hard
    You're working with several sensors that are designed to predict a particular energy consumption metric on a vehicle. Using the outputs of the sensors, you build a linear regression model to make the prediction. There are many sensors, and several of the sensors are prone to complete failure. What are some cost functions you might consider, and which would you decide to minimize in this scenario?

14. Expectation maximization
    This problem was asked by Netflix. ML, hard,
    What is Expectation-Maximization and when is it useful? Describe the setup algorithmically with formulas.

15. Fraud detection

This problem was asked by Stripe. ML< hard
Say we are using a Gaussian Mixture Model (GMM) for anomaly detection on fraudulent transactions to classify incoming transactions into K classes. Describe the model setup formulaically and how to evaluate the posterior probabilities and log likelihood. How can we determine if a new transaction should be deemed fraudulent?

16.  Information gain and entropy

This problem was asked by Microsoft. ML medium
Explain what Information Gain and Entropy are in a Decision Tree.

17. Kernel regression estimator
    This problem was asked by Netflix. ML,hard
    Describe the idea and mathematical formulation of kernel smoothing. How do you compute the kernel regression estimator?

18. Guessing Gaussian

This problem was asked by Stripe. ML hard,
Say we have N observations for some variable which we model as being drawn from a Gaussian distribution. What are your best guesses for the parameters of the distribution? Derive it mathematically.
19. LS equivalent

This problem was asked by Airbnb. ML hard
Suppose you are running a linear regression and model the error terms as being normally distributed. Show that in this setup, maximizing the likelihood of the data is equivalent to minimizing the sum of squared residuals.

20. Logistic regression
    This problem was asked by Stripe. ML hard
    Describe the model formulation behind logistic regression. How do you maximize the log-likelihood of a given model (using the two-class case)?

21. Linear decision boundaries
    This problem was asked by Opendoor. ML hard
    Describe the setup and assumptions of using linear discriminant analysis (LDA). Show mathematically that the decision boundaries are linear.

22. LDA subspaces

This problem was asked by Opendoor. ML, hard

Suppose you are running a linear discriminant analysis (LDA) model on some data with K classes. Describe mathematically how you would project centroids to some L < K-1 dimensional subspace.

23. Bayesian linear regression
    This problem was asked by Airbnb. ML hard
    Suppose you use a Gaussian prior on β of a linear regression. Derive the MAP estimate of β.

24. Maximum entropy
    This problem was asked by Netflix. ML, hard
    Describe entropy in the context of machine learning, and show mathematically how to maximize it assuming N states.

25. Projection matrix
    This problem was asked by Airbnb. ML, hard
    In linear regression, what is the projection matrix? Derive the matrix formulation of it.

26. variance estimate for ls
    This problem was asked by Stripe. ML, hard
    Derive the variance-covariance matrix of the least squares parameter estimates in matrix form.




27. Deriving PCA
    This problem was asked by Netflix. ML, hard
    Describe the idea behind PCA and go through its formulation and derivation in matrix form. Go through the procedural description and solve the constrained maximization.

28. SVMs
    This problem was asked by Microsoft. ML, hard
    Formulate the background behind an SVM, and show the optimization problem it aims to solve.

29. Generative and discriminative

This problem was asked by Amazon. ML, medium
Describe both generative and discriminative models and give an example of each.

30. Gradient descent
    This problem was asked by Amazon. ML, medium
    Describe gradient descent and the motivations behind stochastic gradient descent.

31. Convex and Non-convex

This problem was asked by Amazon. ML, medium
Define what it means for a function to be convex. What is an example of a machine learning algorithm that is not convex and describe why that is so.

32. Random forest and boosting
    This problem was asked by Overstock. ML, medium
    Compare and contrast gradient boosting and random forests.




33. Improving logistic regression

This problem was asked by Airbnb. ML, easy
Say you are running a simple logistic regression on a problem but find the results to be unsatisfactory. What are some ways you might improve your model or what other models might you look into?

34. Cross validation
    This problem was asked by Overstock. ML, medium
    Define the cross validation process. What is the motivation behind using it?

35. GNB vs LR
    This problem was asked by Citadel. ML, medium
    Compare and contrast GNB and logistic regression. When would you use one over the other?

36. Boosting description

This problem was asked by Overstock. ML, easy
Describe the idea behind boosting. Give an example of one method and describe one advantage and disadvantage it has.

37. Precision and recall

This problem was asked by Overstock ML easy
Describe precision and recall and their formulas. Why are they important to look at and what is the trade-off between the two?


## Python/Coding 
Sum of the consecutive numbers
This problem was asked by Robinhood. Python/Coding, Hard
Given a number n, return the number of lists of consecutive positive integers that sum up to n.

2.
This problem was asked by Lyft. Coding, Medium
Say we are given a list of several categories (for example, the strings: A, B, C, and D) and want to sample from a list of such categories according to a particular weighting scheme. Such an example would be: for 100 items total, we want to see A 20% of the time, B 15% of the time, C 35% of the time, and D 30% of the time. How do we simulate this? What if we care about an arbitrary number of categories and about memory usage?

3. Generating integer partitions
   This problem was asked by Stripe. Coding, Medium,
   Write a program to generate the partitions for a number n. A partition for n is a list of positive integers that sum up to n. For example: if n = 4, we want to return the following partitions: [1,1,1,1], [1,1,2], [2,2], [1,3], and [4]. Note that a partition [1,3] is the same as [3,1] so only the former is included.

4. Correlation by hand
   This problem was asked by Robinhood. Coding, medium,
   Write a program to calculate correlation (without any libraries except for math) for two lists X and Y.



5. Max Sum increasing  subsequence

This problem was asked by Uber. Coding, medium,
Given a list of positive integers, return the maximum increasing subsequence, that is, the largest increasing subsequence within the array that has the maximum sum. Examples: if the input is [5, 4, 3, 2, 1] then return 5 (since no subsequence is increasing), if the input is [3, 2, 5, 7, 6] return 15 = 3 + 5 + 7, etc.

6. perfect square count
   This problem was asked by Palantir. Coding, Medium,
   Given a positive integer n, find the smallest number of perfect squares that sum up to n. For example, for n = 7, you should return 4 since 7 = 4 + 1 + 1 +1, and for n = 13, you should return 2 since 13 = 4 + 9.

7. friendship distance
   This problem was asked by Facebook. Coding, Medium,
   You have the entire social graph of Facebook users, with nodes representing users and edges representing friendships between users. Given the edges of the graph and the number of nodes, write a function to return the smallest number of friendships in-between two users.
   For example, if the graph consists of 5 users A, B, C, D, E, and the friendship edges are: (A, B), (A, C), (B, D), (D, E) then the function should return 2 for the input A and E.

8. Estimating PI

This problem was asked by Stripe. Coding medium
Estimate π using a Monte Carlo method. Hint: think about throwing darts on a square and seeing where they land within a circle.




9. Median of data stream

This problem was asked by Palantir. Coding, hard,
Given a stream of elements (of arbitrary size), write a class to find the median at any given time. Your class should have a function to add numbers to the stream and a function to calculate the median.

10. Finding the peaks
    This problem was asked by Reddit. Coding,  Medium
    Given an array A of positive integers, a peak element is defined as an element that is greater than its neighbors.
    For example, if A = [3, 5, 2, 4, 1] you should return either 1 or 3 since index 1 is 5, and index 3 is 4, and both are peak elements. Find the index of any peak elements.

11. Topic groups

This problem was asked by Twitter. Coding, medium
Say that there are n topics on Twitter and there is a notion of topics being related. Specifically, if topic A is related to topic B, and topic B is related to topic C, then topic A is indirectly related to topic C.
Define a topic group to be any group of topics that either directly or indirectly related. Given an n by n adjacency matrix N, where N[i][j] = 1 if topic i and topic are j related and 0 otherwise, write a function to determine how many topic groups are there.
12. Permutations
    This problem was asked by Dropbox. Coding, medium
    Given n distinct integers, write a function to generate all permutations of those integers.

13. Intersection of two arrays.

This problem was asked by Pinterest. Coding, easy
Given two arrays, write a function to get the intersection of the two.
For example, if A = [2, 4, 1, 5, 0], and B = [3, 4, 5] then you should return [4, 5].
14. Palindromic subset
    This problem was asked by Airbnb. Coding, medium
    Given a number x, define a palindromic subset as any subsequence within x that is a palindrome. Write a function that returns the number of digits of the longest palindromic subset.
    For example, if x is 93567619 then you should return 5 since the longest subset would be 96769, which is a 5 digit number.

15. Splitting parenthesis
    This problem was asked by Twitter. Coding medium,
    Given a string with lowercase characters and left and right parentheses, remove the minimum number of parentheses so that the string is valid.
    For example, if the string is ")a(b((cd)e(f)g)" then return "ab((cd)e(f)g)".

16. First Missing Positive

This problem was asked by Snapchat. Coding, hard,
Given an arbitrary array of positive integers, find the smallest missing positive integer. Can you do it with O(1) space?
For example, if A = [1, 3, 6, 2, 7] and then you should return 4.

17. Obstacle paths
    This problem was asked by Twitch. Coding medium
    You are given an m by n matrix with with 0s and 1s, where a 1 represents an obstacle and a 0 represents no obstacle. Determine the number of ways to navigate from the top-left corner of the matrix to the bottom right corner given that at any point in time there is only a move down or to the right as long as there is not an obstacle in that spot.
    For example, if the matrix is given by: [[0, 0, 0], [1, 1, 0], [0, 1, 0]] then you should return 1 since there is exactly one path.


18. Max of sliding window
    This problem was asked by Lyft. Coding hard
    Given an array A of positive integers and an integer k, write a function to get the largest value within the sliding window of size k for A. Each sliding window is k numbers and moves from the leftmost to the rightmost within A, one position at a time.
    For example, if A = [2, 5, 3, 1, 4] and n = 2, then you should return [5, 5, 3, 4].

19. Smallest K pairs

This problem was asked by Apple. Coding medium
Given two sorted arrays of positive integers, and an integer k, determine the k smallest pairs among the two arrays, where a pair is defined as having exactly one element from the first array and one element from the second array.
For example, if the k = 3 and the two arrays are [1, 3, 6, 10] and [2, 5, 7, 9] then [[1, 2], [3, 2], [1, 5]] since those are the three smallest pairs.


20. palindrome counting
    This problem was asked by Opendoor. Coding medium
    Given a string, return the count of substrings within the string that are palindromes.
    For example, if input is "aba": return 4, since the palindromes are: "a", "b", "a", and "aba".

21. All combinations
    This problem was asked by Twitch. Coding medium
    Given an integer n and an integer k, output a list of all of the combinations of k numbers from 1 to n.
    For example, if the n = 3, and k = 2 then return: [1, 2], [1, 3], [2, 3].




22. Anagram grouping

This problem was asked by Slack. Coding medium
Given an array of strings, return a list of lists whereby each list has the strings that are an anagram of one another.
For example, if input is ["abc", "abd", "cab", "bad", "bca", "acd"] then return: [["abc", "cab", "bca"], ["abd", "bad"], ["acd"]].

23. Matrix Paths

This problem was asked by Twitch. Coding hard
Given an m by n matrix with positive integers, determine the length of the longest path of increasing integers within the matrix.
For example, if the matrix is given by: [[1, 2, 3], [4, 5, 6], [7, 8, 9]] then you should return 5.

24. Repeating subarrays
    This problem was asked by Dropbox. Coding medium,
    Given two arrays with integers, return the maximum length of a common subarray within both arrays.
    For example, if the two arrays are [1, 3, 5, 6, 7] and [2, 4, 3, 5, 6] then return 3 since the maximum length is [3, 5, 6].

25. Palindrome subsequence
    This problem was asked by Slack. Coding medium
    Given a string, find the length of its longest palindrome subsequence.
    For example, if the string is "acabcbabb" then return 5 since the longest palindrome subsequence is "abcba".


26. Tree diameter
    This problem was asked by Pinterest. Coding medium
    Given a binary tree, write a function to determine the diameter of the tree, which is the longest path between any two nodes.

27. choosing signs

This problem was asked by Uber. Coding, medium
You are given an array of integers and a target number. For each number, you can place either a + sign or a - sign in front of it. Write a function to calculate how many ways are there to do so such that the sum of the resulting expression is the target number.
For example, if the array is: [1, 2, 3, 4] and the target is 4 then return 2 since the valid expressions are: -1-2+3+4 and +1+2-3+4.

28. Equal elements

This problem was asked by Dropbox. Coding medium
Find the minimum number of increments or decrements (by 1) needed to make all elements of an array be equal.
For example, if the array is: [1, 2, 3, 4, 5] then return 1+2+0+2+1 = 6 since that is the smallest number of increments or decrements to make all elements of the array the same (3).

29. Total Anagrams
    This problem was asked by LinkedIn. Coding, medium
    You are given two strings A and B. Write a function to return a list of all the start indices within A for substrings of A that are anagrams of B.
    For example, if A = "abcdcbac" and B = "abc" then you want to return [0, 4, 5] since those are the starting indices of A whereby there are anagrams of B.



30. Internal removal
    This problem was asked by Pinterest. Coding, hard
    You are given an array of intervals, where each interval is represented by a start time and an end time, such as [1, 3]. Determine the smallest number of intervals to remove within the list such that the rest of the intervals are not overlapping (the times can "touch" such as [1, 3] and [3, 5] but overlap such as [1, 3] and [2, 5]).
    For example, if the interval list given is: [[1, 3], [3, 5], [2, 4], [6, 8]] then return 1 since the desired removal is the [2, 4] interval.

31. Closest points

This problem was asked by Dropbox. Coding , easy
Given a list of points, write a function to find the k closest points to the origin.
For example, if the k = 3 and the points are: [[2, -1], [3, 2], [4, 1], [-1, -1], [-2,2]] then return [[-1, -1], [2, -1], [-2, 2]] since those are the three closest points.

32. List removal
    This problem was asked by Square. Coding, medium
    Write a function to remove the kth node from a linked list and return the head of the linked list.
    For example, if you have the linked list 3 → 2 → 5 → 1 → 4 and k = 3 then remove the 5 and return the linked list 3 → 2 → 1 → 4.

33. Subarray sum

This problem was asked by Apple. Coding, medium
You are given an array and an integer k. Determine the number of continuous subarrays that have a sum equal to k.
For example, if the array list is given by [1, 2, 3, 2, 1] and k = 6, then return 2 since the two subarrays are: [1, 2, 3] and [3, 2, 1].


34.  Minimal Sum
     This problem was asked by Square., Coding , medium
     You are given an m-by-n matrix with positive integers. Say you start at the top-left corner at each time step can move either right or down. Determine the minimal sum of elements along this traversal in reaching the bottom right corner.

35. Matching wildcards

This problem was asked by Slack. Coding, hard
You are given an input string composed of the lowercase letters a-z and a particular regular expression that contains lowercase a-z, ?, or * whereby the ? matches any one character, and the * matches an arbitrary number of characters (empty as well). Write a function to return whether the regex matches the input string.

36. String subsequence
    This problem was asked by Twitter. Coding ,easy
    Given two strings, determine if the first string is a subsequence of the second string. Note that relative positioning matters.
    For example, if the inputs are "abcd" and "xyazbcd" then return true, but if the inputs are "abcd" and "xyazbdc" then return false.

37. Inorder traversal
    This problem was asked by Citadel. Coding, easy
    Given a binary tree, conduct an inorder traversal and return the values in an array.

38. Longest parenthesis
    This problem was asked by Citadel. Coding, hard
    Given a string with left and right parentheses, write a function to determine the length of the longest well-formed substring.
    For example, if the input string is ")(())(" then return 4 since the longest substring is

39. max of three

This problem was asked by D.E Shaw. Coding, easy
Given an integer array, return the maximum product of any three numbers in the array.
For example, if the input is [-5, 2, 6, -4, 8, 2] then return 160.

40. Product without self

This problem was asked by Dropbox. Coding, easy
Say you have an array of n integers. Write a function to output a new array of values such that each value is the total product of the original array except for the current element. Can you do it in O(n) time without using division?
For example, if the input is [1, 2, 3] then return [6, 3, 2].

41. Max subarray

This problem was asked by Akuna Capital. Coding, easy
Given an integer array, find the sum of the largest contiguous subarray within the array.
For example, if the input is [-1, -3, 5, -4, 3, -6, 9, 2] then return 11.

42. Sorted matrix kth smallest

This problem was asked by Reddit. Coding, easy
Say you have an n by n matrix of elements which is sorted in ascending order both in the columns and rows. Return the kth smallest element of the matrix.
For example, if the input is [[1, 4, 7], [3, 5, 9], [6, 8, 11]] and k = 4 then return 5.










43. Splitting array

This problem was asked by Snapchat. Coding, hard
Given an array A of positive integers and an integer n, write a function to minimize the largest sum among any arbitrary split of A into n non-empty contiguous subarrays.
For example, if A = [9, 3, 6, 8, 4] and n = 2, then you should return 18 since the best possible split is: [9, 3, 6] and [8, 4] which results in the largest sum of 18.

44. Dice Roll Target

This problem was asked by Uber. Coding, medium
Suppose you have n dice, and each has k faces from 1..k. Write a function to determine the number of ways of rolling the die such that the sum is a particular given target value.
For example, if n = 2, k = 6, and the target is 7, then you should return 6 since there are 6 possible ways to get a total sum of 7.

45. Minimum depths

This problem was asked by Uber. Coding, easy
Given a binary tree, write a function to determine the minimum depth of the tree (the number of nodes on the shortest path from the root down to a leaf node).



## Open ended Product Questions
1.Social graph comparison

This problem was asked by Facebook. Easy, Product

Imagine the social graphs for both Facebook and Twitter. How do they differ? What metric would you use to measure how skewed the social graphs are?

2. Surge pricing
   This problem was asked by Uber. easy, product

You’re on the data science team and are responsible for figuring out surge pricing. Why does it need to exist and what metrics and data should you track?

3. Difficulties in A/B testing

This problem was asked by Airbnb., Easy, Product
What are some factors that might make testing metrics on the Airbnb platform difficult?

4. Rider app change
   This problem was asked by Lyft. Product, easy
   Your team is trying to figure out whether a new driver app with extra UI features will increase the number of rides taken. How would you test whether the extra features in the app make it better than the original version?

5. News feed metrics

This problem was asked by Facebook. Product, easy,
Let’s say that you are the first person working on the Facebook News Feed. What metrics would you track and how would you improve those metrics?




6. Improving product engagement

This problem was asked by Twitter.  Product, easy
How would you improve product engagement on Twitter?

7. Two factor authentication
   This problem was asked by Robinhood. Product, easy
   Say you are deciding whether to implement two-step authentication when users log in. What data would you look at and how can you make your decision?

8. Measuring the comments

This problem was asked by Facebook. Product, easy,
Let's say Facebook has expanded into a previously untapped geographical region. Looking at weekly metrics, you see a slow decrease in the average number of comments per user over several months. You also know that new users have been growing at a steady linear rate in the area for the same time frame. What are some reasons why the average number of comments per user would be decreasing and what metrics would you look into?
9. Posting drop.
   This problem was asked by Facebook. Product, medium
   Let’s say that the usage of a Facebook posting tool dropped from 2% posts per user last month to 1% post per user today. What might be some potential causes and how would you go about understanding this drop?
10. Disney+ retention

This problem was asked by Disney.    Product, easy
Disney+ offers a 7-day free trial period. After 7 days, customers are charged whatever package they chose. Assume that there are customers who commit to Disney+ right away and therefore don't end up having a 7-day free trial period.
Disney wants to measure the success of the free trial. What metrics and analysis might you do to determine whether or not the free trial successfully acquires new customers?

11. shipping times
    This problem was asked by Wayfair. Product , easy
    If you are selling a product and want to decrease the shipment time from 2 days to 1 day to increase your amount of customers, what are 2 ways to quantify it and 2 risks of this idea?

12. Linkedin Status

This problem was asked by LinkedIn. Product, easy
LinkedIn recently launched a "status" feature where you can now see if a LinkedIn connection is online, symbolized by a green dot, idle, symbolized by an orange dot, or offline (gray dot) status that says how long ago the user was active. Assume that this feature has been around for a few months. What metrics would you look at to assess the success of this feature?

13. Acquiring new customers
    This question was asked by Dropbox. Product easy
    You are a data scientist who works directly with the CEO. Your boss says she is incredibly ecstatic because the average cost of acquiring a customer is a lot lower than the expected value of a customer. She thinks that the acquisition cost has been minimized and the value of a customer has almost been maximized. Help her interpret the metric and give a suggestion about how she should use it to try and maximize revenue.

14. Slack Engagement

This problem was asked by Slack. Product, easy
What are some metrics you would use to measure user engagement at Slack? How would you be able to tell early whether or not user engagement is declining?






15. Uber eats
    This problem was asked by Uber. Product easy
    Say you are on the UberEats team and considering shipping out a potential feature X. What metrics would you look at in order to A/B test this change?

16. Uber Pro

This problem was asked by Uber. Product easy
Uber Pro is a program that is designed to reward outstanding drivers. Think of it like a reward program on the driver side. What do you think are the important metrics for Uber Pro to look at, and how might Uber be able to tell if the service is effective?

17.  Duolingo success
     This problem was asked by Duolingo. Product easy
     How would you measure Duolingo's success from a product standpoint, and another metric you would use to measure its success from a financial standpoint?


18. Google doodle
    This problem was asked by Google. Product easy
    Let's say you are on the team for Google Doodles. What metrics would you use to measure how successful a given Doodle was?

19. New feature on duolingo

This problem was asked by Duolingo. Product easy
Duolingo wants a feature that will increase the user engagement and overall network effect. What features would you recommend and what data would you test and or look at to support your hypotheses?



20. Fake news

This problem was asked by Facebook. Product easy
How would you identify the volume of news feed posts on Facebook that should be deemed as "fake" via a machine learning model? What features and input data would be relevant?

21. Credit card stickiness
    This problem was asked by Capital One. Product, easy
    How would you assess the stickiness of the Capital One Quicksilver card?

22. growth or retention
    This problem was asked by Netflix. Product, easy
    Your manager has two potential features for Netflix to pursue. One is focused on increasing user growth while the other is focused on increasing user retention. Which product would you prioritize and what metric you would use to evaluate whether or not the product is successful?

23. Newest user batch

This problem was asked by Facebook. Product, easy
You work at Facebook and see that there is an increase in the number of accounts created per month, but you want to see whether or not the amount of sticky/engaged users is growing or not from these sign-ups. How might you define and monitor the new batch of users?

24. Evaluating product engagement

This problem was asked by LinkedIn. Product, easy
Say you are working at LinkedIn and your manager is worried that LinkedIn is a product that many people have due to the large professional network it has, but is not particularly engaging. What metrics would you look at to assess this?


25. Decrease in active users

This problem was asked by Snapchat. Product, easy
Let's say Snapchat saw an overall 10% decrease in daily active users, a trend that stayed consistent over the last two weeks. How would you try to look at the root cause of this?

26. News feed ranking
    This problem was asked by Facebook. Product, easy
    Suppose you are to build out Facebook's news feed ranking system. What types of signals would you look into and why?

27. Market expansion
    This problem was asked by Walmart. Product easy
    You work at Walmart, and need to figure out the next city for international expansion. How would you pick the city? What metrics would you look at to help inform this decision?

28. Driver time
    This problem was asked by Lyft. Product, easy
    The average wait time of a driver has increased. What factors do you think influenced this and why?

29. Mobile discrepancy
    This problem was asked by Facebook. Product, easy
    If 70% of Facebook users on iOS use Instagram, but only 35% of Facebook users on Android use Instagram, how would you investigate the discrepancy?



30. new pricing
    This problem was asked by Netflix. Product, easy
    Let's say Netflix is planning to launch its service in a few new countries internationally. How would you think about pricing for each country?

31. Handling outliers
    This problem was asked by Spotify. Product, medium
    How do you deal with outliers? What are some causes for them?

32. Market sizing
    This problem was asked by Uber. Product, easy
    How would you estimate the market size for Uber in the US in large cities? How might your assumptions be wrong?

33. Customer segmentation
    This problem was asked by Apple. Product easy,
    Say you have data on millions of users with many transactions across a variety of products. What types of insights would you look into and why?

