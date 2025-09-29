# 🎲 Dice Dual Game

A simple Python console-based dice game for **2 to 4 players**.  
The goal is to reach **50 points** first — but beware, rolling a **1** resets your turn’s score!

---

## 📌 Features
- Supports **2 to 4 players**.
- Players take turns rolling a dice.
- Rolling **1** ends the turn and resets that round’s score.
- First player to reach **50 points** wins.

---

## 🕹️ Gameplay
1. Enter the number of players (**2–4**).  
2. Each player takes turns rolling the dice by pressing **Y**.  
3. If a **1** is rolled → turn ends and no points are added.  
4. Otherwise, keep rolling to accumulate points.  
5. The **first player to 50 points wins**!

---

## 💡 Example
```text
Enter the number of players (2-4): 2
Game Begins!

Player 1's turn has just started!
Your total score is: 0

Would you like to roll (Y)?
> Y
You rolled a: 5
Your score is: 5

Would you like to roll (Y)?
> Y
You rolled a: 1
You rolled a 1! Turn done!
Your total score is: 0

-----------------------------------

Player 2's turn has just started!
Your total score is: 0

Would you like to roll (Y)?
> Y
You rolled a: 6
Your score is: 6

Would you like to roll (Y)?
> N
Your total score is: 6

...

🎉 Player 2 is the winner with a score of: 50 🎉
