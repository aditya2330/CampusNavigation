## CampusNavigation
An interactive campus navigation system built using OpenStreetMaps and Python's Folium library. This project allows users to view a mapped layout of university buildings and find the shortest path between two selected buildings.

Features:
- Interactive Map: Displays a detailed map of the university campus with accurately marked buildings.
- Shortest Path Finder: Allows users to search for the shortest route between any two buildings on campus.
- Custom Layers: Overlays building locations and paths on OpenStreetMaps using GeoJSON and coordinates.
- User-Friendly Interface: Easily select starting and destination points with real-time updates on the shortest path.

Technologies Used:
- OpenStreetMaps: Provides the map base layer for the campus layout.
- Folium: Used to create and style interactive maps.
- GeoJSON: For marking building locations and paths with coordinate-based layers.
- Python: Backend scripting to process locations, paths, and handle map rendering.

How It Works:
- Mapping Buildings: Used Google Maps and Google Earth to get exact coordinates of campus buildings.
- GeoJSON for Marking: Applied GeoJSON to create CSV files for layering building locations on OpenStreetMaps.
- Pathfinding: Predefined paths allow users to view the shortest route as a dynamic, dotted line on the map.

Future Enhancements:
- Add real-time GPS tracking for dynamic navigation.
- Integrate with mobile devices for on-the-go navigation.
