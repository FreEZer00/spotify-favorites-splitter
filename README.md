# spotify-saves-splitter
## Purpose
My list of saved songs got very long so I want to use the spotify API to split this into different playlists for each year. I want to try using rust for this.

## Dependencies I need
- log, env_logger — for, well, logging
- reqwest, tokio — for REST API processing
- futures — for multithreading execution
- serde — for JSON response model
- chrono — for dates parsing
