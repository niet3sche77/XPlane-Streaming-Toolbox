# XPlane-Streaming-Toolbox

## Project Description ##

This project will serve as a companion dashboard and standalone set of Python scripts designed to ease streaming of X-Plane to Twitch.


## Proposed Core Features ##

* Plane type/designation
* Route/Flight Plan
* "Nearest" VOR/RNAV/Waypoint display
	* When approaching an airport:
		* Give the airport ICAO code if it "looks like" landing/takeoff is happening;
		* If it looks like landing is happening, guess runway


### DataRef Requirements ###

* Plane type / text description
* Flightplan
* "Near" DataRef
	* "Airport" Data:
		* ICAO code
		* TPA (if none, 1,000' AGL for single prop; 1,500' AGL for turbo & multi-prop & jet traffic)
		* Airport runways


## Proposed "Stretch" Feature ##

* KML (?) GoogleMaps plugin data layer--can save/replay flight paths.
	* Look at SkyVector's API--do they have a custom data layer?
