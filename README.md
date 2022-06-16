# music-charts

This app scrapes music chart data from the NZ Top 40 and the Billboard Hot 100, which can be then used to create spotify playlists of the top charting songs. 

### To Run App:
Install dependencies:
- pip install beautifulsoup4
- pip install requests
- flask
- spotipy

Get Spotify Client Secrets
- Create a spotify developer account
- Create new application on https://developer.spotify.com/dashboard/applications
- Make note of your Client ID and Client Secret
- [The Spotify developer website has a good tutorial on this](https://developer.spotify.com/documentation/general/guides/authorization/app-settings/)

Run App (from terminal):

> set FLASK_APP=app
> 
> flask run

### To do:
- Make a script that downloads all the dependencies easy
- Create front end that user can interact with
  - Allow user to choose a playlist name + description (but have a default as just "NZ Top 40 week dated dd/mm/yy" or something)
  - Allow user to upload a playlist cover art