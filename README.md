Dijkstra's Shortest Path Algorithm Implementation in C
This C project implements Dijkstra's Algorithm to find the shortest path from a single source node to all other nodes in a weighted, undirected graph.
The program uses an Adjacency Matrix to represent the graph structure and weights. The implementation includes logic to find the unvisited node with the minimum distance and correctly update distances through a relaxation process.
**Graph Details:**
The project uses a fixed, weighted graph with 8 vertices (A-H) and the following edges and weights:
(A,B,2), (A,C,5), (B,C,1), (B,D,3), (C,D,2), (C,E,3), (D,E,1), (E,F,2), (D,F,4), (E,G,5), (F,G,1), (G,H,2), (D,H,6)
**Key Features:**
**Graph Representation**: Utilizes a fixed $8 \times 8$ Adjacency Matrix.
**Dijkstra's Logic:** Implements the core algorithm using a visited array and a distance array to track minimal path costs.
**Path Reconstruction:** Uses a parent array to store predecessors, allowing the program to reconstruct and print the shortest path from the source (A) to every other node (including H).
**Efficiency:** The current implementation iterates through all vertices to find the minimum distance, which is suitable for small, dense graphs.
##################################################
**Implementierung des Dijkstra-Algorithmus in C zur Bestimmung des Kürzesten Pfades**
Dieses C-Projekt implementiert den Dijkstra-Algorithmus, um den kürzesten Pfad von einem einzelnen Quellknoten zu allen anderen Knoten in einem gewichteten, ungerichteten Graphen zu finden.
Das Programm verwendet eine Adjazenzmatrix zur Darstellung der Graphenstruktur und der Gewichte. Die Implementierung beinhaltet die Logik zur Bestimmung des unbesuchten Knotens mit der minimalen Distanz und zur korrekten Aktualisierung der Distanzen durch einen Relaxationsprozess.
**Details zum Graphen:**
Das Projekt verwendet einen festen, gewichteten Graphen mit 8 Knoten (A-H) und den folgenden Kanten und Gewichten:
(A,B,2), (A,C,5), (B,C,1), (B,D,3), (C,D,2), (C,E,3), (D,E,1), (E,F,2), (D,F,4), (E,G,5), (F,G,1), (G,H,2), (D,H,6)
**Hauptmerkmale:**
**Graphendarstellung:** Verwendet eine feste $8 \times 8$ Adjazenzmatrix.
**Dijkstra-Logik:** Implementiert den Kernalgorithmus unter Verwendung eines Besuchs-Arrays (visited) und eines Distanz-Arrays (dist), um die minimalen Pfadkosten zu verfolgen.
**Pfadrekonstruktion:** Verwendet ein parent-Array, um Vorgänger zu speichern, wodurch das Programm in der Lage ist, den kürzesten Pfad von der Quelle (A) zu jedem anderen Knoten (einschließlich H) zu rekonstruieren und auszugeben.
**Effizienz: ** Die aktuelle Implementierung iteriert über alle Knoten, um die minimale Distanz zu finden, was für kleine, dichte Graphen geeignet ist.

