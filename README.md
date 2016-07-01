# titanic_visualization
Udacity d3 dimple.js visualization project

Summary

This is an exerpt from Kaggle website.
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. 
One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.
The goal this visualization is to illustrate the differences between chances of survival for different groups of people based on sex, age and class.

Design

Bar chart was chosen to represent survival rates of groups of people because it is very good in displaing relative numbers/proportions of multiple categories. Color was used as a visual encoding to such categories as passenger sex and class. Ages were binned in 10-year intervals. Two charts in the upper row show average survival rates for different age groups and classes. Below in a secod row charts show total number of passengers in each category for comparison. Sometimes very few passengers are in the given category which helps to interpret the outliers in the survival rates charts.

To address questions raised in feedback_1 a new column named "total" was added in the data table. Now the tooltip displayes "Total: number" and not "Survived: number" as before when hovering over bars in a chart "Total passenger number by sex and age". It shows counts for total amount of people in each category same as before, but the name of the category was corrected.

In addition, a texbox with the description of the titanic fron Wikipedia was added with the link to site to accomodate another suggestion from feedback-1.

Feedback_2 suggested at the end to make much simpler graphs, just one for sex age and class. While it would look simpler it would convey less information in each chart, so this suggestion was not acted upon.

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

3.

Resources

https://www.kaggle.com/c/titanic
