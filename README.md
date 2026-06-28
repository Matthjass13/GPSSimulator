# GPS Navigation System
## Project Description
The goal of this project is to model a real-time GPS navigation system that maximizes traffic control in contemporary cities. In a graph structure, the system depicts intersections as nodes and roads as edges. Admin users can modify travel times according to actual traffic conditions, like congestion or road closures, and users can use Dijkstra's algorithm to determine the shortest path between two points.
For improved scalability and maintainability, the system is constructed using SOLID principles. Multiple users can connect at once, send path requests, and get real-time updates thanks to its client-server architecture. The server keeps the most up-to-date and accurate road network while processing user inputs.

<img width="538" height="274" alt="Image1" src="https://github.com/user-attachments/assets/dc1611c7-3f23-4911-aa9b-5ebd9a3305fa" />
<img width="345" height="308" alt="Image2" src="https://github.com/user-attachments/assets/cb446045-f7fd-4c95-9d0f-68fd63f782f9" />

## Features
- **Graph Representation**: Roads are edges, intersections are nodes, and each road is assigned a travel time.
- **Shortest Path Calculation**: Uses Dijkstra’s algorithm to calculate the shortest route between two points.
- **Dynamic Travel Time Updates**: Admin users can update travel times due to traffic jams, accidents, or road closures.
- **Client-Server Architecture**: Supports multiple users and ensures data consistency with real-time updates.
- **Concurrency Control**: Handles multiple user connections and simultaneous requests.
## How to run
Open the project your favorite IDE. Run the Server class, then a client Class to simulate the connections between the two.
## Access
You can access the full project documentation and source code via the following link:
[Project Report](FinalReport.pdf)
