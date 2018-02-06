# dand-p3-investigate-dataset
Investigate a dataset project from Udacity's Data Analyst Nanodegree

<h4>Investigate the Titanic dataset</h4>

The titanic dataset contains information about 891 passengers on board the titanic. Variables related to each passenger include their name, gender, age, ticket class, cabin, fare, where they embarked, who was with them, and if they survived.

Given this information I would like to investigate whether any variables contribute to a passenger's likelihood of survival. The question I will be using to guide my analysis of the dataset is: What factors make people more likely to survive?

<h4>Summary</h4>

The analysis of the Titanic dataset revealed several interesting patterns in terms of the variables that impacted the rate of survival. Factors such as ticket class, gender, age, and number of accompanying passengers were analyzed against survival. The trends that emerged were:

- As ticket class increases (from 1 to 3), the rate of survival decreases
- Women had a much higher rate of survival than men
- Children (aged 0 - 10) had higher rates of survival as compared to older passengers
- Passengers with 1 to 3 accompanying parents and or children had the higher survival rates as compared to those with 0 or 4+ accompanying parents and/or children
- Passengers with 1 acompanying spouse/sibling had higher rates of survival than those with 0 or 2+ accompanying siblings and/or spouse

In addition to looking at single factors against survival, multiple factors were also considered to dig deper into the patterns. This included an analysis of as ticket class & age, ticket class & gender, and gender & age. The trends tha emerged were:

- A decreasing survival rate as ticket class increases (socio-economic status decreases) for both men and women. Similarly, in each ticket class, women had a higher rate of survival as compared to men.
- Children (ages 0 - 16) have a higher rate of survival than adults (ages 16 - 80) in each ticket class. As ticket class increases (socioeconomic status decreases), survival rate goes down for both children and adults.
- Women have a higher rate of survival for both children and adults. The gap between the survival rate of female children and the survival rate of male children is smaller than the gap between the survival rate of female adults and the survival rate of male adults. Female adults also have a higher rate of survival than female children.

In all the cases, the trends that emerged can point to tentative conclusions, but require deeper statistical analysis to attribute any cause to the results. That being said, on first pass it looks there are certain groups that were given preference when boarding the lifeboats. These groups include women, children, parents of children, spouses of women, and those with higher socioeconomic statuses (lower ticket classes), based on the trends in survival rates.

Overall the dataset was able to provide interesting insights into the factors that may have contributed to a passenger's survival, however, there are a few ways in which the dataset could have been improved. For example, not all of the passengers were part of the dataset. As a result, the missing passenger information could skew the results and lead to different conclusions. Furthermore, factors such as 'SibSp' and 'Parch' look at accompanying passenger information by combining two categories (siblings & spouses, parents & children) together. It would be easier to derive accompanying passenger trends (such as the affect of a spouse, elderly parents, or young children) if the categories had been recorded separately. On the whole, the available information was still sufficient to draw preliminary conclusions.
