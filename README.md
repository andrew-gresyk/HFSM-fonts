# Monospaced bitmap Unicode fonts for **[HFSM2](https://hfsm.dev)** and **[FFSM2](https://flat.hfsm.dev)** libraries

- Bounding Box: **5x11**
- Uppercase Height: **7px**
- Lowercase Height: **5px**
- Numeric Height: **6px**
- Character Width: **4px**
- Ascend: **9px**
- Descend: **2px**
- Encoding: **Unicode**
- Bases and Inspirations:
    - 4x6 **[tom-thumb](https://robey.lag.net/2010/01/23/tiny-monospace-font.html)**
    - 5x8 **[spleen](https://github.com/fcambus/spleen)**
    - 5x9 **[tamzen-9](https://github.com/sunaku/tamzen-font#tamzen-9)**
    - 5x11 **[creep](https://github.com/romeovs/creep)**
    - 5x11 **[creep2](https://github.com/raymond-w-ko/creep2)**
    - 5x11 **[mochi](https://addy-dclxvi.github.io/post/bitmap-fonts/#mochi)**
    - 5x11 **[scientifica](https://github.com/nerdypepper/scientifica)**
- Software:
    - **[Bits'N'Picas](https://github.com/kreativekorp/bitsnpicas)** ❤

---

## Features

- Basic Latin Glyphs (adjusted **[creep](https://github.com/romeovs/creep)**)
    ```
    ABCDEFGHIJKLMNOPQRSTUVWXYZ ;: <?> {~!@#$%^&*()_+}
    abcdefghijklmnopqrstuvwxyz ,. \|/ [`1234567890-=]
    ```
    - Redrawn `aecrzGZ` and some others
    - Adjusted braces and arithmetic operators after staring at code for hours

- Latin Glyphs with Diacritics (adjusted **[creep](https://github.com/romeovs/creep)** and **[Mochi](https://addy-dclxvi.github.io/post/bitmap-fonts/#mochi)**)
    ```
    Příliš žluťoučký kůň úpěl ďábelské ódy.
    Høj bly gom vandt fræk sexquiz på wc.
    Victor jagt zwölf Boxkämpfer quer über den großen Sylter Deich.
    Glāžšķūņa rūķīši dzērumā čiepj Baha koncertflīģeļu vākus.
    Stróż pchnął kość w quiz gędźb vel fax myjń.
    Pijamalı hasta yağız şoföre çabucak güvendi.
    ```
    - reduced height of capital letters (e.g. `ŘÍIŠŽŤČÝŮŇÚĚĎÁÉÓ`)

- Cyrillic Glyphs (hand-drawn)
    ```
    АБВГҐДЕЄЖЗИІЇЙКЛМНОПРСТУФХЦЧШЩЬЮЯ {₴!"№;%:?*()_+}
    абвгґдеєжзиіїйклмнопрстуфхцчшщьюя ['1234567890-=]
    ```

- Greek Glyphs (**[creep](https://github.com/romeovs/creep)**)
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

- Arrows, math symbols, dingbats, etc. (hand-drawn + **[Mochi](https://addy-dclxvi.github.io/post/bitmap-fonts/#mochi)**)

- **[Box Drawing and Block Elements](https://github.com/romeovs/creep#box-drawing)** (from **[creep](https://github.com/romeovs/creep)**)

- **[Braille](https://github.com/romeovs/creep#braille-and-drawille)** (from **[creep](https://github.com/romeovs/creep)**)

---

## Motivation

1. [**Box drawing**](https://github.com/romeovs/creep#box-drawing) for the [**FSM debug draw**](https://gresyk.dev/features/2018/01/15/hfsm-magic.html):
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
1. Arrows, math symbols, dingbats, etc.

---

## Vector Alternative

- 5x11 **[Sudo](https://www.kutilek.de/sudo-font/)** @8px (with Clear Type)

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
