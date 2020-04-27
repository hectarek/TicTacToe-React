#Welcome to Hector's Tic Tac Toe app!

This was made as part of a in class assignment to learn about react. 

Some of the lessons learned in this include:

- It is best practice to make pure components or components that are not directly mutated. 
    - This is becasue it makes it easier to see what has changed and when to re-render.
- Controlled components - components whose state is controlled by the parent component.
- Lifting up state to the parent will allow it easier to make a history of moves.

If we did not use .slice(), then it would have been really difficult to track the history of each move. 

