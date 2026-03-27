# PokéDesk

A desktop companion app that lets Pokémon roam freely on your Windows desktop. Spawn your favourite Pokémon from all generations and watch them wander across your screen — above every window, below every click.

## Demo

![PokéDesk on Desktop](static/demo.png)

---

## Features

- **Pokémon from Gen 1 (Kanto), Gen 2 (Johto), Gen 3 (Hoenn), and Gen 4 (Sinnoh)** — more generations to follow as [vscode-pokemon](https://github.com/jakobhoeg/vscode-pokemon) adds them
- **Animated sprites** — walk and idle GIFs at 8fps, with proper directional flipping
- **Multiple pets** at once, each roaming independently with their own walk/idle cycle
- **Full-screen transparent overlay** — pets float above your desktop without blocking anything
- **Click-through** — transparent areas pass clicks straight to your desktop
- **Taskbar-aware** — pets walk above the taskbar, never over it
- **Drag** pets to reposition them anywhere on screen
- **Double-click** a pet for an excited reaction
- **System tray menu**:
  - Per-generation submenus with the full catalog
  - Speed controls (Slow / Normal / Fast)
  - Size controls (Small / Normal / Big / Huge)
  - Remove Last Pet / Remove All Pets
  - Quit

---

## Credits & Special Thanks

PokéDesk would not exist without the following projects and their creators:

### Pokémon Sprites
All animated Pokémon sprites (walk and idle GIFs) are sourced from:

**[vscode-pokemon](https://github.com/jakobhoeg/vscode-pokemon)** by [jakobhoeg](https://github.com/jakobhoeg)
— A VS Code / Cursor extension that adds nostalgic Pokémon sprites to your code editor. The manually crafted 8fps animated GIFs for all 565 Pokémon across four generations are what make PokéDesk possible. If you enjoy the sprites, consider [sponsoring jakobhoeg](https://github.com/sponsors/jakobhoeg).

> Pokémon sprites: © The Pokémon Company / Nintendo / Game Freak. Used here for non-commercial, fan project purposes only.

---

### Inspiration

**[DeskPets](https://github.com/Jumitti/DeskPets)** by [Jumitti](https://github.com/Jumitti)
— A Python-based desktop pet app for Windows that proved the concept of sprite-based desktop companions outside of a code editor. The idea of taking VS Code pets and setting them free on the whole desktop directly inspired PokéDesk's approach.

**[vscode-pets](https://github.com/tonybaloney/vscode-pets)** by [tonybaloney](https://github.com/tonybaloney)
— The original VS Code extension that started it all — small animated pixel creatures living in your editor. vscode-pokemon and DeskPets are both built on the foundation that tonybaloney laid.

---

## Disclaimer

PokéDesk is an unofficial fan project and is not affiliated with, endorsed by, or connected to Nintendo, The Pokémon Company, or Game Freak in any way. All Pokémon names and sprites are property of their respective owners.
