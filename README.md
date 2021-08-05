## Welcome to Window!

![Window Photo](https://dereklouis.github.io/photos/window/window0.jpg)

Window is a chrome extension that animates the current weather conditions in your city. No words, no numbers, your own virtual window to the outside world.

## Add Window To Your Browser

1. Git clone https://github.com/dereklouis/window

2. In Chrome, go to chrome://extensions, select "Load Unpacked", then navigate to the Widnow directory and select the "dist" folder within it

3. Go to your chrome extensions bar and pin Window

## Video Walkthrough

[![Video walkthrough for Window](https://img.youtube.com/vi/V3NOdydimPk/0.jpg)](https://www.youtube.com/watch?v=V3NOdydimPk)

## Additional Information

Using Axios, Window transforms a GET request to OpenWeatherMap API, into a multi-layered visual rendering. Launch window, and pick your city. Boston, Chicago, Los Angeles, or New York City will render matching skylines, however, any city can be launched with a generic skyline. Once you luanch your city, Window takes the UNIX time for sunrise, sunset, and the moment the code executes, to position the sun on one of 130 possible locations along a progress arc. Once, the sun position has been determined, all other major weather conditions such as day/night, clouds, rain and snow are set.

City selections on Window will persist between sessions thanks to local storage. Want to watch the sunset through your virtual window? Just leave Window open, and it will update once every 60 seconds.
