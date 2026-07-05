# dynamics notebook

Twelve rungs and a storm — interactive pages that teach the language of natural motion
from one atom up. Every page is one new idea bolted onto the mantra:

> state makes force · force remakes state · repeat

| rung | page | the one new idea |
|---|---|---|
| 1 | [rung-1-spring.html](rung-1-spring.html) | the damped spring — the atom |
| 2 | [rung-2-wander.html](rung-2-wander.html) | the push can roll dice (OU wander) |
| 3 | [rung-3-field.html](rung-3-field.html) | randomness can live in space (noise fields, fbm, worley, midpoint displacement) |
| 4 | [rung-4-curl.html](rung-4-curl.html) | rotate the slope — swirl for free (curl noise) |
| 5 | [rung-5-fluid.html](rung-5-fluid.html) | the field carries itself (advection + projection + buoyancy, stable fluids) |
| 6 | [rung-6-chaos.html](rung-6-chaos.html) | no dice, still unpredictable (Lorenz, double pendulum) |
| 7 | [rung-7-sync.html](rung-7-sync.html) | many springs learn to agree (Kuramoto, waves, the conductor) |
| 8 | [rung-8-gravity.html](rung-8-gravity.html) | the pull flips — 1/d² gravity, softening, axis×r swirl (the attractor) |
| 9 | [rung-9-light.html](rung-9-light.html) | the ray is a state too (Beer-Lambert, self-shadow, Henyey-Greenstein) |
| 10 | [rung-10-growth.html](rung-10-growth.html) | the field decides where growth goes (Laplace, DBM lightning, delay-sum thunder) |
| 11 | [rung-11-sph.html](rung-11-sph.html) | the particles are the field (SPH kernels, density, pressure) |
| 12 | [rung-12-mpm.html](rung-12-mpm.html) | particles and grid trade the field (MLS-MPM, deformation gradient) |
| ☈ | [storm.html](storm.html) | every rung at once — the capstone storm |

Each file is fully self-contained vanilla HTML/JS — no dependencies, no build.
Open any page straight from disk, or serve the directory with anything
(`python3 -m http.server`, `npx serve`, ...).

## the standing challenge

These pages are reference implementations. The test that makes the language yours:
pick a rung, open a blank file, rebuild it from memory, then diff your understanding
against the source. Predict before you run; wrong predictions are the curriculum.
