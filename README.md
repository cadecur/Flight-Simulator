# Project I: Flight Simulator

## CSCI 155 Computer Graphics, Spring 2019

### Purpose

This project brings together many of the topics we have covered in Module I by implementing:

- viewing
- shading
- interaction
- geometry

### The Problem Set

The problems are defined in `main.tex` which is to be compiled using a LaTeX compiler.

### Grading

The marks for this assignment are shown in `rubric.csv`.

### Submission

There are 2 parts to the submission.

#### 1. Problem Set

Make sure to submit _all_ required files, e.g. the `Common` folder, or make sure that your code includes them over the Internet.

_Deadline_: 7 p.m. on Monday, April 15 on GitHub.

#### 2. Feedback Form
Every student has to submit feedback on the project at [`Sakai -> Tests & Quizzes`](https://sakai.claremont.edu/x/u9zokH). It is recommended that you fill this as soon as you submit your solution but the deadline is 2 days later just in case.

_Deadline_: 7 p.m. on Wednesday, April 17 on [`Sakai -> Tests & Quizzes`](https://sakai.claremont.edu/x/u9zokH).

### Review Notes

Add your notes at the end of this README by including a new section with the heading, _Submission Notes_. These notes would include information on

- the controls
- any choices you have made in the code with regard to efficiency 
- any bonus functionality you have implemented

### Discussion

There is a lot to handle and there are bound to be confusions and queries. Please share them using the following avenues.

- discuss with your teammate
- post in the [class forum](https://workplace.facebook.com/groups/354167592088891/)
- discuss with your peers in the [discussion sessions](https://workplace.facebook.com/groups/354167592088891/permalink/382523642586619/)
- talk to me in our meeting
- talk to me after class

### Tips

- There is no late submission. Submit whatever you have by the deadline.
- Failure to turn in any of the above submissions will result in a withholding of marks for the homework.
- Clearly indicate your program's controls on the page, e.g. by displaying some informative text.
- Include all necessary files.
- viel Spaß!

# Controls
You can control the speed of your plan with the W and S keys.  You can control the yaw of your plane with the A and D keys.  You can control the pitch of your plane with the up and down arrow keys.  You can control the roll of your plane with the left and right arrow keys.


# Efficiency
We implemented the following code efficiency:

## Terrain Generation
We manage to make our load time per chunk relatively low using the speed efficient perlin function to generate our height.

## Chunk Saving
We were able to cut down more time by saving chunks we have previously for when we come back to them.

# Bonus
We implemented the following bonus functionalities:

## Skybox
We implemented a basic skybox that gives the world a more natural look, instead of the white or black background it typically is.  This also allows us to adjust the 'render distance' of our simulator, as we can grow or shrink the skybox.

## Smooth terrain
Due to our use of perlin noise, we were able to achieve terrain smoothness, where there are no jagged jumps or valleys, but isntead a single continuous smooth look.

## Fog
We implemented a fog effect which, when turned up slightly, can hide the generation of far away chunks.