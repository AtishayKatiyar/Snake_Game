# Snake Game

<html>
<head><meta http-equiv=Content-Type content="text/html; charset=UTF-8">
<style type="text/css">
<!--
span.cls_004{font-family:Times,serif;font-size:20.0px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
div.cls_004{font-family:Times,serif;font-size:20.0px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
span.cls_006{font-family:Times,serif;font-size:16.0px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
div.cls_006{font-family:Times,serif;font-size:16.0px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
span.cls_008{font-family:Times,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_008{font-family:Times,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_009{font-family:Times,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
div.cls_009{font-family:Times,serif;font-size:12.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
span.cls_011{font-family:Times,serif;font-size:14.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_011{font-family:Times,serif;font-size:14.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_014{font-family:Times,serif;font-size:14.0px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
div.cls_014{font-family:Times,serif;font-size:14.0px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
span.cls_017{font-family:Times,serif;font-size:18.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
div.cls_017{font-family:Times,serif;font-size:18.1px;color:rgb(0,0,0);font-weight:bold;font-style:normal;text-decoration: none}
span.cls_018{font-family:Arial,serif;font-size:14.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_018{font-family:Arial,serif;font-size:14.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_016{font-family:Times,serif;font-size:16.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_016{font-family:Times,serif;font-size:16.0px;color:rgb(0,0,0);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_020{font-family:Times,serif;font-size:14.0px;color:rgb(17,84,204);font-weight:normal;font-style:normal;text-decoration: none}
div.cls_020{font-family:Times,serif;font-size:14.0px;color:rgb(17,84,204);font-weight:normal;font-style:normal;text-decoration: none}
span.cls_021{font-family:Times,serif;font-size:14.0px;color:rgb(17,84,204);font-weight:normal;font-style:normal;text-decoration: underline}
div.cls_021{font-family:Times,serif;font-size:14.0px;color:rgb(17,84,204);font-weight:normal;font-style:normal;text-decoration: none}
-->
</style>
<script type="text/javascript" src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/wz_jsgraphics.js"></script>
</head>
<body>
<div style="position:absolute;left:50%;margin-left:-306px;top:0px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background01.jpg" width=612 height=792></div>
<div style="position:absolute;left:248.74px;top:183.26px" class="cls_004"><span class="cls_004">Snake Game</span></div>
<div style="position:absolute;left:157.24px;top:272.00px" class="cls_006"><span class="cls_006">COMPUTER GRAPHICS LAB PROJECT</span></div>
<div style="position:absolute;left:274.24px;top:348.75px" class="cls_008"><span class="cls_008">Submitted by</span></div>
<div style="position:absolute;left:265.24px;top:363.00px" class="cls_009"><span class="cls_009">Atishay Katiyar</span></div>
<div style="position:absolute;left:269.74px;top:376.50px" class="cls_009"><span class="cls_009">2K18/MC/026</span></div>
<div style="position:absolute;left:275.74px;top:404.25px" class="cls_009"><span class="cls_009">Dhruv Vyas</span></div>
<div style="position:absolute;left:273.49px;top:417.75px" class="cls_009"><span class="cls_009">2K18/IT/047</span></div>
<div style="position:absolute;left:198.49px;top:514.50px" class="cls_008"><span class="cls_008">COMPUTER SCIENCE & ENGINEERING</span></div>
<div style="position:absolute;left:179.74px;top:528.26px" class="cls_011"><span class="cls_011">DELHI TECHNOLOGICAL UNIVERSITY</span></div>
<div style="position:absolute;left:204.49px;top:544.01px" class="cls_011"><span class="cls_011">BAWANA ROAD, DELHI-110042</span></div>
<div style="position:absolute;left:263.74px;top:561.00px" class="cls_009"><span class="cls_009">November, 2020</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:802px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background02.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:83.00px" class="cls_006"><span class="cls_006">Abstract</span></div>
<div style="position:absolute;left:99.49px;top:138.26px" class="cls_011"><span class="cls_011">This project summarizes the development of a Snake Game using the</span></div>
<div style="position:absolute;left:99.49px;top:162.26px" class="cls_011"><span class="cls_011">graphics library in C and lays an emphasis on the detailed usage of the</span></div>
<div style="position:absolute;left:99.49px;top:186.26px" class="cls_011"><span class="cls_011">concepts of computer graphics. The main objective of the project is to</span></div>
<div style="position:absolute;left:99.49px;top:210.26px" class="cls_011"><span class="cls_011">execute the concepts of computer graphics and figure out how to execute</span></div>
<div style="position:absolute;left:99.49px;top:234.26px" class="cls_011"><span class="cls_011">them in a practical work while getting negligible error. We also need to</span></div>
<div style="position:absolute;left:99.49px;top:259.01px" class="cls_011"><span class="cls_011">analyse the error we encounter during the progress of the project.</span></div>
<div style="position:absolute;left:99.49px;top:283.01px" class="cls_014"><span class="cls_014">Computer Graphics</span><span class="cls_011"> is the branch of computer science that deals with</span></div>
<div style="position:absolute;left:99.49px;top:307.01px" class="cls_011"><span class="cls_011">generating images with the aid of computers. Today, computer graphics is a</span></div>
<div style="position:absolute;left:99.49px;top:331.01px" class="cls_011"><span class="cls_011">core technology in digital photography, film, video games, cell phone and</span></div>
<div style="position:absolute;left:99.49px;top:355.01px" class="cls_011"><span class="cls_011">computer display, and many specialized applications. A great deal of</span></div>
<div style="position:absolute;left:99.49px;top:379.76px" class="cls_011"><span class="cls_011">specialized hardware and software has been developed, with the displays of</span></div>
<div style="position:absolute;left:99.49px;top:403.76px" class="cls_011"><span class="cls_011">most devices being driven by computer graphics hardware. It is a vast and</span></div>
<div style="position:absolute;left:99.49px;top:427.76px" class="cls_011"><span class="cls_011">recently developed area of computer science.</span></div>
<div style="position:absolute;left:99.49px;top:451.76px" class="cls_011"><span class="cls_011">This project aims to bring the fun and simplicity of the classic snake game</span></div>
<div style="position:absolute;left:99.49px;top:475.76px" class="cls_011"><span class="cls_011">with some new features using the graphics library in C. The game includes</span></div>
<div style="position:absolute;left:99.49px;top:500.51px" class="cls_011"><span class="cls_011">multiple levels with varying difficulties and complex mazes where the</span></div>
<div style="position:absolute;left:99.49px;top:524.51px" class="cls_011"><span class="cls_011">length of the snake increases when it eats the fruit and the game ends when</span></div>
<div style="position:absolute;left:99.49px;top:548.51px" class="cls_011"><span class="cls_011">we lose the 3 lives on colliding with the maze objects that spawn in the later</span></div>
<div style="position:absolute;left:99.49px;top:572.51px" class="cls_011"><span class="cls_011">levels. We have chosen this particular project as it revolves around the</span></div>
<div style="position:absolute;left:99.49px;top:596.51px" class="cls_011"><span class="cls_011">usage of basic and advanced tools of computer graphics. This project</span></div>
<div style="position:absolute;left:99.49px;top:621.26px" class="cls_011"><span class="cls_011">challenges us to execute on a practical level, our learnings from the subject</span></div>
<div style="position:absolute;left:99.49px;top:645.26px" class="cls_011"><span class="cls_011">and work on the project as a team thus developing on our team building</span></div>
<div style="position:absolute;left:99.49px;top:669.26px" class="cls_011"><span class="cls_011">skills.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:1604px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background03.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:69.50px" class="cls_006"><span class="cls_006">Contents</span></div>
<div style="position:absolute;left:101.74px;top:120.75px" class="cls_009"><span class="cls_009">Abstract</span></div>
<div style="position:absolute;left:497.74px;top:120.75px" class="cls_009"><span class="cls_009">i</span></div>
<div style="position:absolute;left:98.74px;top:148.50px" class="cls_009"><span class="cls_009">1</span></div>
<div style="position:absolute;left:121.24px;top:148.50px" class="cls_009"><span class="cls_009">Introduction</span></div>
<div style="position:absolute;left:494.74px;top:148.50px" class="cls_009"><span class="cls_009">1</span></div>
<div style="position:absolute;left:134.74px;top:162.00px" class="cls_008"><span class="cls_008">1.1</span></div>
<div style="position:absolute;left:202.24px;top:162.00px" class="cls_008"><span class="cls_008">Motivation.</span></div>
<div style="position:absolute;left:493.99px;top:162.00px" class="cls_008"><span class="cls_008">2</span></div>
<div style="position:absolute;left:98.74px;top:189.75px" class="cls_009"><span class="cls_009">2</span></div>
<div style="position:absolute;left:121.24px;top:189.75px" class="cls_009"><span class="cls_009">Background Details</span></div>
<div style="position:absolute;left:494.74px;top:189.75px" class="cls_009"><span class="cls_009">3</span></div>
<div style="position:absolute;left:98.74px;top:217.50px" class="cls_009"><span class="cls_009">3</span></div>
<div style="position:absolute;left:121.24px;top:217.50px" class="cls_009"><span class="cls_009">Project Details</span></div>
<div style="position:absolute;left:494.74px;top:217.50px" class="cls_009"><span class="cls_009">4</span></div>
<div style="position:absolute;left:98.74px;top:244.50px" class="cls_009"><span class="cls_009">4</span></div>
<div style="position:absolute;left:121.24px;top:244.50px" class="cls_009"><span class="cls_009">Game Interface</span></div>
<div style="position:absolute;left:494.74px;top:244.50px" class="cls_009"><span class="cls_009">8</span></div>
<div style="position:absolute;left:97.99px;top:272.25px" class="cls_009"><span class="cls_009">5</span></div>
<div style="position:absolute;left:121.99px;top:272.25px" class="cls_009"><span class="cls_009">Testing and Evaluations</span></div>
<div style="position:absolute;left:489.03px;top:272.25px" class="cls_009"><span class="cls_009">14</span></div>
<div style="position:absolute;left:97.99px;top:300.00px" class="cls_009"><span class="cls_009">6</span></div>
<div style="position:absolute;left:121.99px;top:300.00px" class="cls_009"><span class="cls_009">Results</span></div>
<div style="position:absolute;left:486.33px;top:300.00px" class="cls_009"><span class="cls_009">16</span></div>
<div style="position:absolute;left:97.99px;top:327.75px" class="cls_009"><span class="cls_009">7</span></div>
<div style="position:absolute;left:121.99px;top:327.75px" class="cls_009"><span class="cls_009">Conclusions</span></div>
<div style="position:absolute;left:487.24px;top:327.75px" class="cls_009"><span class="cls_009">17</span></div>
<div style="position:absolute;left:98.74px;top:355.50px" class="cls_009"><span class="cls_009">Some Coding Functions and their Proofs</span></div>
<div style="position:absolute;left:488.74px;top:355.50px" class="cls_009"><span class="cls_009">18</span></div>
<div style="position:absolute;left:98.74px;top:382.50px" class="cls_009"><span class="cls_009">References</span></div>
<div style="position:absolute;left:488.74px;top:382.50px" class="cls_009"><span class="cls_009">21</span></div>
<div style="position:absolute;left:97.99px;top:414.00px" class="cls_009"><span class="cls_009">Code File</span></div>
<div style="position:absolute;left:488.98px;top:414.00px" class="cls_009"><span class="cls_009">21</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:2406px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background04.jpg" width=612 height=792></div>
<div style="position:absolute;left:85.99px;top:78.75px" class="cls_017"><span class="cls_017">1. Introduction</span></div>
<div style="position:absolute;left:85.99px;top:112.00px" class="cls_011"><span class="cls_011">This project is the perfect example of a computer game written in C language</span></div>
<div style="position:absolute;left:85.99px;top:136.01px" class="cls_011"><span class="cls_011">based on the classic game called ‘Snake’ which has been around since the</span></div>
<div style="position:absolute;left:85.99px;top:160.76px" class="cls_011"><span class="cls_011">early days of home computing and then re-emerged on early feature phones. It</span></div>
<div style="position:absolute;left:85.99px;top:184.76px" class="cls_011"><span class="cls_011">is not a very complex game but does give an idea of what can be achieved</span></div>
<div style="position:absolute;left:85.99px;top:208.76px" class="cls_011"><span class="cls_011">with a relatively simple program using Computer Graphics, and perhaps the</span></div>
<div style="position:absolute;left:85.99px;top:232.76px" class="cls_011"><span class="cls_011">basis by which to extend the principles and create more interesting games.</span></div>
<div style="position:absolute;left:85.99px;top:256.76px" class="cls_011"><span class="cls_011">The main goals are:</span></div>
<div style="position:absolute;left:103.99px;top:282.26px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> To reinforce many of C and its programming concepts.</span></div>
<div style="position:absolute;left:103.99px;top:306.26px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> To get valuable experience of design and implementation of a large</span></div>
<div style="position:absolute;left:121.99px;top:329.51px" class="cls_011"><span class="cls_011">problem.</span></div>
<div style="position:absolute;left:103.99px;top:355.01px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> To provide a framework of a more challenging, and thus rewarding,</span></div>
<div style="position:absolute;left:121.99px;top:378.26px" class="cls_011"><span class="cls_011">exercise.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:3208px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background05.jpg" width=612 height=792></div>
<div style="position:absolute;left:97.99px;top:74.00px" class="cls_006"><span class="cls_006">1.1 Motivation</span></div>
<div style="position:absolute;left:99.49px;top:105.25px" class="cls_011"><span class="cls_011">The motivation for the project comes from the curiosity and the passion to</span></div>
<div style="position:absolute;left:99.49px;top:129.26px" class="cls_011"><span class="cls_011">learn  new  and  challenging  things  and  create  exciting  projects  using</span></div>
<div style="position:absolute;left:99.49px;top:154.01px" class="cls_011"><span class="cls_011">computer graphics. It is unbelievable what all can be achieved using</span></div>
<div style="position:absolute;left:99.49px;top:178.01px" class="cls_011"><span class="cls_011">computer graphics. Advances in computer graphics have transformed how</span></div>
<div style="position:absolute;left:99.49px;top:202.01px" class="cls_011"><span class="cls_011">we use computers. Computer graphics has given us the "mouse" input</span></div>
<div style="position:absolute;left:99.49px;top:226.01px" class="cls_011"><span class="cls_011">device, the computer-aided design system used to create the Boeing 777,</span></div>
<div style="position:absolute;left:99.49px;top:250.01px" class="cls_011"><span class="cls_011">the ability to visualize molecular dynamics and other scientific phenomena,</span></div>
<div style="position:absolute;left:99.49px;top:274.76px" class="cls_011"><span class="cls_011">the  animation  used  in  educational  software  and  the  advertising  and</span></div>
<div style="position:absolute;left:99.49px;top:298.76px" class="cls_011"><span class="cls_011">entertainment industries, and virtual reality systems whose applications</span></div>
<div style="position:absolute;left:99.49px;top:322.76px" class="cls_011"><span class="cls_011">range from architectural prototyping to surgical training to entertainment.</span></div>
<div style="position:absolute;left:99.49px;top:346.76px" class="cls_011"><span class="cls_011">Therefore, the need and curiosity to learn and apply the principles of</span></div>
<div style="position:absolute;left:99.49px;top:370.76px" class="cls_011"><span class="cls_011">Computer Graphics motivated us to create this game.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:4010px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background06.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:78.75px" class="cls_017"><span class="cls_017">2. Background Details</span></div>
<div style="position:absolute;left:99.49px;top:114.25px" class="cls_011"><span class="cls_011">The project will be using the principles of Computer Graphics. It makes</span></div>
<div style="position:absolute;left:99.49px;top:137.51px" class="cls_011"><span class="cls_011">you learn about the concepts of programming in C.</span></div>
<div style="position:absolute;left:99.49px;top:176.51px" class="cls_011"><span class="cls_011">The main aim of the project is to create a Snake game that allows users to</span></div>
<div style="position:absolute;left:99.49px;top:199.76px" class="cls_011"><span class="cls_011">control the movement of a snake on a screen, score points for eating food</span></div>
<div style="position:absolute;left:99.49px;top:223.76px" class="cls_011"><span class="cls_011">and avoiding running into the maze objects. In this game, we want to write</span></div>
<div style="position:absolute;left:99.49px;top:247.76px" class="cls_011"><span class="cls_011">a code where a graphical representation of a snake moves across the screen.</span></div>
<div style="position:absolute;left:99.49px;top:271.76px" class="cls_011"><span class="cls_011">When it encounters a piece of food, the snake grows longer and we gain 20</span></div>
<div style="position:absolute;left:99.49px;top:296.51px" class="cls_011"><span class="cls_011">points. If it hits the maze objects, we lose a life, eventually dying if we lose</span></div>
<div style="position:absolute;left:99.49px;top:320.51px" class="cls_011"><span class="cls_011">all 3 lives. So, the objective of the game is to collect the dots (food) and</span></div>
<div style="position:absolute;left:99.49px;top:344.51px" class="cls_011"><span class="cls_011">avoid the obstacles (maze objects). As you collect food, the snake gets</span></div>
<div style="position:absolute;left:99.49px;top:368.51px" class="cls_011"><span class="cls_011">longer. When you have collected enough food, you progress onto the next</span></div>
<div style="position:absolute;left:99.49px;top:392.51px" class="cls_011"><span class="cls_011">level, where your snake moves at a faster speed. The game will also keep a</span></div>
<div style="position:absolute;left:99.49px;top:416.51px" class="cls_011"><span class="cls_011">track of your highscore.</span></div>
<div style="position:absolute;left:99.49px;top:455.51px" class="cls_011"><span class="cls_011">Prerequisites include an understanding of general programming concepts</span></div>
<div style="position:absolute;left:99.49px;top:478.76px" class="cls_011"><span class="cls_011">along with the fundamentals of Computer Graphics. Good understanding of</span></div>
<div style="position:absolute;left:99.49px;top:502.76px" class="cls_011"><span class="cls_011">the graphics library in C is really important for the development of this</span></div>
<div style="position:absolute;left:99.49px;top:527.51px" class="cls_011"><span class="cls_011">project.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:4812px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background07.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:78.75px" class="cls_017"><span class="cls_017">3. Project Details</span></div>
<div style="position:absolute;left:99.49px;top:112.00px" class="cls_011"><span class="cls_011">In this project, we want to write a game where a graphical representation of</span></div>
<div style="position:absolute;left:99.49px;top:136.01px" class="cls_011"><span class="cls_011">a snake moves across the screen. When it encounters a piece of food, the</span></div>
<div style="position:absolute;left:99.49px;top:160.76px" class="cls_011"><span class="cls_011">snake grows longer and we gain points. If it hits the maze objects, we lose a</span></div>
<div style="position:absolute;left:99.49px;top:184.76px" class="cls_011"><span class="cls_011">life and die if all 3 lives get exhausted.</span></div>
<div style="position:absolute;left:99.49px;top:232.76px" class="cls_011"><span class="cls_011">To write this program we are going to need:</span></div>
<div style="position:absolute;left:103.99px;top:258.26px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> A way of representing the snake</span></div>
<div style="position:absolute;left:103.99px;top:282.26px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> A way of representing the food</span></div>
<div style="position:absolute;left:103.99px;top:306.26px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> A way to display the score</span></div>
<div style="position:absolute;left:103.99px;top:330.26px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> A way to display the remaining number of lives</span></div>
<div style="position:absolute;left:103.99px;top:355.01px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> A way for our instructions to reach the snake</span></div>
<div style="position:absolute;left:103.99px;top:379.01px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> And a way to know when we’ve run into something and died</span></div>
<div style="position:absolute;left:99.49px;top:426.26px" class="cls_011"><span class="cls_011">Here are the requirements (functional requirements) for how the snake</span></div>
<div style="position:absolute;left:99.49px;top:451.01px" class="cls_011"><span class="cls_011">moves.</span></div>
<div style="position:absolute;left:99.49px;top:475.01px" class="cls_011"><span class="cls_011">1. The snake must appear to move around the screen.</span></div>
<div style="position:absolute;left:99.49px;top:499.01px" class="cls_011"><span class="cls_011">2. The snake must turn in response to user input.</span></div>
<div style="position:absolute;left:99.49px;top:523.01px" class="cls_011"><span class="cls_011">3. The snake will increase in length if it eats food.</span></div>
<div style="position:absolute;left:99.49px;top:547.01px" class="cls_011"><span class="cls_011">4. The snake will die if it runs into the maze objects.</span></div>
<div style="position:absolute;left:99.49px;top:571.76px" class="cls_011"><span class="cls_011">5. The snake never stops moving.</span></div>
<div style="position:absolute;left:99.49px;top:619.76px" class="cls_011"><span class="cls_011">To keep the game interesting,</span></div>
<div style="position:absolute;left:99.49px;top:643.76px" class="cls_011"><span class="cls_011">1. The snake must move at a speed fast enough to be interesting but slow</span></div>
<div style="position:absolute;left:99.49px;top:667.76px" class="cls_011"><span class="cls_011">enough to control.</span></div>
<div style="position:absolute;left:99.49px;top:692.51px" class="cls_011"><span class="cls_011">2.   The   code  must  make  use  of  the  graphics  library</span></div>
<div style="position:absolute;left:459.19px;top:692.51px" class="cls_011"><span class="cls_011">(curriculum</span></div>
<div style="position:absolute;left:99.49px;top:716.51px" class="cls_011"><span class="cls_011">requirement).</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:5614px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background08.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:73.00px" class="cls_011"><span class="cls_011">The snake moves in a very precise way. Based on what the user inputs, the</span></div>
<div style="position:absolute;left:99.49px;top:97.00px" class="cls_011"><span class="cls_011">snake will move in a given direction. Each time the snake moves, the head</span></div>
<div style="position:absolute;left:99.49px;top:121.75px" class="cls_011"><span class="cls_011">will go in the new direction, and every piece of the snake will move up, by</span></div>
<div style="position:absolute;left:99.49px;top:145.76px" class="cls_011"><span class="cls_011">occupying the space that was formerly occupied by the piece in front of it.</span></div>
<div style="position:absolute;left:99.49px;top:169.76px" class="cls_011"><span class="cls_011">To grow in size, the snake has to eat food. How can we show the snake</span></div>
<div style="position:absolute;left:99.49px;top:193.76px" class="cls_011"><span class="cls_011">eating? The simplest answer is that if the head of the snake and the food are</span></div>
<div style="position:absolute;left:99.49px;top:217.76px" class="cls_011"><span class="cls_011">in the same place, we consider that the snake eats the food. This means that</span></div>
<div style="position:absolute;left:99.49px;top:242.51px" class="cls_011"><span class="cls_011">we have to know where the food is. When it’s eaten, it disappears, the</span></div>
<div style="position:absolute;left:99.49px;top:266.51px" class="cls_011"><span class="cls_011">snake grows, and the food shows up somewhere else randomly. The</span></div>
<div style="position:absolute;left:99.49px;top:290.51px" class="cls_011"><span class="cls_011">coordinates of the food are part of its variables and it has a function move,</span></div>
<div style="position:absolute;left:99.49px;top:314.51px" class="cls_011"><span class="cls_011">which will move it to a different place. To make the game interesting, we</span></div>
<div style="position:absolute;left:99.49px;top:338.51px" class="cls_011"><span class="cls_011">probably want this to be a random location, which means that we'll have to</span></div>
<div style="position:absolute;left:99.49px;top:363.26px" class="cls_011"><span class="cls_011">make sure that our program can generate random numbers. But we also</span></div>
<div style="position:absolute;left:99.49px;top:387.26px" class="cls_011"><span class="cls_011">want to show a score, so we need a variable to keep track of that as well. In</span></div>
<div style="position:absolute;left:99.49px;top:411.26px" class="cls_011"><span class="cls_011">this case, we’ll create a High Score function as well.</span></div>
<div style="position:absolute;left:99.49px;top:459.26px" class="cls_011"><span class="cls_011">Let's look at how a program to run the whole game might look:</span></div>
<div style="position:absolute;left:99.49px;top:484.01px" class="cls_011"><span class="cls_011">1. Draw the playing area with a bounding rectangle, set the counter to zero</span></div>
<div style="position:absolute;left:99.49px;top:508.01px" class="cls_011"><span class="cls_011">and display it.</span></div>
<div style="position:absolute;left:99.49px;top:532.01px" class="cls_011"><span class="cls_011">2. Draw the snake in a starting position.</span></div>
<div style="position:absolute;left:99.49px;top:556.01px" class="cls_011"><span class="cls_011">3. Draw the food in a starting location.</span></div>
<div style="position:absolute;left:99.49px;top:580.01px" class="cls_011"><span class="cls_011">4. On user input, change snake direction.</span></div>
<div style="position:absolute;left:99.49px;top:604.76px" class="cls_011"><span class="cls_011">5. Move the snake one move.</span></div>
<div style="position:absolute;left:99.49px;top:628.76px" class="cls_011"><span class="cls_011">6. If the snake is over food, eat it, increase the score, increase the snake</span></div>
<div style="position:absolute;left:99.49px;top:652.76px" class="cls_011"><span class="cls_011">length, move the food,</span></div>
<div style="position:absolute;left:99.49px;top:676.76px" class="cls_011"><span class="cls_011">7. else if the snake is over a maze object, subtract a life.</span></div>
<div style="position:absolute;left:99.49px;top:700.76px" class="cls_011"><span class="cls_011">8. Go back to 4.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:6416px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background09.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:73.00px" class="cls_011"><span class="cls_011">9. Until the snake loses all 3 lives and dies.</span></div>
<div style="position:absolute;left:99.49px;top:121.75px" class="cls_011"><span class="cls_011">We didn’t talk about what makes the snake die. The snake eats when the</span></div>
<div style="position:absolute;left:99.49px;top:145.76px" class="cls_011"><span class="cls_011">food and the snake’s head are in the same place. In a game, we refer to that</span></div>
<div style="position:absolute;left:99.49px;top:169.76px" class="cls_011"><span class="cls_011">as collision detection. Although the objects didn’t really collide, in a</span></div>
<div style="position:absolute;left:99.49px;top:193.76px" class="cls_011"><span class="cls_011">real-world sense, they are in the same place and we can perform actions</span></div>
<div style="position:absolute;left:99.49px;top:217.76px" class="cls_011"><span class="cls_011">based on this. We’re going to use collision detection to see when the snake</span></div>
<div style="position:absolute;left:99.49px;top:242.51px" class="cls_011"><span class="cls_011">runs into a maze object, which means that we’re going to have to keep track</span></div>
<div style="position:absolute;left:99.49px;top:266.51px" class="cls_011"><span class="cls_011">of the head of the snake within our program. Just because something is</span></div>
<div style="position:absolute;left:99.49px;top:290.51px" class="cls_011"><span class="cls_011">drawn  on the screen doesn’t mean that it’s still stored in a variable</span></div>
<div style="position:absolute;left:99.49px;top:314.51px" class="cls_011"><span class="cls_011">somewhere.</span></div>
<div style="position:absolute;left:99.49px;top:338.51px" class="cls_011"><span class="cls_011">Most of the data representation in the program is straightforward. The score</span></div>
<div style="position:absolute;left:99.49px;top:363.26px" class="cls_011"><span class="cls_011">is a number. The position of the food is given by an (x, y) coordinate pair</span></div>
<div style="position:absolute;left:99.49px;top:387.26px" class="cls_011"><span class="cls_011">but the food’s move function needs to know the size of the canvas if it’s</span></div>
<div style="position:absolute;left:99.49px;top:411.26px" class="cls_011"><span class="cls_011">going to randomly appear in a place where we can eat it. Our Score</span></div>
<div style="position:absolute;left:99.49px;top:435.26px" class="cls_011"><span class="cls_011">functions needs to be told when the score has increased and this function</span></div>
<div style="position:absolute;left:99.49px;top:459.26px" class="cls_011"><span class="cls_011">will be called whenever the snake runs over food. The Snake is more</span></div>
<div style="position:absolute;left:99.49px;top:484.01px" class="cls_011"><span class="cls_011">complex as it needs to know the bounds of the canvas, the location of the</span></div>
<div style="position:absolute;left:99.49px;top:508.01px" class="cls_011"><span class="cls_011">food, and the location of all pieces of itself. Thus, the move function keeps</span></div>
<div style="position:absolute;left:99.49px;top:532.01px" class="cls_011"><span class="cls_011">track of where the head of the Snake is but stores a list of body pieces as</span></div>
<div style="position:absolute;left:99.49px;top:556.01px" class="cls_011"><span class="cls_011">well. By providing a collide function in the move function, the Snake head</span></div>
<div style="position:absolute;left:99.49px;top:580.01px" class="cls_011"><span class="cls_011">matches to see if it coincides with the positions of the maze objects. The</span></div>
<div style="position:absolute;left:99.49px;top:604.76px" class="cls_011"><span class="cls_011">result of this search is returned to the calling program. The Snake’s eat</span></div>
<div style="position:absolute;left:99.49px;top:628.76px" class="cls_011"><span class="cls_011">method, should take food as a parameter and check to see if the food and</span></div>
<div style="position:absolute;left:99.49px;top:652.76px" class="cls_011"><span class="cls_011">the Snake are in the same place. If they are, the Snake should grow, the</span></div>
<div style="position:absolute;left:99.49px;top:676.76px" class="cls_011"><span class="cls_011">counter should increase, and the food should move.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:7218px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background10.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:74.00px" class="cls_006"><span class="cls_006">Technology:</span></div>
<div style="position:absolute;left:103.99px;top:115.75px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> Used Visual Studio Code (C) and Code Blocks along with graphics</span></div>
<div style="position:absolute;left:121.99px;top:139.01px" class="cls_011"><span class="cls_011">library to program the game.</span></div>
<div style="position:absolute;left:103.99px;top:163.76px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> Simple GL is used to display the images of the related objects in the</span></div>
<div style="position:absolute;left:121.99px;top:187.01px" class="cls_011"><span class="cls_011">game.</span></div>
<div style="position:absolute;left:103.99px;top:212.51px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> Some of the graphics commands have also been used (putpixel,</span></div>
<div style="position:absolute;left:121.99px;top:235.76px" class="cls_011"><span class="cls_011">initgraph, etc.).</span></div>
<div style="position:absolute;left:103.99px;top:260.51px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> Built-in Libraries of Visual Studio Code and Code Blocks.</span></div>
<div style="position:absolute;left:103.99px;top:284.51px" class="cls_018"><span class="cls_018">●</span><span class="cls_011"> Different functions have been created for achieving various</span></div>
<div style="position:absolute;left:121.99px;top:308.51px" class="cls_011"><span class="cls_011">functionalities within the game.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:8020px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background11.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:97.50px" class="cls_017"><span class="cls_017">4. Game Interface</span></div>
<div style="position:absolute;left:263.74px;top:413.25px" class="cls_009"><span class="cls_009">Loading Page</span></div>
<div style="position:absolute;left:268.99px;top:726.00px" class="cls_009"><span class="cls_009">Main Menu</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:8822px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background12.jpg" width=612 height=792></div>
<div style="position:absolute;left:251.74px;top:367.50px" class="cls_009"><span class="cls_009">Game Instructions</span></div>
<div style="position:absolute;left:244.24px;top:681.00px" class="cls_009"><span class="cls_009">About the Developers</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:9624px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background13.jpg" width=612 height=792></div>
<div style="position:absolute;left:262.24px;top:348.75px" class="cls_009"><span class="cls_009">Options Menu</span></div>
<div style="position:absolute;left:158.74px;top:661.50px" class="cls_009"><span class="cls_009">Varying Game Difficulty Levels (Easy, Medium, Hard)</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:10426px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background14.jpg" width=612 height=792></div>
<div style="position:absolute;left:254.74px;top:349.50px" class="cls_009"><span class="cls_009">Pause Dialog Box</span></div>
<div style="position:absolute;left:253.99px;top:662.25px" class="cls_009"><span class="cls_009">New Level Dialog</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:11228px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background15.jpg" width=612 height=792></div>
<div style="position:absolute;left:223.99px;top:349.50px" class="cls_009"><span class="cls_009">Gameplay Interface (Level 2)</span></div>
<div style="position:absolute;left:223.99px;top:663.00px" class="cls_009"><span class="cls_009">Gameplay Interface (Level 4)</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:12030px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background16.jpg" width=612 height=792></div>
<div style="position:absolute;left:256.24px;top:349.50px" class="cls_009"><span class="cls_009">Thank You Page</span></div>
<div style="position:absolute;left:255.49px;top:663.00px" class="cls_009"><span class="cls_009">Game Over Page</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:12832px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background17.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:94.50px" class="cls_017"><span class="cls_017">5. Testing and Evaluation</span></div>
<div style="position:absolute;left:99.49px;top:145.25px" class="cls_016"><span class="cls_016">Testing  is  the  major  control  measure  used  during  software</span></div>
<div style="position:absolute;left:99.49px;top:172.25px" class="cls_016"><span class="cls_016">development. Its basic function is to detect errors in the software</span></div>
<div style="position:absolute;left:99.49px;top:200.00px" class="cls_016"><span class="cls_016">and to uncover the requirements, design and coding errors in the</span></div>
<div style="position:absolute;left:99.49px;top:227.75px" class="cls_016"><span class="cls_016">programs. To display the snake, the first thing we want to do is to</span></div>
<div style="position:absolute;left:99.49px;top:255.50px" class="cls_016"><span class="cls_016">make sure that we can draw the snake and move it around on the</span></div>
<div style="position:absolute;left:99.49px;top:283.25px" class="cls_016"><span class="cls_016">screen. So, our testing for correct function will be:</span></div>
<div style="position:absolute;left:99.49px;top:310.25px" class="cls_016"><span class="cls_016">1. Can I display the snake on the screen?</span></div>
<div style="position:absolute;left:99.49px;top:338.00px" class="cls_016"><span class="cls_016">2. Will it move around as I want it to using keyboard controls?</span></div>
<div style="position:absolute;left:99.49px;top:365.75px" class="cls_016"><span class="cls_016">3. Is it displaying correctly?</span></div>
<div style="position:absolute;left:99.49px;top:393.50px" class="cls_016"><span class="cls_016">4. Is the body moving correctly?</span></div>
<div style="position:absolute;left:99.49px;top:425.00px" class="cls_016"><span class="cls_016">If we identify an error in the snake, because it's a part of a</span></div>
<div style="position:absolute;left:99.49px;top:452.75px" class="cls_016"><span class="cls_016">separate function, we will go into the move function and fix it</span></div>
<div style="position:absolute;left:99.49px;top:480.50px" class="cls_016"><span class="cls_016">there. However, because we've written the highscore and maze as</span></div>
<div style="position:absolute;left:99.49px;top:508.25px" class="cls_016"><span class="cls_016">separate functions, whatever we do in the move function shouldn't</span></div>
<div style="position:absolute;left:99.49px;top:536.00px" class="cls_016"><span class="cls_016">break anything in there, unless we accidentally change the code</span></div>
<div style="position:absolute;left:99.49px;top:563.00px" class="cls_016"><span class="cls_016">without noticing. The next step for the snake will be checking</span></div>
<div style="position:absolute;left:99.49px;top:590.75px" class="cls_016"><span class="cls_016">what  happens  when  the  head  is  detected  as  colliding  with</span></div>
<div style="position:absolute;left:99.49px;top:618.50px" class="cls_016"><span class="cls_016">something. Does it grow when it eats food? Does it die when it</span></div>
<div style="position:absolute;left:99.49px;top:646.25px" class="cls_016"><span class="cls_016">hits a maze object? We'd then continue to test the program until</span></div>
<div style="position:absolute;left:99.49px;top:674.00px" class="cls_016"><span class="cls_016">we've tested all of the individual elements and their interactions</span></div>
<div style="position:absolute;left:99.49px;top:701.00px" class="cls_016"><span class="cls_016">together. One useful test case is to see if everything is being</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:13634px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background18.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:74.00px" class="cls_016"><span class="cls_016">drawn where you expect. Because we aren't using all of the</span></div>
<div style="position:absolute;left:99.49px;top:101.75px" class="cls_016"><span class="cls_016">screen, it's possible to draw the food or the snake so that it</span></div>
<div style="position:absolute;left:99.49px;top:128.75px" class="cls_016"><span class="cls_016">overlaps with the boundary or with the maze objects. Has the</span></div>
<div style="position:absolute;left:99.49px;top:156.50px" class="cls_016"><span class="cls_016">programmer put the correct limits on the ranges where the snake</span></div>
<div style="position:absolute;left:99.49px;top:184.25px" class="cls_016"><span class="cls_016">and the food can appear? Testing the non-functional requirements</span></div>
<div style="position:absolute;left:99.49px;top:212.00px" class="cls_016"><span class="cls_016">often falls into the realm of playability.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:14436px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background19.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:98.25px" class="cls_017"><span class="cls_017">6. Results</span></div>
<div style="position:absolute;left:99.49px;top:146.51px" class="cls_011"><span class="cls_011">The Snake Game is successfully planned, designed and implemented using</span></div>
<div style="position:absolute;left:99.49px;top:169.76px" class="cls_011"><span class="cls_011">the various technologies mentioned. The Project was thrilling and exciting</span></div>
<div style="position:absolute;left:99.49px;top:194.51px" class="cls_011"><span class="cls_011">and we learned various technologies and principles of computer graphics</span></div>
<div style="position:absolute;left:99.49px;top:218.51px" class="cls_011"><span class="cls_011">while making this project. The Project is successfully developed and tested.</span></div>
<div style="position:absolute;left:99.49px;top:242.51px" class="cls_011"><span class="cls_011">The Project has helped us in many sectors like- planning, designing,</span></div>
<div style="position:absolute;left:99.49px;top:266.51px" class="cls_011"><span class="cls_011">developing, managing, programming skill, and so on.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:15238px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background20.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:118.50px" class="cls_017"><span class="cls_017">7. Conclusions</span></div>
<div style="position:absolute;left:99.49px;top:157.76px" class="cls_011"><span class="cls_011">Finally, we conclude our work and present the results of our project</span></div>
<div style="position:absolute;left:99.49px;top:181.76px" class="cls_011"><span class="cls_011">work. In this project, we learned several project management techniques</span></div>
<div style="position:absolute;left:99.49px;top:205.76px" class="cls_011"><span class="cls_011">used by professionals to develop large scale projects. The experience of</span></div>
<div style="position:absolute;left:99.49px;top:229.76px" class="cls_011"><span class="cls_011">working   as   a   team   and   the   integration   of   modules   developed</span></div>
<div style="position:absolute;left:99.49px;top:254.51px" class="cls_011"><span class="cls_011">independently, with just requirement specifications, was a very important</span></div>
<div style="position:absolute;left:99.49px;top:278.51px" class="cls_011"><span class="cls_011">achievement for our team. The future of the project is inhibited only by</span></div>
<div style="position:absolute;left:99.49px;top:302.51px" class="cls_011"><span class="cls_011">creativity and the available technology. The project was really crucial</span></div>
<div style="position:absolute;left:99.49px;top:326.51px" class="cls_011"><span class="cls_011">from a learning aspect. Multiple ways in which the project can be further</span></div>
<div style="position:absolute;left:99.49px;top:350.51px" class="cls_011"><span class="cls_011">extended include but are not limited to including a timer to make the</span></div>
<div style="position:absolute;left:99.49px;top:375.26px" class="cls_011"><span class="cls_011">snake starve if it doesn’t eat quickly enough or by integrating a two or</span></div>
<div style="position:absolute;left:99.49px;top:399.26px" class="cls_011"><span class="cls_011">multi-player game or a single player vs computer game. Addition of</span></div>
<div style="position:absolute;left:99.49px;top:423.26px" class="cls_011"><span class="cls_011">more complex levels and mazes can further add to the difficulty of the</span></div>
<div style="position:absolute;left:99.49px;top:447.26px" class="cls_011"><span class="cls_011">game. We can also maintain a leaderboard with the Top 10 scores. As a</span></div>
<div style="position:absolute;left:99.49px;top:471.26px" class="cls_011"><span class="cls_011">whole, this project really helped us learn and implement the various</span></div>
<div style="position:absolute;left:99.49px;top:496.01px" class="cls_011"><span class="cls_011">fundamentals of Computer Graphics learned over the course of the</span></div>
<div style="position:absolute;left:99.49px;top:520.01px" class="cls_011"><span class="cls_011">semester.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:16040px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background21.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:69.00px" class="cls_017"><span class="cls_017">Appendix A</span></div>
<div style="position:absolute;left:99.49px;top:109.25px" class="cls_006"><span class="cls_006">Some Coding functions</span></div>
<div style="position:absolute;left:103.99px;top:145.76px" class="cls_014"><span class="cls_014">1.</span></div>
<div style="position:absolute;left:121.99px;top:145.76px" class="cls_014"><span class="cls_014">border()</span></div>
<div style="position:absolute;left:121.99px;top:161.51px" class="cls_011"><span class="cls_011">This function is used to display the Borders on the Welcome / Loading</span></div>
<div style="position:absolute;left:121.99px;top:177.26px" class="cls_011"><span class="cls_011">Screen and the Main Menu.</span></div>
<div style="position:absolute;left:103.99px;top:209.51px" class="cls_014"><span class="cls_014">2.</span></div>
<div style="position:absolute;left:121.99px;top:209.51px" class="cls_014"><span class="cls_014">border1()</span></div>
<div style="position:absolute;left:121.99px;top:226.01px" class="cls_011"><span class="cls_011">This function is used to display the Borders within the Game Window.</span></div>
<div style="position:absolute;left:103.99px;top:258.26px" class="cls_014"><span class="cls_014">3.</span></div>
<div style="position:absolute;left:121.99px;top:258.26px" class="cls_014"><span class="cls_014">firstpage()</span></div>
<div style="position:absolute;left:121.99px;top:274.01px" class="cls_011"><span class="cls_011">This function is used to display the Welcome / Loading Screen.</span></div>
<div style="position:absolute;left:103.99px;top:306.26px" class="cls_014"><span class="cls_014">4.</span></div>
<div style="position:absolute;left:121.99px;top:306.26px" class="cls_014"><span class="cls_014">menupage()</span></div>
<div style="position:absolute;left:121.99px;top:322.76px" class="cls_011"><span class="cls_011">This function is used to display the Main Menu with all the Options by</span></div>
<div style="position:absolute;left:121.99px;top:338.51px" class="cls_011"><span class="cls_011">using setcolor, settextstyle, outtextxy.</span></div>
<div style="position:absolute;left:103.99px;top:370.76px" class="cls_014"><span class="cls_014">5.</span></div>
<div style="position:absolute;left:121.99px;top:370.76px" class="cls_014"><span class="cls_014">menufunction()</span></div>
<div style="position:absolute;left:121.99px;top:386.51px" class="cls_011"><span class="cls_011">This function is used to select among the various menu options by</span></div>
<div style="position:absolute;left:121.99px;top:403.01px" class="cls_011"><span class="cls_011">using switch.</span></div>
<div style="position:absolute;left:103.99px;top:435.26px" class="cls_014"><span class="cls_014">6.</span></div>
<div style="position:absolute;left:121.99px;top:435.26px" class="cls_014"><span class="cls_014">move()</span></div>
<div style="position:absolute;left:121.99px;top:451.01px" class="cls_011"><span class="cls_011">This  function  contains  the  main  code  snippet  which controls the</span></div>
<div style="position:absolute;left:121.99px;top:467.51px" class="cls_011"><span class="cls_011">movement of the snake along with the random placement of the fruit. It</span></div>
<div style="position:absolute;left:121.99px;top:483.26px" class="cls_011"><span class="cls_011">also keeps a track as to when the snake eats the food (when the head of</span></div>
<div style="position:absolute;left:121.99px;top:499.76px" class="cls_011"><span class="cls_011">the snake is at the same place as the fruit) and increases the length of</span></div>
<div style="position:absolute;left:121.99px;top:515.51px" class="cls_011"><span class="cls_011">the snake everytime it eats a fruit.</span></div>
<div style="position:absolute;left:103.99px;top:547.76px" class="cls_014"><span class="cls_014">7.</span></div>
<div style="position:absolute;left:121.99px;top:547.76px" class="cls_014"><span class="cls_014">check()</span></div>
<div style="position:absolute;left:121.99px;top:564.26px" class="cls_011"><span class="cls_011">This function is used to keep a track of the lives by detecting collisions</span></div>
<div style="position:absolute;left:121.99px;top:580.01px" class="cls_011"><span class="cls_011">of the snake with the maze objects</span></div>
<div style="position:absolute;left:103.99px;top:612.26px" class="cls_014"><span class="cls_014">8.</span></div>
<div style="position:absolute;left:121.99px;top:612.26px" class="cls_014"><span class="cls_014">mark()</span></div>
<div style="position:absolute;left:121.99px;top:628.01px" class="cls_011"><span class="cls_011">This function is used to keep a track and display the Current Score,</span></div>
<div style="position:absolute;left:121.99px;top:644.51px" class="cls_011"><span class="cls_011">Remaining Lifes and the Current Level at the bottom of the game</span></div>
<div style="position:absolute;left:121.99px;top:660.26px" class="cls_011"><span class="cls_011">window.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:16842px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background22.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.99px;top:66.25px" class="cls_014"><span class="cls_014">9. lvl1()</span></div>
<div style="position:absolute;left:121.99px;top:82.75px" class="cls_011"><span class="cls_011">This function is used to set the attributes for Level 1 such as lifes,</span></div>
<div style="position:absolute;left:121.99px;top:98.50px" class="cls_011"><span class="cls_011">score, score upper limit, level number along with the speed of the snake</span></div>
<div style="position:absolute;left:121.99px;top:115.00px" class="cls_011"><span class="cls_011">depending upon the difficulty level chosen in the options section.</span></div>
<div style="position:absolute;left:103.99px;top:147.26px" class="cls_014"><span class="cls_014">10.lvl2()</span></div>
<div style="position:absolute;left:121.99px;top:163.01px" class="cls_011"><span class="cls_011">This function is used to set the attributes for Level 2 such as score,</span></div>
<div style="position:absolute;left:121.99px;top:179.51px" class="cls_011"><span class="cls_011">score upper limit, level number along with the speed of the snake</span></div>
<div style="position:absolute;left:121.99px;top:195.26px" class="cls_011"><span class="cls_011">depending upon the difficulty level chosen in the options section.</span></div>
<div style="position:absolute;left:103.99px;top:227.51px" class="cls_014"><span class="cls_014">11.lvl3()</span></div>
<div style="position:absolute;left:121.99px;top:244.01px" class="cls_011"><span class="cls_011">This function is used to set the attributes for Level 3 such as score,</span></div>
<div style="position:absolute;left:121.99px;top:259.76px" class="cls_011"><span class="cls_011">score upper limit, level number along with the speed of the snake</span></div>
<div style="position:absolute;left:121.99px;top:276.26px" class="cls_011"><span class="cls_011">depending upon the difficulty level chosen in the options section.</span></div>
<div style="position:absolute;left:103.99px;top:307.76px" class="cls_014"><span class="cls_014">12.lvl4()</span></div>
<div style="position:absolute;left:121.99px;top:324.26px" class="cls_011"><span class="cls_011">This function is used to set the attributes for Level 4 such as score,</span></div>
<div style="position:absolute;left:121.99px;top:340.01px" class="cls_011"><span class="cls_011">score upper limit, level number along with the speed of the snake</span></div>
<div style="position:absolute;left:121.99px;top:356.51px" class="cls_011"><span class="cls_011">depending upon the difficulty level chosen in the options section.</span></div>
<div style="position:absolute;left:103.99px;top:388.76px" class="cls_014"><span class="cls_014">13.lvl5()</span></div>
<div style="position:absolute;left:121.99px;top:404.51px" class="cls_011"><span class="cls_011">This function is used to set the attributes for Level 5 such as score,</span></div>
<div style="position:absolute;left:121.99px;top:421.01px" class="cls_011"><span class="cls_011">score upper limit, level number along with the speed of the snake</span></div>
<div style="position:absolute;left:121.99px;top:436.76px" class="cls_011"><span class="cls_011">depending upon the difficulty level chosen in the options section.</span></div>
<div style="position:absolute;left:103.99px;top:469.01px" class="cls_014"><span class="cls_014">14.maze()</span></div>
<div style="position:absolute;left:121.99px;top:485.51px" class="cls_011"><span class="cls_011">This function is used to set the placement of the maze objects for levels</span></div>
<div style="position:absolute;left:121.99px;top:501.26px" class="cls_011"><span class="cls_011">3 and 4.</span></div>
<div style="position:absolute;left:103.99px;top:533.51px" class="cls_014"><span class="cls_014">15.maze1()</span></div>
<div style="position:absolute;left:121.99px;top:549.26px" class="cls_011"><span class="cls_011">This function is used to set the placement of the maze objects for level</span></div>
<div style="position:absolute;left:121.99px;top:565.76px" class="cls_011"><span class="cls_011">5.</span></div>
<div style="position:absolute;left:103.99px;top:598.01px" class="cls_014"><span class="cls_014">16.lvlcomplete()</span></div>
<div style="position:absolute;left:121.99px;top:613.76px" class="cls_011"><span class="cls_011">This function is used to display the Next Level Dialog and also switch</span></div>
<div style="position:absolute;left:121.99px;top:630.26px" class="cls_011"><span class="cls_011">between levels upon pressing ‘S’ by using switch.</span></div>
<div style="position:absolute;left:103.99px;top:662.51px" class="cls_014"><span class="cls_014">17.win()</span></div>
<div style="position:absolute;left:121.99px;top:678.26px" class="cls_011"><span class="cls_011">This function is used to display the “Congratulations! You WIN the</span></div>
<div style="position:absolute;left:121.99px;top:694.76px" class="cls_011"><span class="cls_011">Game” Dialog.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:17644px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background23.jpg" width=612 height=792></div>
<div style="position:absolute;left:103.99px;top:66.25px" class="cls_014"><span class="cls_014">18.gameover</span></div>
<div style="position:absolute;left:121.99px;top:82.75px" class="cls_011"><span class="cls_011">This function is used to display the GAME OVER Dialog.</span></div>
<div style="position:absolute;left:103.99px;top:115.00px" class="cls_014"><span class="cls_014">19.hiscrt()</span></div>
<div style="position:absolute;left:121.99px;top:130.76px" class="cls_011"><span class="cls_011">This function is used to open the file that stores the name and highscore</span></div>
<div style="position:absolute;left:121.99px;top:147.26px" class="cls_011"><span class="cls_011">and update (write) the name along with the new highscore using files in</span></div>
<div style="position:absolute;left:121.99px;top:163.01px" class="cls_011"><span class="cls_011">C++.</span></div>
<div style="position:absolute;left:103.99px;top:195.26px" class="cls_014"><span class="cls_014">20.hisrd()</span></div>
<div style="position:absolute;left:121.99px;top:211.76px" class="cls_011"><span class="cls_011">This function is used to access (read) the file that stores the name and</span></div>
<div style="position:absolute;left:121.99px;top:227.51px" class="cls_011"><span class="cls_011">highscore and display it on the screen using files in C++.</span></div>
<div style="position:absolute;left:103.99px;top:259.76px" class="cls_014"><span class="cls_014">21.option()</span></div>
<div style="position:absolute;left:121.99px;top:276.26px" class="cls_011"><span class="cls_011">This function is used for displaying the Game Options.</span></div>
<div style="position:absolute;left:103.99px;top:307.76px" class="cls_014"><span class="cls_014">22.difficulty()</span></div>
<div style="position:absolute;left:121.99px;top:324.26px" class="cls_011"><span class="cls_011">This  function  is  used  for  displaying  and  choosing  among  the</span></div>
<div style="position:absolute;left:518.67px;top:324.26px" class="cls_011"><span class="cls_011">3</span></div>
<div style="position:absolute;left:121.99px;top:340.01px" class="cls_011"><span class="cls_011">Difficulty Levels (Easy, Medium, Hard) by using switch.</span></div>
<div style="position:absolute;left:103.99px;top:372.26px" class="cls_014"><span class="cls_014">23.intro()</span></div>
<div style="position:absolute;left:121.99px;top:388.76px" class="cls_011"><span class="cls_011">This function is used for displaying the Game Instructions.</span></div>
<div style="position:absolute;left:103.99px;top:421.01px" class="cls_014"><span class="cls_014">24.about()</span></div>
<div style="position:absolute;left:121.99px;top:436.76px" class="cls_011"><span class="cls_011">This  function  is  used  for  displaying  the  About  the  Developers</span></div>
<div style="position:absolute;left:121.99px;top:453.26px" class="cls_011"><span class="cls_011">information.</span></div>
<div style="position:absolute;left:103.99px;top:485.51px" class="cls_014"><span class="cls_014">25.quit()</span></div>
<div style="position:absolute;left:121.99px;top:501.26px" class="cls_011"><span class="cls_011">This function is used to display the Thank You for Playing message</span></div>
<div style="position:absolute;left:121.99px;top:517.01px" class="cls_011"><span class="cls_011">before quitting the game.</span></div>
<div style="position:absolute;left:103.99px;top:549.26px" class="cls_014"><span class="cls_014">26.pausegame()</span></div>
<div style="position:absolute;left:121.99px;top:565.76px" class="cls_011"><span class="cls_011">This function is used for playing / pausing the game.</span></div>
</div>
<div style="position:absolute;left:50%;margin-left:-306px;top:18446px;width:612px;height:792px;border-style:outset;overflow:hidden">
<div style="position:absolute;left:0px;top:0px">
<img src="14f25f82-3018-11eb-8b25-0cc47a792c0a_id_14f25f82-3018-11eb-8b25-0cc47a792c0a_files/background24.jpg" width=612 height=792></div>
<div style="position:absolute;left:99.49px;top:69.00px" class="cls_017"><span class="cls_017">References</span></div>
<div style="position:absolute;left:103.99px;top:115.75px" class="cls_011"><span class="cls_011">1.</span><span class="cls_020"> </span><A HREF="https://www.wikipedia.org/">https://www.wikipedia.org/</A> </span></div>
<div style="position:absolute;left:103.99px;top:131.51px" class="cls_011"><span class="cls_011">2.</span><span class="cls_020"> </span><A HREF="https://www.geeksforgeeks.org/">https://www.geeksforgeeks.org/</A> </span></div>
<div style="position:absolute;left:103.99px;top:148.01px" class="cls_011"><span class="cls_011">3.</span><span class="cls_020"> </span><A HREF="https://stackoverflow.com/">https://stackoverflow.com/</A> </span></div>
<div style="position:absolute;left:103.99px;top:163.76px" class="cls_011"><span class="cls_011">4.</span><span class="cls_020"> </span><A HREF="https://medium.com/">https://medium.com/</A> </span></div>
<div style="position:absolute;left:103.99px;top:180.26px" class="cls_011"><span class="cls_011">5. </span><A HREF="https://github.com/">https://github.com/</A> </div>
<div style="position:absolute;left:99.49px;top:211.50px" class="cls_017"><span class="cls_017">Code Link</span></div>
<div style="position:absolute;left:103.99px;top:250.76px" class="cls_011"><span class="cls_011">1. </span><A HREF="https://github.com/atishaykatiyar/snake_game/">https://github.com/AtishayKatiyar/Snake_Game</A> </div>
</div>

</body>
</html>
