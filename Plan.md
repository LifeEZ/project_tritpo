### Содержание
  1. [Introduction](#1)
  2. [Testing object](#2)
  3. [Risks](#3)
  4. [Testing aspects](#4)
  5. [Testing approaches](#5)
  6. [Presentation of results](#6)
  7. [Conclusion](#7)

<a name="1"></a>
### 1. Introduction
  This file contains a test plan for the ** Aptrgangr ** game. The main purpose of testing is to validate the application against the SRS.

### 2. Test object
Test object - game ** Aptrgangr **.
The application must have certain quality attributes:
   
   1. Functionality:
+ functional completeness: the application is obliged to perform all declared functions in accordance with the SRS;
+ functional correctness: the application must perform all the declared functions;
+ functional feasibility: there are no undeclared functions that would prevent the application from performing the originally assigned tasks.

2. Ease of use:
+ intuitive interface: controls are intuitively predictable on the screen;

<a name="3"> </a>
### 3. Risks
Risks include the following points:
* Possible acceleration of gameplay by increasing the frame rate

<a name="4"> </a>
### 4. Testing Aspects
Testing aspects include the implementation of the main functions of the application:
* operability of menu and display
* performance of game mechanics
* crafting system

#### Functional requirements:

##### Character cntrol
This use case should be tested for:
1. Display of the list of the craftable objects
2. Correct display of available resources  
3. Correct display of animations of gathering

##### Game mechanics
This use case should be tested for:
1. Procedural generated terrain
2. Procedural placed objects
3. Resource gathering

##### Interface Menu
This use case should be tested for:
1. Correct display of the interface
2. Interface update
3. Clickability of buttons

#### Non-functional requirements:
1. Intuitive interface
2. Intuitive controls

<a name="5"> </a>
### 5. Testing approaches
Every aspect of testing has been done through system testing.
System testing is testing a program as a whole.
Each test is done manually.

<a name="6"> </a>
### 6. Presentation of results
Test results are presented in [table] (./Results.md).

<a name="7"> </a>
### 7. Conclusions
This test plan allows you to test the main functionality of the application.
Successful passing of all tests may indicate that the application
meets all the stated requirements and works stably.
