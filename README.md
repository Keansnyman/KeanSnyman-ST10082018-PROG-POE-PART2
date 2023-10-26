Project Name: Prog7312_POE_Part1_ST10082018_V2
=========================================================

 
Author: Kean Snyman - ST10082018
==========================================================

Description:
==============
The Identify Areas game is a Windows Forms Application intended to entertain and educate its users on the Dewey Decimal Classification (DDC) system predominantly utilized in libraries. Through a playful interface, users can match call numbers with their appropriate descriptions. Enhancing the immersive experience, the application showcases background music and a rhythmic "disco" background effect. This is the second part in a three-part project. 

Getting Started
===============

Prerequisites
-------------
1. Windows Operating System
2. .Net Framework

Installation:
-------------
-Open the project in Visual Studio or any compatible IDE.
-Restore the NuGet packages (if needed).
-Build and run the project.

Classes For Part 2:
-------------
MatchingColumnsForm.cs
QuestionGenerator.cs
Form1

How To Play
===============

Main Menu
--------------
-When the application is launched, the main form appears with three buttons, "Replace Books", "Identify Areas" and "Finding Call Numbers(Coming Soon)".
-Click on the "Identify Areas" button to begin the game.

Gameplay
------------
1. Objective 
	- Match the call numbers with their corresponding descriptions from two list boxes

2. Controls
	- Use your mouse to select items from both list boxes.
	- Click the "Start Game" button to initiate the timer and begin matching.
	- Use the "Reset Game" button to restart the game at any time.

3. Features
	- Timer: You have 60 seconds to make as many matches as possible.
	- Lives: You only have 3 lives, so dont make too many mistakes.
	- Music: Background music accompanies the gameplay, which can be toggled using the "Toggle Music" button.
	- Disco Effect: The form's background color changes rhythmically, creating a disco effect. This can be toggled using the "Toggle Disco" button.

4.Scoring
	- Successfully matching items rewards points. The aim is to achieve the highest score within the time limit.

5.End of Game
	- Once the timer runs out or the user runs out of lives, the game stops. You can restart by clicking the "Reset Game" button.
