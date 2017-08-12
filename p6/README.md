# DataVisualization
Udacity Unit on d3.js &amp; dimple.js

## Summary 
This visualization shows the demographics of 891 of the 1317 passengers aboard the Titanic. Specifically, gender, class, port of embarkment, age, and number of family members aboard were explored. There were more men than women, more third class passengers than first class, and the most common age range was between 21 - 30.  Next, survivorhsip within each of these categories was explored.  Unsurprisingly, women, children, and first class passengers were more likely to survive.

## Design 

### Dataset information
This dataset is taken from [Kaggle]( https://www.kaggle.com/c/titanic/data?train.csv#) website. 

## Acknowledge

This project is first analysis by `Investigate a Dataset`

Then, I finish the project using D3.

## Feedback & Change

Zhenyuan Le(Students of Liberal Arts)

1. Don't like the color(I won't change that!)
2. My English sucks, write in English!
3. Why is there a category “Unknown” in the graph on “Port Survivor %”? If there’s a reason for including this category, it’s not clear to me .
4. Could you please just explain a little bit that why would it happened in a historical view?
5. Is there a possible explanation on why no survivors among those with number of family members 7 and 10?
6. `Port/Survivor Breakdown` doesn't seems reasonable to me that with such little member list on the graph.
7. The tooltip seems unclear to me, it has been blocked so I can't see it!

Yutian Song(Student of Computer Science)

1. Chart is simple and understandable.
2. It is very hard for me to recognize the `Family/Survivor Breakdown` has survived or not. Make it happened!

The Second Version will fix:

1. Write in English. (My friends don't like it~ )**I will write it in Chinese in the next version so that my friends could read it easily.**
2. Fix the framework, so it will looks better.
3. I had to rebuild the entire tooltip so it looks more readable than before.

The Third Version:

1. The data visualization of the Family/Survivor Breakdown part do not work well, they suggest me to change a little bit that they can actually see the survivors of the family member number that is bigger than three because the people who have over 3 family member aboard have such few number. **Next Version will change the visualization part.**
2. Labels has been added inside of the bars for graphs with percentages. Now we can see the exact number of passengers was easily seen. I reformatted the charts so that all axes labels could be seen.  

## Resources 
(Listed in order of usage)

- Titanic Wikipedia Entry https://en.wikipedia.org/wiki/RMS_Titanic
- Titanic Facts http://www.titanicfacts.net/titanic-passengers.html
- Dimple.js documentation http://dimplejs.org/examples_index.html
- Udacity Forum Discussion https://discussions.udacity.com/t/project-6-feedback-and-help-request-titanic-data/198669
- Dimple Wiki on Github https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.series#addOrderRule
- Vverde's repository https://github.com/vverde/Udacity-Data-Analyst-Nanodegree-P6
- Stack Overflow Exchange http://stackoverflow.com/questions/17791926/how-to-rotate-x-axis-text-in-dimple-js
- Stack Overflow Exchange http://stackoverflow.com/questions/33179439/d3-js-dimple-getting-a-title-on-a-graph
- DailyMail Article http://www.dailymail.co.uk/debate/article-2087585/Cruise-ship-Costa-Concordia-sinking-Whatever-happened-women-children-first
- Anna Pawlicka's tooltip tutorial http://annapawlicka.com/pretty-charts-with-dimple-js/
- Stack Overflow Exchange http://stackoverflow.com/questions/30434627/how-to-change-the-position-and-size-of-the-tooltip-in-dimple-js
- Dimple.js Storyboard Control http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
- Stack Overflow Exchange http://stackoverflow.com/questions/4247067/jquery-menus-appear-disappear-on-click-v2/4247689#4247689
- w3 Schools CSS http://www.w3schools.com/css/css_navbar.asp
