# Spotify Clone

A web-based Spotify clone built using **HTML**, **CSS**, **JavaScript**, **PHP**, and the **Spotify Developer API**. This project replicates the look and functionality of Spotify, including track playback, playlist display, and user-friendly interface.It includes  approximately 315 songs were given in database and can search the songs and artist names playlists were designed library for recently played songs dynamic java script functionality clickables super polished UI fetching data from spotify web api

Folder Structure 📁 your-project/ ├── 📁 css/ ├── 📁 img/ ├── 📁 js/ │ └── script.js ├── 📁 php/ │ ├── check_login.php │ ├── fetch_artist_playlists.php │ ├── get_trending.php │ ├── logout.php │ └── spotify_token.php and many... ├── 📁 songs/ ├── index.php ├── login.html ├── signup.html ├── .gitignore └── README.md

 MyMusic — PHP Music Streaming Web App
This is a fully functional music streaming platform built using PHP + MySQL + JavaScript, with features inspired by Spotify. The project includes login/signup, playlist browsing, song streaming, artist-based discovery, and Spotify API integration for real metadata and album covers.

## Features

- Responsive UI similar to Spotify
- Play/pause functionality for tracks
- Display of playlists and song metadata
- Integration with Spotify Developer API to fetch real-time data
- Backend connectivity using PHP

## Technologies Used

- HTML5
- CSS
- JavaScript
- PHP
- Spotify Developer API


Installation (Local Setup with XAMPP)
Clone the repo
   git clone https://github.com/your-username/your-repo.git
Move it to XAMPP

bash Copy Edit mv your-repo/ /xampp/htdocs/your-repo/ Import the SQL file

Open phpMyAdmin

Create a database music_app

Import music_app.sql if provided (or manually create users/songs table)

Set Up Spotify API

Go to Spotify Developer Dashboard

Create an app and get Client ID & Client Secret

Add them to php/spotify_token.php

php Copy Edit $client_id = "YOUR_CLIENT_ID"; $client_secret = "YOUR_CLIENT_SECRET"; Run XAMPP and go to http://localhost/your-repo/index.php

 Developer Notes Songs must be placed in the /songs/ folder.

Cover images should be named/linked appropriately via cover_url.

Spotify API is used only to fetch metadata, not for actual music streaming.

This is a hobby/demo project. Not for commercial use.
