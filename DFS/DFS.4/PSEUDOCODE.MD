BEGIN

Create a graph using an adjacency list.

Define DFS(NODE, VISITED).

IF NODE is not in VISITED, THEN

a. Print NODE.

b. Add NODE to VISITED.

c. FOR each NEIGHBOUR of NODE, DO

      Call DFS(NEIGHBOUR, VISITED).

  END FOR

END IF

Call DFS(A, empty set).

END
