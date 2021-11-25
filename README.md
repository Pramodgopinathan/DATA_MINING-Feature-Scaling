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
