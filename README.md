# Pop Party 🎈

A fast-paced, browser-based clicker game where players race against the clock to pop as many colourful balls as possible before the timer runs out. Built entirely with vanilla web technologies, the game features a responsive layout, CSS animations, and a dynamic JavaScript game loop.

## 🎮 Features

- **Time-Attack Gameplay:** Players are given a strict 30-second time limit to pop balls[cite: 1].
- **Dynamic Targets:** Targets spawn one at a time in randomized colors and coordinates within the game arena.
- **Live HUD:** The top interface cleanly displays the player's current score and remaining seconds in real-time[cite: 2].
- **Post-Game Summary:** Once the timer hits zero, the arena clears and displays the final score alongside a "Play again" button to instantly restart the loop[cite: 3].
- **Responsive UI:** Utilizes CSS Grid, Flexbox, and fluid typography (`clamp()`) to ensure the game board scales perfectly across both desktop and mobile devices.

## 🛠️ Tech Stack

- **HTML5:** Semantic structure with accessibility features (`aria-live`, `role="status"`).
- **CSS3:** Custom properties for themes, linear gradients, and `@keyframes` for smooth "pop-in" animations and hover states.
- **Vanilla JavaScript:** DOM manipulation, event listeners, and `setInterval` logic for the core game loop and timer management.

## 🚀 Getting Started

Since this project has no external dependencies or build steps, running it is incredibly simple:

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/pop-party.git](https://github.com/YOUR-USERNAME/pop-party.git)
   ```
