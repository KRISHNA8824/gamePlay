# gamePlay
This is an spring boot application to create a rest Api for the game Rock, Paper, Scissor. The api takes a parameter which is the move of player1(Rock, Scissor, Paper). In spring boot application there is a random funtion which generates a random move for player2. Then it compares both move and returns if player1 wins, loses or tie.

RestApi takes an parameter in this format

{
   "input": "Rock"
}

we can also put paper or scissor instead Rock which will act as player1 move.