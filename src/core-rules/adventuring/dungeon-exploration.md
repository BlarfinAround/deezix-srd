# Dungeon Exploration

Dungeon exploration uses a structured turn-based procedure. **One turn = 10 minutes** of in-game time.

## The Turn

Each turn, the party may:

- **Move** through the dungeon (exploring cautiously), OR
- **Take an action** (search a room, rest, listen at a door, force a stuck door, etc.).

Simple combined tasks are allowed (move to a door, then listen at it), but a thorough search of a room takes a full turn.

## Movement Rate

| Condition | Per Turn (exploring) | Per Turn (running) |
|-----------|--------------------|--------------------|
| Unencumbered | 120' | 240' |
| Encumbered | 60' | 120' |

*A party moves at the rate of its slowest character.*

**Exploring cautiously** means moving carefully, watching for traps and ambushes.

## Light and Wandering Monsters

### Light

| Light Source | Duration |
|-------------|---------|
| Torch | 6 turns (1 hour) |
| Lantern | 24 turns per flask of oil |
| Candle | 6 turns, 5' only |

::: {.callout-important title="Darkness"}
Without a light source the party cannot see. **Movement halves**. Tasks that require sight automatically fail. Attacks are made at **−2**.
:::

Parties carrying a light in dark environments usually **cannot surprise** others.

### Wandering Monsters

Check every **2 turns**, or more frequently if the party is being noisy or drawing attention: roll 1d6 — encounter on a **1**. When a check indicates an encounter, follow the [Encounter Sequence](encounters.md#encounter-sequence).

## Doors

Doors in dungeons are often stuck, locked, or swollen from damp. Failed attempts to force a door make noise.

::: {.callout-important title="Doors"}
- **Stuck**: [Break](skills.md#break) roll. Retry takes a full turn of effort.
- **Locked**: requires the key, a *Cast Knock* spell, or a [Tinker](../character/classes/thief.md#class-skills) roll (Thief).
- **Secret**: found by a successful [Search/Listen](skills.md#search-listen) roll while actively searching, or by direct investigation (e.g. removing a painting from a wall).
- **Barricaded / portcullised**: combined STR effort or mechanical solution (winch, crowbar). Multiple characters may roll [Break](skills.md#break) and aggregate successes.

Failure on Stuck or Locked triggers an immediate wandering monster check from the noise.
:::

## Traps

::: {.callout-important title="Traps"}
- **Finding**: active [Search/Listen](skills.md#search-listen) (1 turn, successful roll).
- **Triggering**: moving through an un-searched trapped area carries a **2-in-6 chance per character** of setting it off. Adjust per trap.
- **Disarming**: once found, [Tinker](../character/classes/thief.md#class-skills) roll. Failure may trigger the trap.
:::