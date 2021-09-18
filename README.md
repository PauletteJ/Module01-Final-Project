# Movie Genre Analysis

## Introduction

The premise of this project is that Microsoft has decided to start a movie studio, and they need to determine what the best kind of movie to make is. This project will analyze the best grossing movies for 2019, 2020, and all time, and break them down by genre, the number of genres they fit, and MPAA rating to determine they type of movie Microsoft should focus their production on.

## The Dataset

I scraped the BoxOffice Mojo web site for the domestic gross, MPAA ratings, and genres of the top 200 movies of three lists: all time grossing movies, highest grossing movies of 2019 and highest grossing movies of 2020. I kept the lists of 2019 and 2020 to 200 movies since movies below that generated small enough revenue ($2.2 million and $150,000 respectively) that they would not be of interest to a major player in the movie industry. The resulting set was a total of 551 movies.

I compared the movies on genre, number of genres each movie contained, and MPAA ratings, against each movie’s domestic gross.

##Domestic Gross by MPAA Rating

The first feature I explored was MPAA rating, as illustrated in the chart below showing the mean gross per movie for each rating. The PG-13 rating is considered to be the sweet spot for movies, and it certainly does do well, but the interesting thing about this chart is that the G rated movies perform just as well, with PG movies not far behind. It is not surprising that R rated movies, with their smaller pool of potential audience members, gross significantly less.

![Gross by MPAA Rating](/images/GrossByMPAARating.jpeg)

##Domestic Gross by Genre

Next I compared the various genres on their domestic gross. BoxOffice Mojo lists 21 different genres. Science fiction outperformed all other genres, including the action and adventure categories. The top seven genres (science fiction, adventure, action, musical, family, and fantasy) have a general theme of escapism. There is a clear break in the mean gross of those genres with that of more realistic genres from comedy to documentary.

![Gross by Genre](/images/GrossByGenre.jpeg)

##Domestic Gross by Number of Genres

A feature that is considered less often is the number of genres a movie fits in. Crossing over genres is important in the publishing industry, as it is seen as an opportunity to broaden the potential audience of a particular work. The chart below illustrates a similar effect for movies, with the peak gross being for movies with six genres. Only one movie, which happened to have a small domestic gross, had eight genres listed.


![Gross by Number of Genres/images/GrossByNumberOfGenresjpeg)

## Summary

The characteristics of the highest grossing movies are:

1. G or PG-13 ratings
2. Genres of Science Fiction, Adventure, Action, Musical, Animation, Family, Fantasy
3. Contain 3-7 genres

Microsoft is well poised to take advantage of these characteristics with the intellectual properties it owns, such as Halo and Minecraft. These fit multiple genres listed above, (science fiction, adventure, action, and family) and would easily fit the G and PG-13 MPAA ratings that are proven to be high revenue generators. Leveraging these properties would have the added advantage of reinforcing sales of games and other merchandising that the company has a strong presence in.