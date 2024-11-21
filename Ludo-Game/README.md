# Dice Game: Race to 50

This Python script is a turn-based dice game where 2-4 players compete to reach a score of 50 first. Players roll a dice to accumulate points, but rolling a `1` ends their turn with no points for that round.

---

## How to Play

1. **Setup**:
   - Run the script, and input the number of players (between 2 and 4).
   - Each player starts with a score of `0`.

2. **Taking Turns**:
   - Players take turns rolling a six-sided dice.
   - If a player rolls a `1`, their turn ends immediately, and they score no points for that round.
   - If they roll a value between `2-6`, it gets added to their current turn score.
   - Players can choose to stop rolling to "bank" their current turn score into their total score.

3. **Winning**:
   - The first player to reach or exceed a score of 50 wins the game.

---

## Example Gameplay

### Input:
```plaintext
Enter the number of players (2 - 4): 3
