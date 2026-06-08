# Monster Statistics

Every monster is described with a standardized stat block. Fields below.

| Field    | Meaning |
|----------|---------|
| **AC**   | Armor Class. Target number an attack roll must meet or beat to hit. |
| **HD**   | Hit Dice. Number of d8 hit dice, average HP in parentheses. `X+Y` / `X−Y` adds or subtracts from the rolled total (min 1 HP). `HD ½` counts as 1 HD for any rule referencing HD. Each `*` after HD marks a special ability that meaningfully raises the monster's threat (not every trait is counted). |
| **AB**   | Attack Bonus added to the monster's d20 attack roll (see table below). |
| **Att**  | Attacks, listed as **count × type (damage)**, e.g., `2 × claw (1d6)`. Special attacks appear as separate trait lines. |
| **MV**   | Movement: feet per dungeon turn, with feet per combat round in parentheses (`MV 120' (40')`). Additional modes follow, e.g., `(Fly 180' (60'))`. |
| **SV**   | Saving Throws — five values in canonical order: **D**eath · **W**ands · **P**aralysis · **B**reath · **S**pells. Monsters save as a **Fighter equal to their HD**; exceptions appear in traits. |
| **ML**   | Morale (2d6 score), 4 (cowardly) to 11 (fearless). Mindless monsters list `—` and never check. |
| **AL**   | Alignment: Lawful (L), Neutral (N), or Chaotic (C). Two values mean behavior varies. |
| **XP**   | Experience awarded for defeating the monster. |
| **NA**   | Number Appearing as `XdY (AdB)`: dungeon encounter, then wilderness lair. A leading `1` with no roll means a fixed single encounter. |
| **TT**   | Treasure Type. A letter code keyed to the Treasure Types tables. `X (Y)` means individuals carry X, the lair holds Y. A dash means no treasure. |

## AB by HD

| Monster HD | AB  |
|------------|-----|
| ½–1        | +0  |
| 2          | +1  |
| 3          | +2  |
| 4          | +3  |
| 5          | +4  |
| 6–7        | +5  |
| 8–9        | +6  |
| 10–11      | +7  |
| 12–13      | +8  |
| 14–15      | +9  |
| 16+        | +10 |
