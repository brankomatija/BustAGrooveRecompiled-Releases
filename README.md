# Bust A Groove Recompiled

Native PC and Nintendo Switch port of **Bust A Groove** (PlayStation, 1998),
built by static recompilation: the game's MIPS code was translated to C ahead
of time and compiled natively. It is not an emulator.

Built on [psxrecomp](https://github.com/mstan/psxrecomp) and
[recomp-ui](https://github.com/mstan/recomp-ui).

**[Download the latest release](https://github.com/brankomatija/BustAGrooveRecompiled-Releases/releases/latest)**

## You need your own copy of the game

No game data is included. You need your own legally dumped copy of
**Bust A Groove (USA)**, SCUS-94263, as a `.cue` with its `.bin` beside it.

| Track 01 | |
|---|---|
| Size | 520,076,592 bytes |
| MD5 | `c4e32fa992711972f82299a3f4483a79` |
| SHA-1 | `4b206a8263a3f08965885f662c03cee76e745ec1` |

No PlayStation BIOS is required: the bundled OpenBIOS is MIT-licensed.

## Features

- 60 FPS native rendering, with resolution, supersampling and filtering options
- Online play through a room server
- Extra mods: autoplay, random steps, pause menu, restored unused ATTACK2 move
- Memory cards saved in the standard 128 KB `.mcd` format
- Local 2-player: a second connected controller joins as Player 2

The game boots straight in. To open the settings launcher (mods, controls,
video), hold **L1** on the controller while it starts (**L** on Switch).

## Windows

1. Download `BustAGroove-vX.Y.Z-windows-x64.zip` and extract it.
2. Put your `.cue` and `.bin` in the `disc\` folder beside the executable.
3. Run `BustAGroove_Recompiled.exe`.

## Nintendo Switch (homebrew)

1. Download `BustAGroove-vX.Y.Z-switch-nro.zip` and copy its `switch` folder
   to the root of the SD card.
2. Put your `.cue` and `.bin` in `SD:/switch/BustAGroove/`.
3. Launch it from the Homebrew Menu.

**Optional HOME menu icon:** also install `BustAGroove-vX.Y.Z-switch.nsp`
(needs sigpatches). The NSP still reads the game and settings from
`SD:/switch/BustAGroove/`, so step 1 and 2 are still required.

## Legal

This project is not affiliated with or endorsed by Sony Interactive
Entertainment, Enix or Metro. Bust A Groove is a trademark of its respective
owners. Do not ask for, or share, game images.
