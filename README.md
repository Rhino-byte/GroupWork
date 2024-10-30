

# Film Performance Analysis


![img readme](https://github.com/user-attachments/assets/3aa19ce8-d3a5-469b-8e12-d4269a350898)




## Overview
Within today's highly competitive entertainment market, companies attract audiences and revenues with unique video content. The company has decided to open a new movie studio in order to take advantage of this trend, although it has little prior experience producing films. This project will analyze the current box office trends and genres of movies that are performing well. Analyzing the data will allow the determination of some key factors of success regarding movie genre, budget, window of release, and audience preference. The insights from this analysis will be translated into actionable recommendations to guide the new movie studio in choosing the right types of films to produce for optimal performance in the market.

## Business Understanding

### Stakeholders
The company owners

### Business Problem
The company now sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies.

We aim to:

1. Identify film genres and types with strong box office performance.
2. Evaluate factors such as budget, release timing, studio and audience reception that influence a movie’s success.
3. Analyze data from multiple sources, including Box Office Mojo, IMDB, TheMovieDB, and The Numbers.
4. Provide recommendations on the types of films to produce based on the analysis results.
5. The findings will help the head of the company's new movie studio decide what type of films to create.


## Data Understanding


### Data Sources

a. [IMDB](imdb.com)

b.[Box Office Mojo](boxofficemojo.com)

c.[The Numbers](the-numbers.com)

d.[The MovieDB](themoviedb.org)




### Data Description

1. genre...the type and category of movies

2. Production Budget....capital

3. studio

4. Gross Revenues....domestic gross revenue, world gross revenue,foreign gross revenue

5. Vote_count....how a movie was voted for

6. Average ratings....fresh or rotten tomatoes

7. Release Dates....when a movie was released

8. Popularity....how popular a particular movie was




## Data Analysis


1. Investigate the genre column what are the different levels in terms of popularity ,average rating,average_vote_count.
2. Time when the film is produced does it have significance difference ;release date and the gross for foreign,domestic.
3. Does a higher budget guarantee a higher gross return or popularity.


Analysis and Visualizations
Our data analysis will include visualizations such as:



### 1.  Plots of different performance and success metrics and the genre



![alt text](Images/image-1.png)


#### Explanation
Top Genres by Popularity: The most popular genres are fantasy, action, sci-fi, adventure, and animation. Large audiences are generally drawn to these genres because of their immersive settings, high-energy narratives, and visual effects. involvement of the Audience: Popular genres typically have high levels of audience involvement on streaming platforms, social media, and trailers, which is crucial for generating initial viewer interest and marketing momentum.

High Vote Total Genres: The genres with the greatest vote averages are drama, comedy, and action, suggesting that they are highly viewed and rated. This popularity indicates that viewers who are interested in plot and character nuance are drawn to these genres.

Popularity vs. Critical Acclaim: Although genres like drama and biography have high vote averages, they might not be as popular as more spectacle-driven genres like action or sci-fi, suggesting that they might be more appealing to viewers who value reality and depth above escape.

Global Blockbusters: The highest grossing genres globally include animation, adventure, and science fiction. This performance demonstrates the global appeal of these genres, most likely as a result of their universally captivating themes and excellent visual effects that appeal to audiences from various backgrounds.

High ROI Potential: Particularly in international markets, genres like animation and adventure that have high global gross relative to their production budget show a great return on investment. These genres might be the best for worldwide releases that maximize profits.

High-Budget Genres: Adventure, Animation, Sci-Fi, and Action require high production budgets, which align with their high visual demands and often require advanced effects and well-known actors.

Cost-Effective Genres: Comedy and Documentary are among the lower-budget genres but can still generate significant domestic and worldwide gross, making them good options for lower-risk investments.



### 2.  Plots of different performance and success metrics and the studio


![alt text](Images/image-2.png)


#### Explanation

As shown above, BV and P/DW studios generated the highest income. We want to look at what kind of genres they produced.


### 3.  Correlation Analysis


![alt text](Images/image.png)





#### Explanation
Both domestic gross (0.48) and worldwide gross (0.52) have moderately positive associations with the popularity of films, suggesting that popular films tend to bring in more money. Though popularity plays a role in box office success, it is not the only one, as evidenced by the weaker association between popularity and production expenditure. Furthermore, there is a moderate correlation between popularity and production budget (0.51), suggesting that movies with bigger budgets typically have greater appeal and visibility due to improved marketing campaigns and better production quality.

However, there is a substantial positive association between the production budget and the worldwide gross (0.76), suggesting that films with larger budgets are more likely to do well in international markets.

The fact that bigger budgets frequently enable higher production quality, more intensive marketing, and wider distribution channels—all of which contribute to global success—supports this association. High-budget movies are more likely to succeed in the US market, according to the strong link with domestic gross (0.69). This link suggests that overseas markets might react more favorably to high-budget movies, despite the fact that it is marginally less than that with global gross. All things considered, although larger production expenses increase a movie's chances of being well-known and making money, the relationship is nuanced and impacted by other variables.





## Conclusion
To wrap it up, investing in these well-liked genres while maintaining a balanced budget offers the best strategy. Projects become more financially feasible and appealing to a larger audience by concentrating on genre pairings and strategic budget management, which also increases the potential return gross. This approach successfully manages the risks connected with large expenditures while striving for both critical and commercial success.Despite the fact that larger production expenditures frequently translate into bigger profits, it is crucial to prioritize compelling content, powerful performances, and frugal spending. Box office results can be increased by utilizing strategic release timing, especially in the second quarter, when films typically do well. Furthermore, the studio will be better positioned for success in the competitive market by working with reputable studios like Paramount/DreamWorks, Buena Vista, Sony, and MGM and copying their success in popular genres.


## Recommendations

1.Genre Selection: Consider investing in action, drama, animation, scifi and adventure genre of movies as they show high popularity and votecounts and have promising returns. A movie can have more than just one genre; this guarantees more popularity and higher vote counts.

2.Production budget: Although higher budgets have a positive correlation with higher grosses, maintaining a reasonable production budget is crucial, focus on factors like good storytelling, good perfomances and concrete market research as these factors contribute towards a movie popularity and its gross earnings.

3.Release timing: Prioritize releasing films during Q2 (April–June) to capitalize on the historically higher median and broader range of worldwide gross revenues.

4.Studio collaborating: Consider collaborating with the following studios: Paramount/DreamWorks(P/DW), Buena Vista (Disney)(BV), Sony and Metro-Goldwyn-Mayer(MGM) since their movies seem to show high performance on the success metrics.

5.Market research and localization: conduct comprehensive market research to understand specific international market cultural preferences and nuances. Adapt the concept of movies, promotion campaigns, and strategic means of distribution to resonate in consonance with the target audience's cultural sensibility and reach maximum global appeal.







[Tableau Visualization](https://public.tableau.com/app/profile/charles.odhiambo/viz/Groupwork5tableau/Dashboard2#1)
