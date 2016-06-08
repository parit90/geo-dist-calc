# geo-dist-calc

 * CreatedOn- 07/06/2016
 * 1.sourcePoints is an object containing latitude,longitude of a one point(start point).
 * 2.destinationPoints is an object containing latitude,longitude of a another point(end point).
 * 3.Get the latitude and longitude of both the points.
 * 4.Get the Radius of earth which is approximate to 6371 km.
 * 5.calculate the difference of two lat long.
 * 6.apply the ‘haversine’ calculation.

	# Installation
	npm install geo-dist-calc
	
	var distance = require('geo-dist-calc');
	
	var sourcePoints = { latitude: 32.123, longitude: 43.21 };
    	var destinationPoints = { latitude: 67.331, longitude: 56.214 };
	var ResultantDistance = distance(sourcePoints,destinationPoints);
	// ResultantDistance will be in km
