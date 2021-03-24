# Lab-04

Group Members 
- Jack Prescott 
- Avneet Sharma
- Bao Li
- Helen Vincent 

List three data types used in this program.
        
    Strings, Integers, boolean 

List any value variables or reference variables in this program.
 
    gameIsPlaying = True

Give an example of a sequence in this program.
 
Give an example of a condition in this program.
 
    if letter == 'X':
     return ['X', 'O']
    else:
     return ['O', 'X']
  
Give an example of an iteration in this program.

    for i in board:
     dupeBoard.append(i)
     
    return dupeBoard
 
Give an example of a list or collection in this program. What is saved in the list / collection?
 
    move = chooseRandomMoveFromList(board, [1, 3, 7, 9])
    if move != None:
     return move
  
Give an example of a function that has at least one parameter in this program. And, briefly explain what the function is trying to achieve.

        def playAgain():
         print('Do you want to play again? (yes or no)')
         return input().lower().startswith('y')
         
    This function returns True if the player wants to play again, otherwise it returns False.
    
How does the program determine who wins the game? List the functions that the program use to determine the winner.
 
If the code on line 165 is changed from break to gameIsPlaying = False, will this change the behaviour of the program?
 
What does while True: do in this program?

