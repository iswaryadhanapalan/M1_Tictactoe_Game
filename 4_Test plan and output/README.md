
# TEST PLAN:
## High level test plan
Test ID: H_01-Check if the graph for playing is being drawn or not.Exp I/P:No input.Exp O/P:3X3 graph is drawn.
Test ID: H_02-Check if player/computer got 3 of his inputs in vertical, horizontal or diagonal format.Exp I/P:'X' or 'O' i/p from the user/computer.Exp O/P:The user/computer won the game.
Test ID: H_03-Check for draw.Exp I/P:9 inputs from (user+computer).Exp O/P:	The game is over.
## Low level test plan
Test ID: L_01-Checking for the basic requirement to the game, i.e., a 3X3 graph is drawn or not. This 3X3 graph is the basic need to play the game as it is like a game board for the game.Exp I/P:Not input expected from the user.Exp O/P:3X3 graph is drawn.
Test ID: L_02-Play proceeds with the user/computer alternately placing their marks in any unoccupied cell. Check if any player/computer finishes with 3 marks in a row(vertical, horizontal or diagonal).Exp I/P: 'X' or 'O' i/p from the user/computer.Exp O/P:The user/computer won the game.
Test ID: L_03-Check if a total of 9 moves have been made( combining that of user and computer), the game ends up in a draw when neither the user nor the computer is able to get 3 marks in a row.Exp I/P:9 inputs from (user+computer).Exp O/P:The game is over. Somebody won or the game ended as a draw.
