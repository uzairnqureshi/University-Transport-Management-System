# Bus Transportation Management System
This is a C++ program for managing the fuel consumption and distance travelled by buses in a fleet. It also performs related tasks such as calculating fuel costs, sorting the data, and generating reports. The program is intended for use by the fleet manager of a bus transportation service.

## Features
The program provides the following features:

1. Finding the total fuel consumption and distance travelled for each bus.
2. Find the average fuel efficiency for each bus and display its details.
3. Find the bus with the highest fuel efficiency and display its details.
4. Calculating the total fuel cost for each bus and the average speed for each bus.
5. Calculate the total fuel consumption and distance travelled for all buses in a month.
6. Calculate the total revenue generated by the bus transportation service for a given month based on the number of passengers and the fare charged per passenger.
7. Find the bus with the lowest fuel efficiency and display its details.
8. Sorting the data based on specific criteria, such as sorting by bus number or fuel efficiency.
9. Error handling for invalid user inputs, such as non-numeric values, negative numbers, and out-of-range values.
10. Data validation to ensure that fuel consumption and distance travelled values are within reasonable ranges.
11. User authentication to restrict access to the program to authorised personnel (Fleet Manager) only.
12. User-friendly interface with simple and intuitive menus.
13. Console background colour and text colour change functionality.
14. Loading screen display for each function or screen, with a progress or working bar showing the percentage.
## Functions
The program provides the following functions to perform various tasks:

1. readData: The system reads in daily fuel consumption and distance traveled figures for each bus from the user and stores them in a multi-dimensional array.
2. totalFuelConsumption: Returns the total fuel consumption for a given number of days and a given bus number.
3. totalDistanceTraveled: Returns the total distance travelled for a given number of days and bus number.
4. minFuelEfficiency: Returns the bus number with the lowest fuel efficiency.
5. avgFuelEfficiency: Returns the average fuel efficiency for a given bus number.
6. maxFuelEfficiency: Returns the bus number with the highest fuel efficiency.
7. totalFuelCost: Returns the total fuel cost for a given number of days and bus numbers, based on the fuel price per gallon.
8. avgSpeed returns the average speed for a given bus number, based on the time taken to travel the distance.
9. fleetSort: Sorts the data based on specific criteria, such as sorting by bus number or fuel efficiency.
10. LoadingBar: Displays a loading or progress bar while executing a function or screen.
11. printData: Prints out the daily fuel consumption and distance travelled figures for each bus.
## Usage
Run the executable file in a console or terminal window to use the program. The program will prompt the user for input and display menus for each task. Enter the appropriate values and choices as prompted by the program. The program will handle errors, validate input, and display loading bars or progress bars during task execution.

## Credits
Uzair Qureshi developed this program as an assignment for the Programming Fundamentals course. It uses the C++ programming language and standard libraries and incorporates ideas and concepts from various sources, including online tutorials, documentation, and forums.
