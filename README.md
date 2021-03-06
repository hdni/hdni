# hdni
A modification of [Faience](http://tiheum.deviantart.com/art/GTK3-Gnome-Shell-Faience-255097456) with different window decorations, matching Firefox userChrome, and other tweaks. Made for GNOME 3.6. [See the preview](http://hdni.github.io/rice/assets/faience_preview.png).

## Installation
### GNOME Shell, GTK 2 & GTK 3, Mutter
* Put the entire repository in `/usr/share/themes/`
* You can then use the Tweak Tool to set the themes.
* It is safe to remove the firefox.css file from the directory.

### Firefox
* Install the [Stylish](https://addons.mozilla.org/en-US/firefox/addon/stylish/) extension.
* Install the [FXChrome](https://addons.mozilla.org/en-US/firefox/addon/fxchrome/) theme.
* Go to your [Add-ons Manager](about:addons), select the User Styles page and then write a new style.
* Give the style a name and paste the contents of firefox.css.
* Set the tabs to be on the bottom. You can do so in [about:config](about:config) by setting `browser.tabs.onTop` to false.
* This style works well with the [Movable Firefox Button](https://addons.mozilla.org/en-us/firefox/addon/movable-firefox-button/), [Favicon Restorer](https://addons.mozilla.org/en-us/firefox/addon/favicon-restorer/?src=search), and [Hide Tabbar](https://addons.mozilla.org/en-us/firefox/addon/hide-tabbar/?src=ss) extensions.
