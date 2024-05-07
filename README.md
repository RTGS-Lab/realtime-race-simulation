# Real-Time Tracking Simulation
This project showcases two simulations: the real-time tracking simulation using SensorLogger data from iPhone and Apple Watch, and the Maple Grove Triathlon Simulation. Both utilize HTML, CSS, JavaScript, and Mapbox GL JS to dynamically display the movements of individuals, demonstrating the potential of real-time GPS tracking for various applications.

The initial simulation leverages SensorLogger data to display real-time movements on predefined routes, testing the integration and functionality of GPS tracking across different devices.

### Purpose and Functionality
- **Dynamic Tracking**: Implements real-time tracking on predefined routes using live data integration to reflect movement dynamically.
- **Multi-Device Compatibility**: Ensures compatibility with SensorLogger on both iPhone and Apple Watch, enhancing applicability across different user devices.
- **User Interaction**: Engages users with dynamic visual tracking, providing a user-friendly interface and interactive tracking capabilities.
- **Tracking Algorithm Development**: Supports the testing and enhancement of algorithms for pace calculation, movement prediction, and route optimization.
- **Scalability and Customization**: Designed to be scalable and customizable, accommodating a range of activities from small group events to large public gatherings.

# Maple Grove Triathlon Simulation
Following the success of the initial real-time tracking tests, the technology was applied to simulate the Maple Grove Triathlon, showcasing detailed participant tracking across swimming, biking, and running segments.

### Features

#### Map Visualization
- **Race Routes**: Visual representation of the triathlon’s swim, bike, and run segments using distinct map layers.
- **Starting Points**: Marks each participant's starting position on the map, providing clear visual indicators for each race segment.

#### Simulation Functions
- **simulateMovement()**: Continuously updates the map to reflect participants' real-time positions and progress along the race route.
- **calculatePace()**: Calculates each participant's pace for different segments based on actual race data.
- **updatePersonLocation()**: Updates participant locations on the map according to their calculated pace and current segment, managing transitions effectively.

## Technical Details

### Integration and Customization
- **Mapbox GL JS**: Used extensively for rendering interactive maps and routes.
- **JavaScript**: Manages map interactions, data updates, and simulation logic in real-time.

### Deployment and Usage
To deploy these simulations:
1. Clone the repository.
2. Open `MGT_v3.html` for the Maple Grove Triathlon or the corresponding HTML file for the initial tracking simulation in a browser supporting JavaScript and Mapbox GL JS.
3. Observe the simulations as they progress, offering insights into real-time movement and participant tracking.

## Conclusion

These simulations not only provide valuable tools for event organizers and participants but also serve as a platform for developing and testing advanced tracking technologies in real-world scenarios.

# Real-Time Race Simulation 

## Overview
This project includes simulations of user activity from SensorLogger and race results from the Maple Grove Triathlon. To achieve this, an HTML document was developed that leverages HTML, CSS, and JavaScript to create a dynamic and interactive visualization of a triathlon race using Mapbox (Mapbox API and Mapbox GL JS).


### Maple Grove Triathlon Simulation
The code sets up map layers and sources to display the race routes, covering swimming, biking, and running segments. Each participant’s starting point is marked on the map with a red circle, and their movement throughout the race is simulated using the `simulateMovement()` function. 
- The `calculatePace()` function calculates each participant's pace for swimming, biking, and running based on their race times and distances. The `timeToSeconds()` function converts time strings into seconds to simplify calculations.
- The `updatePersonLocation()` function updates the location of each participant on the map according to their current race segment and pace, managing transitions between segments effectively.
- The `simulateMovement()` function continuously updates the participants' locations on the map at regular intervals, effectively simulating their progress through the race until all participants have finished.

[View Maple Grove Triathlon Simulation](https://hx7n46.csb.app/)
<br>

<img width="1167" alt="MGT" src="https://github.com/RTGS-Lab/realtime-race-simulation/assets/103837294/5d6756be-e2e1-4190-bcc6-110beacb7756">
