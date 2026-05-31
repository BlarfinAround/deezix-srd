# Designing Monsters

## The Design Process

1. **Concept**: What is this creature? What does it do? What makes it interesting?
2. **HD**: Set Hit Dice based on intended threat level.
3. **AC**: Set based on natural toughness or size.
4. **Attacks**: Set damage to match the threat level.
5. **Special abilities**: Add one or two that make the creature feel unique.
6. **Morale**: Set based on behavior and intelligence.
7. **XP**: Calculate from HD and specials.

## Hit Dice as the Core Lever

HD determines:

- Total HP (roll HD × d8)
- Attack bonus
- Save level (Save as Fighter at HD level)
- Challenge level for the party

| HD  | Suitable For                                | Example Monsters                   |
| --- | ------------------------------------------- | ---------------------------------- |
| ½   | Very weak; groups only                      | Giant Rat, Kobold, Giant Centipede |
| 1   | Minor threat; appropriate for level 1 PCs   | Orc, Skeleton, Bandit              |
| 2   | Meaningful threat; challenging for level 1–2 | Gnoll, Giant Spider, Wolf         |
| 3–4 | Significant threat; dangerous for level 2–3 | Wight, Harpy, Ogre                 |
| 5–6 | Boss-level; challenging for level 3+        | Troll                              |
| 7+  | Beyond this bestiary; for higher-level play | Giants, dragons, and the like (not statted here) |

These are starting points, not brackets — a creature a hit die off its row is still in range.

## Armor Class Guidelines

| AC | Rationale |
|----|-----------|
| 10–11 | Soft body; no armor or natural protection |
| 12–13 | Light hide or leather; fast and agile creatures |
| 14–15 | Scales, thick hide, or medium armor |
| 16–17 | Heavy armor or significant natural plating |
| 18–19 | Extraordinary protection (dragon scales) |
| 20+ | Near-invulnerable; requires special conditions to damage |

## Damage Calibration

Match the monster's single-attack damage to its role. These are rough guides, not limits:

| Role | Damage per Attack | Examples |
|------|-----------------|---------|
| Nuisance | 1d3–1d4 | Giant Rat, Kobold, Stirge |
| Standard threat | 1d6 | Orc, Goblin, Wolf |
| Heavy hitter | 1d8–1d10 | Hobgoblin, Zombie, Ogre |
| Devastating | 2d6 or 1d10+ | Beyond this bestiary (giants, dragons) |

## Special Abilities

These are examples of special abilities and behavioral traits, each pointing to a bestiary monster that shows it in action.

**Save-or-suffer**
Forces a saving throw on a hit:

- **Poison** (**Death** save) — Giant Spider, Giant Centipede
- **Paralysis** (**Paralysis** save) — Ghoul
- **Charm** (**Spells** save) — Harpy's hypnotic song
- **Ability or level drain** (usually no save) — Shadow (Strength), Wight (level)

**Resistances and immunities**
Limits how the party can hurt the monster:

- **Silver or magic** to wound — Wight
- **Magic only** to wound — Shadow
- **Elemental immunity** — Gray Slime (fire and cold)

**Persistent effects**
Keep working after the first hit:

- **Regeneration** (only fire or acid stops it) — Troll
- **Ongoing drain** on a hit — Stirge (blood)

**Behavioral traits**
How the creature fights and acts. These shape an encounter but typically don't count as special abilities for XP — leave them out of the asterisk count.

- **Enhanced surprise** — Shadow, Giant Spider, Gray Slime
- **Pack courage** (morale bonus in numbers) — Wolf

## XP Calculation

Mark each notable special with an asterisk after the HD (e.g., HD 2\*\* = 2 specials). Use the [Monster XP table](../core-rules/character/experience-and-advancement.md#monster-xp): **Total XP = Base + (asterisks × Bonus per Ability)**.

::: {.callout-note title="Example: Giant Leech"}
**Concept**: A swamp creature — a massive leech that lurks in shallow water and drains blood.

**Decisions**:

- HD: 3 (solid dungeon threat for levels 1–2)
- AC: 12 (slimy, tough but not armored)
- **Attacks**: 1 × bite (1d6) + Blood Drain
- **Blood Drain**: On hit, the leech latches; 1d6 automatic damage per round until detached (Break skill)
- **Immune to**: piercing weapons (half damage — arrows barely hurt it)
- **Morale**: 8 (animal, retreats if hurt badly)
- XP: 35 base (3 HD) + 15 (blood drain) + 15 (piercing immunity) = 65 XP

**Result**:

**Giant Leech** — *a bloated blood-sucking worm, 5–7 feet long.*

**AC** 12, **HD** 3** (14hp), **AB** +2, **Att** 1 × bite (1d6 + Blood Drain), **MV** 60' (20') (Swim 120' (40')), **SV** D3 W2 P3 B2 S1, **ML** 8, **AL** Neutral, **XP** 65, **NA** 1d4 (1d4), **TT** —

- **Blood Drain**: Once attached (on a successful bite), the leech deals **1d6 automatic damage per round** without needing attack rolls. Detaching requires a Break skill roll (or 2 rounds of effort).
- **Piercing Immunity**: Arrows, spears, and similar piercing weapons deal half damage.
- **Aquatic**: Moves at full speed in water; reduced to 20' on land.
:::

