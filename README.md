# ROAR_Competition

The submission by the BHS Racing team for the Summer 2024 ROAR Competition on the Monza map.

## Unofficial time spread

Time over 10 runs:

- Average: 325.765 seconds
- Fastest: 325.250 seconds
- Slowest: 326.050 seconds

Reliability:

- 10 runs with no crashes
- 20 runs with 2 crashes

## Waypoints

To create new waypoints, you have to run the waypoint_collect.py file and select your starting location, and then drive around the track until you have collected all your desired waypoints. If you only want to do a section, close the Pygame window and the program will save the waypoints you drove.

Then, you can either use these new waypoints as is or splice them into an existing waypoint file with waypointSplicer.py. Running waypointSplicer.py will display a graph of the base waypoint file (the file with the primary waypoints) and the new waypoints you want to substitute in. Click on the end points of the section you want to replace, or double click if you want to replace from that point to the end of the track.
