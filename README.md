# Spotify Interface

Spotify interface that will use the Spotify API and the Openweathermap API to create playlist of songs that you have never heard of, or played before but pulled from playlist of other Spotify users with similar taste in music, based on the daily weather predictions drawn from the weather API.

Before you run the jupyter notebook, there are two prerequisites:

1. You will need to create a spotify_keys.json file that contains your Spotify username, Client ID, Client Secret, Redirect URI, Playlist ID of the playlist you want to change and WeatherAPI key.

   ```
   {
   	"username": "<YOUR-USERNAME>",
   	"client_id": "<YOUR-CLIENT-ID>",
   	"client_secret": "<YOUR-CLIENT-SECRET>",
   	"redirect_uri": "<YOUR-REDIRECT-URI>",
   	"playlist_id": "<YOUR-PLAYLIST_ID>",
   	"weather_api_key": "<YOUR-WEATHER_API_KEY>"
   }
   ```

   

2. You will also need to install the Python packages and libraries needed for the Interface

   ```
   pip install -r requirements.txt
   ```

   