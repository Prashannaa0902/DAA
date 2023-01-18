# DAA

// In the given case 
                
                PRIMS:
                
                  The shortest path using Prims algorithm will work as the first case will itself be the best case in finding the shortest path at the minimal cost.
 The minimum cost acheived using prim's algorithm is 8. The code and the output of the same is attached.But generally , Prims algorithm fails to work for directed graphs as not every node will be reacahble from a given node.
 
 distances from a to other nodes : 
 
 A - B : 3
 A - C : 2
 A - D : 6
 A - E : 1
 
                KRUSKALS:
                
                   In the given case , kruskals wont succed in finding the shortest path with the use of minal cost. The basic idea behind kruskals is that it chooseS the edge with the shortest length. But the given graph contains a negative weight , it will get confused in selecting the shortest path between -5 and 1 . So kruskals algorithm wont succeed in finding the shortes path for the given graph.Also, generally Kruskals algorithm wont work for diRected graph as all the nodes in the graph may or may not be reachable from a particular node ( of any choice ).
                   
                 DIJSKTRAS:
                 
                   For this given case , Dijsktras fails to give us the shortest path as this algorithm generally fails for negative weights. Lets say when all the nodes are visited starting from the source node , the shortest path is taken ignoring the negative weight or penalizing it to infinty. But if we include the negative weight , the shortest path might change leading to a even better and optimised path than the one provided b y the dijsktras algorithm . So at this point this dikjstras algorithm fails to give an optimial solution for the shiortest path .
                   
                   
                   On a whole , to get the optimal shortest path , the most preferred Algorithm is Bellman ford .
                   
                
                
                   

