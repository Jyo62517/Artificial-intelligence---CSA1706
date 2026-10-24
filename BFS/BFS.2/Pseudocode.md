BEGIN

Create the graph using an adjacency list.

Define BFS(START).

Initialize VISITED as an empty set.

Initialize QUEUE with START.

WHILE QUEUE is not empty, DO

a. Remove the first node from QUEUE.

b. IF the node is not in VISITED, THEN

     i. Print the node.

     ii. Add the node to VISITED.

     iii. FOR each NEIGHBOUR of the node, DO

             IF NEIGHBOUR is not in VISITED, THEN
                 Add NEIGHBOUR to QUEUE.
             END IF

          END FOR
c. END IF

END WHILE

Call BFS(1).

END
