# What makes a video game succeed?

### Background

This project is part of the Data Scientist training program from Practicum by Yandex. More info in link below:

https://practicum.yandex.com/data-scientist 

### Project Setup

You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.

In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017.

(The important thing is to get experience working with data. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2027 sales based on data from 2026.)

The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.

**Skills Used: Data PreProcessing, Exploratory Data Analysis, Statistical Data Analysis**

### Data Description

* Name
* Platform
* Year_of_Release
* Genre
* NA_sales (North American sales in USD million)
* EU_sales (sales in Europe in USD million)
* JP_sales (sales in Japan in USD million)
* Other_sales (sales in other countries in USD million)
* Critic_Score (maximum of 100)
* User_Score (maximum of 10)
* Rating (ESRB)

Data for 2016 may be incomplete.


### Conclusion

#### What Makes a Game Succeed?

In short, the answer is the right combination of genre, platform, and rating depending on which geographical market you are looking to target. Let's break this down. 

**Which geographical market should online game store Ice target?**
* Japan is an area of opportunity as they have transitioned from consoles without new releases (Bandai and Sega ones) to more current ones. However, the market's taste is so unique it has a higher risk and it is more cost effective to focus on North America and Europe where there is plenty of chance of overlapping taste.
* North America makes the most revenue and has less language variation (especially as a good portion of Canada, Ontario, is English-Speaking) which affects marketing content and staff so it seems like the best choice. Before proceeding, I would try to source data and analyze an important metric missed here: **how many video game stores are there in North America vs Europe (particularly online)?**. We may have a case where although there are more sales, there is also much more competition. 

**If North America chosen, what makes a game succeed? What types of games should the marketing and supply strategy revolve around?**

* **Timing**: We should focus on games for current platforms with less then 4.5 years out (the middle of its product life).
* **Platform**: XBox consoles should be the primary focus, followed equally by Nintendo and Playstation consoles.  A bonus is that these platforms have a higher chance of having games that are multi-platform (same title across platforms) and hence when we choose games for campaigns, the best bet is a multi-platform one. Although still used, I would completely disregard unpopular PC games.
* **Genre**: "Shooter" and "Platform games sell the most in North America (and Europe!). These are indicators of two different age groups and taste and showcasing both widens our reach. If needed, 'Sports' games sell well and have wide appeal.
* **Critical Acclaim**: As critical acclaim increases, so do sales. Hence, we should remain flexible. If a game is receiving positive critical reviews, we should focus our efforts in promoting it (particularly if it is multi-platform, from genres shooter or platform, and assumingly from a recent console).

### Technologies Used

* Python (Pandas, Numpy, Seaborn, Scipy)

