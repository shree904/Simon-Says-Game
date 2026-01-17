Simon Says Game 🎮
Developed an interactive memory game using HTML, CSS, and JavaScript that challenges players to recall and repeat an increasing sequence of colors. Implemented core JavaScript concepts such as DOM manipulation, event handling, game state management, and real-time validation with responsive UI styling. Demonstrates strong fundamentals in front-end development and logical problem-solving.

🔹 Game Initialization
The game initializes with empty sequences for both the system (gameSeq) and the user (userSeq). A predefined set of color buttons is used to generate random patterns. The game remains inactive until the user presses any key to begin.
<img width="1918" height="925" alt="image" src="https://github.com/user-attachments/assets/8c5e98ca-b15b-4315-91e6-ef3750bc92ae" />

🔹 Game Start (Level 1)
Upon pressing any key, the game starts and advances to Level 1.
A random color is selected from the available buttons.
The selected button flashes to indicate the system-generated sequence.
The level number is displayed dynamically on the screen.
<img width="1913" height="923" alt="image" src="https://github.com/user-attachments/assets/21e3cc56-dd0e-4372-8857-72addc9ce6da" />

🔹 Level Progression
With each new level:
The game sequence grows by one additional random color.
The entire sequence is visually replayed using button flash animations.
The user must repeat the sequence in the exact order by clicking the buttons.
User input is validated step-by-step in real time.
<img width="1907" height="927" alt="image" src="https://github.com/user-attachments/assets/148d16e7-74b0-4480-80c5-7795bd8ebd08" />

❌ Game Over Condition

If the user clicks an incorrect button:
The game immediately ends.
A Game Over message is displayed along with the final score (level reached).
The background flashes red briefly to indicate failure.
The player is prompted to press any key to restart.
<img width="1917" height="923" alt="image" src="https://github.com/user-attachments/assets/6632cea6-2437-417c-b080-8ba5fb481e25" />




