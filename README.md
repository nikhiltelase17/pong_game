# Pong: Relive the Retro Rivalry**

**Welcome to the classic game of Pong, brought to life with Python!** Get ready to test your reflexes and challenge your friends in this two-player battle of pixelated paddles and bouncing balls. 

## Getting Started

**1. Prerequisites:**

- **Python 3.x:** Ensure you have Python installed on your system. Download it here if needed: [https://www.python.org/downloads/](https://www.python.org/downloads/)
- **Libraries:** The game uses the `turtle` library, which is usually included with Python. If not, install it using `pip install turtle` in your terminal.

**2. Running the Game:**

1. **Clone the repository:** Open your terminal or command prompt and navigate to your desired directory. Then, clone the repository using the following command:

   ```bash
   git clone https://github.com/nikhiltelase17/pong_game
   ```

2. **Navigate to the project directory:**

   ```bash
   cd pong
   ```

3. **Run the game:**

   ```bash
   python pong.py
   ```

**3. Playing the Game:**

- **Player 1:** Controls the right paddle using the "Up" and "Down" arrow keys.
- **Player 2:** Controls the left paddle using the "W" and "S" keys.
- **Goal:** Keep the ball bouncing and prevent it from hitting your paddle's side of the screen. The first player to score 10 points wins!

## How It Works

- **Screen Setup:** The game uses the `turtle` library to create a visual interface, setting the screen dimensions, background color, and title.
- **Object Creation:** It creates paddles, a ball, and a scoreboard, each with their own properties and behaviors.
- **Keyboard Controls:** The game listens for keyboard events and binds specific keys to control the paddles' movements.
- **Game Loop:** The core of the game runs in a continuous loop, performing the following actions:
    - Updates the ball's position and movement.
    - Detects collisions with walls and paddles, adjusting the ball's trajectory accordingly.
    - Updates the scoreboard based on player scores.
    - Checks for a winning condition (10 points scored).

## Customization

Feel free to explore the code and experiment with different settings to personalize your Pong experience:

- **Adjust speed:** Change the ball's speed by modifying the `time.sleep()` value in the game loop.
- **Change colors:** Modify the colors of the paddles, ball, and background using `turtle.color()` functions.
- **Add features:** Explore adding new features like power-ups, sound effects, or different game modes.

**Have fun, challenge your friends, and unleash your inner Pong champion!** 
