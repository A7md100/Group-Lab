# # Game Instructions

- Game Name: `Rock, Paper, Scissors`
- Objective: The game aims to beat your opponent by choosing the fitting hand gesture.

# Instructions
```markdown
The game is played between two players, and each player chooses one of three possible hand gestures: `rock`, `Paper`, or `Scissors`.
The game is typically played over a series of rounds, with the first player to win a set number of matches being declared the winner.
In each round, the players simultaneously reveal their chosen hand gesture, and the winner of the round is determined based on a set of rules:
`rock` beats `Scissors` (`rock` crushes `Scissors`)
`Scissors` beat `Paper` (`Scissors` cut `Paper`)
`Paper` beats `rock` (`Paper` covers `rock`)
If both players choose the same hand gesture, the round is tied and must be replayed until a winner is determined.
```
# Algorithmic Explanation
```markdown
Start the game by setting a variable to keep track of the number of rounds to be played.
While the number of rounds is greater than 0, repeat the following steps:
a. Prompt each player to choose their hand gesture (`rock`, `Paper`, or `Scissors`).
b. Compare the choices made by each player using a set of conditional statements:
If player 1 chooses `rock` and player 2 chooses `Scissors`, player 1 wins the round.
If player 1 chooses `Scissors` and player 2 chooses `Paper`, player 1 wins the round.
If player 1 chooses `Paper` and player 2 chooses `rock`, player 1 wins the round.
If player 2 chooses `rock` and player 1 chooses `Scissors`, player 2 wins the round.
If player 2 chooses `Scissors` and player 1 chooses `Paper`, player 2 wins the round.
If player 2 chooses `Paper` and player 1 chooses `rock`, player 2 wins the round.
If both players make the same choice, the round is tied and must be replayed.
c. Display the round winner, and update each player's score accordingly.
d. Decrement the number of rounds remaining.
When the game ends, declare the winner based on the player with the highest score.
```
