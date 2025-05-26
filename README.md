# NBA Evolution Analysis: How the League Has Changed (2015–2025)

## Project Overview

This Exploratory Data Analysis (EDA) project investigates how the NBA has transformed over the last decade, with a particular focus on the ripple effects of Stephen Curry’s 2014–2015 MVP season and the rise of analytics-driven basketball. That season is widely considered a strategic turning point teams across the league began shifting toward 3-point-heavy offenses, greater pace, and positionless play.

By combining individual and team-level metrics with league-wide historical data, we explore how strategy, recognition, and player roles have evolved. Data was sourced from [Basketball Reference](https://www.basketball-reference.com) and focuses primarily on regular-season stats from 2015 to 2025. Outlier seasons impacted by COVID-19 (notably 2019–2020 and 2020–2021) were considered during interpretation.

## Tools and Libraries
**Language:** Python
**Libraries:**
Pandas
Numpy
Matplotlib
Seaborn
Scipy.stats (pearsonr) 
**Environment:** Jupyter Notebooks (developed in VSCode)

## Project Setup
To run this project locally:
 ''' bash
 git clone https://github.com/nyckienite/Cohort-B-Athlete
 cd Cohort-B-Athlete
 code .
'''


## Central Research Question

**How has the NBA changed in the last 10 years?**

Our analysis is broken into four themes: offensive evolution, MVP profile shifts, defensive impact on success, and draft class outcomes  each explored by a different analyst.

## Contributors
### Adewale Thompson – *Offensive Strategy & 3PT Revolution*
- **Q6:** How has the 3-point shot impacted the league over time (attempts, makes, accuracy)?  
- **And:** How has points per game changed over the last 20 seasons?
> Tracks the league-wide shift toward perimeter shooting and increased offensive pace, with visual trends in 3PT attempts, accuracy, and scoring averages.

**Analytical Questions**
### Dontaye Bell – *Defense and Team Success*
- **Q1:** How has the defensive rating changed over the years?  
- **Q2:** Is there a correlation between team defensive rating and win percentage?  
- **Q3:** Which teams have combined elite defense with winning records?
> Explores how declining defensive efficiency has influenced win rates and playoff success in a league increasingly defined by scoring volume.

### Julissa Morales – *MVP Profiles & Evolving Criteria*/
- **Q5:** How have MVP winners' stat profiles changed over time, and what does this say about evolving MVP criteria?
> Compares MVP stat lines to top vote-getters and league averages. Uses z-score normalization and archetype classification to show how the definition of “Most Valuable” has shifted toward versatility, efficiency, and all-around impact.

### Nicole Ogbomoh – *Draft Class Performance & Scouting Trends*
- **Q4:** How do players from the same draft class perform over time?  What trends emerge in long-term scouting success by position or role?
>Analyze draft class consistency and positional development trends to evaluate the effectiveness of scouting over time.

## Project Structure
**Notebook Overview**
Each notebook explores a different angle of the NBA's evolution from 2015 to 2025, using data scraped from Basketball Reference or a csv file.

*(Please Review the notebooks in this order)*

**notebooks_adewale.ipynb**
- **Focus:** League-wide trends in offensive output and 3-point shooting
- **Data Used:** Team-level stats from 2005 to 2025, scraped from per game totals
- **Summary:** Analyzes the rise in 3-point attempts, makes, and efficiency, along with points per game and pace of play.

**notebooks_julissa.ipynb**
- **Focus:** MVP stat profiles and award criteria
- **Data Used:** MVP tables and advanced player stats from 2015 to 2025
- **Summary:** Tracks MVP scoring, playmaking, defense, and efficiency to evaluate how the award’s criteria have shifted. Includes comparisons to league-wide averages and top vote-getters.
 
**notebooks_dontaye.ipynb**
- **Focus:** Defensive rating trends and correlation with team success
- **Data Used:** Team-level defensive/offensive rating and win-loss records (2015–2025)
- **Summary:** Evaluates whether elite defenses still predict winning, and which teams combined top defensive metrics with championship performance.
 
**notebooks_nicole.ipynb**
- **Focus:** Draft class performance and long-term positional success
- **Data Used:** Player-level data across multiple draft years
- **Summary:**  Will analyze performance trends among players drafted in the same year to evaluate the consistency and value of scouting by position or archetype.

## Key Findings
**Dontaye's Key Findings**
- Defense effeciciency is declining and teams are trying to outscore one another by more volume of shoooting rather than stopping teams from scoring.

**Julissa's Key Findings** 
- MVPs are evolving: Recent MVPs showcase more well-rounded skill sets, blending scoring, efficiency, and playmaking rather than relying solely on high point totals.

- Efficiency matters more: Metrics like Win Shares and FG% show that modern MVPs are recognized not just for volume, but for doing more with fewer possessions.

- Versatility is rising: The “All-Around” archetype has become increasingly common, reflecting a league-wide shift toward positionless, impact-driven basketball.

- Top vote-getters are often similar: Statistical comparisons between MVPs and 2nd/3rd place finishers show small margins, suggesting narrative and team success may tip the scale.

- MVPs consistently outperform the league: Across scoring, assists, and efficiency, MVPs exceed league averages year after year — highlighting their elite status.


## Connecting the Themes
Each notebook contributes to a holistic view of NBA evolution:
- **Adewale** sets the foundation with league-wide shifts in scoring strategy.
- **Julissa** tracks how that shift changed MVP expectations.
- **Dontaye** investigates how defense has been deprioritized (but still matters).
- **Nicole** will evaluate how teams scout and build for this new reality.


## License
This project is for educational purposes only. All data is publicly available and sourced from https://www.basketball-reference.com.

