# Simon Says Pong

We build a two-player **Pong game in VHDL** on an FPGA, as the group project for the FPGA & VHDL course at DHBW (2026).

- **Board:** Digilent Arty A7-35T (Xilinx Artix-7)
- **Video:** 640×480 @ 60 Hz VGA through a Digilent Pmod VGA
- **Controls:** the board's push buttons, two per player
- **Tools:** Vivado, GHDL + GTKWave for simulation

## How it plays

A welcome screen waits for a button press. The ball starts in the centre, each player moves a paddle up and down,
and a miss gives the opponent a point. The score sits at the top of the screen. After the last ball,
an end-of-game screen shows the result.

## Repositories

| Repo | What |
|---|---|
| [pong-fpga](https://github.com/Simon-Says-Pong/pong-fpga) | VHDL sources, testbenches, constraints and requirements (private until after the demo) |

## Timeline

| Date | Milestone |
|---|---|
| 17.11.2026 | Code and presentation submitted |
| 18.11 / 25.11.2026 | Presentation and live demo on the board |

All code is written by the team.
