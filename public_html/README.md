# SkyAware 4.0 Features

## Customize display via URL query strings

Syntax: <ip_address>/dump1090-fa/?parameter=value

Examples:

    http://<ip_address>/dump1090-fa/?sidebar=hide

    http://<ip_address>/dump1090-fa/?altitudeChart=hide

    http://<ip_address>/dump1090-fa/?rangeRings=hide

    http://<ip_address>/dump1090-fa/?ringCount=3&ringBaseDistance=100&ringInterval=50

| Parameter | Possible Values |
| :---------: | :---------: |
| banner  | show/hide |
| altitudeChart | show/hide |
| aircraftTrails | show/hide |
| map | show/hide | 
| sidebar | show/hide | 
| zoomOut | 0 - 5 | 
| zoomIn | 0 - 5 | 
| moveNorth | 0 - 5 | 
| moveSouth | 0 - 5 | 
| moveWest | 0 - 5 | 
| moveEast | 0 - 5 | 
| displayUnits | nautical/imperial/metric |
| rangeRings | show/hide | 
| ringCount | integer |
| ringBaseDistance | integer |
| ringInteval | integer | 



## New World/US/Europe Basemaps and Overlays

Click the OpenLayers icon on the bottom right of the map to select baselayers and overlays

## Ability to show/hide columns in the aircraft table

The "Select Columns" button on the aircraft table allows you to choose which columns to show for your preferred display
