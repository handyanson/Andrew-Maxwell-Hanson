# Andrew Maxwell Hanson
andrew.maxwell.hanson@gmail.com

Portfolio of my data science projects

## [Project 1: Analyzing the 2017 Houston Astros Cheating Scandal](https://github.com/handyanson/Astros-Cheating-Project/tree/master/astros-project)
* Did a basic exploratory analysis of the 2017 which confirms a stat boost coinciding with their cheating.
* Analyzed over 8000 pitches from home games to find which players used and benefited most from the sign stealing scheme.
* Built a model to predict the outcome the 2017 season.  
* Utilized a Mann-Whitney U test our hypothesis

### A Look at Relative Advantage (λ)
$$ \lambda_s = \alpha_s^{r_1} * \beta_s^{r_2} * \gamma_s^{r_3} $$ 
Where $\alpha$ denotes the winning percentages ratio between the home and away team, $\beta$ denotes the ratio between the batting averages, $\gamma$ denotes the ratio of the ERA, in this instance the ratio between away and home.

$1/\lambda_s$ is relative advantage for away games.

$r_i$ is a uniform distribution, and accounts for any uncertainty and unpredictability.
As the function calculates the relative advantage a team has throughout their season, lets look at the Astros' relative advantage over their opponents. When $λ > 1$, that means that the team has an advantage. When $λ < 1$, the team has a disadvantage.


