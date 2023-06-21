Outerplanar graphs must not have K2,3 and K4 as minor ....
1. Forest: Xcfon=2
2. Rings(cyclic chain) : Xcfon=2 for even length, Xcfon=3 for odd length
3. When an acyclic chain is added with rings having odd lengths will reduce the Xcfon from 3 to 2 
4. Complete Bipartite Graph: Xcfon=2
5. Edges that are not part of any ring do not increase the Xcfon when added to an existing graph having Xcfon>1 [We can therefore remove all such edges to find an upper bound of the original graph]
6. Chain of rings formed by connecting one ring to another such that each vertex is shared by at most 2 rings, and 2 rings share at most 1 edge: Xcfon<=3
7. If 2 rings shares more than 1 edge then the structure becomes outerplanar since it contains K(2,3) minor
8. Windmill graph: Graphs that have multiple rings sharing a single vertex but do not share any edges. Xcfon<=3 
9. If the colors of two vertices are fixed and there is an acyclic chain(n>1) then it can always be 3 colorable.
10. Whenever there is a 3-membered ring color all of them are different. [Except in windmill graph]
11. Spiral Graph: Graphs that have multiple rings and share a single vertex and 2 adjacent rings shares an edge.
12. For the spiral graph color the centre with color A (suppose). Color one of its neighbors with A and the other neighbors with B and C alternatively...
