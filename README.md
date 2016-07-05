# titanic_visualization
Udacity d3 dimple.js visualization project

Summary

This is an exerpt from Kaggle website.
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. 
One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.
The goal this visualization is to illustrate the differences between chances of survival for different groups of people based on sex, age and class.

Design

Bar chart was chosen to represent survival rates of groups of people because it is very good in displaing relative numbers/proportions of multiple categories. Color was used as a visual encoding to such categories as passenger sex and class. Ages were binned in 10-year intervals. The decision to make age into a categorical variable was made based on available data that children were more likely to survive than older people. 

Initial design: 

Two charts in the upper row show average survival rates for different age groups and classes. Below in a secod row charts show total number of passengers in each category for comparison. Sometimes very few passengers are in the given category which helps to interpret the outliers in the survival rates charts.

Change in design to address reviewer comments:

Lower charts were representing total passenger numbers were dropped as providing too much details there were not appropriate for an explanatory visualization. Passenger class chart was re-formatted. Survival rates were plotted against passenger class series stratified by age groups. This should better indicate trend in upper class and younger age survival.

To address questions raised in feedback_1 a new column named "total" was added in the data table. Now the tooltip displayes "Total: number" and not "Survived: number" as before when hovering over bars in a chart "Total passenger number by sex and age". It shows counts for total amount of people in each category same as before, but the name of the category was corrected.

In addition, a texbox with the description of the titanic fron Wikipedia was added with the link to site to accomodate another suggestion from feedback-1.

Feedback_2 suggested at the end to make much simpler graphs, just one for sex age and class. While it would look simpler it would convey less information in each chart, so this suggestion was not acted upon.

To address suggestion in feedback_3 tooltips were modified to display two decimal points in values of survival rates.


Feedback

Feedback_1. I noticed that females survive better. And First class passenger survive better, except for the children, where the second class children survived more.

It is not clear to me what the "total passenger number" means. At first I thought "total number of passenger that were in the titanic". But the tooltip that appears when hovering with the mouse on a bar says "survived". So I would change the vertical axis title to be "total number of survivors".

The main takeaway is that gender and passenger class were determinant to survival. Maybe you could find some reference to link where it explains the reasons for this.

Feedback_2.

I immediately noticed the much higher survival rates for women compared with men. I also saw how the third class had much lower survival rates.
I don't really have questions about the data, I've seen it before.
I notice that the upper classes are older than the 3rd class, which is predominately very young.
I think the main takeaway is that women and the upper classes faired much better than men and the lower class.
No, the graphic is very clear and easy to understand. 
A suggestion that I have would be to create bar graphs for age, sex, and class, instead of using age with the other two variables subsetted. This would make your overall message more clear.

Feedback_3.

I noticed that the percent of women who survived was 
significantly higher than the percent of men, even when accounting 
for the much greater number of men than women on board. The number 
of children under 10 who survived was higher than almost any other 
demographic (except women 60-69, of whom there were only 4). In 
general, the visualization was very clear and easy to read. I 
liked that the graphs for survivors and total number of passengers 
are aligned vertically. This makes it very easy to compare between 
them. I also liked that when I hover my mouse over a bar, a line 
appears that shows me exactly where on the y-axis the bar ends. 
This makes the relationship between the different bars very clear 
(how far apart of the y-axis the different bars fall). For 
example, this helped me to realize that the percent of survivors 
age 60-69 in second and third class was the same as the percent of 
survivors age 50-59 in second class.
The main takeaway of this visualization is that more women and 
children than men survived. Also, more of the upper classes 
survived. Howevever at least half the people on board did not 
survive. 
The graphic was clear and easy to read. I noticed that when I 
hover my mouse onver a bar the statistics that appear are rounded 
up to the nearest tenth. It would be better if they showed the 
true, non-rounded percent. Overall, I thought it was a very 
interesting graphic.


Resources

https://www.kaggle.com/c/titanic
https://en.wikipedia.org/wiki/RMS_Titanic#Survivors_and_victims

