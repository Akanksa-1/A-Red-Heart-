# A-Red-Heart-
import turtle

# Set up the turtle
t = turtle.Turtle()
t.speed(2)  # Set the turtle speed to a moderate value

# Draw a heart shape
t.color("red")
t.fillcolor("red")
t.begin_fill()
t.left(50)
t.forward(133)
t.circle(50, 200)
t.right(140)
t.circle(50, 200)
t.forward(133)
t.end_fill()

# Hide the turtle
t.hideturtle()

# Keep the window open
turtle.done()
