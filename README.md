# T-SHAPED-TRAFFIC-LIGHT-CONTROL-USING-VERILOG
We have considered a T - shaped road and heavy load of traffic is present over this road where we must control it using traffic signal. Six cases have been considered here and analyzed using state diagram and state table.
The directions, M1, MT, M2, S, that is been considered for analysis of our problem is shown in the figure 1. 
•	Green light indicates that there is no traffic and there is easy flow of vehicles in that route/direction. 
•	Red light indicates that there is a traffic jam and that route is blocked for the vehicles to move and, 
•	Yellow light indicates that the route has medium flow of vehicles

Time delays for changing from one state to another (shown in Figure 2) is considered as, TMG (from S1 to S2), TY (from S2 to S3), TTG (from S3 to S4), TY (from S4 to S5), TSG (from S5 to S6) and TY (from S6 to S1) and the cycle continues.
The time delays are considered as follows: 
•	TMG = 7 seconds 
•	TY = 2 seconds 
•	TTG = 5 seconds 
•	TSG = 3 seconds 

Until TMG seconds, the signal will remain in S1 state, and after TMG seconds, it will move to S2 state. Until TY seconds it will remain in S2 state and after TY seconds, it will move to S3 state, and so on. After TY seconds, in state S6, it will go back to S1 state and the cycle continues. 

