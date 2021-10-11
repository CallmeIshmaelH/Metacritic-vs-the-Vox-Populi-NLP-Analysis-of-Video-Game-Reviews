# DAFT2021-Final-Project                                                                                              ![Videogame_analysis_image](technology-ge12d8af74_1280.jpg)
An analysis of User videogame user reviews versus the metacritic scoring system.
## Background  

As of 2021 the international electronic gaming industry generates over USD$300 billion annually.  This includes money from sales, subscriptions, paid downloadable content (DLC),
game expansions and competitive gaming events (e-sports). Numerous platforms and communitities have sprung up around the culture of 'gaming' spawing para-social communities such as Twitch, Steam, RAWG and the thousands of YouTube channels devoted to producing videogame-based content.
In short, videogames and gaming culture are an enormous market and one full of information that is critical for stakeholders within the videogaming industry to understand.
At present one of the most popular metrics for measuring a game's performance is its Metacritic Score, as provided by the internet review aggregator site, Metacritic (https://www.metacritic.com/game).
Metacritic explains that their scoring process is based solely on the aggregation of reviews from a select body of professional videogame critics. This of course suggests that there is some authority to their patented scores. However, it has been noted that in addition to the scores themselves being vague (Metacritic uses a simple numeric value from 0-100 to denote overall reception), as the scores are based solely on the reviews of a selected few, key information available from everyday players and consumers of videogames is not being considered. In this respect, it is debatable just how well metacritic scores reflect how the majority of consumers/players actually feel about the game in question.    
Some questions we can look at in this project include
**1) How well do metacritic scores reflect actual gamer sentiments?**  
**2) What are some features of games that are correlated with higher metacritic scores?**   
**3) Do longer reviews mean stronger sentiments about a given game?**  
**4) Can we accurately predict metacritic scores based on average user reviews?**  
**5) What features are commonly associated with positive reviews for games and what are most associated with negative reviews for games?**  

We would like to determine:
- How useful metacritic might be as a means of determining a given game's success.
- Identifying what features of games seem to be most popular based on metacritic scoring. 
- what average users actually think about games regardless of metacritic scores. 
- What features make games good or bad, based on popular opinion as expressed in reviews 

## Process
1. Collect and transform data from RAWG.io video game community API, Steam Store platform and Wikipedia 
2. Clean and refine data for NLP processes.
3. Using app id data, scrape reviews for games from RAWG.io and Steam Store. Clean and pickle data for ease of use with pandas.
4. Carry out EDA using pandas, numpy and python visualization libraries Matplotlib/Seaborn
5. Create more detailed visualizations with Tableau.

## Repo Contents   
This repo includes:  
1. A jupyter notebook for collecting and cleaning data about different games for analysis (Game_Analysis_Data_Collection_and_Preparation.ipynb)
2. A jupyter notebook for collecting application ids from the Steam Store.(steam_app_ids.ipynb)  
3. A jupyter notebook for collecting reviews using selected steam app ids from the steamreviews package for Python.(steam reviews.ipynb)
4. A jupyter notebook for collecting and assembling data scraped from https://rawg.io/
5. A jupyter notebook for NLP analaysis, exploratory data analysis and preliminary visualization using the RAWG dataset (NLP_Analysis_RAWG_data.ipynb)
6. A jupyter notebook for NLP analaysis, exploratory data analysis and preliminary visualization using the STEAM dataset (NLP_Analysis_STEAM_data.ipynb)   
7. A Microsoft Powerpoint containing the preliminary results of analysis from the RAWG dataset.
8. A Tableau workbook containing visualizations of data can be found here : https://public.tableau.com/app/profile/ishmael.ho7925/viz/NLP_AnalysisofVG/Sheet9?publish=yes 

**NOTE:**
**NOT INCLUDED: The data files or pickled data in the interest of keepign this repo within the storage capacity alotted by GitHub.** 

## Have fun! 
