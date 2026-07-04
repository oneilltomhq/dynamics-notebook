# dynamics notebook

Seven interactive pages that teach the language of natural motion from one atom up.
Every page is one new idea bolted onto the mantra:

> state makes force · force remakes state · repeat

| rung | page | the one new idea |
|---|---|---|
| 1 | [rung-1-spring.html](rung-1-spring.html) | the damped spring — the atom |
| 2 | [rung-2-wander.html](rung-2-wander.html) | the push can roll dice (OU wander) |
| 3 | [rung-3-field.html](rung-3-field.html) | randomness can live in space (noise fields, fbm) |
| 4 | [rung-4-curl.html](rung-4-curl.html) | rotate the slope — swirl for free (curl noise) |
| 5 | [rung-5-fluid.html](rung-5-fluid.html) | the field carries itself (advection + projection, stable fluids) |
| 6 | [rung-6-chaos.html](rung-6-chaos.html) | no dice, still unpredictable (Lorenz, double pendulum) |
| 7 | [rung-7-sync.html](rung-7-sync.html) | many springs learn to agree (Kuramoto, waves, the conductor) |

Each file is fully self-contained vanilla HTML/JS — no dependencies, no build.
Open any page straight from disk, or serve the directory with anything
(`python3 -m http.server`, `npx serve`, ...).

## the standing challenge

These pages are reference implementations. The test that makes the language yours:
pick a rung, open a blank file, rebuild it from memory, then diff your understanding
against the source. Predict before you run; wrong predictions are the curriculum.
