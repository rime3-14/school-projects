# Delivery Route Planner

**INSA Lyon · 4A semester 1 · Team H24**

The planner takes a street graph and a pickup-and-delivery request as XML. It finds paths on the graph with Dijkstra's algorithm, then uses a TSP-based search to sequence stops while respecting pickup-before-delivery constraints. A Leaflet interface shows routes on the map.

I worked on time-aware route optimization and built route sheets for one or more couriers. A courier can inspect the ordered stops and export a route sheet as CSV.

The TypeScript application builds, imports sample map and delivery XML, and serves its map and route-sheet pages. All 20 Jest tests pass. The team source repository is private.
