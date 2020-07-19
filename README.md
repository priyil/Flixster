# Flixster

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flixster MVP 2

### Features

- [X] Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [X] Allow video posts to be played in full-screen using the YouTubePlayerView.

<!--- #### BONUS

- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [X] Add a rounded corners for the images using the Glide transformations. (1 point) --->

### App Walkthough GIF

<img src="https://github.com/priyil/Flixster/blob/master/walkthrough1.gif"><br>

<!---### Notes

The stretxh stories took me most of the time, but I had a lot of fun doing it. Improved UI elements. --->

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

---

## Flixster MVP 1

### Features

- [x] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [x] Views can should be responsive for both landscape/portrait mode.
   - [x] In portrait mode, the poster image, title, and movie overview is shown.
   - [x] In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
- [X] Improved the user interface by experimenting with styling and coloring.
<!--- - [X] Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading 
- [ ] (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.--->

### App Walkthough GIF

<img src="https://github.com/priyil/Flixster/blob/master/walkthrough.gif" width=450><br>

<!--- ### Notes
Made a small mistake which increased time by a lot. Took a lot longer than expected. --->

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
