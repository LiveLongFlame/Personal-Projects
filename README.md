# A* Path Finding

THis is my python A* path finding algorithm. 

The code lets you place a start node (SN) and a end node (EN) as well as a bunch of walls (W) inbetween. 

Once the user has placed the SN  and EN the program will calulate the shortest path. 

It calulates the shortest path by giving each square a total score. 

The total score is created by finding the distance between the SN to the square and the distance from EN to the square , and combines the total. 
The aim is to find the lowest score possible between each square. 

Then once the program has found out the shortest path it will go and highlight the path in pruple 
