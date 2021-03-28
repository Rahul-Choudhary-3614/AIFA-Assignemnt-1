# AIFA-Assignemnt-1
This is our solution to Electric Vehicle Routing Problem

Required Libraries  
1) numpy
2) collections
3) pandas
4) itertools
5) argparse

How to run the code on terminal


python3 Optimal_Algorithm.py  --n <node 1> <node 2> <distance between the nodes 1 and 2> --n <node 3> <node 4> <distance between the nodes 3 and 4> --num_cars <no of cars> --c <source of car> <destination of car> <init_battery of car> <Max_battery of car> <charging_rate of car > < discharging_rate of car > < Average speed of car> 
 --c <source of another car> <destination of another car> <init_battery of another car> <Max_battery of another car> <charging_rate of another car > < discharging_rate of another car > < Average speed of another car> 
                                  OR 
python3 Heuristic_Algorithm.py  --n <node 1> <node 2> <distance between the nodes 1 and 2> --n <node 3> <node 4> <distance between the nodes 3 and 4> --num_cars <no of cars> --c <source of car> <destination of car> <init_battery of car> <Max_battery of car> <charging_rate of car > < discharging_rate of car > < Average speed of car> 
 --c <source of another car> <destination of another car> <init_battery of another car> <Max_battery of another car> <charging_rate of another car > < discharging_rate of another car > < Average speed of another car> 
  
Initially the user has to define the graph. This is done by using  --n <node 1> <node 2> <distance between the nodes 1 and 2> --n <node 3> <node 4>. The user can as many as edges of the graph using this line multiple times (like above example will add two edges to the graphs)

Next Comes the num_cars which take no of cars as an input and next comes -c <source> <destination> <init_battery> <Max_battery> <charging_rate > < discharging_rate> < Average speed> which is used to provide the details of the cars. Using the line multiple times the user can provide details of all the cars (like above example will add details of two cars)
  
Note: In case of optimal algorithm the time of execution increases way more times with increase in no of cars and no of edges in graphs so if you use no of cars greater than than 4 then wait patiently untill the execution is completed. 
