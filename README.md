# bts-colours
An exploration into finding dominant colours using BTS album covers

## Project Ambitions
### Data Processing
* to better understand the use of k-means to identify dominant colours in images (using BTS album covers as images, all album covers saved from [official BTS discography](https://ibighit.com/bts/chn/discography/index.php))
* the k in k-means should preferably be dynamically determined
	* method decided upon: silhouette score elbow analysis (for clearer indication as compared to distortion elbow analysis and ease of programming)

### Front-End ([hosted on glitch](https://map-of-bts-colours.glitch.me))
* first-timer implementation of vue to create a Single Page Application (SPA) with better understanding of:
	* computed variables
	* calling of methods
	* v-cloak
	* binding of styles

## Front-End Version Information
* 0.0.0: bare minimum with little styling and just getting dropdown choice to change album cover and colour display
* 0.0.1: minor style changes - mainly to change font colours in bar representing colours to ensure that text are visible against its background
* 1.0.0: major style changes - the background changes its gradient based on the colours of the selected album and the colour of fonts also changes according the background colour (if background is light, font should be black and vice versa)