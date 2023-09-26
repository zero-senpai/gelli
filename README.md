## Gelli0

This is a native music player for Android devices that connects to Jellyfin media servers. The code is based on a relatively recent version of Phonograph and was made for personal use, but contributions are welcome! Please open an issue to discuss larger changes before submitting a pull request. I am open to an improved icon if any graphic designers have a good suggestion.

[<img src="https://f-droid.org/badge/get-it-on.png" alt="Get it on F-Droid" height="90">](https://f-droid.org/packages/com.dkanada.gramophone)

## Features

* Basic library navigation
* Cache songs individually or through batch actions
* Gapless playback
* Sort albums and songs by different fields
* Search media for partial matches
* Media service integration with notification
* Favorites and playlists
* Playback history reporting
* Filter content by library

## Issues

Since this was a small project intended mainly for myself, there are some things I haven't resolved yet. I would appreciate pull requests to fix any of these issues!

* Artist sorting isn't available through the API
* Playlists and favorites will not update automatically when changed
* Artist with a , in their name are not foundd in the search results (for example, _Time, The Valuator_, will show up, but as an empty artist object. The only way to find the actual Activity is through searching an album first)

## Branch information

This is my small hobby for adding functionality and fixes to Gelli as I see fit. I currently use the main app on my moto razr+ to listen to my Jellyfin music library, and I like it a lot, but there coul be much more. I figured it would be a good learning project to dig through the source code and add some features missing from the current master, such as:

* Artist Overviews native from Jellyfin's getOverview API
* Android Media Player tweaks, such as including a favorite button on it
* Some UI tweaks
* Some big fixes for things I found (see **Issues**)

## Screenshots

<img src='https://raw.githubusercontent.com/dkanada/gelli/master/metadata/en-US/screenshots.png'>
