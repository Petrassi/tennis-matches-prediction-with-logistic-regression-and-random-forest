## Forecasting the winner of tennis matches in the Men’s ATP World Tour 

This is my capstone project of my Data Science part-time course at General Assembly in 2016:

- The goal was to estimate the likelihood of ”wins” in tennis matches of the men’s ATP tour. A "win" occurs,
by definition, when a higher-ranked player wins the match against a lower-ranked player.
- This is a classification problem where the outcome is either 1 if the match result is a win or 0 otherwise
- The unit of the analysis is the match 
- The predictors used were:
  - Types of surface (hard, grass or clay)
  - Round of the match (from first round to the final)
  - Maximum number of playable sets (best of 3 or best of 5)
  - Name of the ATP Series (Grand Slam, Masters 1000, ATP 250 and ATP 500) 
  - Difference between the logarithms of the rankings (instead of just difference between rankings) to take into account the
 non-linearity of the players quality 
 - The following models were used:
   - Logistic regression
   - Decision trees
   - Random forests
- The accuracy was measured using standard techniques. For games of 5 sets, the ROC curve was found to have an AUC of around 0.7.
