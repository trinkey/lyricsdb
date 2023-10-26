# LyricsDB
A place to put and get lyrics to songs, along with other data

## How to contribute:
1. Find a song you want to add
2. Create a fork of this repository
3. Make a file named `lyrics.txt` at the path `{ARTIST}/{SONG_NAME}/` (all lowercase)
4. Put the lyrics there and save the file
5. Create another file named `info.json` and put it in the same folder
6. Put the info based on the template below in there
```json
{
  "song": "Song Name",
  "release-date": {
    "year": 1999,
    "month": 12,
    "day": 31
  },
  "album": "Album Name"
}
```
7. Make a pull request and wait for me to accept it or tell if you need to fix anything.
8. Rejoyce!

## How to use in code:
Get the folder url for the song you want (`https://raw.githubusercontent.com/trinkey/lyricsdb/main/{ARTIST}/{SONG_NAME}/`)

To get the lyrics, append `lyrics.txt` to the end of the url.

To get other info, append `info.json` to the end of the url instead.