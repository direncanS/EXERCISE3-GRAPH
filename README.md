# Exercise3-Graph
Shortest path in Vienna's transport network
Program: Shortest Path in Vienna Public Transportation Network

Task:
Work in pairs on the following programming example. The choice of programming language is up to you (C, C++, C#, Java).

Problem Statement: Shortest Path in Vienna Public Transportation Network
Given a graph with weighted edges, develop and implement an algorithm to find the most cost-effective way between two nodes. The graph to be searched is provided through a text file with the following structure. Each line starts with the name of a line in the Vienna public transportation network (only subway and tram), followed by a colon. Then, alternately, a string in quotes (station name) and a number (travel time to the next station = edge cost) follow. There can also be cyclic lines (i.e., stations can be visited multiple times).
Example:
U1: "Leopoldau" 2 "Grossfeldsiedlung" 1 "Aderklaaer Strasse" 1
"Rennbahnweg" 2 "Kagraner Platz" 2 "Kagran" 1 "Alte Donau" 2
"Kaisermuehlen-VIC" 1 "Donauinsel" 2 "Vorgartenstrasse" 1
"Praterstern" 1 "Nestroyplatz" 1 "Schwedenplatz" 1
"Stephansplatz" 2 "Karlsplatz" 2 "Taubstummengasse" 1
"Suedtirolerplatz" 2 "Keplerplatz" 1 "Reumannplatz"

Your Task:
Your task is to write a program named "find_path" that takes three arguments in the following structure:

find_path filename_graph start destination
filename_graph: File containing the graph in the format described above.
start: Starting station.
destination: Destination station.
Your program should first read the graph from the input file and store it in a suitable data structure. Then, execute the algorithm to find the shortest path from the start to the destination and display the found path in a clear format. While the output format is not fixed, it should at least include:

The edges traversed in order and the lines used for each edge.
Where transfers need to be made.
The total cost (travel time) of the path.
