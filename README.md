# Hoppy Heights

**Hoppy Heights** is a simple 2D platformer game written in MIPS Assembly as the final project for the course **CSCB58: Computer Organization** at the University of Toronto. The player controls a frog that jumps across floating platforms, collects power-ups, and avoids falling. The game is designed to run on a bitmap display using basic assembly logic for movement, collision detection, health tracking, and gravity simulation.

---

## How to Play

- The frog starts at the bottom of the screen and must jump upward by landing on platforms.
- Use the **WASD** keys to control the frog's movement.
- Collect hearts and power-ups to maintain your health and progress through the level.
- The game ends when the player falls off the screen or loses all health.
- The objective is to reach the top platform.

### Power-Ups

- **Red Mushroom** – Slows gravity.
- **Purple Mushroom** – Grants a double jump ability.
- **Pink Mushroom** – Restores 1 health (up to a maximum of 3 hearts).

---

## Bitmap Display Configuration

The game uses a bitmap display with the following configuration:

- **Unit Width in Pixels:** 8  
- **Unit Height in Pixels:** 8  
- **Display Width in Pixels:** 512  
- **Display Height in Pixels:** 512  
- **Base Address for Display:** `0x10008000 ($gp)`

---

## 🛠 Installation & Setup

1. Download the [MARS MIPS Simulator](https://computerscience.missouristate.edu/mars-mips-simulator.htm).
2. Open `game.asm` in MARS.
3. Go to **Tools > Bitmap Display** and configure the display using the settings above.
4. Assemble and run the program.
