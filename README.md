# Stochastic-Scheduling-With-LBBD

This repository contains the problem instances used in our paper
Stochastic Planning and Scheduling with Logic-Based Benders Decomposition.

Please refer to the description below for detailed description of each instance.
In our computational study, we use the first k scenarios to solve the instances that has k<500 scenarios. 
We adjust probabilities accordingly (i.e., 1/k).

    Line 1: 'rnd'
    Line 2: Number of tasks
    Line 3: Number of facilities
    Line 4: Number of scenarios
	Next array: Release times of the jobs (the size of the array is given 
		in line 2.)
	Next array: Deadlines of the jobs (the size of the array is given 
		in line 2.)	
	Next array: Capacities of the facilities (the size of the array is given 
		in line 3.)	
	Next array: Probabilities of the scenarios (the size of the array is given 
		in line 4.)			
    Next array of arrays: Fixed costs of assigning tasks on facilities.
		(The first line is the cost of assigning each task on facility 1.)
		
    Next array of arrays: Consumption of capacities of tasks on facilities.
		(The first line is the consumption of each task on facility 1.)		
		
    Next array of arrays: Mean processing times of tasks on facilities.
		(The first line is the mean processing time of each task on facility 1.)
			
    Next array of arrays of arrays: Processing times of tasks on facilities under
		different scenarios.
		(The first line is the processing time of task 1 on facility 1 
		under different scenarios,
		 The second line is the processing time of task 2 on facility 1
		under different scenarios.)

We use the instance in "makespan" folder in Tables 1-4 and EC1-EC2, 
"makespan-alternate-processing-times" in Table 5,
"fixed-cost" in Table 6, and "tardiness" in Table 7.
