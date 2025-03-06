# Tennis-Star

Tennis has long been defined by the dominance of three extraordinary players—Novak Djokovic, Rafael Nadal, and Roger Federer. Their achievements, spanning almost two uncontested decades, have set an unparalleled benchmark in the sport. Their rivalry, marked by intense matches and moments of brilliance, has captivated fans around the world, pushing the boundaries of what was thought possible in tennis. 

This report aims to provide:

- A quantitative exploration of the Big 3’s dominance

- A data-driven analysis of how the sport has evolved, and

- A statistical approach to identifying the key attributes that define a tennis superstar. 

Leveraging analytical techniques—including visualisations, regressions, and principal component analysis (PCA) - this study uncovers patterns in performance metrics, player trajectories, and the factors influencing success at the highest level. This report offers insights into the shifting dynamics of professional tennis and highlights the emerging talents most likely to leave their mark on the sport.


### Data Collection

Data used for this report includes:

- [Association of Tennis Professionals (ATP) Match Statistics]('https://github.com/JeffSackmann/tennis_atp') by Jeff Sackmann, containing raw match summaries from major ATP tournament from 1968 to 2024, including details such as match duration, match outcomes, and basic statistics such as Aces or Break Points Saved.

- [ATP Player Information](https://github.com/JeffSackmann/tennis_atp/blob/master/atp_players.csv) by Jeff Sackmann, containing the personal attributes of ATP players, including details such as player birth year, country of origin, and other personal attributes.

- [ATP Rankings](https://github.com/JeffSackmann/tennis_atp/blob/master/atp_rankings_00s.csv) by Jeff Sackmann, containing the weekly rankings of all ATP players.

- [ATP Advanced Match Statistics (Manual Match Labels)](https://doi.org/10.1093/jrsssa/qnae027) by Nirodha Epasinghege Dona, Paramjit S. Gill, and Tim B. Swartz, which aggregates manually labeled shot-by-shot data from Sackmann's open-source Match Charting Project. The primary dataset used in this report is sourced from Journal of the Royal Statistical Society Series A: Statistics in Society, Volume 188, Issue 1, January 2025, Pages 188–204.

- [Tennis Abstract Metrics](https://www.tennisabstract.com/cgi-bin/leaders.cgi) by Jeff Sackmann, containing the Top 100 player related statistics, scraped from the site.

