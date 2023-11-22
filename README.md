# Google Maps Example
For [topic 2218764](https://gathering.tweakers.net/forum/list_messages/2218764): A demonstration of a simple Google map with display of customers by group (in this case "partner").

Note that this is old code that I dug up and quickly patched up to work in a modern browser. **Unfortunately I am unable to offer any support on this 'project'**

## Quickstart

* [Get yourself a Google API key](https://developers.google.com/maps/documentation/javascript/get-api-key) and make sure it is enabled/activated.
* Put the API key in the [`index.html`](https://github.com/RobThree/MapsExample/blob/3a40d2d378f258ca448222b01f2104201fb471b6/index.html#L11) file as indicated.
* The markers are based on the partner-id; you will want to change the [`getMarker`](https://github.com/RobThree/MapsExample/blob/3a40d2d378f258ca448222b01f2104201fb471b6/index.html#L207) method to something of your liking

## Known bugs / issues

* After changing the group selection ("partner" in this case) you need to click outside the "dropdown" to update the map. This should be [an easy fix](https://github.com/RobThree/MapsExample/blob/3a40d2d378f258ca448222b01f2104201fb471b6/index.html#L281)
