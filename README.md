# Black Hole Light Bending (Turtle Simulation)

A visualization of gravitational lensing near a **Schwarzschild black 
hole** using Python's `turtle` graphics.

The simulation launches light rays past a black hole and demonstrates how 
curved spacetime alters their paths. Some rays escape, while others are 
captured by the event horizon.

---

## Physics Concepts

This project illustrates several key general relativity ideas:

### Event Horizon
The Schwarzschild radius

\[
r_s = \frac{2GM}{c^2}
\]

defines the boundary where nothing, not even light, can escape.

### Photon Sphere

Light can orbit a black hole at

\[
r_{ph} = \frac{3GM}{c^2}
\]

This orbit is **unstable**, meaning small perturbations cause photons to 
either escape or fall inward.

### Gravitational Lensing

Light passing near massive objects follows curved paths (null geodesics), 
producing bending similar to what this simulation visualizes.

---

## Simulation Features

- Schwarzschild-inspired black hole geometry
- Photon sphere visualization
- Light ray deflection
- Capture vs escape trajectories
- Adjustable curvature strength
- Real-time controls

---

## Controls

| Key | Action |
|----|------|
| `r` | Reset simulation |
| `p` | Pause / unpause |
| `t` | Toggle trails |
| `[` | Decrease curvature |
| `]` | Increase curvature |

---

## How It Works

Each light ray moves at constant speed while its **direction rotates 
slightly toward the black hole**, representing spacetime curvature.

This is an **effective geometric model** rather than a full numerical 
solution of the Schwarzschild null geodesic equations, but it reproduces 
the qualitative behavior of:

- strong bending near the black hole
- photon sphere trajectories
- capture vs escape

---

## Running the Simulation

Clone the repository:

```bash
git clone https://github.com/jyarick/black-hole-lensing.git
cd black-hole-lensing
Run:
python3 blackhole_lensing_turtle.py
```
