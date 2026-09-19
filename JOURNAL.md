# Pad6K2R — Build Journal

A log of building my macropad, Pad6K2R, from scratch (Hack Club project). Mostly here so I remember what actually gave me trouble, not just what went right.

---

## PCB Design (KiCad)

This is where most of the early struggle happened. Coming into this with basically no circuit design experience, KiCad's learning curve hit hard right away.

**What I dealt with:**
- Understanding footprints and how they map to actual components — this wasn't obvious at all in the beginning
- Routing traces cleanly without things turning into a mess
- The constant fear of shorting something by accident — double- and triple-checking connections before feeling okay about it
- Just getting comfortable with the KiCad interface itself, since everything about it was new

**Toughest part:** Trusting that the schematic actually translates correctly into a working physical board. There's no easy way to "test" it until it's real, so a lot of this was just careful, repeated checking rather than any one big breakthrough.

**Result:** Got the PCB fully designed. This was the first point where Pad6K2R stopped feeling abstract and started feeling like an actual object.

<img width="1366" height="685" alt="640313628-93746db8-32ab-4932-8c28-af202513a2ba" src="https://github.com/user-attachments/assets/feea85ab-4a9c-40bd-9ccc-d897a8c25b42" />
---

## 3D Model (EasyEDA)

Not done yet — this is the next thing to tackle. Expecting this to be its own learning curve since it's a different tool than KiCad, with its own quirks for how it expects components and dimensions to be defined.

---

## Firmware / Coding (VS Code)

Also pending. Realized early that the hardware side is only half the project — Pad6K2R doesn't do anything without code behind it.

**What's tough here going in:** I don't come from a strong coding background, so picking up Python, C++, and HTML at the same time as trying to write firmware logic feels like building the plane while flying it. Haven't hit the hard part yet, but expecting the firmware step to be where a lot of debugging time goes.

---

## Status

-  Schematic + PCB design (KiCad) <Done>
-  3D model (EasyEDA) <Currently working on it >
---
