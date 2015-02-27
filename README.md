# ESRI REST Diagnostics

A list of JavaScript bookmarklets that can be used to test ArcGIS Server Map Services through the browser.

## Features

The bookmarklets provided add extra information to the ArcGIS Server REST endpoint pages. They work by scraping the underlying data and adding the results to the current HTML REST Service page. Some of features include:

- Folder level:
  - [Extract Map Service data for each Map and Feature Service in the folder.](https://github.com/raykendo/ESRI_REST_Diagnostics/tree/master/MapServiceData)
  - [Compare Spatial References of all Map and Feature Services in a folder.](https://github.com/raykendo/ESRI_REST_Diagnostics/tree/master/SpatialRefCompare)
- Map Service level:
  - [Extract Layer data for each layer in the service.](https://github.com/raykendo/ESRI_REST_Diagnostics/tree/master/MapLayerData)
  - [Get counts of features and shapes for each layer in the service.](https://github.com/raykendo/ESRI_REST_Diagnostics/tree/master/MapLayerCount)
- Map Service Layer level
  - [Test each field for number of non-empty results.](https://github.com/raykendo/ESRI_REST_Diagnostics/tree/master/FieldTester)
  - [Test each field for content and see how fast the results return.](https://github.com/raykendo/ESRI_REST_Diagnostics/tree/master/FieldTester)
  - [Test each field with a coded value domain to see how many features have each coded value.](https://github.com/raykendo/ESRI_REST_Diagnostics/tree/master/DomainDataCounter)
- Layer Query REST Page
  - [Search REST Services for specific field or text string](https://github.com/raykendo/ESRI_REST_Diagnostics/tree/master/RestSearch)
  - [Adding ArcGIS REST API compliant geometry json to queries, based on a map of the map service.](https://github.com/raykendo/ESRI_REST_Diagnostics/tree/master/GeometryHelper)

Some features in the works
- Query Helper similar to Select By Attributes control in ArcMap
- View a map on the REST Service page.
- More items on request.
  
## Instructions

### Installation

Installation on the browser is as simple as adding a bookmark. From the [bookmarklet.html](https://github.com/raykendo/ESRI_REST_Diagnostics/blob/master/bookmarklets.html) page... 

- Chrome: drag the anchor link to your browser toolbar.
- Firefox: right-click on the link and select "Bookmark this link".
- IE: right-click on the link and select "Add to Favorites".
- Safari: untested.
- Opera: untested.

### Basic Use

Each tool as its own basic use policy. They all involve navigating your web browser to the map service REST endpoint. From there, select the proper bookmark from the bookmark list.

## Requirements

- Desktop browser (IE8+, Chrome, Firefox)
- Security settings that support bookmarklets.
- Access to [ESRI JavaScript API library](http://js.arcgis.com/3.10/).
- Access to an ArcGIS Server REST endpoint in browser.

## Resources

[ESRI JavaScript API](https://developers.arcgis.com/javascript/index.html)

## Contributing

Anyone is welcome to contribute to this project.

## Licensing

This is currently licensed under the MIT Licensing ([See License here](https://github.com/raykendo/ESRI_REST_Diagnostics/blob/master/LICENSE)).