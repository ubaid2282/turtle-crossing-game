# Turtle Crossing Game

A simple arcade-style game built using Python's `turtle` module. The objective is to help the turtle cross the road while avoiding moving cars. The game gets progressively harder as the player advances.

## 🛠 Features
- Player-controlled turtle using the `Up` arrow key.
- Randomly generated moving cars.
- Increasing difficulty with each successful crossing.
- Score tracking with level increments.
- Game over when the turtle collides with a car.

## 🌜 How to Play
1. Run the `main.py` script.
2. Use the `Up` arrow key to move the turtle upwards.
3. Avoid incoming cars.
4. Reach the top of the screen to advance to the next level.
5. If you collide with a car, the game ends.

## 🏠 Project Structure
```
📂 turtle-crossing-game/
│-- 💜 main.py          # Main game loop and event handling
│-- 💜 player.py        # Player (turtle) movement logic
│-- 💜 car_manager.py   # Car creation and movement
│-- 💜 scoreboard.py    # Score tracking and level management
```

## 🖥 Requirements
- Python 3.x
- `turtle` module (built-in with Python)
- `time` module (built-in with Python)

## ▶️ Running the Game
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/turtle-crossing-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd turtle-crossing-game
   ```
3. Run the game:
   ```bash
   python main.py
   ```

## 📌 Future Improvements
- Add sound effects for collisions and level-ups.
- Implement difficulty settings.
- Introduce power-ups and obstacles.

## 📝 License
This project is licensed under the MIT License.

---

Enjoy playing the Turtle Crossing Game! 🐢🚗🎮

