# Realtime Race Simulation 

## Overview
This project will take an iterative approach to data collection and prediction focused on using wearable and cell phone data to predict human mobility and health.

This project includes simulations of user activity from SensorLogger and race results from the Maple Grove Triathlon. To achieve this, an HTML document was developed that leverages HTML, CSS, and JavaScript to create a dynamic and interactive visualization of a triathlon race using Mapbox (Mapbox API and Mapbox GL JS).

### Maple Grove Triathlon Simulation

The code sets up map layers and sources to display the race routes, covering swimming, biking, and running segments. Each participant’s starting point is marked on the map with a red circle, and their movement throughout the race is simulated using the `simulateMovement()` function. 
- The `calculatePace()` function calculates each participant's pace for swimming, biking, and running based on their race times and distances. The `timeToSeconds()` function converts time strings into seconds to simplify calculations.
- The `updatePersonLocation()` function updates the location of each participant on the map according to their current race segment and pace, managing transitions between segments effectively.
- The `simulateMovement()` function continuously updates the participants' locations on the map at regular intervals, effectively simulating their progress through the race until all participants have finished.
