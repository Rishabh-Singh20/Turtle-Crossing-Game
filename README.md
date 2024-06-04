Turtle crossing game using TurtlePy.

Make the turtle cross the traffic without hitting them. Turtle can only walk forward. Speed of the traffic increases once crossed.

car_manager.py is responsible for the functioning of the cars. It controls the size, colour and position on the board. It also
increases speed once the turtle manages to cross the board without hitting any car.

player.py determines the colour, starting place and movement of the turtle.

scoreboard.py is responsible for updating the scoreboard and to deliever the "GAME OVER" message if turtle hits the car.

main.py controls everything for the efficient functioning of the game. It manages the screen, to listen to the input given by the player,
and to call the functions whenever required during the execution of the game.
