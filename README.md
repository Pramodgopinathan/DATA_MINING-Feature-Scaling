# Frequent Patterns
How many time patterns have appear in the dataset.

# Why?
It help us to understand the relationships among data. By identifying frequent patterns we can observe strongly correlated items togethers and easily identify similar characteristics and association among them.

# Market Basket Analysis:
Market Basket Analysis is one the key techniques used by large retailers to uncover associations between items. 
Example:
<p>(Bread also tend to buy Butter) </p> <p> (Laptops also tend to buy bag) </p>

Association Rule Mining:
A (IF) -> B (THEN)

# There are three type of matrices which help to measure the association algorithm
<p>
1. Support 
Is the frequency of the items brought, Filter out the items which are not frequent bought.
Support = freq(A,B) / N

<p>
2. Confidence
How offend the items A and B occur together, like if person bought A and B but not C then we can rule out
</p>Confidence = freq(A,B) / freq(A)

# How does it work?
![](https://github.com/Pramodgopinathan/DATA_MINING-Frequent-Patterns/blob/d07e8f55e17ec0d53d44949194bc7c1447a40007/Apriori%20Alogrithm.png)

# Association Rule

computer -> antivirus_software [support = 2%, confidence = 60%]
<br>A support of 2% means that 2% of all the transactions under analysis show that computer and antivirus software are purchased together </br>
<br>A confidence of 60% means that 60% of the customers who purchased a computer also bought the software. Confidence tells about the number of times these relationships have been found to be true. </br>
<br>Association rules are considered interesting if they satisfy both a minimum support threshold and minimum confidence threshold.</br>


# <br>In general, association rule mining can be viewed as a two-step process: </br>

<br>
1. Find all frequent itemsets By definition, each of these itemsets will occur atleast as frequently as a predetermined minimum support count, min_support </br>

<br>
2. Generate strong association rules from the frequent itemsets: By definition, these rules must satisfy minimum support and minimum confidence.
