# MoFahad2921-Turtle_module_smiley_face
Using turtle to draw a smile face emoji in python.

Using the turtle module to create a basic smiley face emoji.

import turtle: imports the turtle module.

s = turtle.Screen(): creates a turtle screen object.

t = turtle.Turtle(): creates a turtle object.

t.pensize(10): sets the thickness of the turtle's pen to 10.

x = 100 and y = 100: sets the x and y coordinates of the turtle's starting position.

t.penup(): lifts the turtle's pen up so it won't draw any lines.

t.goto(x,y): moves the turtle to the (x,y) coordinates without drawing any lines.

t.pendown(): puts the turtle's pen back down so it can draw lines.

t.circle(100): draws a circle with a radius of 100 pixels.

t.penup(): lifts the turtle's pen up again.

t.goto(x-35, y + 120): moves the turtle to the (x-35, y+120) coordinates without drawing any lines.

t.pendown(): puts the turtle's pen back down.

t.dot(25): draws a dot with a diameter of 25 pixels.

t.penup(): lifts the turtle's pen up again.

t.goto(x + 35, y + 120 ): moves the turtle to the (x+35, y+120) coordinates.

t.pendown(): puts the turtle's pen back down.

t.dot(25): draws another dot with a diameter of 25 pixels.

t.penup(): lifts the turtle's pen up again.

t.goto(x - 60 , y + 65): moves the turtle to the (x-60, y+65) coordinates.

t.pendown(): puts the turtle's pen back down.

t.setheading(-60): sets the turtle's heading to -60 degrees.

t.circle(70, 120): draws an arc with a radius of 70 pixels and an angle of 120 degrees.

Overall, this code draws a yellow circle for the face, two black dots for the eyes, and a smile using an arc.
