#  -------- Analysis of Affecting Factors of Films Worldwide Gross --------

## Overview
The goal of this project is to aid _The Microsoft Production Company_ (TMPC) in optimizing the profitability of future films. The measure used to evaluate profitability for this project is worldwide gross of films. Worldwide gross has been chosen because, presumably, increased worldwide gross yields a higher return on investment. Furthermore, increased worldwide popularity likely results in boosted global merchandising opportunities, creating additional revenue sources. 

The following factors were explored to determine if and how they impact worldwide gross: 
- Production Budget
- Month of Release
- Month of Release grouped by Genre
- Rating
- Production Budget & Worldwide Gross, Grouped by Rating

## Business Problem
To begin creating original video content, Microsoft has decided to create a new movie studio: _The Microsoft Production Company_ (TMPC) . TMPC needs an assessment of the factors which contribute to a films success.

## Data
This project used data from:
-	__The Numbers__
 - 5,782 films from 1915 to 2020
-	__Rotten Tomatoes__
 -	1,559 films from 1921 to 2018
-	__IMDb__
 -	98,940 films (unknown timeframe) 
 
### As the databases were joined together their sizes were reduced.  Information about the datasets used in analysis are below: 

### tn: 5,782 films from 1915 to 2020
-	__Used for:__
 -	_Relationship Between Production Budge & Worldwide Gross_
 -	_Worldwide Gross grouped by Month of Release_

<img src="budget vs gross.png">

<img src="Worldwide Gross grouped by Month of Release.png">

### tnimdb (tn joined with imdb): 3,325 films from 1915 to 2019
-	__Used for:__
 -	_Worldwide Gross per Month of Release, grouped by Genre_ (7,309 genres)
 - ( __<font color=gold>GOLD</font> &#9651;__'s mark the mean)

> January Top 3 Genres: __Sport, Animation, Horror__ 

![jan-2.png](attachment:jan-2.png)

> February Top 3 Genres: __Musical, Music, Adventure__ 

![feb-2.png](attachment:feb-2.png)

> March Top 3 Genres: __Musical, Fantasy, Documentary__ 

![mar.png](attachment:mar.png)

> April Top 3 Genres: __Animation, Adventure, Sci-Fi__ 

![apr.png](attachment:apr.png)

> May Top 3 Genres: __Animation, Sci-Fi, Adventure__ 

![may.png](attachment:may.png)

> June Top 3 Genres: __Sci-Fi, Animation, Adventure__ 

![jun.png](attachment:jun.png)

> July Top 3 Genres: __Animation, Adventure, Action__ 

![jul.png](attachment:jul.png)

> August Top 3 Genres: __Fantasy, Adventure, Action__ 

![aug.png](attachment:aug.png)

> September Top 3 Genres: __Animation, Family, Musical__ 

![sep.png](attachment:sep.png)

> October Top 3 Genres: __Animation, Sci-Fi, Thriller__ 

![oct.png](attachment:oct.png)

> November Top 3 Genres: __Fantasy, Animation, Adventure__ 

![nov.png](attachment:nov.png)

> December Top 3 Genres: __Horror, Fantasy, Adventure__ 

![dec.png](attachment:dec.png)

### rttnimdb (rt joined with tnimdb): 67 films from 2010 to 2018
-	__Used for:__
 -	_Worldwide Gross grouped by Rating_
 -	_Money Spent vs Money Returned_

![gross%20by%20rating.png](attachment:gross%20by%20rating.png)

![return%20on%20investment.png](attachment:return%20on%20investment.png)

## Methods
This project uses descriptive and visual analysis, including description of trends over time. This provides a useful overview of film industry trends, specifically the factors that contribute to increased worldwide gross. 

## Results
- Production Budget, Month of Release, Genre, and Rating were all positively correlated with Worldwide Gross. 
- Production Budget and Worldwide Gross are most strongly correlated with a Pearson correlation of .75
- May & June are top two grossing months followed by July & November
- Animation & Adventure are in all those months’ Top 3 Genres
- May & June have the same top 3 Genres just in different order
- Based on the mean value, PG-13 is the top grossing movie rating and is so with a lower production budget on average when compared to PG movies 
- An R rating significantly limits worldwide gross 

 
## Conclusions
Deciding to fund a film can be risky, by understanding the correlation between worldwide gross and the aforementioned factors TMPC can optimism revenue potential by aligning all positively correlated factors.

-	__Bank on the budget:__ higher production budget yields higher worldwide gross
-	__The month matters:__ May & June are the top two months to release a film
-	__Each months top genres matter too:__ May & June have the same top 3 genres: Animation, Sci-Fi, & Adventure 
-	__R is NOT for Revenue:__ R rated movies restrict your audience and your worldwide gross

### Next Steps
1. Release a film in May or June
2. The film should contain one of the following genres:
 - Adventure
 - Animation
 - Sci-Fi 
3. The movie should be rated PG-13
4. Don’t shy away from higher production cost to increase Worldwide Gross.

### _Limitations to consider._
- This analysis was based strictly on worldwide gross and does not reflect other factors which influence profitability of a film. A few examples being: postproduction costs, merchandising income, marketing, return on investment, foreign rights, distribution fees… etc. 
- Investigation into the return on investment (in this case difference between worldwide gross and production budget) may yeild additional insight into ideal genres, ratings, or months-of-release.
- The data frames contain films dating back a century. Further analysis is needed to measure if the analysis is skewed (specifically the Musical genre) by these older films and not reflective current trends. 
- No calculations to account for inflation were done.

### Thank you!

__Email:__ cassigroesbeck@gmail.com

__GitHub:__ @AgathaZareth

__LinkedIn:__ linkedin.com/in/cassarra-groesbeck-a64b75229
