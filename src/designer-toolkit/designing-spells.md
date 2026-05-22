# Designing Spells

A spell entry has four mechanical fields: **level**, **range**, **duration**, and **save** (which may be none). This page covers what each does and the standing conventions for each.

## Spell Levels

Spell level gates access by class advancement and signals the mechanical envelope of the effect.

- **1st-level**: limited single-target effects. Damage and healing cap around 1d6+1.
- **2nd-level**: lasting effects, small-area control, or significant utility. Damage is unusual at this tier.
- **3rd-level**: scaling area damage (1d6 per caster level), multi-target control, party transformation, or permanent state change.

## Range

| Range | Notes |
|-------|-------|
| The caster | Self-only (*Shield*, *Mirror Image*) |
| The caster or a creature touched | Self-or-ally; may require a melee touch in combat (*Cure Light Wounds*, *Fly*) |
| 10'–30' | Close range; safe from self-harm in area effects (*Web*, *Striking*) |
| 60' | Within a large room (*Detect Magic*, *Snake Charm*) |
| 120' | Across most dungeon encounters (*Light*, *Dispel Magic*) |
| 150'–180' | Long range (*Lightning Bolt*, *Silence, 15' Radius*) |
| 240' | Open-air or area effects (*Sleep*, *Fireball*) |

## Duration

| Duration | Length | Notes |
|----------|--------|-------|
| Instant | — | Resolves at the moment of cast (*Cure Light Wounds*, *Dispel Magic*, *Fireball*) |
| Single round | 1 round | The effect completes during one combat round (*Knock*, *Know Alignment*) |
| Brief | 1–3 turns | Short utility or readiness (*Shield*, *Read Magic*, *Haste*, *Detect Magic*) |
| Combat-length | ~6 turns | Buffs, debuffs, and personal-scale enchantments (*Bless*, *Mirror Image*, *Levitate*) |
| Exploration-length | 12 turns | Sustains a dungeon stretch (*ESP*, *Silence, 15' Radius*, *Protection from Normal Missiles*) |
| Day-length | Many hours, "1 day" | Significant time investment (*Web*, *Water Breathing*, *Infravision*) |
| Indefinite | Until broken or dispelled | Trigger-based end (*Charm Person*, *Invisibility*) |
| Permanent | — | *Continual Light*, *Wizard Lock*, *Purify Food and Water* |

Some durations scale per caster level — e.g., *Light* lasts 6 turns + 1 turn per caster level.

## Saving Throws

Designed spells use the **Spells** category. Death, Wands, Paralysis, and Breath are reserved for non-spell threats (poisons, monster abilities, dragon breath, traps).

Three patterns cover most spells:

- **No save** — for capped damage (*Magic Missile*) or HD-limited control (*Sleep*). Avoid no-save spells without a built-in cap.
- **Save for half** — area damage default (*Fireball*, *Lightning Bolt*).
- **Save negates** — control and debuff default (*Charm Person*, *Hold Person*).

## Reversed Spells

Some spells — most often divine spells of opposition (*Cure Light Wounds*/*Cause Light Wounds*, *Bless*/*Blight*) — have a reversed form. Keep both forms in a single entry; write the reversal into the description. The two forms should be true inversions: mechanics (range, duration, save type) match between them, with only the direction of the effect flipped.
