import turtle as t
import random as rd
import time as ti


def inside_window():
    left_limit = (-t.window_width()/2) + 100
    right_limit = (t.window_width()/2) - 100
    top_limit = (t.window_height()/2) - 100
    bottom_limit = (-t.window_height()/2) + 100
    (x,y) = t.pos()
    inside = left_limit < x < right_limit and bottom_limit < y < top_limit
    return inside

def move_turtle():
    if inside_window():
        angle = rd.randint(0, 100)
        dist = rd.randint(10, 150)
        t.right(angle)
        t.forward(dist)
    else:
        t.backward(100)


t.shape('turtle')
t.fillcolor('red')
t.bgcolor('black')
t.speed('slow')

while True:
    move_turtle()
