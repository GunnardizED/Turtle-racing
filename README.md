Turtle Race Game

This is a Python script that simulates a turtle race game using the turtle module. It allows the user to place a bet on the winning turtle color and displays the result of the race.

Prerequisites

    Python 3.x
    Turtle module

Installation

    Make sure you have Python 3.x installed on your system.
    The turtle module is a built-in module in Python, so no additional installation is required.

Usage

    Save the script to a file with a .py extension (e.g., turtle_race.py).
    Run the script using the following command:

    python turtle_race.py

    The turtle race game window will appear.
    Follow the instructions in the prompt to enter your bet. Enter the color of the turtle you think will win the race.
    The race will start automatically.
    After the race finishes, the result will be displayed in the console. If your bet matches the winning turtle color, you will be declared the winner. Otherwise, you will be declared the loser.

Customization

You can customize the following aspects of the turtle race game:

    Window Size: Modify the width and height values in the screen.setup(width=500, height=400) line to change the size of the game window.
    Turtle Colors: Modify the colors list to change the available colors for the turtles.
    Turtle Starting Positions: Modify the y_positions list to change the starting positions of the turtles along the y-axis.
    Race Distance: Modify the rand_distance = random.randint(0, 10) line to change the distance each turtle moves forward in each iteration.
