# 2D Sandbox Game

A tile-based 2D sandbox game built from scratch in C++ using SFML. Features procedural terrain generation, real-time physics, and fully interactive world editing with buildable and destructible terrain.

![Sandbox Screenshot](https://github.com/user-attachments/assets/8acd5e4e-de91-4925-b3cc-618b4ba1f229)

[▶ Demo Video](screenshots/Terraria_Clone_Building.mov)

---

## Overview

This project started as an exercise in building a game engine architecture from scratch — no game frameworks, just C++ and SFML. The focus was on writing clean, modular systems for rendering, physics, input, and world state that could scale independently as the project grew.

---

## Features

- **Procedural terrain generation** using noise functions for varied, natural-looking worlds
- **Real-time physics** — player movement, gravity, and collision detection against the tile world
- **Interactive world editing** — place and destroy terrain tiles with immediate world updates
- **Chunked world layout** for scalable, performant maps beyond a single screen
- **Sprite-based rendering** with animation support
- **Modular architecture** — rendering, physics, input, and world logic are cleanly separated

---

## Tech Stack

- **Language:** C++17
- **Graphics:** SFML 2.6.x
- **Build System:** CMake
- **Noise Generation:** FastNoise2

---

## Assets

Tileset assets sourced from an open source Terraria asset pack for development and prototyping purposes. All visual assets belong to their respective owners.

---

## License

MIT License

---

## Contact

John Boulanger — [LinkedIn](https://www.linkedin.com/in/john-boulanger-42a706279/) — john03yyc@gmail.com
