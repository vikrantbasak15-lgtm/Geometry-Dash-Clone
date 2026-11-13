# ◆ Geometry Dash Clone

**A fast, neon-lit 2D platformer that runs in your browser.** Dash, jump, stomp enemies and race through five glowing levels. It is built from a single HTML file with no libraries, no assets and no network required. Everything, including the graphics and sound, is generated in code with Canvas2D and the Web Audio API.

> In-game title: **NEON DRIFT**

---

## 🎮 Play

1. Download or clone the repo.
2. Open `neon-drift.html` in any modern browser. It works straight from `file://`.

---

## ⌨️ Controls

| Action | Keyboard | Mouse | Gamepad |
| --- | --- | --- | --- |
| Move | `A` `D` / `←` `→` | | Left stick / D-pad |
| Jump (hold for higher) | `Space` / `Z` / `W` / `↑` | Left click | `A` / Cross |
| Dash | `Shift` / `J` / `X` / `K` | | `X` / `B` / `RB` |
| Pause | `Esc` / `P` | | Start |
| Restart level | `R` | | Y / Back |
| Mute | `M` | | |
| Fullscreen | `F` | | |
| Confirm (menus) | `Enter` / `Space` / `Z` | Left click | `A` / Cross |

---

## ✨ Features

- **5 handcrafted levels**, each with its own gimmick and colour theme:

  | # | Level | Gimmick |
  | --- | --- | --- |
  | 1 | First Light | Find your feet |
  | 2 | Crossfire | Stomp the sentries |
  | 3 | Phased | Platforms flip on and off |
  | 4 | Scramble | Things break and move |
  | 5 | Ascent | Climb the spire |

- **Tight movement**: variable-height jumps, coyote time, jump buffering, wall sliding and jumping, and a quick dash with a cooldown.
- **Hazards and platforms**: spikes, springs, crumbling blocks, moving platforms and phasing platforms.
- **Enemies**: walkers, spiky enemies, flyers and brutes (which take two stomps).
- **Collectibles**: gems, extra lives and checkpoints.
- **Star ratings**: finish a level for 1 star, finish with zero deaths for a 2nd, and collect 80% of the gems for a 3rd.
- **Progress saved**: best times, star ratings and unlocked levels are stored in `localStorage`.
- **Juicy effects**: screen shake, hit-stop, particle bursts, dash trails and parallax backgrounds.
- **Synthesised audio**: sound effects and music are generated with the Web Audio API.
- **Controller support**: plug in a gamepad and play.

---

## 🧰 Tech stack

- **Vanilla JavaScript**, in a single file
- **Canvas2D** for rendering
- **Web Audio API** for sound effects and music
- **Gamepad API** for controller support
- **localStorage** for saves

---

## 🌐 Browser support

Any modern desktop browser (Chrome, Edge, Firefox, Safari). The game is designed for keyboard, mouse and gamepad, so there are no touch controls.

---

## 📄 License

Add your preferred license here (for example [MIT](https://choosealicense.com/licenses/mit/)).

---

## 👤 Author

Built by **Vikrant Basak**.
