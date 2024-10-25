# 2023 US Energy Generation Analysis
## Energy generation metrics for the year of 2023 by state and energy source. The key functionality of this tableau file is its extensive interactive ability.

INTRODUCTION: This Analysis will assist in detemining the landscape of energy geneation in US states. Using this information, the US can determine what states need to "step up their game" and take more carbon efficient energy generation initiatives, and where those initiatives could be taken. 

DATA/ OPERATIONS ABSTRACTION DESIGN: There are two data sources used in this project. The first data source comes from the EIA (Energy Information Administration) via [https://www.eia.gov/electricity/data/state/] and the name of the dataset is "EIA-923 Power Plant Operations Report (released: 10/4/2024)". The second dataset simply contains population by state and is obtained via [https://www.statista.com/statistics/183497/population-in-the-federal-states-of-the-us/]. The EIA dataset contains many variables which haven't been used in this analysis and which were removed from the data souce prior to being inserted into tableau. Some new variables have also been created using existing variables. This dataset contained no missing values which, however as previously stated some information was removed. You can find the original dataset titled "TITLE HERE" and "TITLE HERE" in this repo, and the cleaned/fully prepared data set titled "HERE" in this repo. 

FUTURE WORK: Some next steps that will be taken including energy generation information by power plant. In the US here are up to hundreds of power plants per energy source which makes data collection a significant effort in this future work. Additionally, historical data is planned to be included so that energy generation trends over time can be analyzed (which will be a significantly lighter workload than aggregating generation data by plant, considering it is already in the "TITLE HERE" dataset.

Link to Tableau Dashboard: [https://public.tableau.com/app/profile/caleb.watson5550/viz/2023_Energy_Generation_by_State_Caleb_Watson_5122Midterm/OverallDashboard]
