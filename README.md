
# Game Cheat Script

This project provides a Python script for implementing cheats in a game, including features like aimbot and ESP (enemy spotting). The script utilizes the Windows API through ctypes to interact with the game process and manipulate game elements.

## Features:

- **Aimbot**: Automatically aims at the closest enemy by calculating the distance between the player's crosshair and enemy positions.
- **ESP (Enemy Spotting)**: Draws bounding boxes around enemies and places crosshairs on their center to aid in spotting them.
- **Hardware ID Spoofing**: Generates and spoofs a random hardware ID to evade anti-cheat measures.
- **Anti-Cheat Bypass**: Temporarily disables anti-cheat mechanisms by modifying memory addresses within the game process.

## Usage:

1. **Setup**: Ensure Python and the necessary libraries (ctypes) are installed.
2. **Configuration**: Modify the script to specify the game window title and adjust memory addresses and structures according to the target game.
3. **Execution**: Run the script while the game is running to activate the cheats.

## Disclaimer:

This project is for educational purposes only and should not be used for cheating in online games or violating the terms of service of any game. Usage of cheats in multiplayer games may result in penalties or bans. The developers of this project are not responsible for any consequences resulting from the use of this software.
