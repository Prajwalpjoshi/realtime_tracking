# realtime-tracking
 
1.Check if the browser supports geolocation.
2.Set options for geolocation:
-Enable high accuracy.
-Set a 5-second timeout.
-Avoid using cached location data.
3.Use watchPosition to track the user's location continuously.
4.Emit latitude and longitude via a socket.
5.Initialize a map using Leaflet.
6.Create an empty object markers.
7.Receive location data via the socket.
8.Manage markers on the map.
9.Remove marker when a user disconnects.