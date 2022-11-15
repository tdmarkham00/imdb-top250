# IMDB Top 250 Movies
The objective of this project is to retrieve information about the imdb top 250 movies. The data will be used to create visualizations and tell a story about the data.

## Table of Contents
[Installation](#Installation)

[Data](#Data)

[Contents](#Contents)

### Installation
For this project, you will need the following libraries:
* Pandas
* request
* BeautifulSoup
* omdbapi


### Data
The data is retrieved in two parts. The first part is a list of the top 250 movies which can be scrapped from the imdb website. The second part inputs each of those titles into the omdb website via the omdb api, and retrieves the following:
* Year - The year that the movie was released
* Rating - The MPAA rating
* Runtime- Runtime in minutes
* Genre - Genre
* Director - Name of director
* Score - IMDB rating
* BoxOffice - Box office amount


### Contents
This repository contains an ipynb containing the code used and a csv of the data exported from the python environment.


