# Mobile-Application-Project
It is an Android Application that can play installed and online songs like any other music player application. It is an application which is able to play Music’s from Mobile memory as well as from database. It is developed in Android Studio which I have used to build the Application and using Java as a UX Programming Language and XML as a UI Language. To store the data(Favourite Songs) SQLite is used as a database storage Language.

It is a responsive Android Application because it can work on Landscape and Portrait mode as well as in various device such as tablet, etc.

## Overview of the Music Player App
### Songs Fragment (Installed Songs Only)

This is the first UI that contains all the pre-Downloaded songs and we can Play the music and we can also control the music from the following navigation at the bottom side. The name and the Album photo is taken based on stored data or else it will show up the default album image set by me. There is also a feature to delete a song permanently from the mobile storage.

### Album Fragment

The app also has the ability to categorize the songs based on album. The albums are retrieved from the phone's storage only. Each album contains the songs stored by the user and once the song is played from the album, only the songs in the album will auto-played one-by-one. We can also add song to the Favourite when playing the songs.

### Favourite Fragment

The app also contains a Favourite Section where a user can add their Favourite songs. The Favourite songs are stored on the individual's storage they are not remotely stored. The user has the ability to add or remove the songs based on his/her choice.

### Adify Fragment

This is the interesting part of the music player app where a user can play the songs from online quite similar to Spotify. The music streaming is absolutely free and the user can play, pause, play next or play previous without ads. This feature make the app to standout from other music Plyer apps.

## More Functionality
### Search
User can Search a Music From Songs and Adify by clicking on the Search icon. When you are in Adify Section then it will search in the Adify songs list only.
### Background Songs Playing
The songs can be played after closing the app from the background and foreground. Where I have used the Foreground Service to display a notification of the playing song in the Background, and we can also play, pause, move to next or move to previous song through the notification only.

## Requried permission
### Write_External_Storage is Required to run the application.
