java c
Midterm stat 291 section 2 Fall 2023
40 points per problem
1)  Suppose you wanted to estimate the percentage of popular vote that Donald trump would get with:
a)   Margin of error .001 (1/10 of 1 percent). How many voters do you have to sample (enough voters that you don’t need finite population correction)
b)  Margin of error .01 (1 percent (ditto)
2)  In the NOAAWSD data set divide it into storms before 2000 and after (and including) 2000 Show the code .95 confidence interval alpha=.05
a)   Calculate the two  bootstrap confidence interval for the average number of severe storms per year  and median number per year using the tidy verse estimate for the two time periods
b)  Calculate the pivotal bootstrap confidence intervals from the generalized.bootstrap (regday3.pck class 12)  for the same 4 confidence intervals.
c)   Find the Pvalue for the difference in means in All disasters before and after using the tidyverse version of pvalue
d)  Do all the methods give rough agreement
3)  Use the slide from class 15 Construct a 1 sample likelihood ration test
•    The actual likelihoods  are for the 1st  101 points aredpois(c(0:100),20)/((dpois(c(0:100),10)+dpois(c(0:100),40))/2)
a)   Order the likelihood ratios and the corresponding observed x values (i.e. 0 to 100)
b)  Work from largest to smallest, find the interval of counts (xvalues of the larger ratio
group) that contains probability .05 or as close as possible without going over for the null hypothesis distribution (remember the null hypothesis distribution is that in the denominator region)
c)   How much does this differ from the test taking .025 probability from the upper tail of the   poisson 10 distribution in union with .025 probability from the lower tail of the poisson 40 distribution
d)  Calculate the power of the likelihood ratio test, the probability in the the interval in b according to the alternative hypothesis
4)  Using FDR
a)   Find interesting genes for  melanoma, and Colon cancer in the NCI60 data set in ISLR. Use a false discovery rate of .2.( Setting it up Are genes from the same cell statistically independent?)
b)  Are there any common interesting genes between these two  cancers? (you can use the intersect function)

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
