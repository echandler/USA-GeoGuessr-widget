# USA GeoGuessr widget
Interactive USA map widget for GeoGuessr.com. When the player correctly selects the state that the location is in the state will be highlighted on the widget automatically with an additional confetti animation for good measure.

### How to use:
* Install greasemonkey or tampermonkey.
* Create a new script and delete the default contents.
* Copy everything in src.user.js to the new script and then save the script.
* Reload the GeoGuessr website.

### Instructions:

* Move widget: Hover pointer over the USA widget, hold the left mouse button down and drag it around.
* Resize widget: Hover the pointer over the USA widget and rotate the scroll wheel on your mouse, easy peezy.
* Toggle state color: Click on the state with left mouse button.
* Enable debugger mode: Hold shift over an icon and a window will popup with coordinates and other info.

Disclaimer: The free geolocation service that the extension uses has a hard time with locations next to borders, especially in rural locations. If it doesn't highlight the state automatically the player would need to click on the map manually to select it. Also, the code depends on the GeoGuessr source code, which I have no control over, so if the Geoguessr code changes it could break this script. If it stops working for some reason check back and see if the code has been updated.
