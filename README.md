# elvis_plugin_refresh_timer

## Installation
- Download or clone this plugin
- Place it inside the `plugins/active` folder
- Scan your elvis for new plugins
 - Go to the elvis management console
 - Go to panel plugins
 - Click "Scan Elvis for plugins"
![Example](https://media.discordapp.net/attachments/588451250123833382/694874223822504026/unknown.png)

This plugin makes use of an txt file inside the `data/elvis/config/` folder. By default that file is `saved-links.txt`. If you would like to change that file, you may want to update the default value of the file used in the panel plugin. Go to the `index.html` file of this plugin and change the path variable on line 15.

Open the panel and press the play icon to start the timer. The interval can be changed by clicking on it typing something else, or use your up and down arrow keys. To stop the timer press the stop button.

To save a current search, press the green save button, and fill in a unique nickname for your search. Click on a saved search to use that search.

The list of search terms is linked to your username.
