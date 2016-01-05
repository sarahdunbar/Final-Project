#Erdgeschoss



## Choose Your Own Adventure Game

Introduction: Set in a fantasy world, this game uses a combination of actions, stats, and a turn counter to 
determine the user's fate. It is structured as an open adventure where the user can type their action, such as 
"open" or "n". The final version is available on runpython, within this document, and is entirely text based.

Commands/Turncounter: This program functions through keyboard input. The commands are as follows:
* n - north (-)
* e - east (-)
* s - south (-)
* w - west (-)
* u - up (-)
* d - down (-)
* l - look 
* i - inventory
* drop - drop object (-)
* grab - grab object (-)
* open - open object (-)
Any object may be operated on by the user, regardless of how unhelpful it is. If the user does not enter a 
correct command, the program will prompt them to do so. 
In addition, the program employs a turn counter, with the player having 40 turns to complete the game.
. Some actions require turns, and some do not. The ones requiring
turns have a (-) beside them. If the object is incorrect for drop, grab, or open, the turncounter will not reduce 
a turn. If the user enters an invalid command, the turncounter will also not cost a turn.

Extra Resources: As this game heavily relies on rooms and directions, a map will be provided to the user
so they do not get confused. No other resources are used.

Accessable Online: Yes
Text: Yes
User Input: Yes
Graphics: No

"""
This document should become the functional specification of the project you are working on.

A functional specification describes in great detail how a device or program will appear to an
outside user. That is, it treats all hardware as a "black box", the contents of which are completely
unknown to the user. The functional specification should include sections with the following information:

Your specification **should include** the following types of information:

* A title. Replace the title at the beginning of this document.
* Summary or introduction. In general, in a few lines or less, what is your program about or what is it about?
* How does the user access your program? Is it shared via http://runpython.com? Is a web site? Embedded in 
  a single board computer? 
* If there are graphics screens involved, describe every screen that the user will experience: what is it for? 
  What did the user have to do to get there and how does she move on to the next?
* For each graphics screen, describe every active control input and what it does. What elements on the screen will
  change in response to user input?
* Does the program respond to mouse input? What, exactly, does the mouse do?
* Does the program respond to keyboard input? How?
* What graphical assets will be used?
* Does the user have to do anything to install the program?

Your specification should **not** include the following types of information:

* The language you will use to create it.
* Names of any specific files in the project.
* How you will structure the classes, functions and code in your program.
* The name of any files or tools that you will use to design the program.
"""
