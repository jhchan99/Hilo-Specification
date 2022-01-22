# Hilo-Specification
First team activity (team 7) 

# Code Planning
There are two classes for this program:

1. The director
2. A card

The following responsibilities, behaviors, and statuses are as follows:

- Director:
1. Resposibilities - Run the game by verifying the conditions of the game are always true before each turn. Keeps track of player's points and cards, and asks the user two questions: if they want another move or what their guess is for the card (whether higher or lower)

2. Behaviors:
    a. Check the points of the player to make sure it is not lower than 0: Points_Below_Zero()
    b. Display the card: Display_Card()
    c. Ask the player for higher or lower: Ask_Higher_Lower()
    d. Display the next card: Display_Card()
    e. Add or subtract points: Point_Adjust()
    f. Ask the player to play again: Play_Again()
    g. Run the program: main()

3. Status:
    a. Player's points - playerPoints (int)
    b. Player's guess - playerGuess (str)
    c. Player's choice to continue - continue (str)
    d. Player's name - name (str)



- Card:
1. Responsibilities - A card to represent a number between 1 and 13

2. Behavior's:
    a. Possess a number - Dealt_Number()

3. Status:
    a. Number on card