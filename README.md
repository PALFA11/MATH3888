# MATH3888

## Things to do for the overlapping nodes idea:
1. Calculate centrality measure for nodes within each cluster, without considering edges that connects to the outside of the cluster (maybe)
2. Sort out the anchor thing for each cluster
3. Run trials to determine overlapping nodes/"drifters"
4. Use profilers to eliminate irrelevant ones
5. Calculate ratio and define a ratio as "good" such that we consider it an appropriate path to go down
6. Determine the path to go down based on ratio which can be considered as edges of a graph
7. Repeat Step 5 to continue constructing edges
8. If a previously visited community/"drifter" or a dead end is reached, choose another path with good ratio to go down or backtrack to previous nodes with appropriate paths
9. Explore all appropriate paths
10. Output the resulting graph

