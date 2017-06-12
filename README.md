## About

Underscores, Bootstrap, and Sass.
# StarterTheme WordPress Theme

http://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html

## Installation

- Download the hurststrap folder from GitHub or from hurststrap.com
- Upload it into your WordPress installation subfolder here: `/wp-content/themes/`
- Login to your WordPress backend
- Go to Appearance → Themes
- Activate the StarterTheme theme

## Developing With npm, Bower, Gulp and SASS and [Browser Sync]

### Installing Dependencies
- Make sure you have installed Node.js, Bower, and Browser-Sync on your computer globally
- Then open your terminal and browse to the location of your StarterTheme copy
- Run: `$ npm install`
- Run: `$ bower install`
- Run: `$ gulp copy-assets`

### Running
To work and compile your Sass files on the fly start:

- `$ gulp watch`

Or, to run with Browser-Sync:

- First change the browser-sync options to reflect your environment in the file `/gulpfile.js` in the beginning of the file:
```javascript
var browserSyncOptions = {
    proxy: "localhost/", // Ex. "startertheme.dev/"
    notify: false
};
```
- then run: `$ gulp watch-bs`

## How to Use the Build-In Widget Slider

The front-page slider is widget driven. Simply add more than one widget to widget position “Hero”.
- Click on Appearance → Widgets.
- Add two, or more, widgets of any kind to widget area “Hero”.
- That’s it.

[1] Visit [http://browsersync.io](http://browsersync.io) for more information on Browser Sync