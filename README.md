# Tic-Tac-Toe
Tic Tac Toe implemented in a HTML+CSS+Javascript interface, combined with an AI with customizable skill level. Features usage of Negamax, and a transposition table. Can also be used as a person vs person interface
___
## Difficulty Levels
Engine difficulty is controlled by a *"difficulty" float* at every move. If a random float generated is greater than the *difficulty float*, then the move made is randomly selected from the remaining legal moves. Otherwise, a perfect move is made.

| Difficulty Level | Chance of Random Move |
| ---------------- | ---------------------:|
| Easy             | 50%                   |
| Hard             | 12%                   |
| Perfect          | 0%                    |
