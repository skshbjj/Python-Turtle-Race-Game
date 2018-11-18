Features:

Fun to play!
Simple Python code
Easy to install
Depends only on the Python Standard Library
 
 
 
 
Python Turtle Graphics:

With turtle graphics you can make drawings in a window, using a special set of commands. In computer graphics, turtle graphics are vector graphics using a relative cursor (the "turtle") upon a Cartesian plane. Turtle graphics is a key feature of the Logo programming language.[ Your page should start with the line:
from turtle import *
The * means “everything”.   You’re importing all the turtle functions into your code, so you can use them to draw.
The idea is that there is a turtle on the screen that you can give commands. 

The turtle has three attributes: a location, an orientation (or direction), and a pen. The pen, too, has attributes: color, width, and on/off state.

The turtle moves with commands that are relative to its own position, such as "move forward 10 spaces" and "turn left 90 degrees". The pen carried by the turtle can also be controlled, by enabling it, setting its color, or setting its width. A student could understand (and predict and reason about) the turtle's motion by imagining what they would do if they were the turtle. Seymour Papert called this "body syntonic" reasoning.

A full turtle graphics system requires control flow, procedures, and recursion: many turtle drawing programs fall short. From these building blocks one can build more complex shapes like squares, triangles, circles and other composite figures. The idea of turtle graphics, for example is useful in a Lindenmayer system for generating fractals.

Turtle geometry is also sometimes used in graphics environments as an alternative to a strictly coordinate-addressed graphics system.


For example: This little program draws a triangle.

from turtle import *
fd(100)
lt(120)
fd(100)
lt(120)
fd(100)
lt(120)
fd means “go forward”, and the number is the distance.
lt means “left turn”, and the number is the angle in degrees.
Here are some more commands:
rt(100) -> Right Turn
circle(50)
                        pd() -> Pen Down
pu() -> Pen Up
color("red")
pensize(5)
 
Loops
Loops in python are a way to do something over and over. The following code is an example in turtle program:
for i in range(4):
    fd(100)
    lt(90)

Filling
You can fill in parts of your drawing with the two commands begin_fill() and end_fill(). Like the following:

color("red", "blue")
penwidth(5)
begin_fill()
for i in range(4):
    fd(100)
    lt(90)
end_fill()


RANDOM Library: 

This is a core module in Python. The random module generates random numbers.


Most important functions: 

random.getrandbits(bits) - return bits of randomness
random.random() - return a random decimal number >= 0.0 but <= 1.0
random.shuffle(dict) - shuffle a dict and return the shuffled version
random.seed(seed) - seed the PRNG with seed, useful for debugging only, the PRNG is usually auto-seeded
random.randint(min, max) - return a random number >= min but <= max
