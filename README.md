# State-Space Life Simulation

An interactive visualization exploring a theoretical idea:

> **Life is not measured by time, but by the distance a system travels through state space.**

Instead of a clock defining life, this simulation models life as a **trajectory through a multidimensional system state** shaped by energy, information, entropy, and environmental constraints.

---

# Core Idea

Traditional thinking measures life using chronological time.

```
Life = f(time)
```

This project explores a different hypothesis:

```
L = ∫ ||dX||
```

Where:

* **L** = life trajectory length
* **X** = system state vector

The state vector is defined as:

```
X = (E, I, S, C)
```

Where:

| Variable | Meaning                     |
| -------- | --------------------------- |
| **E**    | Energy state                |
| **I**    | Information / learning      |
| **S**    | Entropy / structural change |
| **C**    | Environmental constraints   |

Life becomes the **accumulated path through this multidimensional space**.

---

# Simulation Overview

This project is a **3D real-time simulation** where a particle represents a living system navigating a constrained state space.

The particle:

* generates multiple possible future states
* filters them through constraint rules
* probabilistically selects the next transition
* leaves a visible trajectory behind

The resulting path represents the **life trajectory**.

---

# Features

### 3D State Space

Three visible axes represent:

* Energy (E)
* Information (I)
* Entropy (S)

Environmental constraints influence movement but remain an invisible dimension.

---

### Constraint-Driven Transitions

At every step:

1. Candidate states are generated
2. Constraint rules remove impossible paths
3. A probability function selects the next state

This models how real systems evolve within limitations.

---

### Life Cycle Simulation

The system progresses through five phases:

| Phase   | Description                   |
| ------- | ----------------------------- |
| Birth   | fragile system initialization |
| Growth  | rapid information increase    |
| Peak    | highest energy and activity   |
| Decline | decreasing resources          |
| Death   | trajectory ends and resets    |

A new life begins with slightly altered parameters.

---

### Adjustable Parameters

Users can influence system behavior through sliders such as:

* Life Hardship
* Resources & Wealth
* Curiosity & Learning
* Will to Live
* Social Constraints
* Risk Taking
* Ambition & Drive
* Life Change Rate

These parameters alter the **constraint landscape** of the simulation.

---

### Compare Mode

A comparison mode demonstrates the difference between:

**Time-Based Model**

```
Life = time progression
```

**State-Space Model**

```
Life = trajectory length
```

The visual difference highlights how a system with intense change can produce a longer life trajectory even with less chronological time.

---

# Technology

* **Three.js** — 3D visualization
* **WebGL** — rendering
* **Vanilla JavaScript** — simulation logic
* **HTML/CSS** — UI and control panels

The simulation runs entirely in a **single HTML file** with no build tools.

---

# Project Motivation

This project explores a conceptual framework where:

* systems evolve through **state transitions**
* environmental constraints shape trajectories
* life becomes a **navigation problem in possibility space**

The goal is not to replace biological or physical models, but to provide a **visual and conceptual exploration of life as a dynamic trajectory rather than a timeline.**

---

# Running the Simulation

Simply open the HTML file in a modern browser.

```
index.html
```

No installation or build process required.

---

# Future Ideas

Potential extensions include:

* multiple interacting agents
* evolutionary trajectory optimization
* constraint field visualization
* entropy-driven dynamics
* information-geometry metrics

---

# Inspiration

Concepts related to this model appear in several scientific areas:

* dynamical systems
* statistical mechanics
* phase-space trajectories
* reinforcement learning
* complex adaptive systems

This project combines those ideas into a **visual model of life as constrained state navigation.**

---

# License

MIT License
