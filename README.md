# Monospaced bitmap Unicode fonts for HFSM2 and FFSM2 libraries

- Bounding Box: **5x11**
- Uppercase Height: **7px**
- Lowercase Height: **5px**
- Numeric Height: **6px**
- Character Width: **4px**
- Ascend: **9px**
- Descend: **2px**
- Encoding: **Unicode**
- Bases and Inspirations:
  - **[creep](https://github.com/romeovs/creep)**
  - **[creep2](https://github.com/raymond-w-ko/creep2)**
  - **[Mochi](https://addy-dclxvi.github.io/post/bitmap-fonts/#mochi)**
- Editor:
  - **[Bits'N'Picas](https://github.com/kreativekorp/bitsnpicas)** ❤

---

## Features

- Basic Latin Glyphs (adjusted, originally from **[creep](https://github.com/romeovs/creep)**)
  ```
  ABCDEFGHIJKLMNOPQRSTUVWXYZ ;: <?> {~!@#$%^&*()_+}
  abcdefghijklmnopqrstuvwxyz ,. \|/ [`1234567890-=]
  ```
  - Redrawn `aecrzGZ` and some others
  - Adjusted braces and arithmetic operators after staring at code for hours

  <details>
    <summary>Example</summary>

    ```
    long console output here
    ```
  </details>

- Latin Glyphs with Diacritics (adjusted, originally from **[creep](https://github.com/romeovs/creep)** and **[Mochi](https://addy-dclxvi.github.io/post/bitmap-fonts/#mochi)**)
  ```
  Příliš žluťoučký kůň úpěl ďábelské ódy
  ```
  - reduced height of capital letters (e.g. `ŘÍIŠŽŤČÝŮŇÚĚĎÁÉÓ`) for legibility
  - some are still missing!

- Basic Cyrillic Glyphs (hand-drawn)
  ```
  АБВГҐДЕЄЖЗИІЇЙКЛМНОПРСТУФХЦЧШЩЬЮЯ {₴!"№;%:?*()_+}
  абвгґдеєжзиіїйклмнопрстуфхцчшщьюя ['1234567890-=]
  ```

- Non-Ukrainian Cyrillic Glyphs (hand-drawn)

- Greek Glyphs (few adjusted, but mostly from **[creep](https://github.com/romeovs/creep)**)
  ```
  αβγδεζηθικλμνξοπρσςτυφχψω
  ΑΒΓΔΕΖΗΘΙΚΛΜΝΞΟΠΡΣ ΤΥΦΧΨΩ
  ```

- Sub- and Super-Script (hand-drawn)
  ```
  ⁱⁿ ⁽⁰¹⁺²³⁴⁻⁵⁶⁼⁷⁸⁹⁾ ºª
  ₑₔ ₍₀₁₊₂₃₄₋₅₆₌₇₈₉₎ ₐₒₓₕₖₗₘₙₚₛₜ
  ```

- Fraction Glyphs (hand-drawn)
  ```
  ⁄ ⅟ ½ ↉ ⅓ ⅔ ¼ ¾ ⅕ ⅖ ⅗ ⅘ ⅙ ⅚ ⅐ ⅛ ⅜ ⅝ ⅞ ⅑ ⅒
  ```

- Arrows, math symbols, dingbats, etc. (hand-drawn and from **[Mochi](https://addy-dclxvi.github.io/post/bitmap-fonts/#mochi)**)

- **[Box Drawing and Block Elements](https://github.com/romeovs/creep#box-drawing)** (from **[creep](https://github.com/romeovs/creep)**)

- **[Braille](https://github.com/romeovs/creep#braille-and-drawille)** (from **[creep](https://github.com/romeovs/creep)**)

---

## Motivation

1. [**Box Drawing**](https://github.com/romeovs/creep#box-drawing) for [**FSM Debug Draw**](https://gresyk.dev/features/2018/01/15/hfsm-magic.html):
  ```
	 ┌ TopLevelState
	 └ TopLevelRegion
	   ╟ OrthogonalRegion
	   ║ ╟ OrthogonalState1
	   ║ ╙ OrthogonalState2
	   ╟─┬ PeerState1
	   ║ └ PeerState2
	   ╟ CompositeRegion
	   ║ ├ CompositeState1
	   ║ └ CompositeState2
	   ╙─╥ OrthogonalPeerState1
		 ╙ OrthogonalPeerState2
  ```
1. Crisp and clean font for programming
1. Cyrillics support
1. Arrows, math symbols, dingbats, etc. so spice up the boring text

---

## Previously Used Fonts

- Vector fonts (with Clear Type)
  - **[Onuava](https://www.dafont.com/onuava.font)** @7px
  - **[Sudo](https://www.kutilek.de/sudo-font/)** @8px

---

## See Also

- **[HFSM2](https://hfsm.dev)**: High-Performance **Hierarchical** Finite State Machine
- **[FFSM2](https://flat.hfsm.dev)**: High-Performance **Flat** Finite State Machine

---

## Get In Touch

- Twitter: **[@andrew_gresyk](https://www.twitter.com/andrew_gresyk)**
- Discord: **[HFSM.dev](https://discord.gg/v4t3tzh)**

---

## Special Thanks

- **[Lorem Ipsum](https://www.lipsum.com/)**
