# 🌀 Dredel-Bike

> A science-fantasy single-track vehicle whose front wheel is a vertically spinning top.

**Dredel-Bike** is a concept-design project: a worldbuilding and image-generation toolkit for an impossible-but-intuitive machine. In place of a front wheel it carries a *dredel* — a broad, lens-shaped spinning top, point-down, with an electric motor sealed inside. The whole vehicle is built around the quiet physical joke that everyone already understands a spinning top and a shopping-trolley caster, so the eye accepts the machine instantly even though it could never exist.

This repository holds the design rationale, a labelled engineering schematic, and a curated set of ready-to-use prompts for generating key-art and technical-drawing imagery of the vehicle in a consistent visual register.

---

## 🔧 What it is

The Dredel-Bike replaces the front wheel's *position and job*, not its geometry:

- **Gyro-top front end.** A lens-shaped top spins about a vertical axis on a single ground-contact point. An electric motor lives inside it; a small internal battery handles regenerative braking.
- **Caster geometry.** The contact point trails *behind* the raked steering axis — exactly like a shopping-trolley caster or a motorcycle's trail. This makes the machine self-centre when travelling straight and lean naturally into the direction it turns.
- **Mass high and aft.** The rider, fuel and a combustion engine are stacked above and behind the centre of gravity. The combustion engine powers the motor directly (a spin-charger) and doubles as the rear counterweight.
- **No rear wheel.** Where a rear wheel would sit, a cantilevered boom carries only the exhaust.

The result reads as an "alternative fantasy transportation" technology: physically impossible, yet immediately legible because it borrows a physical grammar people already trust.

### Why "Dredel"?
A dreidel is a spinning top — and a spinning top is the heart of the machine. The name encodes the whole idea in one word.

---

## 📂 What's in the repo

| File | Description |
| --- | --- |
| `ImagePrompt-Concept.md` | The full prompt set — a shared style spine, 6 key-art prompts, and 6 technical-drawing prompts. |
| `README.md` | This document. |

*(Schematics and generated imagery can be added to an `/assets` folder as the project grows.)*

---

## 🎨 Using the prompts

1. Open `ImagePrompt-Concept.md`.
2. Copy the **shared style spine** at the top — it keeps every image in the same visual world.
3. Pick a prompt (key-art for mood, technical-drawing for engineering views) and prepend or merge the style spine.
4. Paste into your image generator of choice.

**Tip:** image models usually render one clean view more reliably than a packed multi-view drafting sheet. If the multi-view sheet comes out muddy, generate the side elevation, front elevation, and gyro-top cutaway separately and compose them afterwards.

### Visual register
The art direction aims for clean unbroken ink outlines, flat luminous planes of colour, enormous quiet skies, vast empty dunes and salt flats, a lone wandering traveller, and a surreal sense of scale — the sun-bleached retro-future mood of late-1970s/early-1980s French science-fantasy comics. Bodywork stays matte; the spinning gyro-top is the single iridescent jewel in every frame.

---

## ⚠️ Status

This is a **creative concept project**, not an engineering proposal. The physics are deliberately a friendly cheat — the machine is designed to *feel* plausible, not to be buildable. Treat it as worldbuilding and art direction.

---

## 📚 Citation

### Academic Citation
If you use this codebase in your research or project, please cite:
```bibtex
@software{dredel_bike,
  title = {Dredel-Bike: a science-fantasy gyroscopic-top vehicle concept},
  author = {[Drift Johnson]},
  year = {2026},
  url = {https://github.com/MushroomFleet/Dredel-Bike},
  version = {1.0.0}
}
```

### Donate:
[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)
