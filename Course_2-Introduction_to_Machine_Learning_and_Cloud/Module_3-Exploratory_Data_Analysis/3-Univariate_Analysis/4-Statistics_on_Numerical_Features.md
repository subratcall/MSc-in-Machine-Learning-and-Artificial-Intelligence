﻿# Statistics on Numerical Features

You have seen how to conduct univariate analysis on categorical variables. Now, let’s look at quantitative or numerical variables.

Numerical variables can be continuous, for example, height, temperature and weight. They can also be discrete, for example, the number of items purchased by a customer at a store, the number of people in a city and the number of ‘heads’ you get when flipping three coins.

In this segment, our expert Anand will walk you through various statistical metrics, such as mean, median, mode and standard deviation.

Now, in the forthcoming video, you will learn how to analyse quantitative variables.   

**VIDEO**   

#### Numeric and Ordered Categorical Variables

Qn: Anand mentioned that you can treat numeric variables as ordered categorical variables. For analysis, you can deliberately convert the numeric variables into ordered categorical; for example, if you have the incomes of a few thousand people, which range from $5,000 to $1,00,000, then you can categorize them into bins such as [5000, 10000], [10000,15000] and [15000, 20000]. _This is called 'binning'._   
Now, which of the following variables can be binned into ordered categorical variables? Mark all correct options.

- The temperature for a city over a certain period of time.
- The revenue generated by a company per day.
- Randomly generated unique customer IDs, such as 17913, 1282, 2380, etc.

Ans: A, B

- _You can bin the temperatures as [0, 10 degrees], [10, 20 degrees], etc._
- _This can also be binned, e.g., [0, 10k], [10k, 20k], etc._

#### Which Metric to Use

Qn: Consider the example Anand is discussing in the video: There is a group of middle-class IT employees and Bill Gates in a room. Now, which metric would you choose if you wanted to get a rough idea of the income of a typical IT employee?

- Mean
- Median
- Mode

Ans: Median, _The average, calculated taking Bill Gates’ income into account, would be an overwhelmingly large number far from the income of any other IT employee in the room. On the other hand, the median will not consider Bill Gates’ income and would be more representative._

Mean and median are single values, which broadly provide a representation of the entire data. As Anand stated clearly in the video, it is very important to understand when to use these metrics in order to avoid inaccurate analysis.

While ‘**mean**’ gives an average of all the values, the ‘**median**’ gives a typical value that can be used to represent the entire group. As a simple rule of thumb, always question someone if they use ‘mean’, since ‘median’ is primarily a better measure of 'representativeness'.

Moving ahead, in the next video, we will look at some other descriptive statistics, such as mode, interquartile distance and standard deviation.   

**VIDEO**   

#### Univariate Analysis

Take a look at the graph below, which represents the numeric variable according to its frequencies, and choose the option that shows the correct order of the mean, median and mode.

**![](https://lh6.googleusercontent.com/JkPZn2mTufguc74eqfMZyJG3v06fxJBqTr3tVvfqy_aS65HzspR0cWDPXFsAtjAJWYsUigbM2EYFeXM11zyYQYUia3nbaux6asMUCjF-L9Z2CmFGXpK95y8PC3clANcTfsABvKo)**

- Median > Mode > Mean
- Median > Mean > Mode
- Mode > Median > Mean
- Mean > Median> Mode

Ans: _The mode value is the lowest among the three parameters because this value has the highest frequency. Median should lie between the mean and mode._

Qn: Which of the following values should be affected by outliers:   

- Mean; median may also be slightly affected
- Mode; median may also be slightly affected
- Standard deviation and variance
- Variance and mode

Ans: A & C.

- _Mean is greatly affected by outliers, and median may be slightly affected._
- _Since mean is impacted by outliers, variance and standard deviation will also be influenced by outliers._

Both standard deviation and interquartile difference are used to represent the spread of the data.

Interquartile difference is a much better metric than standard deviation if there are  **outliers**  in the data. This is because standard deviation will be influenced by outliers, whereas the interquartile difference will simply ignore them.

In the video, you also saw how box plots are used to understand the spread of the data.

Question 1/1

Mandatory

#### Statistics

Qn: The table below shows the marks scored (out of 100) in a course exam:
![Marks_Scored_Statistics_Question](https://i.ibb.co/WyNK4Vv/Marks-Scored-Statistics-Question.png)

Which of the following statements is FALSE?

- About 1/4 of the class received a score of 55 or less.
- About 3/4 of the class received a score of 78 or less.
- About 50% of the class received grades between 55 and 78.
- The median of class marks is more than 66.
- About 1/30 of the class received a score of 48 or less.

Ans: D & E

- _Median is simply the 50th percentile of the data; hence, the median of the data is 66, and not more than 66._
- _About 10% of the class received a score of 48 or less._
