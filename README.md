# Postman-collections-for-Live-Objects
 
This repository holds a series of postman collections demonstrating a variety of use cases for all of the Live Objects REST APIs. More information about our APIs can be found on https://liveobjects.orange-business.com

These examples have been created for use with the Postman utility. Postman is a testing framework for REST APIs. The tool can be downloaded from www.getpostman.com.

To import the collection, first clone this repository, then open the Postman utility and select the Import option. Select the Folder tab from the dialog and drag and drop the cloned repository folder into the target.

To use our APIs, you will have to subscribe to Live Objects and create an API key (with the accurate rights depending of the use).

To get a free Live Objects go on https://liveobjects.orange-business.com/#/request_account

Then go in configuration tab and create a API key. Finally enter it as mentioned below : 

<img src="https://github.com/DatavenueLiveObjects/Postman-collections-for-Live-Objects/blob/master/Postman-collections-for-Live-Objects.jpg" alt="Postman">

The collections contained in this repository are organized under this scheme:

    REST APIs
        Batch Geocoder API
        Geocoder API
        Map Image API
        Map Tile API
        Places API
        Public Transit API
        Routing API
        Traffic API
        Venue Maps
        Weather API
    Platform Extensions
        Custom Location Extension API
        Platform Data Extension API
        Route Match Extension API
        Waypoint Sequence Extension API

    NOTE: In order to get the postman requests to work, you must replace all instances of the {YOUR_APP_ID} and {YOUR_APP_CODE} variables within the collection and use your own HERE credentials. Within Postman, set the variables using the Manage environments menu.

    You can obtain a set of credentials from the Plans Page on developer.here.com.

See the LICENSE file in the root of this project for license details.
REST APIs

The HERE REST APIs provide a flexible and fast access to a variety of map data and other map data functions. Developers can use the HERE Rest APIs to perform tasks ranging from batch geocode requests and advanced traffic incident reports to creating an isoline route.

    Documentation on these APIs can be found on the developer.here.com portal.

Batch Geocoder API

    Batch Geocode Addresses - Start asynchronously geocoding a large set of addresses in one batch
    Batch Geocode Job Status - Request the status of a batch geocoder job
    Batch Reverse Geocode Locations - Start asynchronously reverse-geocoding a large set of locations in one batch
    Download Geocoded Data - Download a zipped geocoded dataset from a completed job

Run in Postman Download Collection
Geocoder API

    Geocode a Street Intersection - Request the latitude, longitude and details of a street intersection
    Geocode an Address within a Bounding Box - Request the latitude, longitude and details of an address restricting results to a specific area
    Geocode using free-form input - Request the latitude, longitude and details of an address based on free-form text input
    Geocode using partial address information - Request the latitude, longitude and details of an address based on partial address information
    Multi-reverse Geocode Addresses - Request the addresses of up to one hundred locations with one multi-reverse geocoding request
    Multi-reverse Geocode Landmarks - Request the nearest landmarks for up to one hundred locations with one multi-reverse geocoding request
    Reverse Geocode Landmarks - Request details of landmarks near to a given latitude and longitude
    Reverse Geocode an Address from a Location - Request address details for a given latitude and longitude
    Reverse Geocode the District containing a Location - Request details about the district containing a given latitude and longitude
    Reverse Geocode the Shape of a Postal Code - Request the shape of a postal district for a given latitude and longitude
    Suppressing Response Attributes - Request only the latitude, longitude for a given address

Run in Postman Download Collection
