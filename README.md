# Fogo de Chao New Location Analysis
Authors: John Sheehan, Yue Yu, Zach Pollatsek

## Overview
Fogo de Chao is a high-end restaurant chain that has found success all across the United States. High-end restaurants tend to perform better when located in neighborhoods/city areas that are in close proximity to higher priced neighborhoods. Fogo de Chao has one location in Bellevue, WA, and the restaurant group has seen tremendous success here. 

## Business Problem
Fogo de Chao has tasked us with finding the best possible location in the Seattle area for their second restaurant in the state of Washington. Specifically, Fogo de Chao wants to know which zip codes a new restaurant could be located in order to optimize success. The restaurant group wants to ensure that the new location will be in close proximity to those who are comfortable paying for a high-end dining experience. 

We will use housing data from King County government to determine answers to the following questions:

- What neighborhood

- What is the relationship between movie budget and expected gross revenue? 

- What season/month should we target releases in order to optimize our return on investment?


## Data

[IMDB](https://IMDB.com) is the largest, most comprehensive movie database publicly available on the web. [The Numbers](https://www.the-numbers.com/) is a trusted resource for movie business information including movie budget, performance and various revenue categories. The data files analyzed herein provide movie titles, genre tags and release date, as well as financial characteristics such as worldwide gross revenue and production budget.

## Methods

This project uses descriptive analysis to provide an overview of the factors that go into executing a successful movie production and release. 

## Results

Movies with the Animation, Adventure or Sci-Fi tags generally produced the highest ROI. War and Western movies were the least profitable.
![](images/MedianROI_genre.png)


There is a strong correlation between production budget and return on investment.
![](images/WorldwideGrossRevenueByProductionBudget.png)


The data reveals that movies released in June, July, or November produce the highest return on investment.
![](images/MedianROI_ReleaseMonth.png)


## Conclusions

- **Movies in the animation, adventure and sci-fi genres tend to produce better return on investment than other genres.** As a result, we recommend prioritizing the creation of content that aligns with these genres. Avoid war and western-themed content as these tend to produce unfavorable ROI.
- **Movies released in June, July and November tend to generate better return on investment than other months.** As a result, we recommend targeting new releases for the summer or November months.
- **There is a strong correlation between movie production budget and return on investment.** Microsoft should direct its movie-making budget toward a relatively small number of projects in the above genres to avoid diluting ROI.

## Next Steps

Entering a new industry comes with significant startup costs. To help Microsoft produce an initial movie that is a blockbuster, we recommend the following additional analysis.

- Additional budgetary data to increase sample size and refine observations.
- Identify replacement metrics to measure success where budget/revenue is unavailable.
- Further analysis of the top grossing 50 movies of the past decade. Taking a more in depth look at what made these movies so financially successful.

## For More Information

See the full analysis in the [Jupyter Notebook](MSFT_Movie_Analysis.ipynb) or review [this presentation](MSFT_Movie_Presentation.pdf).

For additional info, contact Ogo Ndugba, Zach Pollatsek or Tom Chapman as follows:

- Ogo:    ogo.ndugba@gmail.com 
- Zach:   zacharypollatsek@gmail.com
- Tom:    thomas.h.chapman@gmail.com

## Repository Contents
- data
- images
- working notebooks
- .gitignore
- README.md
- MSFT_Movie_Presentation.pdf
- MSFT_Movie_Analysis.ipynb
