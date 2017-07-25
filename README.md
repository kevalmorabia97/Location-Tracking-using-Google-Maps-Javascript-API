# Location-Tracking-using-Google-Maps-Javascript-API
This was a part of my project during my internship at WATConsult, Mumbai
<br>![Image](https://mrcheerful.000webhostapp.com/Maps-Bus-Tracking.PNG)
<br>Here the red marker on the path is current location and A and B markers are starting and ending locations respectively.

To use this location tracting project, you will have to get an API Key from google: https://developers.google.com/maps/documentation/javascript/get-api-key

You will have to use a gps module to get the location and then update latitude and longitude in _location.php_ file.
<br>The _maps.html_ file continuously fetches location from _location.php_ file at intervals of 5 sec and move the marker to that position.
