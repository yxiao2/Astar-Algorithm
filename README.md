# Astar-Algorithm
An update of the Astar algorithm will be posted here

The <strong>Connecting Distance</strong> determines the connections from each node to neighbooring cells.  This means that the algorithm is not restriced to 4 or 8-directions (which often is the case in other implementations). In general a longer connecting distance require some more computation time.  

See the following examples for <strong>Connecting Distance</strong> varying between 1, 4 and 8;

<img src="https://github.com/EinarUeland/Astar-Algorithm/blob/TestRnd/Figures/ASTARSHOWCon1.png"   width="430" height="323"> <img src="https://github.com/EinarUeland/Astar-Algorithm/blob/TestRnd/Figures/ASt3arC1.gif"   width="430" height="323">

<img src="https://github.com/EinarUeland/Astar-Algorithm/blob/TestRnd/Figures/ASTARSHOWCon4.png"   width="430" height="323"> <img src="https://github.com/EinarUeland/Astar-Algorithm/blob/TestRnd/Figures/ASt3arC4.gif"   width="430" height="323">

<img src="https://github.com/EinarUeland/Astar-Algorithm/blob/TestRnd/Figures/ASTARSHOWCon8.png"   width="430" height="323"> <img src="https://github.com/EinarUeland/Astar-Algorithm/blob/TestRnd/Figures/ASt3arC10.gif"   width="430" height="323">


In the above example, the A-Star algorithm needed to explore most cells. Efficiency can be improved by using the <strong>2-sided</strong> solver as seen here;  

<p align="center"><img src="https://github.com/EinarUeland/Astar-Algorithm/blob/TestRnd/Figures/2Sided.gif"   width="430" height="323"> 

<strong>Multiple goal nodes</strong> can be specified. In the below example, there is 3 different goal cells.
<p align="center"><img src="https://github.com/EinarUeland/Astar-Algorithm/blob/TestRnd/Figures/Multiple.gif"   width="430" height="323"> 

An example of use of provided method is the use in <em>Frontier Based Exploration</em>  where the "robot" search for the nearest unexplored cell:
<p align="center"><img src="https://github.com/EinarUeland/Astar-Algorithm/blob/TestRnd/Figures/FRONTIER.gif"   width="430" height="323"> 

See full examlpe video 

![alt text](https://www.youtube.com/watch?v=BUihBGbhfDA&list=UU1A6Jx2ywuj62UYKbIAUcOQ&index=3&t=0s
 "Logo Title Text 1")


-----------------

This code was written for a project, which I have written a paper about: 
http://proceedings.asmedigitalcollection.asme.org/proceeding.aspx?articleid=2655682
This paper provides some more details on the code, and how it can be applied in a practical example. If you use the code for academic work/publishing I will appreciate if you could cite the above paper.



