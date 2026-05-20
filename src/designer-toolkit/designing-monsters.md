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
- Attack bonus (see [Monster Statistics — AB](../core-rules/referee/monsters/monster-statistics.md#ab--attack-bonus))
- Save level (Save as Fighter at HD level)
- Challenge level for the party

| HD  | Suitable For                                     | Example Monsters                 |
| --- | ------------------------------------------------ | -------------------------------- |
| ½   | Very weak; groups only                           | Giant Rat, Kobold, Centipede     |
| 1   | Minor threat; appropriate for level 1 PCs        | Goblin, Skeleton, Bandit         |
| 2   | Meaningful threat; challenging for level 1–2     | Orc, Wolf, Giant Spider          |
| 3–4 | Significant threat; dangerous for level 2–3      | Ghoul, Gnoll, Ogre               |
| 5–6 | Boss-level; challenging for level 3+             | Troll, Wight, powerful creatures |
| 7+  | Beyond basic play; appropriate for future levels | Giants, Dragons, Demons          |

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

Match the monster's single-attack damage to its role:

| Role | Damage per Attack | Examples |
|------|-----------------|---------|
| Nuisance | 1d3–1d4 | Giant rat, kobold, stirge |
| Standard threat | 1d6 | Orc, goblin, wolf |
| Heavy hitter | 1d8–1d10 | Hobgoblin, wight, ogre |
| Devastating | 2d6 or 1d10+ | Giant, dragon bite |

For multi-attack monsters, reduce individual damage accordingly: 3 attacks at 1d4 is roughly equivalent to 1 attack at 1d8.

## Special Abilities

Use sparingly — one or two per monster is ideal.

**Category 1: Save-or-suffer**
Forces a saving throw on a hit. Classic examples:

- **Poison** (**Death** save — failure: effect)
- **Paralysis** (**Paralysis** save — failure: immobilized)
- **Petrification** (**Paralysis** save — failure: turned to stone)
- **Level Drain** (no save — very powerful, use rarely)

**Category 2: Area threats**
Affects multiple targets or an area:

- **Breath weapon** (**Breath** save for half)
- **Gaze attack** (**Wands** save to avoid)
- **Fear aura** (**Spells** save or flee)

**Category 3: Resistances and immunities**
Limits how the party can hurt the monster:

- **Silver** required (only hurt by silver/magic)
- **Magic** required (immune to mundane weapons)
- **Fire/cold/acid immunity** (specific damage type)

**Category 4: Utility and behavior**
Changes how the encounter plays out:

- **Regeneration** (must use fire/acid; creates ongoing tension)
- **Pack tactics** (bonus to attack with allies)
- **Stealth** (enhanced surprise chance)
- **Web/net** (immobilizes characters)

## XP Calculation

Base XP by HD, plus a bonus per notable special ability. Mark each notable special with an asterisk after the HD (e.g., HD 2\*\* = 2 specials).

| HD          | Base XP | Bonus per Ability |
|-------------|---------|-------------------|
| Less than 1 |     5   |       1           |
| 1           |    10   |       3           |
| 1+          |    15   |       4           |
| 2           |    20   |       5           |
| 2+          |    25   |      10           |
| 3           |    35   |      15           |
| 3+          |    50   |      25           |
| 4           |    75   |      50           |
| 4+          |   125   |      75           |
| 5           |   175   |     125           |
| 5+          |   225   |     175           |
| 6           |   275   |     225           |
| 6+          |   350   |     300           |

**Total XP = Base + (number of asterisks × Bonus per Ability)**.

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

- **Blood Drain**: Once attached (on a successful bite), the leech deals **1d6 automatic damage per round** without needing attack rolls. Detaching requires a [Break](../core-rules/adventuring/skills.md#break) skill roll (or 2 rounds of effort).
- **Piercing Immunity**: Arrows, spears, and similar piercing weapons deal half damage.
- **Aquatic**: Moves at full speed in water; reduced to 20' on land.
:::

