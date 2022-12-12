# Qatar2022
******Analyzing FIFA World Cup Teams******

**Introduction:**
Streamlit App: _____

**Research Question: **
	1. What were the rankings of each of the 32 World Cup teams leading up to the Qatar World Cup?
	2. What are the respective ratings of each team? 

**In this app:**
You will be able to navigate across 8 tabs, analyzing the 32 teams in the 2023 FIFA World Cup in their respective groups.
	
		Group A: Senegal, Qatar, Netherlands, Ecuador
		Group B: Iran, England, USA, Wales
		Group C: Argentina, Saudi Arabia, Mexico, Poland
		Group D: Denmark, Tunisia, France, Australia
		Group E: Germany, Japan, Spin, Costa Rica
		Group F: Morocco, Croatia, Belgium, Canada
		Group G: Switzerland, Cameroon, Brazil, Serbia
		Group H: Uruguay, South Korea Portugal, Ghana


	From there, you will be able to analyze the following from each team:
		FIFA Rankings over leading up to the Qatar World Cup
		Goalkeeper, Defensive, Midfield, and Offensive Scores

**Data/Operation Abstraction Design: **

This data is gathered by aggregating FIFA Rankings data of the 32 teams as well as their scores from their individual matches.

Clean the dataset
	-Check for missing values
	-Filtering out the data before 2018, which was the last World Cup

Visualize the FIFA Rankings
	-Creating via Altair line graph
	-Invert the y-axis in order to show a team’s improvement in rank was 		parallel to the direction of the graph

Averaging the Mean Scores for each team 
	-Aggregate the scores from the 32 team’s matches
	-Averaging the score from the past 4 years (2018 and above)

Future Work: 
To improve my app, I would want to add scores from each of the games and analyze the entirety of the Qatar World Cup.
