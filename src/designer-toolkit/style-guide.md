# Style Guide

Use these conventions for all Deezix material.

## Game Terminology

**Ability scores.** Uppercase abbreviations in mechanical text: STR, INT, WIS, DEX, CON, CHA. Full capitalized names when introducing the concept: *Strength*, *Charisma*.

**Ability modifier.** Signed: +1, −1, ±0. Use the en-dash (−) for negatives.

**Armor Class.** Capitalized. Abbreviated AC.

**Attack Bonus.** Capitalized. Abbreviated AB.

**Attack rolls.** "Attack roll" is standard; "hit roll" is acceptable.

**Chances and skills.** Always written as `X-in-6` (never "X in 6" or "X/6"). In prose, attach the noun `chance`: "a **2-in-6 chance** of being surprised", "the default **1-in-6 chance**". In stat blocks, advancement tables, and rated-value labels, the contextual label (`Strong save`, `Stealth`, `Turn Undead`) substitutes for the noun — write the bare rating: `Stealth 3-in-6`. The system name itself stays bare: `the X-in-6 mechanic`, `Rule — X-in-6 Roll`.

**Reaction and morale rolls** use **2d6 + modifiers** against a numeric score (4–11 for morale and loyalty). They are referee-side procedures and are directly compatible with classic material.

**Classes.** Capitalize class names: Fighter, Cleric, Magic-User, Thief. Magic-User is always hyphenated.

**Damage dice.** Lowercase d, no spaces: 1d6, 2d8+1.

**Die rolls.** The player or referee rolls, never the character.

**Hit Dice.** Capitalized. Abbreviated HD. Plain number with optional bonus, fractional values, and asterisks for specials: `HD 2`, `HD 4+1`, `HD 1−1`, `HD ½`, `HD 3**`.

**Hit points.** Lowercase. Abbreviated HP.

**Modifiers.** Signed: +1 to attack, −2 to AC. En-dash for negatives.

**Player and character.** Lowercase. The player rolls and decides; the character acts.

**Referee.** Lowercase. Never GM, DM, or game master.

**Rounds, turns, watches.** A *round* is ~10 seconds of combat. A *turn* is 10 minutes of dungeon exploration. A *watch* is one-third of a night camp.

**Saving throws.** Lowercase: "make a death save", "saves vs. spells". Bold the save category when it is the active mechanic: "target makes a **Paralysis** save".

**Saving throw categories.** Capitalized when named: Death, Wands, Paralysis, Breath, Spells.

**Spell casters.** "Arcane spell caster" or "divine spell caster" when the rule applies broadly. Use the class name when it applies to one class.

**Spell names.** Italicized: *Magic Missile*, *Cure Light Wounds*.

**Surprise.** "A creature surprises on a 1–2."

**Treasure and XP.** 1 gp returned to civilization = 1 XP. Gold left in the dungeon does not count.

## Quarto Markdown Conventions

Deezix is built with [Quarto Book](https://quarto.org/docs/books/). Source files are plain Markdown with Quarto extensions.

### File names and extensions

- Kebab-case for all filenames and folders. No spaces, no leading numbers.
- Either `.md` or `.qmd` works for chapter files. Quarto resolves both. Use `.qmd` when needed for executable code or per-file engine settings; otherwise either extension is fine, including for files that use callouts or shortcodes.

### Headings

- One H1 per file, matching the chapter title in `_quarto.yml`.
- H2 for sections, H3 for subsections.
- Avoid H4 and deeper; promote into its own page or restructure.
- No trailing punctuation on headings.

### Horizontal rules

Never use `---` in body text.

### Tables

Pipe-delimited Markdown tables with a header row. Align columns visually in source.

```
| Level | XP    | Hit Dice | Attack Bonus |
|-------|-------|----------|--------------|
| 1     | 0     | 1d8      | +1           |
```

### Equipment tables

In equipment tables, item names carry their encumbrance category through formatting:

- **Plain text** — 1 item slot (standard).
- ***Italic*** — bundleable; one item slot per bundle. The bundle count appears in the name, e.g., *Torches (×6)*.
- ***Bold italic*** — oversized

Each equipment table is followed by a single-line key reminding readers of the convention based on the items in the chart.
`*Items in italic are bundleable.* ***Items in bold italic are oversized.***`

### Stat lines

Monster stat blocks follow the classic single-line format. All fields appear on one line, comma-separated, with bold labels:

```
**AC** 13, **HD** 2** (9hp), **AB** +1, **Att** 1 × bite (1d6), **MV** 120' (40') (Climb 120' (40')), **SV** D3 W2 P3 B2 S1, **ML** 8, **AL** Neutral, **XP** 30, **NA** 1d6 (1d6), **TT** U
```

Traits and special abilities follow as a bulleted list:

```

- **Poison**: On a bite hit, the target makes a **Death** save or suffers the listed effect.
```

### Spell entries

Spell entries appear as H3 subsections under the appropriate level heading. Range and Duration share a single line with a pipe separator, followed by a blank line, then prose:

````text
### Charm Person
**Range**: 120' | **Duration**: Special

One humanoid (or human-like creature of 4+1 HD or less) makes a **Spells saving throw** or treats the caster as a trusted friend. …

*Reversed*: *Cause Light Wounds* — inflicts 1d6+1 damage on a touched creature.
````

Reversed forms live inside the parent entry, not as a separate H3. A spell shared between arcane and divine lists (*Detect Magic*, *Light*, *Protection from Evil*, *Hold Person*) is written in both files with class-appropriate range and duration; mechanics otherwise match.

### Inline value lists

For short lists of labeled values, use the middle dot `·` as separator:

```
**Death** 3 · **Wands** 2 · **Paralysis** 3 · **Breath** 2 · **Spells** 1
```

### Callouts

Mechanical content uses [Quarto callouts](https://quarto.org/docs/authoring/callouts.html). **Three** kinds are recognized — no others:

| Kind | Quarto type | Use for |
|---|---|---|
| **Rule** | `important` | A procedure the referee reads verbatim during play. |
| **Note** | `note` | A caveat, scope statement, or non-obvious consequence of an existing rule. |
| **Example** | `note` | A worked illustration of a rule. Same visual style as Note; disambiguated by an `Example:` title prefix. |

Source syntax (fenced div):

````text
::: {.callout-important title="Saving Throw"}
Roll 1d6. If the result is **equal to or less than** the character's save value, the throw succeeds. A **6 always fails**.
:::
````

- One **Rule** per distinct mechanic. A page covering several sub-procedures (scroll creation, potion brewing) may use one Rule per sub-procedure. Notes and Examples may appear as often as the content warrants.
- Don't repeat the kind in the title (`title="X-in-6 Roll"`, not `title="Rule — X-in-6 Roll"`).
- Optional attributes: `collapse="true"` for long Examples, `appearance="simple"` to drop the background on dense reference pages.

### Bold and italics

- **Bold** the first introduction of a defined term.
- **Bold** mechanical values inside prose: HP totals, modifiers, the active save category.
- *Italics* for spell names and book titles.
- Avoid ALL CAPS except ability score abbreviations.

### Links

**Mechanics.**

- Standard Markdown: `[Link text](path-to-page.md)`.
- Relative paths only. Both `.md` and `.qmd` extensions resolve to the rendered page.
- Section anchors are Quarto's auto-generated kebab-case from heading text: `[Break](../adventuring/skills.md#break)`.
- Add an explicit `{#anchor}` to a heading only when the auto-generated slug would be wrong (e.g., `### Search/Listen {#search-listen}`, where the slash drops). Don't otherwise tag headings with anchors.

**When to link.**

- **Link the first mention in a file** of a defined term-of-art (a skill, mechanic, spell, class feature, or treasure type defined elsewhere) where understanding the sentence requires recognizing the term: `apply STR modifier to [Break](...)`.
- **Link procedural directives** that tell the reader to execute a specific procedure now: `follow the [Encounter Sequence](...)`, `roll [Search/Listen](...)`.
- **Don't use "see X" parentheticals or trailing "See [X]." pointers.** Chapters are reachable from the table of contents; navigational pointers are noise.
- **Don't link the same target twice in one file.** Subsequent mentions use plain text.

### YAML frontmatter

Optional. Add a YAML block at the top of a file when you need to override defaults:

```
---
title: "Magic-User"
description: "The arcane spellcaster class."
order: 3
---
```

Common fields:

- `title` — overrides the H1 for sidebar and page title. Omit unless the displayed title must differ from the H1.
- `description` — used in HTML metadata and (optionally) in summary listings.
- `order` — numeric ordering hint when Quarto auto-generates a listing.
- `draft: true` — exclude from the rendered book.

Keep frontmatter minimal. Most chapter files need none.

### Lists

- Bulleted lists for unordered alternatives.
- Numbered lists for sequences of steps.
- Bullet headers: bold label, colon, then description: `- **Surprise**: ...`.

## Text Structure and Style

### Tone

Reference-manual tone: terse, precise, player-facing. Avoid filler and hedging.

### Person and voice

- Third person. Never "you".
- Gender-neutral "they" / "their". Rephrase to "the character" if awkward.
- Active voice where it tightens the sentence.

### Sentences

- Full sentences for rules text.
- Fragments are acceptable in stat blocks, table cells, and bullet headers.
- One idea per sentence. Split compound rules into bullets.

### Ordering

1. The general rule.
2. Modifiers, exceptions, and edge cases.
3. Examples.

If no natural ordering presents itself, sort alphabetically.

### Commentary

Commentary, rationale, and author notes belong in the [Designer Toolkit](designing-classes.md), not in core rules pages.

### Verbosity

Cut every sentence that does not add a fact, modifier, or example.
