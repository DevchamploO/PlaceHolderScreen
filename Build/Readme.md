##########################
How to add it to a webpage:

- Can be embedded in an html file like so:
- First rename this index.html to something like "MaskedSingerPlayer.html"
- then inside the webpage where it's to be hosted, say it's called start.html
	- <iframe src="MaskedSingerPlayer.html" height="<INSERT HEIGHT>" width="<INSERT WIDTH>" scrolling="no" style="border:none;"></iframe>
	- If the iframe needs to be responsive then you can maybe try setting the width and height of the parent of the iframe to be 100%.	

Note: Responsive behavior might change in the actual player, so it's best to stick to a 16:9 ratio for the iframe

############################

How to run it locally:

- Chrome blocks file run webgl builds, they need to be hosted on a local server.
- A simple python -m http.server should take care of that.
- Otherwise it can be run simply by opening it in edge.

####################################
