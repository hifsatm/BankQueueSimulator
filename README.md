# BankQueueSimulator
Java program of a queue simulator that simulates people coming into a bank or ships coming to a port and waiting to be served in turn. In this project, I used the LinkedList&lt;E> class, that is predefined in Java language. 


The java simulator must request 2 inputs: 
-	Number of minutes to run for (duration of simulation), and
-	Number of available queues.

Rules:-
1.	Every queue has its own server (teller/dock). 
2.	When a new client comes, it will join the queue with the least number of clients. 
3.	Every client will have a random service time between 2 and 5 minutes (depends on required service).
4.	Clients arrive to the place with a frequency between 5 and 30 seconds, Therefore, you must use a random number between 5 and 30 to know when to generate a new client.

The simulation runs for the entered number of minutes. Every few seconds (depends on the frequency) a new client arrives and enters the queue with the least number of clients. 

Once the simulation time is over, no more clients arrive, but the ones that are already in the queues must be served. Once all the queues are empty, the simulation stops.

The objective of the simulation is to get data from all 3 possible scenarios (1, 2, or 3 queues), and determine which one is better. The data that should be collected is:

- Served clients and service time per each queue and to
- Overall average service time
- Total number of served clients

