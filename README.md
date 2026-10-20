# BFDI Branches Commander X16 port
The unofficial Commander X16 port of BFDI: Branches [original by Team Branches]

## Disclaimer
This project is unofficial and is not affiliated by Team Branches, jacknjellify or Commodore.

I asked in the BFDI: Branches Discord that is it okay to port the game on the Commodore 64, C128, C64 Ultimate, or Commander X16, and they said yes, stated that would be awesome to see, as long as we say "Unofficial Port" on the title screen.

Shoutouts go to:
- Meester Tweester (from Team Branches)
- supersonico16 (from Team Branches)
- Lapis (from Team Snowflakes)
- GDNacho (from Team Branches, and The Bracelety Inquisition)
- The rest of Team Branches and Team Snowflakes

You are all amazing :3

The Branches Demake Team will not make profits in any way.

[Watch BFDI by jacknjellify](https://www.youtube.com/@BFDI)

[Play BFDI: Branches by Team Branches](https://bfdibranches.com)

## Why the X16 port?
Same reason as the Commodore 64 port [See the reason in the C64 port](https://github.com/branches-demake/bfdi-branches-64/tree/main#why-the-c64-port)

# Criteria for the BFDI Branches C64 port
## Programming Language
I would want this port to be written in 65c02 assembly or C for the game code because writing the entire game in BASIC could run painfully slow due to being an interpreter and requires contiguous memory map (40 KB of low RAM).

Interpreted languages are **not recommended** for the game code.

## Hardware
I would prefer at least to run on an original Commander X16 with 512 KB of High RAM, 40 KB of Low RAM, and 128 KB of VRAM, but if you find RAM limitations hindering the development, you can use up to 2 MB of RAM. Running on the official Commander X16 emulator is recommended for testing.

I would prefer to be on an SD card, but you can use Commodore disk drives or custom ROM cartridges.

Multiple device support can be useful for saving and loading levels, as well as downloading online levels and software updates, but that would be overkill.

Speaking of downloading levels and updates, I would also have support the ESP32 network card to connect to the internet.

It can be controlled with a keyboard or a Super Nintendo / Super Famicom controller, because two SNES ports are already integrated on the Commander X16.

## Features
I would prefer to have an original story mode (not finished yet), as well as additional side stories, speedrun mode, level editor and online features as the original, but nix the outbound online features like level uploads, completion submissions and online accounts since it's an unofficial port. No DLCs, no microtransactions, no ads, no tracking.

Music and sound mode options: VERA PSG, FM, or both.

Import levels from the Commodore systems like the 64, 128, Plus/4 or VIC-20 to the Commander X16 version, with compatibility settings. Only the level data and metadata will be imported.

## Integrity
I prefer to avoid LLM model coding, known as "vibe-coding," as it is unreliable, unethical, and hated by the community.

**ALL CODE MUST BE WRITTEN IN A TRADITIONAL WAY. NO EXCEPTIONS.**

Any vibe-coded pull requests will be declined without question. Habitual vibe-coding will result in a permanent ban from contributing to the project.

Also, assets must not be AI generated.

## Commander X16 clones
I am aware that there are X16-compatible computers such as the OtterX.
