# The-Simon-Game
The **Simon Game** is a memory-based game created using HTML, CSS, JavaScript, and jQuery. The game consists of four colored buttons (red, blue, yellow, and green) that flash in a randomly generated sequence. Players must observe and memorize the flashing pattern, then repeat it by clicking the buttons in the same order.

### Key Features:
- **User Interface**: The game board has four colored buttons laid out in a square, styled using CSS. Each button flashes and animates when activated, providing both visual and audio feedback.
- **Pattern Generation**: Each round, the game generates a random color pattern that increases in complexity as the user progresses. This pattern is stored and presented using JavaScript.
- **Player Interaction**: The player’s input is detected using jQuery. Each button click is compared to the stored sequence to check if the input is correct.
- **Feedback & Sounds**: Every color corresponds to a unique sound effect, enhancing the user experience. jQuery is used for animations (like flashing effects) and sound triggering.
- **Game Logic**: If the player repeats the correct sequence, the game moves to the next level, adding one more color to the pattern. A mistake resets the game, and the user must start over.

The game combines intuitive gameplay with a clean, responsive interface, making it an engaging exercise in memory and focus.
