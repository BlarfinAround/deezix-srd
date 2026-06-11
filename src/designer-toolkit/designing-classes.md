# Designing Classes

A class is built by making choices along each of the dimensions below — defense, skills, magic, identity. The combined choices determine the class's power level, which in turn sets its XP progression. Use the four core classes as anchor values for comparison, and the X-in-6 chassis for any new resolution mechanic introduced.

## Defense

### Hit Die

| Hit Die | Role |
|---------|------|
| **d8** | Tough warrior |
| **d6** | Balanced combatant |
| **d4** | Fragile specialist |

### Armor Access

The maximum armor the class may wear.

| Tier | Max |
|------|-----|
| **Heavy** | Plate |
| **Medium** | Chain |
| **Light** | Leather |
| **None** | Unarmored |

### Shield Use

Yes or No. Independent of armor tier — the Cleric pairs Medium armor with a shield; the Thief uses Light armor without one.

## Combat

### Combat Progression

The Attack Bonus curve by level.

| Level | Martial | Semi-Martial | Non-Martial |
| ----- | ------- | ------------ | ----------- |
| 1     | +1      | +0           | +0          |
| 2     | +1      | +0           | +0          |
| 3     | +2      | +1           | +0          |
| 4     | +3      | +1           | +1          |
| 5     | +3      | +2           | +1          |
| 6     | +4      | +2           | +1          |
| 7     | +5      | +3           | +2          |
| 8     | +5      | +3           | +2          |
| 9     | +6      | +4           | +2          |
| 10    | +7      | +4           | +3          |
| 11    | +7      | +5           | +3          |
| 12    | +8      | +5           | +3          |
| 13    | +9      | +6           | +4          |
| 14    | +9      | +6           | +4          |
| 15    | +10     | +7           | +4          |

### Weapon Access

Choose one:

- **Any** — no restriction.
- A **themed restriction** — a named subset reflecting the class's identity. The core classes provide two examples: *Blunt only* (Cleric, religious tradition) and *Daggers, staves, and slings* (Magic-User, scholar's arms). New classes may define their own list.


## Skills

### Skill Profile

| Profile        | Summary                                                                         |
| -------------- | ------------------------------------------------------------------------------- |
| **Basic**      | Key ability modifier applies to designated General Skill                        |
| **Advanced**   | As Basic, plus one class skill at 2-in-6; improves by +1 at levels 4, 9, and 14 |
| **Specialist** | As Basic, plus 4 class skills + 2 points at creation; +2 points per level through 9, then +1 every other level |

### Key Ability

The ability score the class is built around — **STR / INT / WIS / DEX**. Determines the General Skill that receives the ability modifier.


## Magic

### Spellcasting

| Type | Resource | Summary |
|------|----------|---------|
| **None** | — | Class does not cast spells |
| **Prepared (Class List)** | Spell slots | Knows the entire class spell list at unlocked levels; prepares slots each morning (Cleric) |
| **Prepared (Spellbook)** | Spell slots | Knows spells recorded in a spellbook; prepares slots each morning (Magic-User) |
| **Innate** | Magic Points (MP) | Knows a small fixed pool of spells; spends **1 MP per spell level** to cast. MP pool is class-specific — see archetypes below |

**Innate Casting** is an alternative form of magic which trades volume and variety for flexibility — they may cast their few known spells whenever Magic Points (MP) allows, with no morning preparation. 

Innate spellcasters follow two primary archetypes:

- **Heavy-magic, low-combat caster**: starts with 1–2 spells at level 1 and learns one new spell every other level thereafter (3, 5, etc.). MP equals caster level, refreshed each morning.
- **Minor-magic supporting caster**: Either unlock the first 1–3 spells along with a small MP pool at level **5**, or grant 1 spell at level 1 with one or two additions and additional MP across the class arc. Restrict access to 1st-level spells only, or to a narrow themed subset. MP is typically sized to roughly one cast of each known spell per day.

### Magical Research

None, or available at level 3+. Specify which items the class may create — scrolls, potions, holy water, blessed oils, spell creation, etc.

## Identity

### Signature Ability

The flavor-defining feature that makes the class feel like itself at the table — Backstab (Thief), Cleave (Fighter), Turn Undead (Cleric), Arcane Lore + Scroll Use (Magic-User). Abilities that resolve via a roll should be modeled as a class skill instead (e.g., Turn Undead).

Guidance:

- **Tie it to identity.** The ability should answer "what does this class do that no one else does?"
- **Scale with level when appropriate.** A level-1 ability that never improves often becomes irrelevant; one that scales (like Backstab's extra dice) gives the class a growth curve.
- **Avoid procedure-killers.** Abilities that auto-find traps, auto-open locks, or auto-survive death erase an entire layer of play.

## Saving Throws

Every class uses the same save shape: **2 Strong (3-in-6), 2 Standard (2-in-6), 1 Weak (1-in-6)**. All saves improve by **+1 at level 5** and again at level 10.

The core class profiles:

| Class | Strong | Weak |
|-------|--------|------|
| Fighter | Death, Paralysis | Spells |
| Cleric | Death, Wands | Breath |
| Magic-User | Wands, Spells | Breath |
| Thief | Paralysis, Breath | Spells |

Pick the two Strong and the one Weak that fit the class's concept; the remaining two categories are Standard.

## Core Class Anchors

### Defense + Combat

| Class | HD | Armor | Weapons | Combat |
|---|---|---|---|---|
| Fighter | d8 | Heavy + Shield | Any | Martial |
| Cleric | d6 | Medium + Shield | Blunt | Semi-Martial |
| Magic-User | d4 | None | Daggers, staves, slings | Non-Martial |
| Thief | d6 | Light | Any | Semi-Martial |

### Skills + Magic + Identity

| Class | Skill | Key | Spellcasting | Research | Signature | L2 XP |
|---|---|---|---|---|---|---|
| Fighter | Basic | STR | None | — | Cleave | 2,000 |
| Cleric | Advanced (Turn Undead) | WIS | Prepared (Class List) | L3 scrolls, holy water, oils | Turn Undead | 1,500 |
| Magic-User | Advanced (Arcane Lore) | INT | Prepared (Spellbook) | L3 scrolls, potions, spell creation | Arcane Lore | 2,500 |
| Thief | Specialist | DEX | None | — | Backstab | 1,200 |

## XP Progression

Once a class's dimensions are chosen, calibrate its advancement speed to the total power of the package. Not every dimension costs the same.

### Cost Weighting

| Weight   | Category                                                        | Why                                                                                                                |
| -------- | --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Highest  | **Magic** (Spellcasting + Magical Research)                     | Single most expensive axis. Each prepared slot, broader repertoire, and research tier compounds quickly.           |
| High     | **Combat** (HD + Combat Progression + Armor + Shield + Weapons) | The full Martial / Heavy / d8 / shield / any-weapon package is roughly equivalent in cost to a full magic package. |
| Moderate | **Signature Ability**                                           | Cost rises with frequency of use — an always-on bonus is more expensive than once-per-encounter.                   |
| Low      | **Skill Profile**                                               | Specialist skills add depth but rarely warp the game; cheapest axis to max.                                        |

### Calibration

Compare a new class against the four anchors. As a guide:

- A class that **looks like a Fighter with a minor ability tacked on** should cost ~2,000–2,200 at L2.
- A class with **Cleric-tier magic and Thief-tier combat** belongs near 1,500.
- A class that **stacks high combat with even minor magic** climbs above 2,500.

If a class lands clearly above the Magic-User in total package (e.g., full magic + medium armor + martial combat), it should cost more than 2,500. Delaying access to class features until later levels can prevent a versatile class from being too powerful. 

## Example

::: {.callout-note title="Example: The Bard"}
**Concept**: An adventuring storyteller — keeper of songs, histories, and dangerous knowledge.

**Dimensions**

- **Hit Die**: d6
- **Armor Access**: leather or chain, no shields
- **Combat Progression**: Semi-Martial
- **Weapon Access**: One-handed melee weapons and slings
- **Skill Profile**: Specialist, with four class skills:
  - **Lore**: Recall legends, notable people and places, the history of a famous item, or the nature of common creatures — beasts, humanoids, giants, and other monsters of the natural world. Does not cover magical beings (undead, constructs, elementals, and the like), nor the properties or activation methods of magic items.
  - **Magic Device**: Activate an arcane scroll or wand that has been identified and explained to the Bard by a friendly Magic-User or a paid sage. On a success, the spell or charge takes effect. On a failure, nothing happens and nothing is expended.
  - **Parley**: Once per encounter, before any violence, shift a reaction result one step toward friendly. The creatures must be able to hear the Bard and share some channel of meaning. Cannot be used once combat has begun.
  - **Mimicry**: Imitate voices, animal calls, and sounds convincingly enough to deceive an unassuming listener.
- **Key Ability**: INT
- **Spellcasting**: None
- **Signature Ability**: *Song of Rest* — allies who complete a full rest in the Bard's company add **+1** to the hit points recovered from natural healing, and retainers among them gain **+1 to Loyalty rolls** for the following day.
- **Saves**: Strong Paralysis, Spells; Weak Death

**XP**: L2 1,400 / L3 2,800
:::
