
# Aim Trainer Game

This is a simple Python-based aim trainer game created using Pygame. The game helps improve your aiming skills by challenging you to click on growing and shrinking targets within a limited number of lives. Your performance is measured by speed, accuracy, and total hits.

## Features

- **Dynamic Targets**: Targets appear on the screen, grow and shrink, and the player must click on them before they disappear.
- **Performance Metrics**: The game tracks your time, speed, hits, and accuracy.
- **Top Bar**: Displays real-time statistics during the game.
- **End Screen**: Summarizes your performance with key statistics after the game ends.
- **Quit Anytime**: Exit the game by pressing the close button or any key on the keyboard during the end screen.

## How to Play

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/aim-trainer-game.git
   cd aim-trainer-game
   ```

2. **Install Requirements**:
   Ensure you have Python and Pygame installed. If not, you can install Pygame using pip:
   ```bash
   pip install pygame
   ```

3. **Run the Game**:
   Execute the script using Python:
   ```bash
   python aim_trainer.py
   ```

4. **Gameplay**:
   - Targets will start appearing on the screen.
   - Click on the targets as quickly as possible before they shrink and disappear.
   - The game tracks your hits, misses, speed, and accuracy.
   - If you miss too many targets, the game ends, and your stats are displayed on the end screen.

## Example Output

During gameplay, the top bar shows the following stats:
- **Time**: The elapsed time since the start of the game.
- **Speed**: The number of targets hit per second.
- **Hits**: The total number of targets you successfully hit.
- **Lives**: The remaining lives, which decrease each time you miss a target.

After the game ends, you will see a summary screen with your final stats:
- **Time**: Total time played.
- **Speed**: Average speed of hitting targets.
- **Hits**: Total targets hit.
- **Accuracy**: Your accuracy percentage based on hits and total clicks
