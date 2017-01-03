# GRAVITATOES
### Rig your website to explode with potatoes using javascript!

GRAVITATOES.js is a small, flexible, and extensible, piece of javascript to rig your website to explode with potatoes!

Other than potato bursts, GRAVITATOES.js also offers the option to have constant falling potatoes. This is a suitable substitute for the popular javascript snow effect!

Features include:
* Falling potatoes
* A variation of "plop!" sounds for when the potatoes hit the bottom of your browser.
* Works on mobile devices
* These potatoes are ready for the modern web!

# [Click here](http://tetrageddon.com/gravitatoes) for a live demo of GRAVITATOES

GRAVITATOES are easy to implement! 
Simply follow these following easy to follow steps:

* Upload the "GRAVITATOES" folder to your server, in the same directory as the page you would like to rig.
* Underneath your page's title tag add:
```html
<script src="GRAVITATOES/GRAVITATOES.js"></script>
```

* Then make a call to one of the following functions:
```javascript
blowtato();//FOR A SHORT BURST
```
Use cases of blowtato() may include: your page's onload event, or tied to a button click event.

```javascript
snowtato();//FOR SNOWING POTATOES
```
Snowtato also doubles up as a substitute for the rain effect. Use cases of snowtato() may include: your page's onload event, or tied to a button so that users may trigger the snow as they please.

```javascript
cleartatoes();//FOR CLEARING ALL THE POTATOES
```
This terminates the potatoes for maximum user experience. Some visitors may not take kindly to a website with potatoes, so this option is provided. 

*  The easiest implementation of GRAVITATOES is to add the following in your pages onload event:
```html
<body onload="snowtato();">
```
This is the recommended use case.

### That's it! Your website is now rigged with potatoes!

GRAVITATOES are based on the critically unclaimed desktop app [RELEASE_THE_POTATOES](https://alienmelon.itch.io/goodtatoes). An app that inundates your desktop with potatoes! This is the latest in potatoware. [Click here](http://potatoware.alienmelon.com/) to visit the website and learn more about it! 
