# Network Interdiction Model<br>
### Effective Relocation of resources using Maximal-Minimal flow in Network Interdiction.

## Need of this Model :
> During emergencies like a terrorist attack, people want to get away from
the terrorists and security and help forces(ambulances,etc) want to get as
close to the site as possible in the least amount of time possible.<br>
> More often than not, a single mishap like an accident or roadblock is
enough to cause massive disruptions in the flow of people due to heavy
traffic.<br>
> This enables the terrorists to cause more damage as people take more
time to flee while aid comes slowly.<br>

## Solution Proposed :
1. During emergencies like a terrorist attack, people want to get away from
the terrorists and security and help forces(ambulances,etc) want to get as
close to the site as possible in the least amount of time possible.<br>
2. More often than not, a single mishap like an accident or roadblock is
enough to cause massive disruptions in the flow of people due to heavy
traffic.<br>
3. This enables the terrorists to cause more damage as people take more
time to flee while aid comes slowly.<br>

### Algorithm Used :
> Dijkstra's algorithm (or Dijkstra's Shortest Path First algorithm, SPF algorithm) is a “Greedy Algorithm” which fixes a single node as the "source" node and finds shortest paths from the source to all other nodes in the graph, producing a shortest-path tree.<br>
> Benders decomposition (or Benders' decomposition) is a divide-and-conquer algorithm that divides the original problem into subsets, iteratively solves these subsets adding more constraints till no new constraint can be added.<br>

## Flow of Program :
1. Our program works on the principle of finding the optimal Bender’s cut(arc to be interdicted) at every iteration and then finding the new shortest path from the source to the destination aiming to find how to maximize the shortest path from source(where the aid is coming from) to the destination(where the terrorist attack is taking place) while applying  the least resources possible.<br>

2. This allows us to determine which arcs(roads) the terrorists are likely to interdict so that they can cause maximum disruptions while spending minimal resources. <br>
3. These risky arcs will be reported as arcs whose infrastructure needs to be upgraded to increase interdiction cost or need to be constantly guarded to avoid interdiction.<br>
