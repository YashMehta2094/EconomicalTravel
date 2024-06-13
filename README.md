# EconomicalTravel
TravelPlanner is a C++ program designed to help users find the cheapest trip between cities based on given flight details. The program uses a priority queue to implement a variant of Dijkstra's algorithm, efficiently calculating the lowest possible travel cost given specific constraints.

Features:

Stores flight details including flight number, departure city, arrival city, flight cost, and times.

Calculates the cheapest trip from a starting city to a destination city within specified time constraints.

Converts times from HHMM format to minutes since midnight for easy comparison.

Handles multiple queries for different city pairs and time constraints.

After compiling the program, you can run it from the command line. The program will prompt you for input in the following format:

Number of cities

Number of flights

Flight details (for each flight: departure city, arrival city, departure time (HHMM), arrival time (HHMM), 
flight number, price)

Number of queries

Query details (for each query: source city, destination city, earliest departure time (HHMM), latest arrival time (HHMM))
