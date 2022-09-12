# Zuul Game - Console Application
*[IntelliJ Ultimate IDEA IJ-App06-Zuul Project](https://github.com/BNU-CO452/BlueJ-Apps)*

## Description
*The student should write a description of their specific game, including how the game can be won or lost*     

This game is based on the classic console based game  *Colossal Cave Adventure* by Will Crowther (1975) see
  
* [Colossal Cave Adventure Short Play](https://www.youtube.com/watch?v=sfGrPM5Bxeo&ab_channel=FridayNightArcade)     
* [Colossal Cave Adventure Play Through](https://www.youtube.com/watch?v=O3etkSoHrR8&ab_channel=GladeSwope)      
* [Colossal Cave Adventure Clone GitHub Repo](https://www.youtube.com/watch?v=UFu1WGJP6rQ&ab_channel=RedHatDeveloper)  
* [GitHub Repository](https://github.com/tvall43/open-adventure)   
* [Play the Game](https://grack.com/demos/adventure/)

## User Requirements
*The student should replace the general user requirements below with a full set of specific user requirements of their chosen game* 

You have been tasked with creating a new small version of Zuul to use as proof of concept.  
For this purpose you game should contain a minimum of 8 locations.  
The game prototype must include the following new features:-
1. Add a Player object with status including 2 attributes such as energy level and a score.
2. A set of Items that the player can pick up and use (minimum of 4)
3. A Map object that contains a set of at least 8 interconnected locations
4. An increased set of recognised commands (minimum of 2 additional commands)
5. A clear single objective with a way of winning the game, and losing the game.

Students can work in teams of 2 for this application.

## Zuul Locations
*The student should replace this simple diagram to show how all the locations in the new game connect*
![Zuul Starting Locations](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/Zuul-00.jpg)

### Use Case Diagram
![Use Case Diagram](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/App06%20Use%20Cases.jpg)  

### UML Class Diagram (20 marks for 10 classes)
*The student should replace this class diagram with a full class diagram of their completed game showing attributes and methods* 

The design must be an extension of this basic design which is based on the [Command Design Pattern](https://refactoring.guru/design-patterns/command).
Using this pattern each **Command** is a kind of **ZuulCommand** (inheritance) and is responsible for executing that command.

![Basic Design](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/App21-06%20Classes.jpg)

*The student should include a more detailed Class Diagram *

## Black Box Testing 
*Each member of the team must product at least 10 Black Box tests and a minimum of 20 in total*
| Test No | Proposed Test | Data Entered | Expected Result | Actual Result | Comments |
|:---:|-----|------|------|------|------|    
| 01 | South from Valley  | "Go South" from valley | Enter Slit |  | |    
| 02 | West from Valley | "Go West" from valley | No exit message |  | |    
| 03 | Wrong Direction | "Go Home" from valley | Go where? message |  | |    
## Game Walkthroughs (Testing 40% of total)

*To test the game the student must produce one example walkthrough of playing the game such as the one shown below, and demonstrate a walkthrough live.
These walkthroughs should include*

1. Going into each of the rooms
2. Winning the game
3. Loosing the game
4. Picking up each item
5. Using each item
6. Using each command word
7. Updating the player status and score
   
![Example Game](https://github.com/BNU-CO452/BlueJ-Apps/blob/master/images/Zuul-01.jpg)

## Programming Issues
*Each member of the team must have posted at least 5 issues and a total of 10 issues*

## Application Evaluation
*An evaluation with list of at least 5 ways the game can be improved or extended.*