# Dimensions and measures

What is the difference between a **dimension **and a **measure**?

If you think about a report, you might realize that there are two kinds of fields.\
Some fields are used to **segment the data into various groups**.** **These are **dimensions**.\
Other fields are used to **compute a value for each segmented group.** These are **measures **(also known as metrics).

**Dimensions group (or segment or slice) the data.**

**Measures compute a single value for each group.**

Common dimensions include **dates **(to group rows by year, month, day, etc...) and **places** (to group rows by country, state, etc...). However, almost any data field can be used as a dimension, because it is very useful to slice the data in different ways.\
In an e-commerce context for example, you might want to slice your sales based on customer type, channel, vendor, status, and dozens of other attributes. You can get very granular. For example, to compute _total sales by customer_, you could choose _customer id_ or _customer email_ as a dimension.

Given that a measure computes a single value per group, measures must **compute an aggregated value** for the entire group (using common aggregation functions such as COUNT, SUM, AVG, MIN, MAX, etc...).\
\
In most domains, there are many more dimensions than measures.\
That is because it is very common to slice your data in a very different and flexible ways. In contrast, a handful of common measures is typically used.

{% hint style="warning" %}
A common mistake is to assume that quantitative/numeric values are always measures and qualitative values are always dimensions (and vice versa). It's a great rule of thumb but it's not always true.

As an example, imagine that you run an e-commerce store.

Using numeric fields as dimensions is sometimes appropriate. For example, you might want to slice your data by ordered quantity, product price, product weight, customer total spend, etc...\
However, this can result in a lot of different groups and in practice you are likely to apply a formula to discretize your numeric fields into a few bins such 'Low' , 'Medium' and 'High'.

Similarly, date and text measures are also encountered. You might want a report to show the _Latest order date by product by location_. Product and location are used as dimensions, while _Latest order date_ is a date measure, and its formula is _MAX(OrderDate)_.\
You can also apply discretization to turn numeric measures into text measures. For example, a report S_ales by region_ might show a 'Low', 'Medium' and 'High' for each region.
{% endhint %}



