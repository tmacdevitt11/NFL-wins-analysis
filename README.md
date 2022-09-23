# NFL-wins-analysis
How do certain variables such as Turnovers, Chunk Plays, QB Sacks, and 3rd down yardage to go impact winning?

## Overview
As a retired football played I’ve long heard recycled coach speak about truisms paramount to success. The most prevalent at all levels - winning the turnover battle, limiting opponents big plays, get after the quarterback while protecting ours, and getting opponents off the field on the money down (3rd down). 

This project will turn this coach speak into variables in order to:
- See if these variables do in fact have a significant impact on the end result of winning & quantify what that impact is


To accomplish this i will utilize 2019 NFL play-by-play data in the following way:
- Aggregate each data point to the game level
- Engineer my dependent variable - Win as a 1 or 0
- Engineer independent variables (offense and defense):
  - Sacks in a game (continuous)
  - Distance on third down needed for conversion (continuous)
  - Turnovers (continuous)
  - Big plays (passes >= 16 yards & runs >=12 yards) (continuous)
- Utilize Logistic regression to determine significance and impact
