---
title: "It's No Accident: Evaluating the Effectiveness of Vehicle Safety Inspections"
collection: publications
permalink: /publication/safetyinspections
excerpt: 'Improvements in vehicle technology mean that vehicles are safer and more reliable than in the past. Accordingly, some states have begun to discontinue their requirements for vehicle safety inspections. To gauge the effect of these policy changes, we examine traffic fatality data from 2000 to 2015, using a synthetic controls analysis with emphasis on New Jersey, which ended its inspection requirements in 2010.'
date: 2018-03-08
venue: 'Contemporary Economic Policy'
paperurl: 'http://alex-hoagland.github.io/files/NoAccident_PublishedVersion.pdf'
---

An increase in technology means that vehicles are more reliable than in the past. Accordingly, states have begun to discontinue their requirements for vehicle safety inspections. To gauge the effect of such changes, we examine traffic fatality data from 2000 to 2015, with emphasis on New Jersey, which ended safety inspection requirements in 2010.

[Read the full paper here!](http://alex-hoagland.github.io/files/NoAccident_PublishedVersion.pdf)

Recommended citation: Hoagland, A., & Woolley, T. (2018). It's No Accident: Evaluating the Effectiveness of Vehicle Safety Inspections. *Contemporary Economic Policy, 36*(4), 607-628.

More details
=====
*Abstract*: An increase in technology means that vehicles are more reliable than in the past. Accordingly, states have begun to discontinue their requirements for vehicle safety inspections. To gauge the effect of such changes, we examine traffic fatality data from 2000 to 2015, with emphasis on New Jersey, which ended safety inspection requirements in 2010. Utilizing a synthetic controls approach, we conclude that ending these requirements did not result in a significant increase in the frequency or intensity of accidents due to car failure, implying that the consumer and government expenditures used for inspections could be reallocated to other areas of travel safety.

Data & Methods
-----
Data for this project come from the United States Department of Transportation’s Fatality Analysis Reporting System, provided through the National Highway Traffic Safety Administration. These data provide information about all traffic accidents occurring on traffic-ways open to the public in the United States and resulting in at least one fatality within 30 days of the accident. The data span the years 2000 to 2015 across all 50 states and the District of Columbia, yielding a total of 551,789 accidents and 822,049 vehicles. Perhaps most importantly, this dataset provides information regarding the vehicle factors surrounding an accident, allowing us to pinpoint the proportion of accidents which were (at least in part) caused by car failure, problems which should be caught in a typical vehicle safety
inspection. 

We use a synthetic controls approach to analyze the impact of discontinuing vehicle safety inspections in New Jersey. Simply put, the synthetic controls approach constructs a weighted average of states similar to some treated state, which can be used as a "synthetic" version of the state that differs only in that it did not receive the treatment. Hence, in this case, we construct a weighted average of states that require vehicle safety inspections to create a unit of observation that mirrors New Jersey in many key variables, but that requires vehicle inspections throughout the entire range of data. Comparing this synthetic New Jersey to the actual data yields important insights into the impact of the law change. 

Key Results
-----
Figure 2 shows the results of the synthetic controls analysis. The panels on the left show how vehicle fatalities (both in general and specifically those related to car failure) evolve over time for synthetic and real New Jersey, where the dashed black line indicates where New Jersey discontinued the requirement for inspections. If there were an effect of doing so, it would manifest itself in differences between the two trends after this point &mdash; however, as the panels on the right show, the differences between the two trends do not grow after the law change. This suggests that ending the requirements for vehicle safety inspections did not lead to increases in fatalities related to vehicle failure, at least in the first 5 years following the law change.

<img src="https://github.com/alex-hoagland/alex-hoagland.github.io/blob/master/images/Vehicles_Synthetic_Controls.PNG" width="400">

Figure 3 tests the validity of these results using a series of placebo tests common to the synthetic controls approach. These placebo tests randomly re-assign the law change implemented by New Jersey to one of 15 other states which currently require safety inspections, and then re-run the analysis. Intuitively, these analyses test the magnitude of the results of the original synthetic controls approach, which are shown in blue (with the placebo tests shown in gray) &mdash; in this case, the results from the actual law change are estimated to be *well within* the effects of these hypothetical law changes. This suggests that the null effect of the New Jersey law change is, in fact, a null effect. 

<img src="https://github.com/alex-hoagland/alex-hoagland.github.io/blob/master/images/Vehicles_Placebos.PNG" width="300">

Real-World Applications
-----
I highly recommend a read of the full paper for more details on the analysis, results, and interpretation. In addition, [this page](https://alex-hoagland.github.io/talks/safety-coverage) on my website includes several discussions of the research aimed at non-specialist audiences. My co-author and I were privileged to work with Dan McCay and the Utah State Legislature to draft and pass a bill that discontinued vehicle safety inspections in the state of Utah as a result of this reserach. 
