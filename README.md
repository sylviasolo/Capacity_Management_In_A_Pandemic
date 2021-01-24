# CovidSimulation
This code runs a Hospital system, by allowing patients with various severities to enter with a Poisson/constant rate and Poisson/constant service rate. 
It has various departments : Emergence Department (low and high priority queues), Clinic and a COVID special clinic. 
Patients enter each of these facilities randomly and based on their offer times, decide which facility they want to join. 
Finally, we can do a complete analysis of the system : How many patients left, with what severity and from which department, what is the distribution
of their wait times, their service times etc.

Inputs : lambda, service rates
outputs : Analysis of the required component of the system (or full)
