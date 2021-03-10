## AI Tic Tac Toe

Using the Minimax algorithm, an AI Tic Tac Toe game is implemented.

A link to the working app:
https://ai-tic-tac-toe-app.herokuapp.com/

### Explanation

The AI Tic Tac Toe game below uses the MiniMax Algorithm and allows you to face your most competitive/ smartest opponent! The logic behind this algorithm is shown on the image on right. As you can see, the diagrams outline scenarios where the number of possibilites are either minimized or maximized. As you can see, the diagram is a Data Sctructure - tree.

We initially set a range from (-1,0, 1) that will determine a Loss, Tie, or Win, respectively. We have set the computer to be X. A node's siblings represents the move for either X or O player. The Computer needs to determine what the minimization for X and Maximization for O given that it wants to win each scenario (+1) and avoid the loss scenarios (-1). We then use recursion to take the Maximization/ Minimization at a node and it's siblings where we want the computer to take either the shortest or the longest route.
