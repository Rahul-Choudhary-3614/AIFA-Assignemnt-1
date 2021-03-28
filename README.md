# AIFA-Assignemnt-1
This is our solution to Electric Vehicle Routing Problem                                                                                                            
Problem Statement-
Consider a city network where we need to route a set of electric vehicles which may require to be charged during its journey from some source to some destination. 
Letus assume that we have n cities(v1, v2, . . . , vn)and the distance between cities vi and vj be eij(if two cities are not connected directly then eij=∞ and eij=eji).
Assume that each city has a single charging station which can charge one EV at a time. Consider a set of k EVs namely P1, P2, . . . , Pk.                                  
For each EV the following information is provided - 
(a)Sr- source node              
(b)Dr- destination node             
(c)Br- battery charge status initially                
(d)cr- charging rate for battery at a charging station (energy per unit time)               
(e)dr- discharging rate of battery while traveling (distance travel per unit charge)               
(f)Mr- maximum battery capacity                
(g)sr- average traveling speed (distance per unit time).                      
Assume that all vehicles start their journey at t= 0 and Pr reaches its destination at t=Tr. We need to route all the vehicles from their respective sources to
destinations such that max{Tr} is minimized. You need to develop both optimal as well as heuristic algorithms.          
