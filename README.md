**Access the page via [GitHub Pages link](https://font.hfsm.dev) to see correctly rendered text.**

---

# Monospaced bitmap font with Unicode support for **[HFSM2](https://hfsm.dev)** and **[FFSM2](https://flat.hfsm.dev)** libraries

## Specs

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
    - 5x9 **[tamsyn5x9](http://www.fial.com/~scott/tamsyn-font/)**
    - 5x9 **[tamzen-9](https://github.com/sunaku/tamzen-font#tamzen-9)**
    - 5x11 **[creep](https://github.com/romeovs/creep)**
    - 5x11 **[creep2](https://github.com/raymond-w-ko/creep2)**
    - 5x11 **[mochi](https://addy-dclxvi.github.io/post/bitmap-fonts/#mochi)**
    - 5x11 **[scientifica](https://github.com/nerdypepper/scientifica)**
- Software:
    - **[Bits'N'Picas](https://github.com/kreativekorp/bitsnpicas)** ❤

---
## Features

### Basic Latin:
<sub>ABCDEFGHIJKLMNOPQRSTUVWXYZ ;: <?> {~!@#$%^&*()_+}</sub><br>
<sub>abcdefghijklmnopqrstuvwxyz ,. \\|/ [ 1234567890-=]</sub>
```
ABCDEFGHIJKLMNOPQRSTUVWXYZ ;: <?> {~!@#$%^&*()_+}
abcdefghijklmnopqrstuvwxyz ,. \|/ [ 1234567890-=]
```

### Latin with Diacritics:
<sub>Příliš žluťoučký kůň úpěl ďábelské ódy.</sub><br>
<sub>Høj bly gom vandt fræk sexquiz på wc.</sub><br>
<sub>Victor jagt zwölf Boxkämpfer quer über den großen Sylter Deich.</sub><br>
<sub>Glāžšķūņa rūķīši dzērumā čiepj Baha koncertflīģeļu vākus.</sub><br>
<sub>Stróż pchnął kość w quiz gędźb vel fax myjń.</sub><br>
<sub>Pijamalı hasta yağız şoföre çabucak güvendi.</sub>
```
Příliš žluťoučký kůň úpěl ďábelské ódy.
Høj bly gom vandt fræk sexquiz på wc.
Victor jagt zwölf Boxkämpfer quer über den großen Sylter Deich.
Glāžšķūņa rūķīši dzērumā čiepj Baha koncertflīģeļu vākus.
Stróż pchnął kość w quiz gędźb vel fax myjń.
Pijamalı hasta yağız şoföre çabucak güvendi.
```

### Cyrillic:
<sub>АБВГҐДЕЄЖЗИІЇЙКЛМНОПРСТУФХЦЧШЩЬЮЯ {₴!"№;%:?*()_+}</sub><br>
<sub>абвгґдеєжзиіїйклмнопрстуфхцчшщьюя ['1234567890-=]</sub>
```
АБВГҐДЕЄЖЗИІЇЙКЛМНОПРСТУФХЦЧШЩЬЮЯ {₴!"№;%:?*()_+}
абвгґдеєжзиіїйклмнопрстуфхцчшщьюя ['1234567890-=]
```

### Greek:
<sub>αβγδεζηθικλμνξοπρσςτυφχψω</sub><br>
<sub>ΑΒΓΔΕΖΗΘΙΚΛΜΝΞΟΠΡΣ ΤΥΦΧΨΩ</sub>
```
αβγδεζηθικλμνξοπρσςτυφχψω
ΑΒΓΔΕΖΗΘΙΚΛΜΝΞΟΠΡΣ ΤΥΦΧΨΩ
```

### Super- and Sub-Script:
<sub>ⁱₑⁿₔ ⁽₍⁰₀¹₁⁻₋²₂³₃⁴₄⁺₊⁵₅⁶₆⁼₌⁷₇⁸₈⁹₉⁾₎</sub><br>
<br>
<sub>Xⁱⁿ X⁽⁰¹⁺²³⁴⁻⁵⁶⁼⁷⁸⁹⁾ 1º 2ª</sub><br>
<sub>Xₑₔ X₍₀₁₊₂₃₄₋₅₆₌₇₈₉₎ Xₐₒₓₕₖₗₘₙₚₛₜ</sub><br>
<br>
<sub>X⁰ X¹ X² X³ X⁴ X⁵ X⁶ X⁷ X⁸ X⁹ X⁺ X⁻ X⁼ X⁽ X⁾</sub><br>
<sub>Xⁱ Xⁿ Xº Xª</sub><br>
<br>
<sub>X₀ X₁ X₂ X₃ X₄ X₅ X₆ X₇ X₈ X₉ X₊ X₋ X₌ X₍ X₎</sub><br>
<sub>Xₐ Xₑ Xₒ Xₓ Xₔ Xₕ Xₖ Xₗ Xₘ Xₙ Xₚ Xₛ Xₜ</sub><br>
<br>
<sub>Hexamminecobalt chloride: [Co(NH₃)₆]³⁺Cl³⁻</sub>
```
ⁱₑⁿₔ ⁽₍⁰₀¹₁⁻₋²₂³₃⁴₄⁺₊⁵₅⁶₆⁼₌⁷₇⁸₈⁹₉⁾₎

Xⁱⁿ X⁽⁰¹⁺²³⁴⁻⁵⁶⁼⁷⁸⁹⁾ 1º 2ª
Xₑₔ X₍₀₁₊₂₃₄₋₅₆₌₇₈₉₎ Xₐₒₓₕₖₗₘₙₚₛₜ

X⁰ X¹ X² X³ X⁴ X⁵ X⁶ X⁷ X⁸ X⁹ X⁺ X⁻ X⁼ X⁽ X⁾
Xⁱ Xⁿ Xº Xª

X₀ X₁ X₂ X₃ X₄ X₅ X₆ X₇ X₈ X₉ X₊ X₋ X₌ X₍ X₎
Xₐ Xₑ Xₒ Xₓ Xₔ Xₕ Xₖ Xₗ Xₘ Xₙ Xₚ Xₛ Xₜ	

Hexamminecobalt chloride: [Co(NH₃)₆]³⁺Cl³⁻
```

### Fractions:
<sub>⁄ ⅟ ½ ↉ ⅓ ⅔ ¼ ¾ ⅕ ⅖ ⅗ ⅘ ⅙ ⅚ ⅐ ⅛ ⅜ ⅝ ⅞ ⅑ ⅒</sub>
```
⁄ ⅟ ½ ↉ ⅓ ⅔ ¼ ¾ ⅕ ⅖ ⅗ ⅘ ⅙ ⅚ ⅐ ⅛ ⅜ ⅝ ⅞ ⅑ ⅒
```

### Arrows, math symbols, dingbats, etc.

### **[Box Drawing and Block Elements](https://github.com/romeovs/creep#box-drawing)** (from **[creep](https://github.com/romeovs/creep)**):
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

### **[Braille](https://github.com/romeovs/creep#braille-and-drawille)** (from **[creep](https://github.com/romeovs/creep)**)

---
## Tests

- **[diacritics](tests/diacritics.md)**

---
## Vector Alternative

- 5x11 **[Sudo](https://www.kutilek.de/sudo-font/)** @8px

---
## See Also

- **[HFSM2](https://hfsm.dev)**: High-Performance **Hierarchical** Finite State Machine
- **[FFSM2](https://flat.hfsm.dev)**: High-Performance **Flat** Finite State Machine

---
## Get In Touch

- Twitter: **[@andrew_gresyk](https://www.twitter.com/andrew_gresyk)**
- Discord: **[HFSM.dev](https://discord.gg/v4t3tzh)**
