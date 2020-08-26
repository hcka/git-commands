# Project Estimation  

Authors: 
- Gabriele Durantini : s276956
- Antonin Louis Leon Poche : s275011
- Alessandro Pisani : s269274
- Huseyin Cagri Karakus : s279122

Date: 22/04/2020  

Version: v1.0

# Contents



- [Estimate by product decomposition]
- [Estimate by activity decomposition ]



# Estimation approach

<Consider the EZGas  project as described in YOUR requirement document, assume that you are going to develop the project INDEPENDENT of the deadlines of the course>

# Estimate by product decomposition

- NC =  7  
[ User, RegisteredUser, Request, Administrator, GasStation, Fuel, Position ]  
- A =  760/7 = 109 LOC  
[ User=80 , RegisteredUser=200, Request=120, Administrator=150, GasStation=130, Fuel=40, Position=40 ]
- S = NC * A = 760 LOC
- C = 2280 €
- Estimated_calendar_time = 2-3 Weeks

### 

|             | Estimate                        |             
| ----------- | ------------------------------- |  
| NC =  Estimated number of classes to be developed   |                             |             
|  A = Estimated average size per class, in LOC       |                            | 
| S = Estimated size of project, in LOC (= NC * A) | |
| E = Estimated effort, in person hours (here use productivity 10 LOC per person hour)  |                                      |   
| C = Estimated cost, in euro (here use 1 person hour cost = 30 euro) | | 
| Estimated calendar time, in calendar weeks (Assume team of 4 people, 8 hours per day, 5 days per week ) |                    |               


# Estimate by activity decomposition


### 

|         Activity name    | Estimated effort (person hours)   |             
| ----------- |:-------------------------------:| 
| Requirements planning | |
| - Review existing systems| 16 |
| - Identify FR and NFR | 16 |
| - Glossary definition | 16 |
| - UI prototype | 16 |
| Design | |
| - Architecture | 32 |
| - low level components | 32 |
| - Verification - inspection | 32 |
| - Verification - prototype | 32 |
| Test Data | |
| - Coding | 128 |
| - Unit test cases | 64 |
| - Acceptance test cases | 64 |
| - System tests | 192 |
 
### GANTT CHART
![Activities](GUI/Gantt_Chart.JPG) 

