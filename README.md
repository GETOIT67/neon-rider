# Neon Rider

**Neon Rider** is a browser-based, first-person traffic-racing game set in a neon-lit city at night. Dodge traffic, weave between lanes, build near-miss combos, earn coins, and unlock new motorcycles as you push for a higher score.

## Features

- **High-speed traffic racing** — Navigate multiple lanes of traffic while avoiding collisions.
- **Near-miss scoring** — Get close to other vehicles to build combos and increase your score.
- **Dynamic gameplay** — Brake, change lanes, react to traffic, and try to survive for as long as possible.
- **Motorcycle garage** — Explore a collection of six bikes, each with its own stats and price.
- **Progression system** — Earn coins, purchase bikes, and save your owned and equipped motorcycles.
- **Online leaderboards** — Compete for a place in the top 10 using Supabase integration.
- **Nighttime city environment** — Race through a stylized, neon-inspired urban setting.
- **Music and sound effects** — Enjoy in-game audio with sound controls.
- **Mobile touch controls** — Play on supported touch-screen devices.
- **Claw’d companion** — Interact with the game's pixel-art crab, featuring randomized dialogue, animations, and click-based milestones.

## Getting Started

### Play Online

Visit the project's GitHub repository:

[**Neon Rider — GitHub Repository**](https://github.com/GETOIT67/neon-rider)

If GitHub Pages or another web-hosting service is configured for the project, you can play using its published website.

### Run Locally

1. Download or clone this repository.
2. Keep `index.html` and the game's required audio files together in the same directory.
3. Open `index.html` in a modern web browser.
4. Start a run and try to beat your high score.

To clone the repository, run:

```bash
git clone https://github.com/GETOIT67/neon-rider.git
cd neon-rider
```

Then open `index.html` in your browser.

## Leaderboards

Neon Rider uses **Supabase** to support online score submission and leaderboard rankings.

To enable leaderboard functionality in your own deployment:

1. Create a Supabase project.
2. Configure the required project URL and public client key in the game's source code.
3. Create the `neon_rider_scores` database table with the columns expected by the game.
4. Configure appropriate database permissions and policies for score submissions and leaderboard reads.

**Security note:** Never expose a Supabase service-role key or other secret credentials in client-side code. Use a public client key with appropriately configured database permissions.

The game can be played locally without setting up your own leaderboard backend, although online leaderboard features may not be available.

## Technology

- **HTML5** — Game structure.
- **CSS3** — Interface styling and visual effects.
- **JavaScript** — Gameplay logic, controls, scoring, and progression.
- **Three.js** — 3D rendering and the game environment.
- **Supabase** — Online leaderboard functionality.

## Project Structure

```text
neon-rider/
├── index.html
├── very_scary_neon_rider_music_for_gameplay.mp3
├── private-property.mp3
└── README.md
```

The audio files should remain alongside `index.html` so the game can load its music and sound effects correctly. Other files may be present depending on the current project version.

## Development

Neon Rider is designed to be lightweight and accessible through a web browser without requiring a traditional game-engine installation.

Contributions, testing, bug reports, and suggestions are welcome. Please describe any issue clearly and include the steps needed to reproduce it.

## Credits

Developed by [GETOIT67](https://github.com/GETOIT67).

Thanks to everyone who plays, tests, and supports Neon Rider.

---

**Neon Rider** — Dodge the traffic. Chase the score. Own the night.
