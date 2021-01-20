# Programme for International Student Assessment (PISA)
## by (Haitham Essam)



## Dataset
The data consists of information regarding 48,5490 students, including
grade, srudent's mindset, teacher's role, facilities and other properties. 
The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1611166993106000&usg=AOvVaw2584P2MKVx610FBqEiZvDp)
with it's dictionary [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1611166993108000&usg=AOvVaw27_q_LEUoTD8Vqte3EpVkB)
with feature documentation available [here](http://www.oecd.org/pisa/aboutpisa/pisa-2012-participants.htm), [here](http://www.oecd.org/pisa/pisaproducts/datavisualizationcontest.htm) and [here](http://www.oecd.org/pisa/data/pisa2012technicalreport.htm)


## Summary of Findings
In the exploration, I found that there was a strong relationship between the
In this exploration, I found a strong relationship between role of teachers 
and role of students to achieve great grades. 
Moreover, I found a somewhat surprising that most of variales (student's idea, 
a good relation between student and teacher and students with his fellow, good 
thought about the school, good attitudes, parents opinions and confidence) leads 
to a good grades, and the main reasons for high grades is the student's efforts 
and teacher's roles, also the psychological state affects the grades tremendously.
Regarding the gender, I didn't find any kind of bias and it doesn't affect the grade

I tried to get relationship between student's effort and teacher's role and the output
on the grade. I found that teacher who gives homework once a week back in time leads 
to high grades even more than teacher who gives homework everyday back in time.




## Key Insights for Presentation

For the presentation, I focus on just make the greatest influence and leave
out rest of the intermediate derivations. I start by introducing the study
time, followed by the realtion between each variables and grade 

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the heatmap and pointplot as they gave me the most information about the
data and I plot them between teacher's role and student's effort which I think
the main reason to achieve the superb grade. I'm only looking at. I've made
sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.

## Resources
[pandas](https://pandas.pydata.org)
[NumPy](https://numpy.org)
[Matplotlib](https://matplotlib.org)
[seaborn](https://seaborn.pydata.org)
[stackoverflow](https://stackoverflow.com/questions/50408886/scrolling-issues-in-reveal-js-slides-created-by-jupyter-nbconvert)
