# Hey, I'm Ayushmaan

> Building a 2D game engine from scratch and replacing numerical solvers with neural networks — because apparently one hard thing isn't enough

I write C. Low-level, manual memory, no GC, no magic. I like knowing exactly what the machine is doing — game engines are the best excuse to care about every single byte, and neural surrogates are the best excuse to question whether you even need the solver in the first place.

---

## What I'm Actually Building

**six_sevenGE — A 2D Game Engine in C**
SDL2. Windows. No engine behind the engine.

Started from a red square on a black window. Now it has a modular architecture split across `core`, `entities`, and `physics` — and I'm currently making things *move properly*. Not just teleport to a new position, but actually accelerate, build momentum, and bleed friction until they stop. Turns out smooth movement is harder than it sounds when you're the one writing the physics loop.

Current status: acceleration + friction system in progress. Collision detection next. Long-term goal: ship a standalone game on Steam built entirely on top of this engine.

→ [six_sevenGE](https://github.com/Ayushu69/6_7GE.git)

---

**Neural Surrogate Model for PDEs**
Exploring whether a neural network can replace expensive numerical solvers for PDE-based simulations. The idea: instead of running the full solver every time, train a model to approximate the solution — faster, scalable, and surprisingly good at the low-frequency modes. High-frequency turbulence is still being annoying.

Currently working with CNN-based rollout models and looking into Fourier Neural Operators for resolution-invariant mappings. The tricky part isn't getting it to learn — it's keeping the errors from snowballing over long rollouts.

*(repo coming soon)*

---

## Tech

**Languages**

[![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)](https://github.com/Ayushu69)
[![C++](https://img.shields.io/badge/C++-004482?style=for-the-badge&logo=cplusplus&logoColor=white)](https://github.com/Ayushu69)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/Ayushu69)

**ML Stack**

[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://github.com/Ayushu69)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://github.com/Ayushu69)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://github.com/Ayushu69)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://github.com/Ayushu69)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://github.com/Ayushu69)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)](https://github.com/Ayushu69)

**Game/Systems Stack:** SDL2 · GCC · MSYS2 UCRT64 · VS Code · Git · Windows

---

## Stuff I Actually Geek Out Over

**Physics-Informed ML / Neural Surrogates**
Why run an expensive numerical solver a thousand times when you can train a network to approximate it? I'm exploring PDE surrogate modeling — CNN rollout models, Fourier Neural Operators, error accumulation over long rollouts. The goal is resolution-invariant mappings that don't fall apart after a few timesteps.

**Deep Learning Architectures**
CNNs, RNNs, LSTMs, MLPs — not just as black boxes, but understanding what each layer is actually doing, how gradients flow, and why your loss is exploding at 3am. Activation functions, optimizers, backprop — I want to know the math, not just `model.fit()`.

**Game Engine Architecture**
Not the "drop a sprite and hit play" kind. The kind where you design your own entity system, figure out how your physics loop talks to your renderer, and spend 3 hours debugging why your delta time is making everything behave like it's underwater.

**Low-Level Systems**
Manual memory management isn't a punishment — it's information. When you know where every allocation lives, your code stops being a black box and starts making sense. That's the reason I'm in C and not somewhere more comfortable.

---

## GitHub Activity

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Ayushu69&theme=tokyonight&hide_border=true)](https://github.com/Ayushu69)

---

## 2026 Goals

- [ ] Ship six_sevenGE with a playable demo
- [ ] Build a standalone game on top of the engine and publish it on Steam
- [ ] Complete collision detection + scene/tilemap system
- [ ] Get neural surrogate rollout stable over long time horizons
- [ ] Land an internship in game dev or systems programming — genuinely, desperately, please

---

## What I'm Learning

- **C++** — Transitioning from C. Learning what abstractions are actually worth paying for
- **Python** — Scripting, ML work, tooling
- **Deep Learning** — Going deeper into CNN/RNN internals, loss landscapes, and training stability
- **Engine architecture** — ECS patterns, data-oriented design, the gap between "works" and "scales"

---

## Talk To Me About

- Game engine internals
- Why you should care about memory layout
- C vs C++ tradeoffs (I have opinions)
- Neural surrogates and physics-informed ML
- CNN/RNN architectures and why your model isn't converging
- GSSoC / open source collab on six_sevenGE

---

## Reach Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayushmaan67)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayushmaandhiman59@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ayushu69)

---

*"If you don't know what the CPU is doing, you don't know what your code is doing."*
