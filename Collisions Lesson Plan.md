## Formal Lesson Plan: Introduction to Collisions using p5.js

### Details:
9th grade
23 students
45 minutes

### Objective:
Students will be able to import the p5.js collisions library and make the colors change when two shapes collide.

### Materials:
- Laptop
- https://15-collisions-answer.yenminyoung.repl.co/
- https://editor.p5js.org/p52dcollide/collections/taUUdSGhj
- https://replit.com/@yenminyoung/15-Collisions#script.js
- https://docs.google.com/presentation/d/1iZNIENY7XXF95NU3CCVr326pHcBoTdkkc4hnq4n9O8w/edit#slide=id.g12406bde2a6_0_15

### Agenda:
1. Warm-Up: On Google Classroom, students will open up this link (https://15-collisions-answer.yenminyoung.repl.co/) and explore the final product they will make.  They should note their observations about what it does. (Share in chat)
2. Mini-Lesson:
    - Students fork the starter code (https://replit.com/@yenminyoung/15-Collisions#script.js) and the teacher briefly explains what the code starts out as.
    - Code along with the teacher as she walks through the steps
    - Step 1: Import the Collision library in the .html file (You should get a new message in the console as confirmation)
    - Collisions are mathematical functions that calculate the difference between two shapes. The distance depends on the type of shape used, so there are different functions for different combinations of shapes.
    - All of the collision functions can be found here (https://editor.p5js.org/p52dcollide/collections/taUUdSGhj)
    - Each collision function starts with "collide" and then combines two shapes together. The number of parameters correspond to the parameters of each individual shape.
    - In our demo, we will be checking to see if our mouse pointer hits the circle, so we will use collidePointCircle(x1, y1, x2, y2, size)
    - Step 2: Define a "hit" variable and assign the value of the collision to "hit"
    - Step 3: Write a conditional statement: if they collide, change the color.
    - Pause for questions.
    - Demonstrate how to do it for the rectangle. This demonstrates how to make separate variables to keep the concepts separate, and how to replace an argument with a variable.
    - If they forget the steps, they can always go back to the powerpoint
3. Activity:
    - Students will begin part 1 of the Smiley Faces, and try to make each part of the face change color upon collision.
    - This is a 3 day assignment.
4. Wrap-Up
    - With 3 minutes remaining, ask the students how comfortable they feel with collisions and keeping track of all the steps (finger scale, 1-5)
    - What was a mistake you made? How did you fix it?
