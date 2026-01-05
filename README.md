# CODE-BREAKER-KARAOKE
A multiplayer code-breaking game in Python simulating a Mastermind-style challenge between players and a computer.

**The Logic Game:**
The logic game works similarly to the board game “Mastermind”. It is a two-player code breaking
game where each player secretly writes down a three-digit secret number (with no repeating digits
and no zeros). The players then take turns guessing each other's secret number, receiving feedback
after each guess. In our case, one of the two players is a computer. The feedback works as follows:
• A “+” for each digit that is correct and in the correct position.
• A “–” for each digit that is correct but in the wrong position.
Example: If a secret number is 589 and the guess is 982, the feedback would be “+-” (or “-+”
because:
• 8 is in the correct position.
• 9 is correct but in the wrong position.
