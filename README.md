# ORIE 4999: Analytics of Sport Betting (NFL Handicapping System)
Jack Jansons (jcj59@cornell.edu), Rob Mosher (ram487@cornell.edu), Jesse Koppel (jrk298@cornell.edu)

### Summary:
The plan for this research project is to develop a handicapping system for the next NFL season. Handicapping entails predicting the spreads of different games and comparing that to the spreads determined by sports books and identifying profitable margins for sports betting. The system we propose is based on the handicapping system used by Billy Walters as described in his book “Gambler: Secrets from a Life at Risk.” This system uses a database of power rankings for each of the 32 teams in terms of spread points and “impact values” for each significant player in the NFL also in terms of spread points. The handicapping system involves comparing the power rankings, player impact values, and external conditions (i.e. home field advantage, weather, momentum, rival, etc.) to predict an appropriate spread for the game. After each game, team power rankings and player impact values are updated based on the outcome and stats from the game. The book provides a table of external factors and their point values and algorithms for updating values after each game. The goal of this research project would be to construct a database of power rankings for each NFL team and impact values for significant players based off of historical NFL game data that could then be used to predict spreads of games in the next NFL season.  

### Methodology
##### 1. Perform literature review to identify current methodologies for forecasting values based on historical data  
  1. Study Walter’s Method for forecasting values and determine what the output of our model needs to look like at the ‘Advanced MasterClass’ chapter level:  
    a. Develop our model of what constitutes a team’s power ranking.  
    b. Determine individual player scores - How much ‘good’ each player is.  
    c. Determine weightings for different positions- How much does each position contribute to the overall power of a team.  
    d. Develop a model for considering environmental and emotional factors, to be applied after team ranking creation.  
##### 2. Harvest relevant data and use model developed in the literature review to construct initial team power rankings and player impact values for the beginning of the 2023-2024 season:  
   1. Build a budget for use in data retrieval, and present it along with our initial model to the department for funding:  
    a. Determine which sources are most relevant for our model per unit cost.  
   2. Build data pipelines for accessing, storing, and processing relevant information for determining solid bets:  
    a. Player Data  
    b. Environmental Data  
    c. Sports Book Odds Data  
##### 3. Test our database with the books external factor table and updating algorithms on this past season of games and determine how effective our system is
  1. Bootstrap testing/validation sets from stratified split based on year.
  2. Temporal component to TT split: 2013-2020 and 2021-2022 for test, 2023 for validation?
##### 4. Compute an expected value for our profits based on the spreads we calculate to measure the effectiveness of our system
  1. Potentially repeat steps 1-3 to make model changes if the testing shows problems in the model.
##### 5. If time permits: identify flaws in our system and reevaluate–update system for start of 2024-2025 season
  1. Put our final model into a real world scenario and follow along as the 2024 season unfolds, updating as we go.

### Academic Objectives:
1. Gain experience in real-world statistical modeling, including organization and initialization of a complex modeling system, feature selection, analysis of results, and change in response to feedback.
2. Practice principles of software engineering and data pipeline construction through team-based development and subsequent harvesting, processing, and analysis of relevant data.
3. Practice data visualization and communication of results in technical writing and presentation form.

