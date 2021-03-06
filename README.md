# Flixster
# Project 2 - *Flixster*

**Flixster** shows the latest movies currently playing in theaters. The app utilizes the Movie Database API to display images and basic information about these movies to the user.

Time spent: **16** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can **scroll through current movies** from the Movie Database API
* [x] Display a nice default [placeholder graphic](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
* [x] For each movie displayed, user can see the following details:
  * [x] Title, Poster Image, Overview (Portrait mode)
  * [x] Title, Backdrop Image, Overview (Landscape mode)
* [x] Allow user to view details of the movie including ratings within a separate activity

The following **stretch** features are implemented:

* [x] Improved the user interface by experimenting with styling and coloring.
* [x] Apply rounded corners for the poster or background images using [Glide transformations](https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#transformations)
* [ ] Apply the popular [View Binding annotation library](http://guides.codepath.org/android/Reducing-View-Boilerplate-with-ViewBinding) to reduce boilerplate code.
* [x] Allow video trailers to be played in full-screen using the YouTubePlayerView from the details screen.

The following **additional** features are implemented:

* [x] App bar color changed to fit into the peach theme of the app
* [x] Implemented illusion of motion through color gradients on vertical scroll


## Video Walkthrough

Here's a walkthrough of implemented user stories:

πΏ View of scrolling through list of movies

<img src='https://github.com/jackjnn/Flixster/blob/master/flixsterscroll.gif' title='' width='500' alt='Video Walkthrough' />

πΆββοΈ Navigate to movie profile

<img src='https://github.com/jackjnn/Flixster/blob/master/flixsterscroll2.gif' title='' width='500' alt='Navigate to movie profile' />

πΊ Navigate to watch movie

<img src='https://github.com/jackjnn/Flixster/blob/master/flixsterwatch.gif' title='' width='500' alt='Navigate to watch movie' />

π Navigate on Landscape mode

<img src='https://github.com/jackjnn/Flixster/blob/master/flixsterlandscape.gif' title='' height='500' alt='Navigate on landscape mode' />

π₯³ Enjoy movie on fullscreen landscape

<img src='https://github.com/jackjnn/Flixster/blob/master/flixsterlandscapewatch.gif' title='' height='500' alt='Navigate on landscape mode' />

GIF created with [Kap](https://getkap.co/).


## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright 2021 Jack Njoroge.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
