# Video Store

Conosole app. To do functional training.
Run `npm install` in the `javascript-exercises` directory to install dependencies.

Run `node index.js` inside directory `video-store` to run the app


# Tasks

The goal of this optional exercise is to design and implement a simple inventory control system for a small video rental store. Define least two classes: a class Video to model a video and a class VideoStore to model the actual store.

Video have the following state:
 - a title;
 - a flag to say whether it is checked out or not;
 - an average user rating.

 
The VideoStore have the state of videos in there currently. The VideoStore have the following behaviour:

 - add a new video (by title) to the inventory;
 - check out a video (by title);
 - return a video to the store;
 - take a user's rating for a video;
 - list the whole inventory of videos in the store.
 
 
Summary of design specs:
 - Store a library of videos identified by title.
 - Allow a video to indicate whether it is currently rented out.
 - Allow users to rate a video and display the percentage of users that liked the video.
 - Print the store's inventory, listing for each video:
    - its title,
    - the average rating,
    - and whether it is checked out or on the shelves.
