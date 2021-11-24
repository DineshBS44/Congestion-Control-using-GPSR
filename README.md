# Congestion Control using GPSR

- We are aiming at the network congestion problem that exists in the Vehicular Ad Hoc networks(VANETs) in this project. The network routing protocol that scales the best compared to the others when there is a large congestion of nodes (can be assumed as high traffic of vehicles on the road) is the Greedy Perimeter Stateless Routing (GPSR) protocol.

- Here congestion control means that we are able to route the packets from the source to destination successfully even when the congestion of the network is high.

## Simulation tool

- In this project, we simulate the basic GPSR protocol using a software called Omnet++ by using inbuilt libraries to do the same. Then we do our own custom implementation using “Routers” to show the Greedy Phase and Perimeter Phase of the GPSR protocol.

- NS3 is also used for comparing the results of different GPSR improvements such as PA-GPSR (Path Aware GPSR) and MM-GPSR (Maxduration-Minangle GPSR).
