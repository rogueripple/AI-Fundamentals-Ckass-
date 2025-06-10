# AI-Fundamentals-Class

## Traveling Salesman Route Optimization

This project implements a solution to the Traveling Salesman Problem (TSP) using real-world geographical data from Kenya. The implementation includes:

- Route optimization between multiple cities
- Real-time distance calculations using OpenRouteService API
- Interactive map visualization with animated car movement
- Detailed route analysis and distance reporting

### Features

- Calculates all possible routes between cities
- Finds the shortest route using real driving distances
- Visualizes the route on an interactive map
- Shows animated car movement along the optimized route
- Displays detailed distance information for each possible route

### Requirements

- Python 3.x
- Required packages:
  - folium
  - openrouteservice
  - matplotlib
  - numpy
  - pandas

### Usage

1. Install the required packages:
```bash
pip install folium openrouteservice matplotlib numpy pandas
```

2. Run the script:
```bash
python TravelingSalesMan_RouteOptimization.py
```

3. View the results:
- Check the console output for route analysis
- Open 'optimized_route_map.html' in a web browser to see the interactive visualization

### Current Implementation

The current implementation includes routes between:
- Nairobi
- Meru
- Nyeri
- Nandi
- Kericho

The program calculates the optimal route starting and ending in Nairobi, considering real driving distances between cities.
