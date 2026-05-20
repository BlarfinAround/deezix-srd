# Combat

## The Combat Round

Time in combat is measured in **rounds**, each representing approximately **10 seconds** of frantic action. In each round, both sides act once. The sequence is:

::: {.callout-important title="Combat Sequence"}

1. **Declarations** — Spells and Disengages.
2. **Roll Initiative** — Each side rolls 1d6. The higher result is the **winning side**.
3. **Winning side acts**, in this order:
    1. Movement
    2. Ranged attacks
    3. Spells resolve
    4. Melee and other actions
4. **Losing side acts**, in the same order.
5. **Morale** — Referee checks for monsters if applicable.
6. **New Round** — Return to step 1.
:::

## Initiative

Initiative is **side-based** and re-rolled every round (step 2 above). When a side wins, its members act in any order the players choose.

On a **tied initiative**, both sides act simultaneously — attacks, damage, and effects resolve at the same moment. Characters may kill each other in the same round.

## Actions in Combat

On their turn, a character may:

- **Move** up to their combat movement rate.
- **Attack** with a melee or ranged weapon (one attack per round).
- **Cast a spell** declared at the start of the round (see [Casting in Combat](../magic/magic-overview.md#casting-in-combat)).
- **Disengage** from melee, declared at the start of the round.
- **Use an item** (drink a potion, light a torch, read a scroll).
- **Perform another action** at the referee's discretion.

## Combat Movement

| Condition    | Combat Movement (per round) |
| ------------ | --------------------------- |
| Unencumbered | 40'                         |
| Encumbered   | 20'                         |

Characters **in melee** move at half their combat movement rate. To leave at full rate, declare **Disengage**.

### Disengage

::: {.callout-important title="Disengage"}
Declare Disengage before initiative is rolled.

A disengaging character moves at **full** combat movement rate, leaving melee. All attacks against them this round are at **+2** and ignore their shield bonus.

A successful [Tumble](skills.md#tumble) roll at declaration negates the penalty.
:::

## In Melee

A character is **in melee** with an opponent when:

- They are within **5'** of the opponent, *and*
- One side has made an attack against the other.

The relationship persists until one party Disengages or is slain.

## Attack Rolls

To hit an enemy in combat, make an **attack roll**: roll 1d20, add the **Attack Bonus** and relevant ability modifier, and compare the total to the target's **Armor Class (AC)**.

::: {.callout-important title="Attack Roll"}
1d20 + Attack Bonus + STR mod (melee) or DEX mod (ranged) **≥ Target's AC** = Hit
:::

### Attack Bonus (AB)

Every class has an **Attack Bonus** that improves as they level.

### Weapon Access

Using a weapon outside the class's permitted list: **−2 to the attack roll**.

### Modifiers to Attack Rolls

| Condition                                               | Modifier        |
| ------------------------------------------------------- | --------------- |
| STR modifier (melee attack)                             | +/− per STR mod |
| DEX modifier (ranged attack)                            | +/− per DEX mod |
| Backstab (thief ability)                                | +4              |
| Attacking into melee with a ranged weapon               | −4              |
| Attacking an unmounted opponent while mounted           | +2              |
| Attacking with a ranged weapon while mounted and moving | −2              |

### Damage

On a hit, the attacker rolls the weapon's **damage die** and subtracts the result from the target's HP.

**STR modifier** applies to melee damage. Ranged weapons add no ability modifier to damage.

See [Armor Class](../character/equipment/weapons-and-armor.md#armor-class) for AC rules.

## Ending Combat

Combat ends when one side is dead, incapacitated, fled, or surrendered. Morale determines when monsters break; see [Morale and Loyalty](../referee/reactions-morale-loyalty.md). Player characters are never forced to flee by morale.

## Special Combat Situations

### Subduing

::: {.callout-important title="Subduing"}
Declare **intent to subdue** before attacking. Damage is rolled normally; if the target would reach 0 HP from this blow, they are knocked unconscious instead. They wake in 1d6 turns (or sooner if disturbed).
:::

Creatures that are not humanoid and roughly human scale may require special means for subdual (referee's discretion).

### Morale

See [Morale and Loyalty](../referee/reactions-morale-loyalty.md).
