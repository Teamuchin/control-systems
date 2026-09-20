# Control Systems Coursework

Modelling a physical system and tuning a controller in MATLAB/Simulink, plus the combinatorial-logic design work that accompanies it.

**Course:** CENG424 — Control Systems  
**Institution:** İzmir Institute of Technology (IYTE) — İzmir, Türkiye

## Contents

| Folder | Contents |
|---|---|
| `matlab-simulink/` | `hw4.m` sets the plant parameters and runs the simulation; `hw4.slx` is the Simulink model |
| `logic-design-hw2/` | Karnaugh-map minimisation and combinatorial-logic design, with the circuit description in `code.txt` and a link to the working circuit in `projectlink.txt` |
| `logic-design-hw3/` | K-maps and a drawn logic circuit (`kmaps.png`, `logic circuit.png`) |

## The model

`hw4.m` works with a motor-like plant — inertia `J`, damping `B` and torque constant `Kt` —
driving towards a commanded position, and compares the closed-loop response against the
target. Open `hw4.slx` for the block diagram, or run the script for the parameter sweep and
plots.

---

Submitted reports, worksheets and lecture material are archived outside this
repository rather than committed, so the repo stays code-only.
