# Interview Questions from [Data Science Prep](https://datascienceprep.com/)
---

## [Probability] Unfair Coin: Facebook [Easy]

There is a fair coin (one side heads, one side tails) and an unfair coin (both sides tails). You pick one at random, flip it 5 times, and observe that it comes up as tails all five times.  Whatis the chance that you are flipping the unfair coin? 

### Solution 
Question 1 in the `pdf` file.

---

## [Coding] Sampling with weights: Lyft [Medium]

Say we are given a list of several categories
(for example, the strings: A, B, C, and D) and want to sample from a
list of such categories according to a particular weighting scheme.
Such an example would be: for 100 items total,
we want to see A 20% of the time, B 15% of the time, C 35% of the time,
and D 30% of the time. How do we simulate this?
What if we care about an arbitrary number of categories and about memory usage?

### Solution 
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/sampling_with_weights.py)

---

## [Probability] Flips until two heads: Lyft [Medium]

This problem was asked by Lyft.

What is the expected number of coin flips needed to get two consecutive heads?

### Solution 

Analytical solution in the Question 2 section in the `pdf` file. Empirical evaluation is [here.](https://github.com/adijo/data-science-prep/blob/master/code/expected_flips_two_heads.py)

---

## [Statistics] Drawing normally: Quora [Medium]

You are drawing from a normally distributed random variable X ~ N(0, 1) once a day. What is the approximate expected number of days until you get a value of more than 2?

### Solution
Analytical solution in the Question 3 section of the `pdf` file. Empirical evaluation is [here.](https://github.com/adijo/data-science-prep/blob/master/code/expected_days_normal_distribution.py)

---

## [SQL] Ad CTR: Facebook [Easy]
Assume you have the below events table on app analytics. Write a query to get the click-through rate per app in 2019.
```sqlite-sql
column_name	type
app_id	        integer
event_id	string ("impression", "click")
timestamp	datetime
```

### Solution
SQL query is [here.](https://github.com/adijo/data-science-prep/blob/master/code/ctr_calculation.sql)

---

## [Statistics] Is the coin biased?: Google [Medium]
A coin was flipped 1000 times, and 550 times it showed up heads. Do you think the coin is biased? Why or why not?

### Solution
Solution is in the Question 4 section of the `pdf` file. The computation is [here.](https://github.com/adijo/data-science-prep/blob/master/code/Is%20this%20coin%20biased%3F.ipynb) I've also added an additional Bayesian Modeling approach to this problem using `pymc3` [here.](https://github.com/adijo/data-science-prep/blob/master/code/Bayesian%20Modelling%20Coin%20Flips.ipynb)

---

## [Probability] Rolls to see all sides: Facebook [Medium]
What is the expected number of rolls needed to see all 6 sides of a fair die?

### Solution
Solution is in the Question 5 section of the `pdf` file.
 
--- 

## [Statistics] Picking between two dice games: Facebook [Hard]
There are two games involving dice that you can play. In the first game, you roll two die at once and get the dollar amount equivalent to the product of the rolls. In the second game, you roll one die and get the dollar amount equivalent to the square of that value. Which has the higher expected value and why?

### Solution
Solution is in the Question 6 section of the `pdf` file.

---
## [Probability] Fair odds from unfair coin: Airbnb [Medium]
Say you are given an unfair coin, with an unknown bias towards heads or tails. How can you generate fair odds using this coin?

### Solution 
Solution is in the Question 7 section of the `pdf` file. Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/unfair_coin.py)

---
## [Probability] Ant Collision: Facebook [Medium]
Three ants are sitting at the corners of an equilateral triangle. Each ant randomly picks a direction and starts moving along the edge of the triangle. What is the probability that none of the ants collide? Now, what if it is k ants on all k corners of an equilateral polygon?

### Solution 
Solution is in the Question 8 section of the `pdf` file.

---
## [Coding] Generating integer partitions: Stripe [Medium]
Write a program to generate the partitions for a number `n`. A partition for `n` is a list of positive integers that sum up to `n.` For example: if `n = 4`, we want to return the following partitions: `[1,1,1,1], [1,1,2], [2,2], [1,3]`, and `[4]`. Note that a partition`[1,3]` is the same as `[3,1]` so only the former is included.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/integer_partitions.py)

---

## [ML] Classification Metrics: Uber [Medium]
Say you need to produce a binary classifier for fraud detection. What metrics would you look at, how is each defined, and what is the interpretation of each one?

### Solution
Question 9 of the `pdf` file.

---

## [Statistics] Simulating a standard normal distribution: Uber [Hard]
Say you are given a random Bernoulli trial generator. How would you generate values from a standard normal distribution?

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/Standard%20Normal%20From%20Bernoulli.ipynb)

---

## [Coding] Correlation by hand: Robinhood [Medium]
This problem was asked by Robinhood.

Write a program to calculate correlation (without any libraries except for math) for two lists X and Y.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/correlation.py)

---

## [Probability] Flipping game: Facebook [Easy]
You and your friend are playing a game. The two of you will continue to toss a coin until the sequence HH or TH shows up. If HH shows up first, you win. If TH shows up first, your friend wins. What is the probability of you winning?

### Solution
Question 10 of the `pdf` file and a simulation is [here](https://github.com/adijo/data-science-prep/blob/master/code/flipping_game.py)

--- 

## [Probability] First to roll side k: Lyft [Medium]
A and B are playing the following game: a number k from 1-6 is chosen, and A and B will toss a die until the first person sees the side k, and that person gets $100. How much is A willing to pay to play first in this game?

### Solution
Question 11 of the `pdf` file.

---

## [Coding] Max Sum Increasing Subsequence: Uber [Medium]
Given a list of positive integers, return the maximum increasing subsequence, that is, the largest increasing subsequence within the array that has the maximum sum. Examples: if the input is [5, 4, 3, 2, 1] then return 5 (since no subsequence is increasing), if the input is [3, 2, 5, 7, 6] return 15 = 3 + 5 + 7, etc.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/max_sum_increasing_subsequence.py)

---

## [Statistics] One extra coin toss: Robinhood [Medium]

A and B are playing a game where A has n+1 coins, B has n coins, and they each flip all of their coins. What is the probability that A will have more heads than B?

### Solution
Question 12 of the `pdf` file.

--- 

## [Probability] Labeling content: Facebook [Easy]
Facebook has a content team that labels pieces of content on the platform as spam or not spam. 90% of them are diligent raters and will label 20% of the content as spam and 80% as non-spam. The remaining 10% are non-diligent raters and will label 0% of the content as spam and 100% as non-spam. Assume the pieces of content are labeled independently from one another, for every rater. Given that a rater has labeled 4 pieces of content as good, what is the probability that they are a diligent rater?

### Solution
Question 13 of the `pdf` file.

--- 

## [Statistics] Coin flips needed to detect bias: Lyft [Medium]
Say you have an unfair coin which will land on heads 60% of the time. How many coin flips are needed to detect that the coin is unfair?

### Solution
Question 14 of the `pdf` file.

---
## [Coding] Friendship distance: Facebook [Medium]

You have the entire social graph of Facebook users, with nodes representing users and edges representing friendships between users. Given the edges of the graph and the number of nodes, write a function to return the smallest number of friendships in-between two users.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/social_graph.py)

---

## [Probability] Max Dice Roll: Spotify [Medium]
A fair die is rolled `n` times. What is the probability that the largest number rolled is `r`, for each `r` in `1..6`?

### Solution
Question 15 of the `pdf` file.

--- 

## [Coding] Mirror Binary Tree: Pinterest [Easy]
Given a binary tree, write a function to determine whether the tree is a mirror image of itself. Two trees are a mirror image if their root values are the same and the left subtree is a mirror image of the right subtree.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/symmetric_tree.py)

---
## [Statistics] Customer Churn MLE: Airbnb [Medium]
Say you model the lifetime for a set of customers using an exponential distribution with parameter `??`, and you have the lifetime history (in months) of `n` customers. What is the MLE for `??`?

### Solution
Question 16 in the `pdf` file

---
## [Statistics] Server Wait Time: Dropbox [Medium]
Dropbox has just started and there are two servers that service users: a faster server and a slower server. When a user is on the website, they are routed to either server randomly, and the wait time is exponentially distributed with two different parameters. What is the probability density of a random user's waiting time?

### Solution
Question 17 in the `pdf` file.

--- 
## [Coding] Estimating Pi: Stripe [Medium]
This problem was asked by Stripe.

Estimate `??` using a Monte Carlo method. Hint: think about throwing darts on a square and seeing where they land within a circle.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/estimate_pi.py)

---

## [Probability] First toss: Lyft [Medium]
This problem was asked by Lyft.

A fair coin is tossed n times. Given that there were k heads in the n tosses, what is the probability that the first toss was heads?

### Solution
Question 18 in the `pdf` file.

---

## [Coding] Topic Groups: Twitter [Medium]
Say that there are n topics on Twitter and there is a notion of topics being related. Specifically, if topic A is related to topic B, and topic B is related to topic C, then topic A is indirectly related to topic C.

Define a topic group to be any group of topics that either directly or indirectly related. Given an n by n adjacency matrix N, where `N[i][j] = 1` if topic `i` and topic are `j` related and 0 otherwise, write a function to determine how many topic groups are there.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/topic_groups.py)

---

## [Probability] Coin Recursion: Robinhood [Medium]

A biased coin, with probability `p` of landing on heads, is tossed `n` times. Write a recurrence relation for the probability that the total number of heads after `n` tosses is even.

### Solution
Question 19 of the `pdf` file has the solution and an implementation of the solution is [here.](https://github.com/adijo/data-science-prep/blob/master/code/even_heads.py)

---

## [Coding] Permutations: Dropbox [Medium]
Given `n` distinct integers, write a function to generate all permutations of those integers.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/permutations.py)

---

## [Probability] Random Testing: Lyft [Easy]
Say that you are pushing a new feature `X` out. You have `1000` users and each user is either a fan or not a fan of X, at random. There are `50` users of `1000` that do not like `X.` You will decide whether to ship the feature or not based on sampling 5 users independently and if they all like the feature, you will ship it. What is the probability that you will ship the feature?

### Solution
Question 20 of the `pdf` file.

---

## [Coding] All Combinations: Twitch [Medium] 
Given an integer n and an integer k, output a list of all of the combinations of k numbers from 1 to n.

For example, if the `n = 3`, and `k = 2` then return: `[1, 2], [1, 3], [2, 3]`.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/all_combinations.py)

---

## [Coding] Obstacle Paths: Twitch [Medium]

You are given an `m` by `n` matrix with `0s` and `1s`, where a `1` represents an obstacle and a `0` represents no obstacle. Determine the number of ways to navigate from the top-left corner of the matrix to the bottom right corner given that at any point in time there is only a move down or to the right as long as there is not an obstacle in that spot.

For example, if the matrix is given by: `[[0, 0, 0], [1, 1, 0], [0, 1, 0]]` then you should return `1` since there is exactly one path.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/obstacle_path.py)

--- 

## [Probability] Fan Groups: Snapchat [Easy]
You are testing a new feature with various sample groups of three people. Assume that each person is equally likely to be a fan or not a fan of the feature. What is the probability that a randomly chosen group has exactly one fan, given that there is a fan among the three?

### Solution
Question 21 of the `pdf` file.

--- 

## [Probability] Hit Show: Netflix [Hard]

Before a show is released, it is shown to several in-house raters. You assume there are two types of shows: hits, which have an `80%` chance of being liked by any viewer, and misses, which have a `20%` chance of being liked by any viewer. There is currently a new show which you believe has a prior distribution of `60%` being a hit, and `40%` being a miss. Given that `8` raters rated the show and `6` of the `8` liked the show, what is the new posterior distribution of being a hit or miss?

### Solution
Question 22 of the `pdf` file.

---

## [Coding] Palindrome Counting: Opendoor [Medium]

Given a string, return the count of substrings within the string that are palindromes.

For example, if input is `aba`: return `4`, since the palindromes are: `a`, `b`, `a`, and `aba`.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/palindrome_counting.py)

---

## [Coding] Intersection of Two Arrays: Pinterest [Easy]

Given two arrays, write a function to get the intersection of the two.

For example, if `A = [2, 4, 1, 5, 0]`, and `B = [3, 4, 5]` then you should return `[4, 5].`

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/intersection_of_two_arrays.py)

---

## [Probability] Waiting Time: Twilio [Easy]

You are modeling the wait time a customer has for a support call as exponentially distributed with a mean of `10` minutes. Suppose a customer calls in and is told that all lines are currently busy, and the most recent last spot was occupied `5` minutes ago. What is the probability that the current customer will need to wait no more than another `5` minutes?

### Solution
Question 23 of the `pdf` file.

---

## [Probability] Favorite Show: Disney [Medium]
Alice and Bob are choosing their top `3` shows from a list of `50` shows. Assume that they choose independently of one another. Being relatively new to Hulu, assume also that they choose randomly within the `50` shows. What is the expected number of shows they have in common, and what is the probability that they do not have any shows in common?

### Solution
Question 24 of the `pdf` file and the simulation is [here.](https://github.com/adijo/data-science-prep/blob/master/code/favorite_show.py)

---

## [Coding] Splitting Parentheses: Twitter [Medium]
Given a string with lowercase characters and left and right parentheses, remove the minimum number of parentheses so that the string is valid.

For example, if the string is `)a(b((cd)e(f)g)` then return `ab((cd)e(f)g)`

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/splitting_parentheses.py)

---

## [Statistics] Bernoulli Samples: Stripe [Medium]
Consider a Bernoulli random variable with parameter `p.` Say you observe the following samples: `[1, 0, 1, 1, 1]`. What is the log likelihood function for `p` and what is the MLE of `p`?

### Solution
Question 25 of the `pdf` file.

---

## [Coding] Palindromic Subset: Airbnb [Medium]

Given a number `x`, define a palindromic subset as any subsequence within `x` that is a palindrome. Write a function that returns the number of digits of the longest palindromic subset.

For example, if `x` is `93567619` then you should return `5` since the longest subset would be `96769`, which is a `5` digit number.

### Solution
Code is [here.](https://github.com/adijo/data-science-prep/blob/master/code/palindromic_subset.py)