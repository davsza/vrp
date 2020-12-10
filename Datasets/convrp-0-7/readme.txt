This set of 5 day Consistent VRP Problems are formatted in TSPLIB format.
These are randomly generated derived from the well-known Christofides
instances where each customer has a probability of p=0.7 of being 
visited on each of the 5 days.  

The NODE_COORD_SECTION gives the locations and the distances are Euclidean.
There is a 1 unit service time whenever a customer is visited.  

The DEMAND_SECTION indicates the days that a customer requires service. A
-1 indicates that the customer requires no service on that day.  If a 
customer is visited, then we use the demand given for that customer in the
original Christofides instance.




The instances are extensions of the ConVRP benchmark dataset of Groër et al. (2009). Those are available at http://www.rhsmith.umd.edu/faculty/bgolden/vrp_data.htm. The modifications to the original dataset only concern the visit frequency. So, the probabilities of a customer to be visited on each of the 5 days were set to p=0.5 and p=0.9, respectively. The instances are structured as follows: The header gives instance parameters like number of customers, planning horizon, vehicle capacity and maximum travel distance. The NODE_COORD_SECTION gives the coordinates for all customers. The DEMAND_SECTION gives the demand of each customer on each day. Service times are listed in the SVC_TIME_SECTION. Finally, the depot coordinates are given in the DEPOT_SECTION. 
