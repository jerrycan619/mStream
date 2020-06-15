# mStream interface mod

New Interface for mStream. 
For more information about mStream checkout the original repository: https://github.com/IrosTheBeggar/mStream

## Desktop UI
![](/git_img/desktop.gif)

## Mobile UI
![](/git_img/mobile.gif)

### Changes
* removed inline CSS and sorted all styles in SASS (7in1 architecture) (WIP)
* 2 complete new UI's. One for desktop usage, One for mobile usage
* build up on Bootstrap
* use updated librarys (i.e howler.js)
* stock icons replaced by materialdesignicons.com
* extended Jukebox controls (seek,volume)
* a lot of other things (mediaSession API, animations, ...)

### Version: 0.1.0
* Initial Release. Alpha testing stage.
* expect Bug's, Glitches and more!
* it's in daily usage by myself -> I fix bugs asap
* Feel free to open issues if you found a bug or have other UI improvement suggestions.

### TODO
* fix sharing playlist
* small position changes of some elements
* get completely rid of izi
* style all buttons
* figure out a way to navigate back in albums / artists / playlists / search (only on mobile)
* find the best style and place for every single thing, so expect moves of buttons, texts, icons, menus, etc.
* more code cleaning / modularization for better maintenance capability
* remove console.logs used for development
* extend jukebox more

## Install:
To install this on an existing mStream server please go to: https://github.com/jerrycan619/mStream-themes
<br/><br/>
Dev. install:<br/>
```shell
git clone -b interface --single-branch https://github.com/jerrycan619/mStream.git
cd mStream
npm install
npm start
```
## Credits

mStream is built on top some great open-source libraries:

* [music-metadata](https://github.com/Borewit/music-metadata) - The best metadata parser for NodeJS
* [LokiJS](https://github.com/techfort/LokiJS) - A native, in-memory, database written in JavaScript.  LokiJS is the reason mStream is so fast and easy to install
* [Audioplayers](https://github.com/luanpotter/audioplayers) - Cross platform audio library for Android and iOS that powers the mobile apps
* [Howler](https://github.com/goldfire/howler.js) - An audio library that powers the WebApp
* [Butterchurn](https://github.com/jberg/butterchurn) - A clone of Milkdrop Visualizer written in JavaScript
* [WebAmp](https://github.com/captbaritone/webamp) - A WinAmp clone that works in the browser

additional libraries for this interface:
* [Clusterize.js](https://github.com/NeXTs/Clusterize.js) - display large data sets in parts on mobile UI
* [Slick](https://github.com/kenwheeler/slick/) - Swipe gestures on mobile UI
* [noUiSlider](https://github.com/leongersen/noUiSlider) - Progress bar and volume slider
* [simplebar](https://github.com/Grsmto/simplebar) - scrollbar replacement for styling



