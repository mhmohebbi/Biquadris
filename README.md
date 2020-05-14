# Biquadris
A remade model of Tetris, part of final project for CS246 - Object Oriented Programming (UW course) 

This repository is about the Biquadris Project which was the final project for CS 246. It received a final mark of 104.6 The source code is available to view upon request, but is not open to the public due to Policy 71 of the University of Waterloo.

This game was written in solely C++ and is composed of 51 .cc and .h files. These modules followed the principles of couopling and cohesion which are essential to allowing this code to be reused and modified in the future for the addition of more features. This modularization also reduces recompilation as 1 change in a certain file likely won't have a huge affect in terms of dependecy for other files.

Below is the UML Diagram for this project was built.

<img width="1585" alt="Screen Shot 2020-05-13 at 11 42 55 AM" src="https://user-images.githubusercontent.com/46338325/81834528-0b02c380-950f-11ea-8a3b-487781d57fd8.png">



The game itself has a graphical user interface that was made using the XWindows library as well as a console interface.

![image](https://user-images.githubusercontent.com/46338325/81883950-9490b080-9564-11ea-808f-feec9fe9fad0.png)



It is also a two player game, hence the name Bi-Quadris, where the two players take turns placing thier blocks and the first person to lose, loses. The rules and workings are very similar to Tetris where players can move left, right, and to rotations. Filling a row clears it, and overfilling the game board causes the player to lose. Players also have the option to play 5 different levels, each of which bringing their own difficultues. 
![image (1)](https://user-images.githubusercontent.com/46338325/81884063-dcafd300-9564-11ea-9c3a-55b74a7c2feb.png)



In terms of bonus features, upon clearing two rows players can cause a special effect on the other player. Below is the 'Blind' effect which essentially blinds a portion of the board with black squares until the player drops their piece.
![image (2)](https://user-images.githubusercontent.com/46338325/81884112-f6511a80-9564-11ea-8171-8e62b8d289f5.png)



The game keeps track of highscores and allows the players to continue multiple games and restarting after a loss.
![image (3)](https://user-images.githubusercontent.com/46338325/81884139-0c5edb00-9565-11ea-8185-4276d8fca87a.png)


