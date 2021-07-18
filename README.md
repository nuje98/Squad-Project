# Squad-Project (Parking Lot System)

## Problem Statement
We own a parking lot that can hold up to ‘n’ cars at any given point in time. Each slot is given a number starting at one increasing with increasing distance from the entry point in steps of one. We want to create an automated ticketing system that allows our customers to use our parking lot without human intervention.
When a car enters the parking lot, we want to have a ticket issued to the driver. The ticket issuing process includes:- 
- We are taking note of the number written on the vehicle registration plate and the age of the driver of the car.
- And we are allocating an available parking slot to the car before actually handing over a ticket to the driver (we assume that our customers are kind enough to always park in the slots allocated to them).

The customer should be allocated a parking slot that is nearest to the entry. At the exit, the customer returns the ticket, marking the slot they were using as being available.

Due to government regulation, the system should provide us with the ability to find out:-
- Vehicle Registration numbers for all cars which are parked by the driver of a certain age,
- Slot number in which a car with a given vehicle registration plate is parked. 
- Slot numbers of all slots where cars of drivers of a particular age are parked.

## Requirements
Python must be installed on the system. The code is compatible with Python3

## Running the Application
1. Clone the repository / Download the source code
2. Open the src directory in terminal
```python
cd ActivityRoundProject\src
```
3. Run the app.py file
```python
python app.py <input file location> 
```
## Running the application on replit
<img src="/snapshots/replit_input_test.PNG" alt="Input Test Case Snapshot" />

## Run the sample test case
```python
python app.py C:\Users\admin\Desktop\ActivityRoundProject\inputs\sample\input.txt
```
<img src="/snapshots/input_test.PNG" alt="Input Test Case Snapshot" />

## Run the extra test cases
4 test cases are present in inputs\test_suite. You can run them using the similar commans as input test case. Jus t type the correct path.

## Run the unit test file
```python
python unit_testing.py
```
<img src="/snapshots/Unit_test.PNG" alt="Unit Test Cases Snapshot" />

## Use-Case Diagram
<img src="/UML/use_case.PNG" alt="Unit Test Cases Snapshot" />
