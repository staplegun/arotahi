# Arotahi | Focus

A mindful viewing experience using the art and taonga from the collections of
the [Museum of New Zealand Te Papa Tongarewa](https://collections.tepapa.govt.nz/).

The web app pans slowly across images with an immersive soundtrack, for deep
contemplation.

## Web app prototype

[Arotahi | Focus](https://staplegun.github.io/arotahi/)

## Usage

The web pages display images accessed via
[Te Papa's Collections API](https://data.tepapa.govt.nz/docs/).

The `arotahiview.html` page accepts querystring parameters to customise
the experience:
* `categoryid` - id of a group record in the API
* `id` - id of a media record in the API
* `iiif` - URL of a IIIF image (instead of the `id` parameter)
* `audio` - URL of an MP3 audio file to play as 'sparkle'
* `speed` - pan speed (1-100, default: 2)

## Requires

* [Pīwakawaka](https://staplegun.github.io/piwakawaka/) - image controller
* [Sonifier](https://staplegun.github.io/sonifier/) - sound generator
* [OpenSeadragon](https://openseadragon.github.io/) - [IIIF](http://iiif.io/) image viewer
* [Tone.js](https://tonejs.github.io/) - sound player
* [NoSleep.js](https://github.com/richtr/NoSleep.js) - fullscreen viewer
* [jQuery](https://jquery.com/)

## Licence

This project is licensed under the MIT Licence - see the
[LICENSE](LICENSE) file for details
