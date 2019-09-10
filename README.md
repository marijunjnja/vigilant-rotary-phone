# vigilant-rotary-phone

## space tracker

#### consoleTracker.js
This file runs a tracker that updates every 10 seconds in the terminal.
Modify <code>const myPosition</code> to that of your location and then run
    node consoleTracker.js


### server.js
This file will run the tracker in the browser, currently it will only show the first distance acquired from the API and write it to the browser. Server would need to be restarted every time a new distance is desired. This will be fixed along with adding geolocation to not have to manually input coordinates
