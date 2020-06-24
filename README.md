# About zipcodebase
Zipcodebase was founded in 2019 to solve common issues with location data. As we have launched geocodeapi.io, a general geocoding API for forward and reverse geocoding, we learned from our customers, that that there was a specific need for zip code data. Our customers were basically looking for a simple solution to do tasks: 

calculate the distance between zip codes
find zip codes around a given zip code
find a major location behind a zip code
match together a list of zip codes by their distance to each other

This was the moment we decixded to launch zipcodebase.com, a feature-complete zip code API. 

The API uses keys to allow access to the API. You can register a free API key at our developer portal: https://app.zipcodebase.com/register?plan=free. This will allow you to conduct 10 000 free searches per month. 

#Endpoints &amp; Examples:
(All links can be copied to your browser for testing, simply replace "YOUR-APIKEY", with your personal key)

##postal code to location information
This endpoint allows you to receive information for one or multiple given postal codes.

https://app.zipcodebase.com/api/v1/search?apikey=YOUR-APIKEY&codes=10005%2C51503

##Distance calculation between postal codes
This endpoint allows you to calculate the distance between one and another (or multiple) postal codes.

https://app.zipcodebase.com/api/v1/distance?apikey=YOUR-APIKEY&code=10005&compare=10006%2C10007&country=us

##postal codes within a radius
This endpoint will convert a list of submitted postal codes into a list of postal code pairs that are located within a given distance to each other.

https://app.zipcodebase.com/api/v1/radius?apikey=YOUR-APIKEY&code=10005&radius=100&country=us

##postal codes within a certain distance
This endpoint returns a list of postal code pairs that are within a given distance to each other.

https://app.zipcodebase.com/api/v1/match?apikey=YOUR-APIKEY&codes=10005%2C10006%2C10009%2C90001&distance=100&country=us


##postal codes by city
This endpoint returns a list of postal codes based on a city.
https://app.zipcodebase.com/api/v1/code/city?apikey=YOUR-APIKEY&city=New%20York&state_code=NY&country=us


##postal codes by state
This endpoint returns a list of postal codes based on a state.

https://app.zipcodebase.com/api/v1/code/state?apikey=YOUR-APIKEY&state_code=NY&country=us



#Documentation
Our full documentation can be found here: https://app.zipcodebase.com

#Need help?
Do not hesitate to contact our support team that will help to get you started.

#Legal
The use of zipcodebase API is subject to our terms & conditions.
