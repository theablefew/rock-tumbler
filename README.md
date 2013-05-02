# Rock Tumbler 

Rock Tumbler takes the pain out of listening to playlists in Spotify. Some might even say that it smoothes out the edges of rock.

## Getting Started

1. Clone this repo into your `~/Spotify` directory. (Hint: You may need to create the path first.)

2. Login here [to upgrade your Spotify account to a "Developer" account](https://developer.spotify.com/login/).

3. Launch Spotify.

4. Type `spotify:app:rock-tumbler` into the search bar and then click "add" to add the app to your favorites. (Note, this will need to be done every time that you launch Spotify.)

5. Drag any playlist into the dashed drop box and once loaded, use the player to the right to begin playing the playlist. Rock Tumbler will remember what you have already listened to and automatically make those song ineligble to be played until you've made it all of the way through the playlist, even if you close the app!

6. Enjoy!

## Helpful Hints

* When on the app screen, `CMD+OPT+R` will reload the app.

* You can drop as many playlists into the dropbox as you wish. Rock Tumbler will play the last playlist dropped and will ignore duplicate drops.

* Rock Tumbler keeps track of changes that you make to your playlists — like adding and removing tracks — and will even keep your history if you rename a playlist.

## Feedback is Welcome

Feel free to contact me at: [tomko@theablefew.com](mailto://tomko@theablefew.com)

## Release History
* __2013/05/02__ - _0.1.0_ - Initial functional release

## TODO
* Make it look good.
* Determine viability of moving to Spotify API 1.x.
* Experiment with variable track removal timeout based on size of playlist. (Next button race condition still exists for very large playlists.)
* Add resume last playing track feature for when a playlist is left in the middle of a track.