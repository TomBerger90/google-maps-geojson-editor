
# Google Maps GeoJSON Editor


This project is a simple web page that allows users to create and edit GeoJSON data using the Google Maps JavaScript API. The interface allows users to draw polygons and place markers on the map, and the resulting GeoJSON data is displayed in a sidebar, which is updated in real-time. The GeoJSON data can be manually edited as well, and the changes will be reflected on the map.


![Screenshot](screenshot.png?raw=true)


## Features

- Draw polygons on the map
- Place markers on the map
- View and manually edit the resulting GeoJSON data
- Copy GeoJSON data to clipboard
- Reset all drawings and markers

## Usage

To use this GeoJSON editor with Google Maps, you need to set up your Google Maps API key. Follow these steps:

1. Open the `index.html` file of the project in a text editor.

2. Scroll to the end of the file and find the following code snippet:

```
<script async defer src="https://maps.googleapis.com/maps/api/js?key=API_KEY&callback=initMap"></script>
```
3. Replace "API_KEY" in the code snippet with your own Google Maps API key. Ensure that there are no spaces before or after the API key.

4. Save the changes to the `index.html` file.

After completing these steps, your Google Maps API key will be set up, allowing you to utilize the Google Maps functionality in the GeoJSON editor. Now, you can open the index.html file in a web browser to access the editor and start creating or editing GeoJSON data on the map.
