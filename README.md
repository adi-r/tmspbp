Travelling Management System using Preferential Behaviour Patterns

The principle behind this project is the usage of preferences while travelling to book the required ticket using minimal effort from the client and at the same time, requiring less time to make the decision.

Let's take an example. Supposing you want to book a flight from City A to City B. Now when you type in the required parameters such as Destination. Source and Date of Journey etcetera, what most travel websites or travel companies do is give you the entire list of flights available on that particular day. Our project takes things a step further by using the preferences given by the customer to filter this list, thereby reducing the amout of time required to traverse/browse the given options. The said "preferences" are input by the customer during the creation of his/her account. The list of preferences include an array of priority values which determine how important a certain factor while travelling. The priorities include the choice of travelling during the day/night, Budget range etcetera. 

We've also tried developing a travel paackage generator which compiles a transportation option through various cities using the preferences of the client.

FUNCTIONING:
1) Say you want to book a flight from Dehradun to Delhi (cities in India). So what the program does is read the flightdb.csv, checks if any flight is present in the .csv file that satisfies the given parameters and prints it out. 
2) The package generator takes certain parameters from the user like Source, Destination, Stops in between, the dates on which the customer wishes to depart from a particular city etcetera. The program again reads all the .csv files and concocts a travel package which is written into another .csv file.

PROS: 

1) The program works. 
2) It uses C language, so its simple enough to understand.

CONS: 
1) The program uses static databases. It reads the data from a .csv file. You could build upon this by creating a web crawler that explores various travel websites and returns the realtime values of different travel options.
2) We've taken a bunch of preferences from the user to filter out the options. But in reality we've only implemented the use of two or three preferences to filter out the results. You can take the time to add more preferences.
3) The package generator works to an extent. It uses the idea of taking a expected budget from the client and generating a travel package that comes as close as possible to the expected price value.
4) The code is written badly. We haven't used functions where we should have, so there's alot of repeated code.
