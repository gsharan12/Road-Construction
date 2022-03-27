# Road Construction
 OS Project

### PROBLEM STATEMENT
 The project titled ROAD CONSTRUCTION USING HIGHWAY PLANNING AND OBSTRUCTION PREVENTION aims to address one of the major issues that the Indian road construction department is facing. These days we notice that a large number of roads are not in proper condition and many of them require restoration. Many of which are in high usage and require immidiate repair. Our project aims to help athorities with providing them the most profitable path for road contruction for a given map and the sequence in which these roads can be addressed so that it would be convenient for both the authorities as well as the general public.Our project collects various forms regarding the map for the road that needs to be constructed, with this data we find the most shortest and profitable path possible . Then we collect data for utility and traffic for all the roads ,then we normalize the data collected and generate a appropriate sequence in which the road construction should be addressed. We have also included a deadline section so that the roads that take more then the allocated time are highlighted and if necessary removed. Also, a check for hindrance detection is added which can be used when we have limited number of resources and a proper allocation of these resources is required. For this we take inputs for resources which can refer to asphalt, machinery, mortar etc. Then we require maximum resources needed for each road, amount of resources allotted for each road, and available resources, based on which a safe sequence is generated that prevents any unwanted stoppage of work.

 ### ALGORITHMS USED
1) DIJAKSTRA ALGORITHM FOR FINDING SHORTEST PATH FOR ROADS
2) DIJAKSTRA ALGORITHM FOR THE MAP(GRAPH)
3) PRIORITY SCHEDULING WITHOUT PREEMPTION
4) BANKERS ALGORITHM TO GENERATE A SAFE SEQUENCE

 ### EXPLANATION

1) First we take inputs for the number of roads
2) Then we will take inputs for the formation of map in form of graph for all the different
roads
3) Then based on the graph we will apply dijakstra algorithm and find the shortest distance
possible between the desired cities
4) This distance is saved as a parameter of size for the roads
5) Also the route of the shortest path will be displayed
6) Then we read the utility, traffic and deadline for all the roads
7) Based on these inputs we check for clashing between the priorities
8) If present the clashing is handled
9) Then the required sequence is generated
10) Based on the sequence we find the waiting and completion times for the roads
11) Now we check if the roads can be completed within their allocated time
12) If deadline is crossed then an error message “DEADLINE NEEDS TO BE
COMPROMISED IS DISPLAYED”
13) If dead line is not passed the generated sequence is displayed and we move to the second
part of project
14) Here we read the number of resources needed for each road,maximum resources needed
for each road, amount of resources allotted for each road, and available resources
15) Based on which a safe sequence is generated
16) If sequence is not generated then an error message is displayed


### 8. Conclusion

The proposed model is highly recommended as it successfully implements all the ideas that
were initially put forth. The main purpose was to find out order in which a group of roads are
mended or constructed so that within short time and correct resources, the roads are dealt
with, without any ambiguity, prioritizing the important ones over the others. So in this way
we get an ideal sequence for a large set of construction processes ongoing in the entire
country which would not have been possible to deal with manually .The designed model is
also able to find the most profitable route for the road construction whose map was given to
us. By applying dijkstra algorithm to this map we were able to find the profitable route for
construction .The model is also able to checks the safe sequence based on the data available
to the authorities, whereby it says if the certain available resources is enough for the safe
mending of all the given roads.


Now we discuss that The reason to implement Priority Scheduling over the other methods is
to ensure that the correct purpose is met and solved. In the given scenario, using other
efficient algorithms like Shortest Job First is not feasible because the prior knowledge of
every parameter is not sometimes possible because continuous damage of various other roads
is possible in real life, and hence they will keep adding to the list making it impossible for
roads of higher priorities to get completed. Also, the interruption of a going on task and
resuming of others, while resuming the first one later is not possible in this scenario because
an important road cannot wait forever once mending it has been started. The traffic and utility
of that particular road does not allow it to wait for others. Hence, the best possible algorithm
for the implementation was Priority Scheduling.