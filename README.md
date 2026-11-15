# Mission Architect 🚀

**Design. Explore. Discover.**

An interactive, browser-based educational space exploration game created by **Team Axiom X** for the **2026 NASA Space Apps Challenge**.

**Creators:** Artin Mansouri and Mahoor Kiani

## About the project

Mission Architect lets players experience the trade-offs behind planning and operating space missions. Across three destinations—**Mars, Europa, and Saturn**—players configure spacecraft systems, manage resources, respond to mission events, and complete interactive challenges.

The engineering models are intentionally simplified for educational gameplay. They are **not** mission-grade simulations.

## The missions

### 1. Mars — Design and plan

Configure a spacecraft and its scientific objectives, select propulsion and communications systems, plan an interplanetary transfer, and make operational decisions. Mission assessments consider engineering constraints such as mass, power, fuel, budget, and transfer feasibility.

### 2. Europa — Survive and explore

Choose shielding, power, communications, and transfer options for a mission near Jupiter. Steer through an interactive flight sequence, avoid hazards, collect science signals, and make decisions about spacecraft operations.

### 3. Saturn — Navigate the rings

Configure spacecraft systems, steer through a simulated ring environment, avoid collisions, preserve spacecraft integrity, and attempt a docking sequence.

## How to play

1. Open the game in a modern browser.
2. Begin with the **Mars** mission.
3. Read the briefing and choose spacecraft and mission settings.
4. Check the engineering assessment and launch when your configuration is feasible.
5. Complete the interactive flight stages and mission decisions.
6. Review your score and medal. A **Gold medal (90+ points)** unlocks the next mission.

**Controls**

- **Mars:** Configuration panels and on-screen decision buttons.
- **Europa:** **Left/Right Arrow** or **A/D** to steer; on-screen controls are available for touch devices.
- **Saturn:** Arrow keys or on-screen controls to navigate.

The game includes a limited-attempt progression system and locally saved progress in the browser.

## Run locally

No build process or package installation is required.

1. Download or clone this repository.
2. Keep `index.html` and all three `.webp` landscape images in the same folder.
3. Open `index.html` in a modern browser.

Alternatively, serve the directory locally:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Project files

```text
Mission-Architect/
├── index.html
├── mars-landscape.webp
├── europa-landscape.webp
├── saturn-landscape.webp
└── README.md
```

## Technologies

- **HTML5** — Interface and structure
- **CSS3** — Responsive styling and animations
- **JavaScript** — Engineering rules, events, scoring, and mission progression
- **HTML Canvas** — Interactive spacecraft sequences
- **Browser storage** — Local game progress

## Educational goals

Mission Architect introduces engineering trade-offs in propulsion, mass, power, shielding, communications, scientific operations, navigation, and risk management. Players learn by comparing configurations and observing how choices affect mission outcomes.

## Scientific background

These NASA pages provide useful background on the environments and technologies represented in the game:

- [Mars facts — NASA](https://science.nasa.gov/mars/facts/)
- [Europa facts — NASA](https://science.nasa.gov/jupiter/jupiter-moons/europa/europa-facts/)
- [Saturn facts — NASA](https://science.nasa.gov/saturn/facts/)
- [Cassini mission — NASA](https://science.nasa.gov/mission/cassini/)
- [Radioisotope Power Systems — NASA](https://science.nasa.gov/planetary-science/programs/radioisotope-power-systems/)

**Data note:** The current game does not claim to integrate live NASA APIs or imported NASA scientific datasets. These links are scientific background references, not a claim that specific NASA data files power the simulation.

## AI assistance

OpenAI's ChatGPT assisted with development, debugging, educational writing, interface refinement and project documentation. The creators directed the work, specified requirements, gameplay ideas, evaluated outputs, and refined the final game.

## Future possibilities

Potential improvements include additional destinations, richer engineering simulations, classroom activities, accessibility enhancements, and integration of verified NASA datasets.

## Credits

**Team Axiom X**  
**Created by Artin Mansouri and Mahoor Kiani**

Created for the **2026 NASA Space Apps Challenge**.

Planetary background artwork is included with the game. The team should confirm asset provenance and any required attributions before public release.

## Disclaimer

Mission Architect is an independent educational project and is **not affiliated with, sponsored by, or endorsed by NASA**. Engineering calculations and hazards are simplified for learning and entertainment.

---

**Mission Architect — Design. Explore. Discover.**
