# Introduction:

Are video games getting worse over time, while sales continue to trend upwards? This is a topic of debate for a lot of people, as video games sales are reaching a point where they are reaching the upwards of 20 million, there are determining factors that these figures are reaching that point but the quality of this area is not reaching the same type of impact. This can be a topic that someone is interested in due to the fact that they may feel a certain way, and how this can be shown in a way that hasn't been seen before. This can be considered a data science problem because it isn't possible to see every single score of every single game over every single year. Being able to contain these into a chart or graph can show exactly what is happening year after year.

# Research Questions:


1. What is the highest selling year?

2. What is the average score of games for the highest seeling year?

3. When was the last highest selling year?

4. How often is this year overtaken? Does this continue to be (CURRENT YEAR)?

5. When it comes to critic score, how has this been deemed similar in today's world?

6. For reverse clarity, what years had the worst scoring games?

7. If this is still (CURRENT YEAR), how can we determine what games should be considered within our lists?


# Approach: 



I was able to find 3 datasets that can help with the questions I have focused above, and how I believe they can be helpful to trying to answer these questions. The first dataset, vgchartz-2024, has the sheet sorted by total sales, with a helpful "Critic Score" and "release date" within their dataset. Using this sheet, I can sort these by release year, and trim out specific scores and sales that may not meet my target goal. However, some of these datsets are not sorted with all sources combined, which will need to be cleaned to meet my goal. Within vgsales, I can find the sales figures for games that do not have sales figures in vgchartz-2024. Albeit a few years out of date, most of the research will need to be done on Nintendo Games, where they do not have sales figures for them. For imdb_video_game_rating, I want to use this to compare to today's world. Using the "votes" heading, we can see how this is more useful to see how many votes for a specific score these games did get.

# How This Fits:

This can address this problem by being able to find exactly what scores when and how scores are sorted. In this data, being able to find sales figures for high scoring games and being able to cross-reference this correctly will be able to determine if sales have gone up without the scores doing the same, or if this is incorrect information.

# Data:
[Brannen, B., & Asaniczka. (2024, January 29). Video Game Sales 2024. Retrieved May 1, 2024.](https://www.kaggle.com/datasets/asaniczka/video-game-sales-2024) - This will be used for the bulk of the information - updated to this year can give us the most up-to-date information on sales, which is the most important out of the three.

[GREGORYSMITH. (2019, September 19). Video Game Sales. Retrieved May 1, 2024.](https://www.kaggle.com/datasets/gregorut/videogamesales) - This data mainly gives us sales numbers for games that do not have them featured on the main dataset - from my research, mainly titles from Nintendo.

[Nyagami, D. (2022, September 19). Video game ratings from imdb. Retrieved May 1, 2024.](https://www.kaggle.com/datasets/nyagami/video-game-ratings-from-imdb) - This gives us public opinion on the games, which features the amount of "votes" as well as the rating for the same games featured in previous sources.
