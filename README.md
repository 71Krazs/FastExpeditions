# Fast Expeditions (Fixed Base Times)

Sets expedition base time by the game’s actual difficulty: **Easy 5 minutes**,
**Normal 10 minutes**, **Hard 15 minutes**, and **VeryHard 20 minutes**. It
covers all 18 current routes.

Only `DT_CharacterTeamMissionDataTable.RequiredSeconds` is changed. Rewards,
reward chances, required strength, Pal elements, unlock conditions, and Pal
counts remain vanilla.

## Requirements

- UE4SS
- PalSchema 0.6.4 or later

## Installation

Extract `FastExpeditions` into:

`<Palworld>/Pal/Binaries/Win64/ue4ss/Mods/PalSchema/mods/`

Use the same mod on the server and clients. Restart the server/game to load a
new installation; expeditions already in progress may retain their duration
that was scheduled when they started.

## Compatibility

Do not use alongside another expedition timer/requirement mod. Those mods
generally patch the same mission table, and whichever one loads last wins.
