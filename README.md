# J124 Final Project: A Look Into the Injury Reports of College-Aged Adults in the United States
## By Paul Ikeda


## Data Summary and Explanation

This data was taken from the Centers for Disease Control and Prevention (CDC). I am looking at the Web Based Injury Statistics Query and Reporting System (WISQARS) data. WISQARS is an online database that provides injury reports (fatal, nonfatal, violent injuries, and cost of injuries) across the United States. For my project, I will examine injury reports among college-aged people, 18 to 22 years old, living in the United States. Furthermore, I will only be focusing on these causes of injury: unintentional injury, assault, sexual assault, legal intervention, and self-harm gathered between 2001 to 2020.

The data will be organized by race/ethnicity, age, and sex. The race/ethnicity is broken down by White Non-Hispanic, Black, Hispanic, Other Non-Hispanic, Not Stated. This data shows the estimated number of injuries, the population of each demographic, and a crude rate per 100,000 individuals.

#### Why am I focusing on this age group?

Based on the WISQARS reports, the 85+ age demographic is the most prone to injuries, and the second highest at-risk demographic is 15-19, followed by 20-24. Yet, I plan to focus solely on my peers 18-22 to understand why people my age are so vulnerable to injury.

This story aims to explain the causes and commonalities of injuries among college-aged adults in the United States. In hope that further research will show the psychological and environmental reasons for the higher injury rates.

#### Why am I focusing on unintentional injury, assault, sexual assault, legal intervention, and self-harm?

According to WISQARS, 18 to 22-year-olds are most prone to injury in this order: unintentional injury, assault, sexual assault, legal intervention, and self-harm. Legal intervention refers to "injuries inflicted by the police or other law enforcing agencies, including military on duty, in the course of arresting or attempting to arrest lawbreakers, suppressing disturbances, maintaining order, and other legal actions. Excludes injuries caused by civil insurrections." This definition comes straight from the CDC.


## Sources<img width="387" alt="Screen Shot 2023-08-08 at 10 42 16 AM" src="https://github.com/bigbob415/J124_Final_Project_PI/assets/140004449/37c8e4de-e538-4bf3-91c5-919403157447">


#### Data Used
I analyzed data from here: [“WISQARS Website”]((https://www.cdc.gov/injury/wisqars/index.html))

The WISQARS Fatal and Nonfatal Injury Reports come from https://wisqars.cdc.gov/reports/?o=NFI&y1=2020&y2=2020&d=0&i=0&m=3000&g=00&s=0&a=ALL&g1=0&g2=199&a1=0&a2=199&r1=INTENT&r2=NONE&r3=NONE&r4=NONE&adv=true

My specific data filters come from here:  https://wisqars.cdc.gov/reports/?o=NFI&y1=2001&y2=2020&d=0&i=0&m=3000&g=00&me=&s=0&r=&e=&a=custom&g1=0&g2=199&a1=18&a2=22&r1=INTENT&r2=RACETHN&r3=AGE&r4=SEX&adv=true

This data comes from this data chart downloaded from the WISQARS website: [“Injury Reports 18-22”]((Injury Counts 18-22.csv))

#### Interview Contacts as sources
1) Robyn Papathakis Shannon, PsyD: Behavioral Health Provider
    * Email: rpshannon@berkeley.edu
    * Dr. Shannon is a Behavior Health Provider for the Tang Health Care Center at Berkeley. She works specifically in Behavior Health and with college-aged people. She could explain why injury rates are so high for this demographic and the behavioral reasoning behind it.
2) Ryan Romeiser MD: Urgent Care
    * Email: ryanromeiser@berkeley.edu
    * Dr. Romeiser would also provide interesting insight into injury reports. Dr. Romeiser also works in the Tang Center but as an Urgent Care Doctor. Instead of providing the behavioral reasoning behind large injury counts, Dr. Romeiser could tell what types of injuries he usually treats in young people.
3) Tang Center
    * Email: telltang@berkeley.edu
    * Phone: (510) 642-2000
    * Address: 222 Bancroft Way University of California Berkeley, CA 94720-4300
    * Aside from contacting the specific doctors. I could email or visit the Tang Center and gather information from nurses and doctors about college-aged patients. While a small, targeted group not representative of all 18 to 22-year-olds in the United States, the Tang Center would provide valuable medical insight and professional help in understanding this large issue.

#### Additional Sources
1) Data Source 1
2) Data Source 2

## Data Analysis

#### Analysis 1: Injuries by Intent

ADD Image

##### Process
1) Created a pivot table with the values set to Estimated Number summarized by SUM.
2) The Row was set to Intent organized by ascending sorted by SUM of Estimated Number

##### Reasoning
This is important for understanding the major causes of injuries among young adults. While Unintentional injury is vastly larger than the others, assault and self-harm also affect millions of young people and would require more research for me to report on.

#### Analysis 2: Unintentional Injuries by Race

ADD IMAGE

##### Process
1) Created a pivot table with the values set to Estimated Number summarized by SUM. The Rows were sorted by Race/Ethnicity, Intent, and Population.
2) Added a filter that sorted Intent by only showing Unintentional.
3) Calculated the percentage of unintentional injuries by race by using the formula (D3/D2) and changing it to percentage using the % button on the top toolbar.

##### Reasoning
It is important to know the number of young adults unintentionally injured as it is the most common injury in this demographic. Understanding the different impacts of unintentional injuries by race is also important. It puts the rest of the data into context.


#### Analysis 3: Injury Reports by Age and Sex

ADD IMAGE

##### Process
1) Created a pivot table with the Estimated Number as the Value summarized by SUM. 
2) Added Sex and Age to the Rows Column
3) Organized by Ascending in terms of SUM of Estimated Number 

##### Reasoning
In this pivot table, it becomes apparent that age and sex both play a factor in all injuries in young adults. As people age, they are less likely to get injured, and males are more likely to get injured than females. This highlights important behavioral factors of younger people and males, which make them more prone to injury.

#### Analysis 4: Sexual Assault by Sex

ADD IMAGE

##### Process
1) Created a pivot table with the Estimated Number as the Value summarized by SUM. 
2) Added Sex and Age to the Rows Column
3) Filtered the data by Intent, only showing Sexual Assault
4) Calculated Female Total/ Male Total or =C7/C13

##### Reasoning
This data shows that sexual assault occurs in women 88 times higher than in men. Hopefully, This huge margin could be explained by some extra sources and may introduce environmental factors that affect women more than men. 

#### Analysis 5: Legal Intervention by Race, Sex, and Age

ADD IMAGE

##### Process
1) Created a pivot table with the Estimated Number as the Value summarized by SUM. 
2) Added Race/Ethnicity, Sex, and Age to the Rows
3) Filtered the data by Intent, only showing Legal Intervention

##### Reasoning
This data shows that Black people are more likely to be injured during Legal Intervention. This adds several things to my story, including aspects of police brutality in the United States and environmental issues facing young people.

## Data Visualization


## Story Pitch

BLAH BLAH PLACEHOLDER

PLACEHOLDER
