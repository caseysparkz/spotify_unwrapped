# spotify_unwrapped
A work in progress.

This script reads the user's most listened-to artists and/or tracks, and returns a playlist of 100 track recommendations.


## Requirements
This script requires that the following environment variables be set on the host:
* `SPOTIPY_CLIENT_ID`
* `SPOTIPY_CLIENT_SECRET`
* `SPOTIPY_REDIRECT_URI`

These can be created/acquired with a Spotify Developer account at https://developer.spotify.com/dashboard/applications.

It also requires the `spotipy` Python package:
`pip install -r requirements.txt`

## Usage
1. Set the above environment variables.
2. Install the requirements: `pip install -r requirements.txt`
3. Run the script: `spotify_unwrapped.py`


## Help
```
./spotify_wrapped.py -h
```
