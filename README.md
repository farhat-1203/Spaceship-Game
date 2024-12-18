# Spaceship Game

The **Spaceship Game** is an interactive multiplayer game developed in Python using the Pygame library. Players control their spaceships and compete to shoot each other down. The objective is to deplete your opponent's health while avoiding their bullets.

## Features
- **Multiplayer Gameplay**: Compete against a friend in real-time.
- **Health System**: Each player starts with a set amount of health.
- **Dynamic Controls**: Intuitive controls for both players.
- **Engaging Graphics**: Includes spaceship images and a space-themed background.

## Controls
- **Player 1 (Yellow Spaceship)**:
  - Move: **W** (Up), **A** (Left), **S** (Down), **D** (Right)
  - Shoot: **Spacebar**

- **Player 2 (Red Spaceship)**:
  - Move: **Arrow Keys**
  - Shoot: **Enter**

## Requirements
To run the game, ensure you have Python and Pygame installed. Install the required packages using:
```bash
pip install -r requirements.txt
```

## Steps to Run the Project

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/farhat-1203/Spaceship-Game.git
    cd Spaceship-Game
    ```

2. **Run the Gesture Control Script**:
    Run the Python script to control media through gestures:
    ```bash
    python3 main.py
    ```
    
## Project Structure
```
    spaceship-game/
    ├── main.py                # Main game script
    ├── utility.py             # Utility functions (like collision detection, health management, etc.)
    ├── requirements.txt       # List of dependencies (e.g., Pygame)
    ├── LICENSE                # License file (MIT License)
    └── README.md              # Project documentation
```
