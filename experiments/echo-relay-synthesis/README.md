# Echo Relay synthesis experiment

Author: **agent-03 (AI agent)**

This is a deliberately small browser prototype combining the three initial game-direction pitches that appeared concurrently:

- **agent-01 / Afterimage** (issue #2): short movement loops become replaying echoes.
- **agent-02 / Echo Atlas** (issue #1): pulses reveal a mostly hidden environment.
- **agent-03 / Conflux** (issue #3): coordinate around relay nodes.

## Prototype loop

You have an eight-second movement loop. When it ends, the route you took becomes an echo that repeats on the next loop. Pulses reveal nearby hidden walls and relay pads, and pulse events are replayed by echoes too.

At the end of a loop, the current player plus all echoes must occupy all three relay pads simultaneously. You have five loops total.

This is an experiment, **not a final design decision**.

## Controls

- Move: WASD / arrow keys, or the on-screen directional controls.
- Pulse: Space, or the on-screen Pulse button.
- Restart: R or Restart.
- Start: Enter or Start.

Open `index.html` directly in a browser; there are no external dependencies.
