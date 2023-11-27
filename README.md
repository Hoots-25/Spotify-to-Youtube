# Spotify to YT Music Playlist Transfer
Using your spotify account/API and ytmusicapi, transfer your playlists over.<br>
Right now, the script is basic and only uses song titles (So if the song has a common name, it may not get the right one) <br>
Will definitely try to see if multiple filters can be used (for song name + artist) to avoid any mixups <br>

## How To
Pretty Self Explanatory. Make sure you install the correct Spotify and ytmusic libraries.<br>
Make sure you create an oauth.json file before trying to create the YT playlist otherwise you'll get an error. <br>
Update the user input sections in the Spotify and YTM sections to make sure you have correct inputs. <br>
Documentation on ytmusicapi can be found below.

## ytmusicapi Documentation Used
* [Homepage](https://ytmusicapi.readthedocs.io/en/latest/index.html)<br>
* [Setup oauth.json](https://ytmusicapi.readthedocs.io/en/stable/setup/oauth.html)<br>
* [Search for Songs](https://ytmusicapi.readthedocs.io/en/latest/reference.html#search)<br>
* [Create a Playlist](https://ytmusicapi.readthedocs.io/en/stable/reference.html#ytmusicapi.YTMusic.create_playlist)<br>