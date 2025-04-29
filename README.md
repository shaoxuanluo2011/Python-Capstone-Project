# Python-Capstone-Project
An Analysis on driving factors behind SG government's operating expenditure

Introduction - Why I chose this topic:
We know that SG government is fiscally prudent and we want to know the driving factors that help the government maintain its fiscal position. Fiscal position is a topic close to our hearts as it influences the Government budget, and major decisions such as GST rate hikes and payouts, etc.

We realised early on that we can reconcile the Overall Fiscal Position against Revenue and Expenditure*. We did a pivot using Total Expenditure table and found out: Overall Fiscal Position = Total Revenue – Total Expenditure

We came up with four hypothesis and did our anaysis using python libraries to draw our conclusion.

Hypothesis 1: 
If govt fiscal position is negative this year, in the next year, the total operating expenditure will decrease. To do this, I need to combine fiscal position and government total expenditure tables. I need to calculate change in total operating expenditure between this year and previous year. I can use scatterplot to take overall last year's fiscal position from fp to compare against this year's change in total operating expenditure

Conclusion on Hypothesis 1: 
We can observe there is a negligible correlationship of 0.025366 between previous year's fiscal position, and the delta in operating expenditure between current and previous year. We believe there are other factors that could affect operating expenditure.

Hypothesis 2: 
We think this increase in headcount could also have an impact on operating expenditure.

Conclusion on Hypothesis 2: 
We can observe a stronger correlationship of 0.28224 between change in headcount and delta in development expenditure.

Hypothesis 3: 
We think that using both independent variables together - previous year's fiscal position and change in headcount - can give us a reasonable prediction on delta in operating expenditure.

Conclusion on Hypothesis 3: 
Government's 2023 estimation: -2.697 billion Our 2023 Prediction: 1.401.24 billion Given that our prediction is significantly different from government’s estimation, more research is required to understand other factors in play that can affect Operating expenditure.

Hypothesis 4: We think that an aging population could have an influence on healthcare expenditure.

Conclusion on Hypothesis 4:
1. More research is required to understand other factors in play that can affect Operating expenditure.
2. Instead of using aggregated manpower and fiscal position numbers, we can analyse data at a more granular level, for example into each ministry, understand the individual driving factors to predict their expenses, then consolidate into an overall number.
3. The model is also simplistic in that we assume SG government only considers previous year's fiscal position and change in manpower headcount, when in reality it would have taken a longer time horizon (i.e past 5 or 10 years change in fiscal position and change in manpower headcount)
4. In our deepdive into health expenditure, and comparing against external data sg population, we are able to observe that the health expenditure trends very closely with the aging population. This suggests that the aging population could be contributing to rising healthcare expenses.
