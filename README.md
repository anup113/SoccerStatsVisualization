# SoccerStatsVisualization
Visulaization of soccer stats for various clubs and players of major european soccer leagues

# Creativity of the players analyzed based on their goal creating actions and shot creating action per90 minutes
Creative players are esstential for each team who are responsible for the attacking phase of the team. These players could be attacker, midfielder or even defenders in the modern soccer tactics. Teams play with different philosphy and the resposibilites of players playing in same position could vary over the teams they play. This analysis wil also validate the roles played by different players at different positions for different soccer teams.

# Data Preprocessing
1. Nan values are dropped 
2. Player must have played atleast 500 minutes of soccer
3. GK are removed from the analysis


We are removing Goalkeepers from our analysis since their main role is not creative though some goalkeeper have cruicial role in playing from the back we assume that the creative action of the goalkeepers would not be captured by the goal creating actions and shot creating actions.

mean_sca_per90 for gks = 0.095
mean_gca_per90 for gks = 0.0011

We consider these values very small which could reduce the overall mean thus remove Goalkeepers from our anlaysis.

Number of Goalkeepers who have played more than 500 minnutes = 27

Numbers of players included in the analysis = 367

# Observations
1. Manchester city players Mahrez, De Bruyne, and D.Silva are among the most creative players in the league. This is consistent with the attacking possession based philosophy of the manager Pep Guardiola. De Bruyne creates the most numnber of shots and Maherz creates most number of goal creating actions. Mahrez with his direct play driving into has the most goal creating actions. De Bruyne is exceptional in picking out the players with his crosses and through balls thus great shot and goal creating actions. De Bruyne is also the player with most assists in the league (20).

2. Liverpool most creative player seem to be Alexander Arnold. Alexander Arnold has the second highest number of assists in the league (13). Liverpool midfield doesnot have any presence near the top which is actually consistent with their philosophy of high pressing attacking football which is havily depended on the fullbacks providing the creativity. Robertson the other winger has total 12 assists in the league and also has the similar goal creating actions to Arnold who has high shot creating actions than Robertson

3. Liverpool players Salah and Mane have almost identical stats. This is because liverpool attakcing shape where the two wingers almost play as two inside forwards and the striker Firmino drops to the midfield. 

4. Players from same team have similar stats; a. Manchester city players Mahrez, De Bruyne, D.Silva and Foden all have very high creative actions b. Liverpool players Salah, Mane, and Arnold have similar stats, c. Chelsea players Willian, Pedro, Hudson-odoi, and Pulisic are also very close to each other. d. Manchester United player Rashford and Martial almost have identical stats. This observation may suggest that the goal and shot crating acitons is heavily influenced by the way each team plays and attacking players from same team are more likely to have similar stats as each player would also be constributing to the raise the other players numbers.

5. Andy Caroll has surprisingly high goal creating actions this maybe because of his ability to win headers and link up with other secondary strikers playing around him.

6. One player who is exactly in the intersection of mean of sca_per90 and gca_per90 is Harry Kane.
