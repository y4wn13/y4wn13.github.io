# Profitability of films that pass the Bechdel Test
*By Andrew Yawn*

## Description: 
The goal of this project is to examine and analyze whether female representation in movies has any noteworthy associations with box office returns. I'd also like to see if I can determine whether female representation has any stastictical significance when attempting to predict a film's ROI.

## A key metric: 
In 1985, a cartoonist named Alison Bechdel drew a comic that unwittingly set the standard for measuring female representation in movies for the next four decades. The comic showed two women opting not to see a movie because it did not pass three criteria:
There must be at least two women
A conversation between two women
A conversation between two women about anything but a man

The Bechdel Test was born, and despite its flaws, it remains the only popular standard by which female representation in movies is judged. I will be using the Bechdel Test as a key feature in this data project to categorize the level of female representation in a movie.

## Data:
9000+ Movies : IMDb and Bechdel - https://www.kaggle.com/datasets/nliabzd/movies-imdb-and-bechdel-information
TMDB + IMDB Merged Movies Dataset - https://www.kaggle.com/datasets/ggtejas/tmdb-imdb-merged-movies-dataset
The first contains data for more than 9,000 films including, crucially, associated Bechdel Test scores (scale: 0-3). The data was scraped from BechdelTest.com, a website that crowdsources Bechdel scores from hundreds to thousands of users per movie.

The second contains data for more than 350,000 films pertaining to budget, revenue, genre, and other, mostly categorical labels such as language, production company and cast. It is also rife with duplicate movie IDs and movie ratings. I am planning to merge the data sets on movie title and IMDB identification numbers.
