# gpstracker
Esri AppStudio Project to create an application that can continuously read the GPS location of a device and write the data to a Feature Service to update the users specific record.

Desired Outcomes of the Project

Phase 1 Project Requirements
1) Requires a person to login with their ArcGIS Online Account
2) Reads the devices present position NMEA Latitude, Longitude, and Altitude/Elevation
3) Writes the present position data to the device display

Phase 2 Project Requirements adds the following to Phase 1
1) Displays a Map centered on the users present position
2) Tracks the use on a Map in real-time updating ever second
3) Shows direction of travel and speed using an Arrowhead icon 
4) Displays the following information on the device display
    a) Heading
    b) Altitude / Elevation
    c) Latitude
    d) Longitude
    e) Speed MPH_KPG And/Or Airspeed Knots
5) Create a Feature Data Service Layer  
6) Write the ussers location data to a Feature Data Service Layer
7) Allow multiple users to update thier specific record in a shared service layer 
 
Phase 3 Project Enhancements
1) Integrate with Workforce using the predefined project(s)
    a) Display a list of all projects a user has access to
    b) Allow a user to select a specific project to load
    c) Write the users location data to the workers layer
