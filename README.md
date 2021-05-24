
# Rocket-Elevators-JavaScript-Controllers

This project aims to simulate the operation of elevators in a residential building using object orientation.
To test the function of the project, it is necessary to make some simulations.
For example:
Scenario 1:
In a building with 10 floors and two elevators.
If one elevator is on the 2nd floor and the other is on the 6th floor.
A user is on the 3rd floor and needs to climb to the 6th floor.


## Scenario01
```
let column = new Column(1,10,2)
column.elevatorsList[0].currentFloor = 2
column.elevatorsList[1].currentFloor = 6
column.requestElevator(3, 'up')
column.elevatorsList[0].requestFloor(7)
```
## Result:
```
Elevator 1 is at floor 3
Door 1 opened.
Door 1 closed.
Elevator 1 is at floor 4
Elevator 1 is at floor 5
Elevator 1 is at floor 6
Door 1 opened.
```