# Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-
This repository compares the incarceration rate in Baltimore City and Washington, DC and analyzes the relationship between the incarceration rate and parent income.

## Background 
According to the 2020 OECD data, US has the highest incarceration rate among OECD countries as of May 2020 [OECD data]( https://www.statista.com/statistics/300986/incarceration-rates-in-oecd-countries/#:~:text=Incarceration%20rates%20in%20OECD%20countries%20as%20of%20May%202020&text=The%20incarceration%20rate%20represents%20the,prisoners%20per%20100%2C000%20U.S.%20residents), and about 0.7% of the United States are currently in jail according to Prison Policy Initiative policy data [Prison Policy data](https://www.prisonpolicy.org/blog/2020/01/16/percent-incarcerated/). Then how do incarceration rates look like for each state? Specifically, for my analysis, I am going to compare the incarceration rate of Baltimore, Maryland which is a city well known for their high crime rate and Washington, DC, a city that used to have a nickname of "Murder Capital." Although, I wasn't born in the United States, I stay in Washington, DC every break since my older sister lives there, so I consider DC my second hometown. I am going to use metrics of incarceration rates of all parent income, 75th percentile parent income, 50th percentile parent income, and 25th percentile parent income in both Baltimore city and Washington, DC. These metrics particularly grabbed my attention since there are many reports and analysis on the relationship between incarceration rate and race, but not necessarily for the relationship between parent income (family financial background) and incarceration rate. I wanted to explore whether one's parents' financial status or environment significantly affects the likelihood of one's likelihood of incarceration, in a more general context, how important the environment children grew up can be for shaping their life trajectories. And if so, I wanted to know why such trend happens and since Baltimore is known for its high crime rate, I wanted to know if there is any unique trend of incarceration rate in Baltimore city compared to Washington, DC. Moreover, research shows that employment rate of people who came out of jail tend to decrease by 24 percent [Employment rate after jail](https://www.vox.com/identities/2018/3/14/17114226/incarceration-family-income-parents-study-brookings-rich-kid-poor-kid). Thus, if people got out of jail and are not able to find jobs because of the imprisonment record, this would lead them to have zero or lower income. Then, this eventually would lead to a same problem of high incarceration rate for their children if the following is true: lower parent income leads to higher incarceration rate of their children. Thus, I wanted to use this metric to find out if there is actually a relationship between the incarceration rate and parent income and how that affects the society in general. 


## Business question 
Does one's parents' income (financial status) affects one's life trajectories, specifically, the likelihood of imprisonment?

## Original Data for Excel Analysis
[Baltimore, MD - Original Incarceration Rate of All Parent Income] https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/commit/780f7f11639c9a5e1941d816491ddd84dbd97565

[Baltimore, MD - Original Incarceration Rate of 75th Percentile Parent Income] https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/commit/ed00c976ddf74a4ce01e7371195cdf39a9fb9a67

[Baltimore, MD - Original Incarceration Rate of 50th Percentile Parent Income] https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/commit/119ce2cad2390fd6ee4ec19bd7e86c414c0f4125

[Baltimore, MD - Original Incarceration Rate of 25th Percentile Parent Income] https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/commit/7e7f64036e68ce61980156a97a5f641766acc5ad

[Washington, DC - Original Incarceration Rate of All Parent Income] https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/commit/bbb6d160f8aa8144f1e0954b1378fdca9e7acd97

[Washington, DC - Original Incarceration Rate of 75th Percentile Parent Income] https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/commit/fc7f79a5a0ee35e7dba1e173079ca7af86732ef5

[Washington, DC - Original Incarceration Rate of 50th Percentile Parent Income] https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/commit/b1c474f195113bf6d6a2905721d8da1272cae981

[Washington, DC - Original Incarceration Rate of 25th Percentile Parent Income] https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/commit/3fea844ecf015234b4d7aca9f3ef9b3589b1b2e1

## Original Data for Python Analysis
### Same data as excel analysis 
[Python_bal_incar_all]https://github.com/michellesykim/Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-/commit/fed4d986a075e05ccb85a73b033d565c3c0fb65a

[Python_bal_incar_75]https://github.com/michellesykim/Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-/commit/fed4d986a075e05ccb85a73b033d565c3c0fb65a

[Python_bal_incar_50]https://github.com/michellesykim/Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-/commit/fed4d986a075e05ccb85a73b033d565c3c0fb65a

[Python_bal_incar_25]https://github.com/michellesykim/Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-/commit/fed4d986a075e05ccb85a73b033d565c3c0fb65a

[Python_dc_incar_all]https://github.com/michellesykim/Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-/commit/fed4d986a075e05ccb85a73b033d565c3c0fb65a

[Python_dc_incar_75]https://github.com/michellesykim/Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-/commit/fed4d986a075e05ccb85a73b033d565c3c0fb65a

[Python_dc_incar_50]https://github.com/michellesykim/Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-/commit/fed4d986a075e05ccb85a73b033d565c3c0fb65a

[Python_dc_incar_25]https://github.com/michellesykim/Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-/commit/fed4d986a075e05ccb85a73b033d565c3c0fb65a

## Data Analysis / Metrics
[Data Analysis on Incarceration data and Parent Income] https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/blob/master/Incarceration%20Data%20Analysis%20in%20BAL%20and%20DC.xlsx

This excel file contains four tabs (sheets). 
1. Baltimore-Incarceration Tab : This contains the incarceration rates of all parent income, 75th percentile parent income, 50th percentile parent income, and 25th percentile parent income for each neighborhood in Baltimore. On the right side of the sheet, I sorted out the minimum and maximum incarceration value for each parent income percentile, and calculated skewness. And based on the data, I made three histograms for each subgroup of parent income of 75th percentile, 50th percentile, and 25th percentile to see how many neighborhoods belong to each range of incarceration rate range. Then, I combined those three histograms as a one linear graph to see how those three histograms differ in trend. 

2. Washington, DC-Incarceration Tab: I did the same exact analysis as the Baltimore-Incarceration Tab. 

3. Combined Linear Graph Tab: I combined the linear graph (which combined three histograms) for both Baltimore and DC to see clearly if there is any difference or similarities in the trends. 

4. Pivot Table Tab: I made pivot tables for both Baltimore and DC to see which city has a higher incarceration rate for each parent income percentile. Values are the average incarceration rate for each parent income percentile. Also, I made linear graphs for each city to show how the grand total average rate of incarceration rate increases as the parent income decreases and to see how significant the difference is. 

## Python Notebooks/Analysis
Used Python and Google Colaboratory to conduct analysis
* **Python - comparing incarceration rate for different parent income in Baltimore City and Washington, DC**: a Google Colaboratory notebook to aggregate data and conduct analysis with Python [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18cx8aFYXv_lqru-SVgoHyZ07n1gX1sQu?usp=sharing)


## Results from my analysis and graphs

![alt text](https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/blob/master/Picture2.png)
As the three histograms on the left side show, as the parent income percentile gets lower (as the parent income gets lower), more neighborhoods tend to have higher rate of incarceration. For instance, for 75th percentile parent income (high income) graph (blue histogram), most of the neighborhoods in Baltimore have the incarceration rate range of 0 ~ 0.4, and for 50th percentile parents (median income), most neighborhoods in Baltimore have the incarceration rate of 0.02 ~ 0.05, and lastly for 25th percentile parent income (low income), most neighborhoods in Baltimore have the incarceration rate range of 0.04 ~ 0.06, and specifically 45 neighborhoods out of 197 have 0.6% of incarceration rate for 25th percentile graph. This could also be explained with the skewness of each histogram. Histogram of incarceration rate of 75th percentile parent income has the highest skewness of 1.81 where the skewness of 25th percentile parent income is the lowest of 0.21. This indicates that both have positive skewness but the values for the 25th percentile histogram are extended further to the right compared to other two histograms. And also looking at the combined linear graph on the right side, it is clear that the peak of the graph tends to move to the right and the graph itself also moves to the right as the parent income percentile falls. This meaning of more neighborhoods experiencing higher incarceration rates as the parent income falls is that low parent income (poor family financial situation) tend to increase the likelihood of their child's imprisonment rate. In a more general context, the environment that one grew up can actually affect one's life trajectories. 

![alt text](https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/blob/master/Picture1.png)
Similar result for DC. As you can see from the combined linear graph, more neighborhoods tend to have higher incarceration rates as the parent income goes down (the peak of the yellow graph is on the left and the peak of the light blue graph is more shifted toward to the right relatively). Also, the skewness of the incarceration rate of 25th percentile parent income is lower than the skewness of the 75th percentile. This similar trend both in Baltimore city and Washington, DC indicates and highlights that children who grew up under poor parents tend to have higher possibility of incarceration compared to children who grew up under rich parents. 

![alt text](https://github.com/michellesykim/Comparing-incarceration-rate-in-Baltimore-MD-and-Washington-DC-/blob/master/picture3.png)
Red lines are from the DC linear graph and black lines are from the Baltimore linear graph. Now, combining two line graphs from Baltimore city and Washington, DC show similar pattern where low parents income increases the incarceration rate of their children. However, one significant difference is that the for Baltimore, it has a very high peak that stands out for 0.06% of incarceration rate. This not only tells that there are more neighborhoods in Baltimore city that have the incarceration rate of 0.06-0.7 but also tells that children who grew up under poor parents (25th percentile) are more vulnerable and more likely to be affected by their parents' low income or unstable financial status in Baltimore city compared to Washington, DC. Thus, this means that when one considers public policies that could lower the incarceration rate in Baltimore city, one has to think about how to help the 25th percentile parent income children specifically since they tend to be more affected by the poor and unstable financial environment. 

![alt text](https://github.com/michellesykim/Comparing-incarceration-rate-and-parent-income-in-Baltimore-City-and-Washington-DC-/blob/master/picture7.png)
Looking at the pivot tables for Washington, DC and Baltimore City, the average incarceration rate in Baltimore city are higher than Washington, DC for all parent income percentile, 75th percentile, 50th percentile, and 25th percentile. This indicates that Baltimore city in general has a higher rate of incarceration than Washington, DC. This also shows that as the parent income percentile gets lower, the average incarceration rate gets higher in both cities. For both cities, incarceration rate of 25th percentile parent income increased more than 100% from 75th percentile value which is a significant increase. Thus, the parent income status does affect their children's life especially their incarceration rate. 

## Summary
Multiple data analyses that I conducted show that in both Washington, DC and Baltimore city, the trend is that for 75th percentile parent income (high income), most cities tend to have lower rate of incarceration and for 25th percentile parent income (Low income), most cities tend to have relatively higher (the peak part moves towards to the right relatively) incarceration rate compared to 75th percentile or 50th percentile. Also, the average incarceration rate for each parent income in both cities show that incarceration rate of poor parents increased more than 100% from the incarceration rate of wealthy parents. This relates back to my business question. These numerical findings all together show that one's family (parents) income (degree of financial stability) affects children trajectories especially their incarceration rate. Growing up in poverty increases the likelihood of incarceration and children who grew up under wealthy parents tend to have less incarceration rate. Thus, where one grew up does matters and can affect one's future life. Additional following data would be useful to build on these findings: 
1. The term of imprisonment - this could help to see how specifically and significantly one's parents' financial situation has affected their one's life. Longer imprisonment term might mean that one's parents' financial situation had more significant impact on one's life. 
2. It would also be helpful to know if lower income parents tend to have poor parenting or lack parental involvement. This way I could suggest a more specific solutions for Baltimore. For example, if lower income parents tend to care less about their children's education, and if I could find a way to resolve this parenting issue, this would help at least some lower income parents to prevent their children for facing a higher incarceration rate. 

For Baltimore centric solution, we would have to focus on the difference in these two cities which is the high incarceration rate of 25th percentile parent income in Baltimore. The solutions have to focus on improving the environment for the 25th percentile parent and their children who are more vulnerable compared to the children from similar background in DC. This analysis and the answer to my business question are important to me since by looking at the relationship between the parents' income and incarceration rate, if we could find out what exactly leads the lower income parent to negatively affect their children's incarceration rate, for example, is it because they do not have enough money to support their child's education? Is it because they tend to have lower parental involvement at school? Is it because of a pervasive discrimination? and if we could answer these questions, this would help myself and my community to provide effective solutions for parents who have lower income and make this place a better and safer place to live. It is important not only for me but for everyone in this society to fully understand this issue to make the United States a place where people from various socioeconomical backgrounds can have a better life. 







