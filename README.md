andrew.maxwell.hanson@gmail.com

Portfolio of my data science projects
## [Project 1: Analyzing the 2017 Houston Astros Cheating Scandal](https://github.com/handyanson/Astros-Cheating-Project/tree/master/astros-project)
* Did a basic exploratory analysis of the 2017 which confirms a stat boost coinciding with their cheating.
* Analyzed over 8000 pitches from home games to find which players used and benefited most from the sign stealing scheme.
* Built a model to predict the outcome the 2017 season.  
* Utilized a Mann-Whitney U test our hypothesis
![](Images/astors%20BA%202017.png)
![](Images/Screenshot_2020-09-05%20Final%20-%20Jupyter%20Notebook.png)
![](Images/2017%20advantage.png)
![](Images/2016%20advantage.png)
### Key Takeaways
* We are unable to reject the null hypothesis that better stats caused by sign-stealing improved their chances of winning.
* We are unable to reject the null hypothesis that advantages gained due to sign stealing improved their advantage over their opponent.
### Room for Improvement
* Get better predicted values using player modeling and gibbs sampling, rather than linear regression and uniform distributions. The R^2 values were around, and less than 50%. Those values are not at all good at predicting, and so a better more accurate model predicting player statistics needs to be used.
* Use a different model taking into account different statistics. This model weighs equally, overall, pitcher, and batter statistics, possibly diminishing the effect of advantages gained through sign-stealing.

[Project Presentation Video](https://www.youtube.com/watch?v=P0FXeKkjiGc)

