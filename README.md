# Game Cheat Script

This project is a Python script designed to enhance gameplay in a specific game by implementing various cheat functionalities, including aimbot and ESP (enemy spotting). The script utilizes ctypes to interact with the Windows API for mouse control, window manipulation, and memory access.

## Features:

### Aimbot:
- Automatically aims at the closest enemy within the game window.
- Calculates the distance between the player's crosshair and enemy positions to determine the closest target.
- Moves the mouse cursor to the center of the closest enemy's hitbox for precise targeting.

### ESP (Enemy Spotting):
- Draws bounding boxes around enemy characters to make them more visible on the screen.
- Places crosshairs at the center of enemy characters for quick targeting.

### Hardware ID Spoofing:
- Generates a random hardware ID to bypass certain game security measures.
- Replaces the original hardware ID with the spoofed one to evade detection by anti-cheat systems.

### Anti-Cheat Bypass:
- Temporarily disables the game's anti-cheat mechanisms to allow the cheat functionalities to work without interference.
- Restores the original anti-cheat settings after use to maintain game integrity.

## Usage:
1. Clone the repository to your local machine.
2. Ensure you have Python installed, along with the necessary dependencies (ctypes, time).
3. Modify the script to specify the target game window title and adjust any game-specific memory addresses or structures.
4. Run the script as administrator.
5. Launch the target game and enjoy the cheat functionalities during gameplay.

**Note:** The use of cheat scripts may violate the terms of service of certain games and could result in penalties or bans. This script is intended for educational purposes only and should be used responsibly.

## Disclaimer:
This project is provided for educational purposes only. The authors are not responsible for any misuse or damage caused by the use of this software.
