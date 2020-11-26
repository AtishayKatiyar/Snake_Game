# Snake Game

Abstract
This project summarizes the development of a Snake Game using the
graphics library in C and lays an emphasis on the detailed usage of the
concepts of computer graphics. The main objective of the project is to
execute the concepts of computer graphics and figure out how to execute
them in a practical work while getting negligible error. We also need to
analyse the error we encounter during the progress of the project.
Computer Graphics is the branch of computer science that deals with
generating images with the aid of computers. Today, computer graphics is a
core technology in digital photography, film, video games, cell phone and
computer display, and many specialized applications. A great deal of
specialized hardware and software has been developed, with the displays of
most devices being driven by computer graphics hardware. It is a vast and
recently developed area of computer science.
This project aims to bring the fun and simplicity of the classic snake game
with some new features using the graphics library in C. The game includes
multiple levels with varying difficulties and complex mazes where the
length of the snake increases when it eats the fruit and the game ends when
we lose the 3 lives on colliding with the maze objects that spawn in the later
levels. We have chosen this particular project as it revolves around the
usage of basic and advanced tools of computer graphics. This project
challenges us to execute on a practical level, our learnings from the subject
and work on the project as a team thus developing on our team building
skills.
Contents
Abstract i
1 Introduction 1
1.1 Motivation. 2
2 Background Details 3
3 Project Details 4
4 Game Interface 8
5 Testing and Evaluations 14
6 Results 16
7 Conclusions 17
Some Coding Functions and their Proofs 18
References 21
Code File 21
1. Introduction
This project is the perfect example of a computer game written in C language
based on the classic game called ‘Snake’ which has been around since the
early days of home computing and then re-emerged on early feature phones. It
is not a very complex game but does give an idea of what can be achieved
with a relatively simple program using Computer Graphics, and perhaps the
basis by which to extend the principles and create more interesting games.
The main goals are:
● To reinforce many of C and its programming concepts.
● To get valuable experience of design and implementation of a large
problem.
● To provide a framework of a more challenging, and thus rewarding,
exercise.
1.1 Motivation
The motivation for the project comes from the curiosity and the passion to
learn new and challenging things and create exciting projects using
computer graphics. It is unbelievable what all can be achieved using
computer graphics. Advances in computer graphics have transformed how
we use computers. Computer graphics has given us the "mouse" input
device, the computer-aided design system used to create the Boeing 777,
the ability to visualize molecular dynamics and other scientific phenomena,
the animation used in educational software and the advertising and
entertainment industries, and virtual reality systems whose applications
range from architectural prototyping to surgical training to entertainment.
Therefore, the need and curiosity to learn and apply the principles of
Computer Graphics motivated us to create this game.
2. Background Details
The project will be using the principles of Computer Graphics. It makes
you learn about the concepts of programming in C.
The main aim of the project is to create a Snake game that allows users to
control the movement of a snake on a screen, score points for eating food
and avoiding running into the maze objects. In this game, we want to write
a code where a graphical representation of a snake moves across the screen.
When it encounters a piece of food, the snake grows longer and we gain 20
points. If it hits the maze objects, we lose a life, eventually dying if we lose
all 3 lives. So, the objective of the game is to collect the dots (food) and
avoid the obstacles (maze objects). As you collect food, the snake gets
longer. When you have collected enough food, you progress onto the next
level, where your snake moves at a faster speed. The game will also keep a
track of your highscore.
Prerequisites include an understanding of general programming concepts
along with the fundamentals of Computer Graphics. Good understanding of
the graphics library in C is really important for the development of this
project.
3. Project Details
In this project, we want to write a game where a graphical representation of
a snake moves across the screen. When it encounters a piece of food, the
snake grows longer and we gain points. If it hits the maze objects, we lose a
life and die if all 3 lives get exhausted.
To write this program we are going to need:
● A way of representing the snake
● A way of representing the food
● A way to display the score
● A way to display the remaining number of lives
● A way for our instructions to reach the snake
● And a way to know when we’ve run into something and died
Here are the requirements (functional requirements) for how the snake
moves.
1. The snake must appear to move around the screen.
2. The snake must turn in response to user input.
3. The snake will increase in length if it eats food.
4. The snake will die if it runs into the maze objects.
5. The snake never stops moving.
To keep the game interesting,
1. The snake must move at a speed fast enough to be interesting but slow
enough to control.
2. The code must make use of the graphics library (curriculum
requirement).
The snake moves in a very precise way. Based on what the user inputs, the
snake will move in a given direction. Each time the snake moves, the head
will go in the new direction, and every piece of the snake will move up, by
occupying the space that was formerly occupied by the piece in front of it.
To grow in size, the snake has to eat food. How can we show the snake
eating? The simplest answer is that if the head of the snake and the food are
in the same place, we consider that the snake eats the food. This means that
we have to know where the food is. When it’s eaten, it disappears, the
snake grows, and the food shows up somewhere else randomly. The
coordinates of the food are part of its variables and it has a function move,
which will move it to a different place. To make the game interesting, we
probably want this to be a random location, which means that we'll have to
make sure that our program can generate random numbers. But we also
want to show a score, so we need a variable to keep track of that as well. In
this case, we’ll create a High Score function as well.
Let's look at how a program to run the whole game might look:
1. Draw the playing area with a bounding rectangle, set the counter to zero
and display it.
2. Draw the snake in a starting position.
3. Draw the food in a starting location.
4. On user input, change snake direction.
5. Move the snake one move.
6. If the snake is over food, eat it, increase the score, increase the snake
length, move the food,
7. else if the snake is over a maze object, subtract a life.
8. Go back to 4.
9. Until the snake loses all 3 lives and dies.
We didn’t talk about what makes the snake die. The snake eats when the
food and the snake’s head are in the same place. In a game, we refer to that
as collision detection. Although the objects didn’t really collide, in a
real-world sense, they are in the same place and we can perform actions
based on this. We’re going to use collision detection to see when the snake
runs into a maze object, which means that we’re going to have to keep track
of the head of the snake within our program. Just because something is
drawn on the screen doesn’t mean that it’s still stored in a variable
somewhere.
Most of the data representation in the program is straightforward. The score
is a number. The position of the food is given by an (x, y) coordinate pair
but the food’s move function needs to know the size of the canvas if it’s
going to randomly appear in a place where we can eat it. Our Score
functions needs to be told when the score has increased and this function
will be called whenever the snake runs over food. The Snake is more
complex as it needs to know the bounds of the canvas, the location of the
food, and the location of all pieces of itself. Thus, the move function keeps
track of where the head of the Snake is but stores a list of body pieces as
well. By providing a collide function in the move function, the Snake head
matches to see if it coincides with the positions of the maze objects. The
result of this search is returned to the calling program. The Snake’s eat
method, should take food as a parameter and check to see if the food and
the Snake are in the same place. If they are, the Snake should grow, the
counter should increase, and the food should move.
Technology:
● Used Visual Studio Code (C) and Code Blocks along with graphics
library to program the game.
● Simple GL is used to display the images of the related objects in the
game.
● Some of the graphics commands have also been used (putpixel,
initgraph, etc.).
● Built-in Libraries of Visual Studio Code and Code Blocks.
● Different functions have been created for achieving various
functionalities within the game.
4. Game Interface
Loading Page
Main Menu
Game Instructions
About the Developers
Options Menu
Varying Game Difficulty Levels (Easy, Medium, Hard)
Pause Dialog Box
New Level Dialog
Gameplay Interface (Level 2)
Gameplay Interface (Level 4)
Thank You Page
Game Over Page
5. Testing and Evaluation
Testing is the major control measure used during software
development. Its basic function is to detect errors in the software
and to uncover the requirements, design and coding errors in the
programs. To display the snake, the first thing we want to do is to
make sure that we can draw the snake and move it around on the
screen. So, our testing for correct function will be:
1. Can I display the snake on the screen?
2. Will it move around as I want it to using keyboard controls?
3. Is it displaying correctly?
4. Is the body moving correctly?
If we identify an error in the snake, because it's a part of a
separate function, we will go into the move function and fix it
there. However, because we've written the highscore and maze as
separate functions, whatever we do in the move function shouldn't
break anything in there, unless we accidentally change the code
without noticing. The next step for the snake will be checking
what happens when the head is detected as colliding with
something. Does it grow when it eats food? Does it die when it
hits a maze object? We'd then continue to test the program until
we've tested all of the individual elements and their interactions
together. One useful test case is to see if everything is being
drawn where you expect. Because we aren't using all of the
screen, it's possible to draw the food or the snake so that it
overlaps with the boundary or with the maze objects. Has the
programmer put the correct limits on the ranges where the snake
and the food can appear? Testing the non-functional requirements
often falls into the realm of playability.
6. Results
The Snake Game is successfully planned, designed and implemented using
the various technologies mentioned. The Project was thrilling and exciting
and we learned various technologies and principles of computer graphics
while making this project. The Project is successfully developed and tested.
The Project has helped us in many sectors like- planning, designing,
developing, managing, programming skill, and so on.
7. Conclusions
Finally, we conclude our work and present the results of our project
work. In this project, we learned several project management techniques
used by professionals to develop large scale projects. The experience of
working as a team and the integration of modules developed
independently, with just requirement specifications, was a very important
achievement for our team. The future of the project is inhibited only by
creativity and the available technology. The project was really crucial
from a learning aspect. Multiple ways in which the project can be further
extended include but are not limited to including a timer to make the
snake starve if it doesn’t eat quickly enough or by integrating a two or
multi-player game or a single player vs computer game. Addition of
more complex levels and mazes can further add to the difficulty of the
game. We can also maintain a leaderboard with the Top 10 scores. As a
whole, this project really helped us learn and implement the various
fundamentals of Computer Graphics learned over the course of the
semester.
Appendix A
Some Coding functions
1. border()
This function is used to display the Borders on the Welcome / Loading
Screen and the Main Menu.
2. border1()
This function is used to display the Borders within the Game Window.
3. firstpage()
This function is used to display the Welcome / Loading Screen.
4. menupage()
This function is used to display the Main Menu with all the Options by
using setcolor, settextstyle, outtextxy.
5. menufunction()
This function is used to select among the various menu options by
using switch.
6. move()
This function contains the main code snippet which controls the
movement of the snake along with the random placement of the fruit. It
also keeps a track as to when the snake eats the food (when the head of
the snake is at the same place as the fruit) and increases the length of
the snake everytime it eats a fruit.
7. check()
This function is used to keep a track of the lives by detecting collisions
of the snake with the maze objects
8. mark()
This function is used to keep a track and display the Current Score,
Remaining Lifes and the Current Level at the bottom of the game
window.
9. lvl1()
This function is used to set the attributes for Level 1 such as lifes,
score, score upper limit, level number along with the speed of the snake
depending upon the difficulty level chosen in the options section.
10.lvl2()
This function is used to set the attributes for Level 2 such as score,
score upper limit, level number along with the speed of the snake
depending upon the difficulty level chosen in the options section.
11.lvl3()
This function is used to set the attributes for Level 3 such as score,
score upper limit, level number along with the speed of the snake
depending upon the difficulty level chosen in the options section.
12.lvl4()
This function is used to set the attributes for Level 4 such as score,
score upper limit, level number along with the speed of the snake
depending upon the difficulty level chosen in the options section.
13.lvl5()
This function is used to set the attributes for Level 5 such as score,
score upper limit, level number along with the speed of the snake
depending upon the difficulty level chosen in the options section.
14.maze()
This function is used to set the placement of the maze objects for levels
3 and 4.
15.maze1()
This function is used to set the placement of the maze objects for level
5.
16.lvlcomplete()
This function is used to display the Next Level Dialog and also switch
between levels upon pressing ‘S’ by using switch.
17.win()
This function is used to display the “Congratulations! You WIN the
Game” Dialog.
18.gameover
This function is used to display the GAME OVER Dialog.
19.hiscrt()
This function is used to open the file that stores the name and highscore
and update (write) the name along with the new highscore using files in
C++.
20.hisrd()
This function is used to access (read) the file that stores the name and
highscore and display it on the screen using files in C++.
21.option()
This function is used for displaying the Game Options.
22.difficulty()
This function is used for displaying and choosing among the 3
Difficulty Levels (Easy, Medium, Hard) by using switch.
23.intro()
This function is used for displaying the Game Instructions.
24.about()
This function is used for displaying the About the Developers
information.
25.quit()
This function is used to display the Thank You for Playing message
before quitting the game.
26.pausegame()
This function is used for playing / pausing the game.
References
1. https://www.wikipedia.org/
2. https://www.geeksforgeeks.org/
3. https://stackoverflow.com/
4. https://medium.com/
5. https://github.com/
Code Link
1. https://github.com/AtishayKatiyar/Snake_Game
