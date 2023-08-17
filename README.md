# spotify-saves-splitter
## Purpose
My list of saved songs got very long so I want to use the spotify API to split this into different playlists for each year. I want to try using rust for this.

## Dependencies I might need
- log, env_logger — for, well, logging
- reqwest, tokio — for REST API processing
- futures — for multithreading execution
- serde — for JSON response model
- chrono — for dates parsing


## Spotify API 
- [Authorization](https://developer.spotify.com/documentation/web-api/tutorials/code-flow)
   - [Example](https://github.com/spotify/web-api-examples/blob/master/authentication/authorization_code/app.js)
- [Get User's Saved Tracks](https://developer.spotify.com/documentation/web-api/reference/get-users-saved-tracks])
- [Create Playlist](https://developer.spotify.com/documentation/web-api/reference/create-playlist)
- [Add Items to Playlist](https://developer.spotify.com/documentation/web-api/reference/add-tracks-to-playlist)
