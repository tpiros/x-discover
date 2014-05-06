# Custom Polymer element for geo based attraction discovery

Inspired by <a href="http://ebidel.github.io/geo-location/components/geo-location/" target="_blank">Eric Bidelman's geo-location</a>

To see this demo in action please register for a <a href="https://foursquare.com/developers/apps" target="_blank">FourSquare OAuth key</a>. Once done, update <code>x-discover.html</code> file with the right client ID and client secret keys (<a href="https://github.com/tamaspiros/x-discover/blob/master/x-discover.html#L32-L33">line 32-33</a>).

## Installation
Simply execute <code>bower install</code> from the project folder

## Usage
Add the custom <code>&lt;x-discover></code> tag to your HTML page (along with the necessary Polymer libraries).  Make sure that you run your index.html from a server (the easiest way if you're on a UNIX environment is to execute this Python command to enable an HTTP server fo the current directory: <code>python -m SimpleHTTPServer</code>) Also make sure that you allow the geo location to be detected by your browser.

## More info
<a href="http://tamas.io/x-discover-another-polymer-element/">http://tamas.io/x-discover-another-polymer-element/</a>