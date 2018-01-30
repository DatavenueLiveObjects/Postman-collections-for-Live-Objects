# Postman-collections-for-Live-Objects
 
This repository holds a series of postman collections demonstrating a variety of use cases for all of the Live Objects REST APIs. More information about our APIs can be found on https://liveobjects.orange-business.com

These examples have been created for use with the Postman utility. Postman is a testing framework for REST APIs. The tool can be downloaded from www.getpostman.com.

To import the collection, first clone this repository, then open the Postman utility and select the Import option. Select the Folder tab from the dialog and drag and drop the cloned repository folder into the target.

To use our APIs, you will have to subscribe to Live Objects and create an API key (with the accurate rights depending of the use).

To get a free Live Objects go on https://liveobjects.orange-business.com/#/request_account

Then go in configuration tab and create a API key. Finally enter it as mentioned below : 

<img src="https://github.com/DatavenueLiveObjects/Postman-collections-for-Live-Objects/blob/master/Postman-collections-for-Live-Objects.jpg" alt="Postman">

The collections contained in this repository are organized under this scheme:

    Live Objets training APIs
        Push Data from LoRa devices API
        Rule Engine API
        Device Management API
        Debug mode API
        Requests on Datazone API
    Live Objets Event Processing Examples
        Example with geo-zones
        Example with state changes
       


<h2><a href="#batch-geocoder-api" aria-hidden="true" class="anchor" id="user-content-batch-geocoder-api"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><a href="/heremaps/postman-collections/blob/master/batch-geocoder.postman_collection">Batch Geocoder API</a></h2><ul>
<li><strong>Geocode a Street Intersection</strong> - Request the latitude, longitude and details of a street intersection</li>
<li><strong>Geocode an Address within a Bounding Box</strong> - Request the latitude, longitude and details of an address restricting results to a specific area</li>
<li><strong>Multi-reverse Geocode Landmarks</strong> - Request the nearest landmarks for up to one hundred locations with one multi-reverse geocoding request</li>
<li><strong>Reverse Geocode Landmarks</strong> - Request details of landmarks near to a given latitude and longitude</li>
<li><strong>Reverse Geocode an Address from a Location</strong> - Request address details for a given latitude and longitude</li>
<li><strong>Reverse Geocode the District containing a Location</strong> - Request details about the district containing a given latitude and longitude</li>
<li><strong>Reverse Geocode the Shape of a Postal Code</strong> - Request the shape of a postal district for a given latitude and longitude</li>
<li><strong>Suppressing Response Attributes</strong> - Request only the latitude, longitude for a given address</li>
</ul>
<p><a href="https://app.getpostman.com/run-collection/4f968ce760f14ed986dc" rel="nofollow"><img src="https://camo.githubusercontent.com/271662c7525b6d3c5e9f88206b3dcc06bfa73a6d/68747470733a2f2f72756e2e7073746d6e2e696f2f627574746f6e2e737667" alt="Run in Postman" data-canonical-src="https://run.pstmn.io/button.svg" style="max-width:100%;"></a>  <a href="/heremaps/postman-collections/raw/master/geocoder.postman_collection"><img src="https://camo.githubusercontent.com/b496d914a355bd579dadffe09d7b07b078446e7a/68747470733a2f2f686572656d6170732e6769746875622e696f2f706f73746d616e2d636f6c6c656374696f6e732f696d672f646f776e6c6f61642e737667" alt="Download Collection" data-canonical-src="https://heremaps.github.io/postman-collections/img/download.svg" style="max-width:100%;">
