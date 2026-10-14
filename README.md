Pachinko Tensei

A Pachinko-inspired mobile/arcade game developed for a 15-day Game Jam.

> **Note:** This repository is a fork/group project. Below is a detailed breakdown of my specific contributions as a Game Programmer.
>
> ## 🎮 Game Overview
- **Event:** 15-Day Game Jam
- **Role:** Junior Game Programmer
- **Engine/Language:** Unity (C#)

- ## 🛠️ My Contributions & Technical Implementation

- During this project, I was responsible for designing and implementing key core gameplay loop mechanics and optimization systems:

- ### 1. Object Pooling System & Ball Behavior (`ObjectPool`, `BallController`)
- **Object Pooling:** Implemented a reusable **Object Pool** for spawning and recycling balls efficiently to eliminate memory allocation overhead and prevent garbage collection hitches during high-volume ball spawning.
- **Ball Launcher:** Programmed the shooting/launching mechanics, allowing players to control power, trajectory, and release timing.

### 2. Gameplay Mechanics: Multipliers & Splitters
- **Score Multiplier:** Programmed events on special button to dynamic adjust scores and multiply launch ball value.
- **Divisor Pin:** Designed and coded the physical divider pin logic that divide active ball into small balls.

### 3. Round & Game Flow Management (`RoundManager`)
- **Round System Logic:** Built the state machine for managing round progression, ball counts, round end/win-loss conditions, and seamless round transitions.

---

## 🕹️ Controls & Features
- **Physics-driven Gameplay:** Responsive physics tuning for satisfying ball bounces and pin interactions.
- **Performance Optimized:** Smooth frame rates even with dozens of active physical elements on screen via object pooling.

---

## 🎨 Credits
- **Programming:** Alex Espadas (Core Loop, Object Pool, Mechanics) & Gerard Caballé (Core Loop, Mechanics)
- **Art & Sound:** Àdam Guàrdia & Eric Baena
- **Design:** Àdam Guàrdia & Eric Baena
