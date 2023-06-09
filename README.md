Download Link: https://assignmentchef.com/product/solved-comp2421-project-4
<br>
In this project you will implement a solution of a very common issue: how to get from one town to another using the shortest route.

You will design a solution that will let you find the shortest paths between two input points in a graph, representing cities and towns, using Dijkstra’s algorithm. Your program should allow the user to enter the input file containing information of roads connecting cities/towns. The program should then construct a graph based on the information provided from the file. The user should then be able to enter pairs of cities/towns and the algorithm should compute the shortest path between the two cities/towns entered.




Attached a file containing a list of cities/towns with the following data:

Field 1: Vertex ID of the 1<sup>st</sup> end of the segment

Field 2: Vertex ID of the 2<sup>nd</sup> of the segment

Field 3: Name of the town

Field 4: Distance in Kilometer




Please note that all roads are two-ways. Meaning, a record may represent both the roads from feild1 to field2 and from the road from feild2 to feild1.




You are required to implement a program to help finding the shortest path between 2 points in the provided file as follows:

<ul>

 <li>Read the file segments.txt and load the data</li>

 <li>Enter 2 points to compute the shortest path between them</li>

 <li>Print the route of the shortest distance to a file called “route.txt”  Exit</li>

</ul>




The user should have the ability to find the shortest path of different pair of cities. Meaning, after finding the shortest route between the A1 and B1, the user can enter other cities, B1 and C1, to get the shortest path between them.