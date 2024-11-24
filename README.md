# Assignment 1 - ReactJS app.

Name: Duan Li

## Overview.

Firstly, I have added three more static endpoints--the NowPlaying Page, TopRated Page and Mustwatch Page. 

Secondly, I have added recommendations and credits to enrich the movie details page. The actors' names can be clicked to their own profie pages, which are new-added, too.

Thirdly, new filtering options are added.(by year and rate) 

AT last, I implemented the pagination function.

### Features.
+ MustWatch Page which can stores your must-watch movies 
+ ActorProfilePage which contains his/her moviies
+ Recommendations on the movie detail page
+ Pagination function
+ flitered by year and rate(high to low, low to high)

## Setup requirements.

There is no non-standard requirements to set up. Just follow the normal steps.

## API endpoints.

+ Discover list of upcoming movies - movie/upcoming
+ Discover list of now_playing movies - movie/now_playing
+ Discover list of top rated movies - movie/top_rated
+ Get movie recommendations - movie/${id}/recommendations
+ Get movie credits - movie/${id}/credits
+ Get actor details - person/${id}
+ Get actor movies - getActorMovies

## Routing.

[ List the __new routes__ supported by your app and state the associated page.]

+ movies/nowPlaying - displays nowPlaying movies list.
+ movies/topRated - displays topRated movies list.
+ movies/mustWatch - displays movies added from upcoming movies list.
+ movies/:id/recommendations - displays recommendations in the movie details page.
+ movies/:id/credits - displays a cast&crew list in the movie datails page.
+ actor/:id - displays detailed information page related to an actor.



## Independent learning (If relevant).

Itemize the technologies/techniques you researched independently and adopted in your project, 
i.e. aspects not covered in the lectures/labs. Include the source code filenames that illustrate these 
(we do not require code excerpts) and provide references to the online resources that helped you (articles/blogs).