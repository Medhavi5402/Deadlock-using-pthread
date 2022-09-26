# Deadlock-using-pthread
This program uses pthread and mutex to implement Banker's algorithm.

Input: There are 2 variables m and n which represent the number of resources and number of processes resprectively which the system asks for initially.
After providing the values of m and n there are three arrays Available, Max and Allocation which indicate the no. of available resources, maximum demand of each process and no of resources of each type currently allocated to each process respectively.

Once all the information reagarding the system and it's resources is provided we obtain the output.

Output: Taking into account all the resources using the Banker's Algorithm the system decides whether the system will enter into a safe state or an unsafe state or whether a deadlock condition occurs or not.
