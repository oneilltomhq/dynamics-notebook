# dynamics notebook

Twenty rungs and a storm — interactive pages that teach the language of natural motion
from one atom up. The first twelve build the language of motion from a single damped spring;
the next eight climb it toward the fundamental laws — least action, fields, relativity, the
quantum, and gauge theory. Every page is one new idea bolted onto the mantra:

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
| 13 | [rung-13-action.html](rung-13-action.html) | the whole path chooses itself (least action, δ∫(T−V)dt = 0, is F=ma read backwards) |
| 14 | [rung-14-wave.html](rung-14-wave.html) | line up the springs and get a field (wave & Klein-Gordon, E²=p²+m²) |
| 15 | [rung-15-maxwell.html](rung-15-maxwell.html) | two fields, each the other's cause (FDTD light, the double slit) |
| 16 | [rung-16-curve.html](rung-16-curve.html) | carry a vector around a loop, it returns turned (holonomy = curvature, geodesic deviation) |
| 17 | [rung-17-orbit.html](rung-17-orbit.html) | curvature steers the planet (Schwarzschild precession, ISCO, light bending) |
| 18 | [rung-18-quantum.html](rung-18-quantum.html) | the state goes complex (Schrödinger, tunneling, the quantum spring) |
| 19 | [rung-19-spinor.html](rung-19-spinor.html) | turn it around twice (720° ≠ 360°, the SU(2) double cover, neutron interferometry) |
| 20 | [rung-20-gauge.html](rung-20-gauge.html) | the phase lives on the links (lattice gauge, plaquette = curvature, Aharonov-Bohm) |
| ☈ | [storm.html](storm.html) | every rung at once — the capstone storm |

## the studies

The rungs each teach one idea; a study climbs the ladder back down — start from one
real thing, decompose it into the rungs it is made of, and build it live.

| study | page | the real thing | rungs inside it |
|---|---|---|---|
| S1 | [study-1-reverb.html](study-1-reverb.html) | reverb — the room answers | 1 · 2 · 6 · 7 · 9 · 10 · 14 · 15 |
| S2 | [study-2-lissajous.html](study-2-lissajous.html) | lissajous — two springs, crossed | 1 · 6 · 7 |
| S3 | [study-3-kick.html](study-3-kick.html) | the kick — the drum lets go | 1 · 14 · 15 |
| S4 | [study-4-rhythm.html](study-4-rhythm.html) | rhythm — time gets a grid | 1 · 2 · 7 |

Each study ends where its decomposition ends — for reverb, the LTI boundary:
everything nature builds from quiet air decomposes into rung-1 springs; shimmer,
modulated tanks, and gated reverbs were engineered to break that promise.
Studies 2–4 form a sound cycle with S1: the figure a signal draws (lissajous),
the hit that makes it (kick), the schedule that repeats it (rhythm), and the
room that answers (reverb).

Each file is fully self-contained vanilla HTML/JS — no dependencies, no build.
Open any page straight from disk, or serve the directory with anything
(`python3 -m http.server`, `npx serve`, ...).

## the standing challenge

These pages are reference implementations. The test that makes the language yours:
pick a rung, open a blank file, rebuild it from memory, then diff your understanding
against the source. Predict before you run; wrong predictions are the curriculum.
