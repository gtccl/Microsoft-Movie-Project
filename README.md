## Microsoft Movie Studios Box Office Analysis


## Project Overview

This project analyzes the best performing films in the box office to give insights into what types of movies Microsoft Movie Studios should create. Exploratory data analysis of the data provides actionable insights on the target audience, genre and performance indicators which guide a film's success. Microsoft Movie Studios can use this analysis to create content and further considerations to achieve long-term success.

### Business Problem

Microsoft would like to create a movie studio and begin making films, however they have never made any films before. A movie studio's success depends on its ability to produce films that not only resonate with audiences but generates revenue. 

This project will allow stakeholders and Microsoft Movie Studios insights into what type of films are performing well in the box office in order to try and replicate that success. Analysing box office data provides the necessary insights to make informed decisions, minimise risks and increase the likelihood of financial success.

### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)

The below are included but not used in this project:
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)


* imdb.title.basics
* imdb.title.ratings
* bom.movie_gross

This data was collected from studio reports, user reviews, box office reports and a combination of the above.


The dataset represents records for each individual movie including the title, release date, genre, budget, box office gross, and ratings which we will use to understand and create business insights from. 



## Methods

We created three basic datasets (df_basicinfo, df_imdb_ratings, df_movie_gross) with the data collected from above. We then merged these databases on *tconst* between df_basic info and df_imdb_ratings and then on *title* with df_movie_gross to create a final table. 

The final table had over 14000 entries, so a Top 50 Grossing Movies dataframe was created so our analysis was more manageable.

This project uses exploratory data analysis for the target variables of movie tite, genre, ratings and box office performance.



## Results

Foreign audiences bring in most of the total gross revenue.

The highest rated films are not necessarily the most profitable.


The Adventure genre is the most common genres in the top 50 grossing films. 




## Conclusions
This analysis of box office films leads to three recommendations for Microsoft Movie Studios:

**Capitalise on the foreign market**: The box office gross is a direct indicator of a movie's financial success. A large proportion of the total gross of films comes from foreign gross as opposed to the domestic gross. Microsoft should capitalize on this area and allocate more promotional and marketing materials to incentivise more audiences to watch the film. Understanding the geographic distribution of revenue can highlight the film's global appeal.


**Ratings drive decision-making:** Ratings provide valuable feedback on how well a film has received and the overall quality of a film. Positive ratings contribute to positive word-of-mouth driving audience attendance and marketing/promotional materials to attract audiences. Microsoft should endeavour to create films of high quality as positive ratings help establish a studio's credibility and create a loyal audience base. By continuing to monitor audience reactions, scores on platforms like IMDB and other sites, Microsoft can gain insights into what worked well and what could be improved which is invaluable for tailoring future content to better align with audiences.

Microsoft should also keep in mind that the ratings can be skewed by the number of votes and the demographic of audience whom are voting. Ratings are inherently subjective and vary based on the individual e.g. critics may focus on artistic elements but the general audience prioritises entertainment.


**Create films in the Adventure genre**: The top 50 grossing films have a combination of genres that include Adventure.  Microsoft Movie Studios should identify what their target audience wants and capitalize on the type of content they want to see. As they are a fledging movie studio, not only do audiences find entertainment value in the Adventure genre, these types of films are among the most profitable, so the studios should start by creating films which include this genre to have the best chance of success. 

Microsoft should tailor promotional materials to the audience associated with each genre. Centain genres can create dedicated fan bases and creating content around this genres can lead to increased audience loyalty and long-term success.

While Adventure is a successful genre, if they continue to produce films similar the top 50 films, this could lead to a market saturation and lack of originality. Originality plays a significant role in capturing audience attention and staying relevent. 


---
While this project analysis aims to explore what type of films are currently doing the best at the box office, as the audience changes, industry trends can change as well. This information is most useful for Microsoft to launch their studios and create for the now, however it will be important to continue doing research to keep ontop of industry trends. Audience preferences evolve over time and the success of a particular set of films may not accurately predict future success.


## Deliverables

There are three deliverables for this project:


GitHub Repository for this project:
|-- zippedData folder
|-- README.md
|--Microsoft Movie Studios Analysis.ipynb
|--

See the full data analysis in the Microsoft Movie Studios Analysis.ipynb (Jupyter Notebook)

See the non-technical presentation in this PDF 


