# Naruto 5e — Resource & Scaling Rules v0.1

**Status:** ESTABLISHED PLAYTEST RULES

This file locks the current resource-recovery, initiative and damage-scaling decisions. Character-specific starting values remain part of character creation and must not be invented from another character.

## 1. Chakra Recovery

Chakra is a numerical pool.

A character may spend their **Action** to recover Chakra.

**Recovery = 40% of maximum Chakra, rounded down.**

`Recovered Chakra = floor(Max Chakra × 0.40)`

Recovery cannot raise Chakra above its maximum.

Example:

`Max Chakra = 44`

`44 × 0.40 = 17.6 → 17 Chakra recovered`

The recovery action consumes the character's Action for that turn.

## 2. Stamina

Stamina is the physical resource used by Taijutsu, strenuous movement and other physically demanding actions.

Stamina is spent for:
- Taijutsu;
- strenuous movement;
- sustained physical exertion;
- other actions whose declared mechanics require physical effort.

The exact Stamina Cost is determined from the declared action and its physical difficulty, using the same declaration-first philosophy as Chakra costs.

A character may spend their **Action** to recover Stamina.

**Stamina recovery = 40% of maximum Stamina, rounded down.**

`Recovered Stamina = floor(Max Stamina × 0.40)`

Recovery cannot raise Stamina above its maximum.

Light movement does not automatically consume a fixed amount of Stamina. The GM determines whether movement is strenuous enough to require a Stamina Cost.

## 3. Initiative

At the start of an encounter, every participating combatant rolls:

`d20`

The result determines initiative order, highest result first.

Ties are resolved by a new d20 roll between the tied participants unless a later established rule provides another tie-breaker.

No Initiative modifier is currently added.

## 4. Damage Scaling

Damage is determined from the **declared technique**, not selected freely by the player after the roll.

The GM evaluates:
- technique type;
- Complexity;
- character level;
- scale;
- number of targets;
- range;
- duration;
- precision;
- special effects;
- relevant Affinity and Proficiency.

The resulting power tier determines the damage dice.

### Scaling principle

Damage should increase progressively rather than jumping arbitrarily between unrelated values.

For recurring techniques, the GM should establish a base damage package at the technique's current power tier and scale it upward primarily through additional dice rather than artificially increasing die size every level.

A technique that becomes substantially stronger through level progression should normally gain approximately **10% additional damage budget per level of meaningful progression**, rounded to a practical whole die/package. This is a scaling guideline for balancing recurring techniques, not permission to calculate fractional dice during play.

Example concept:

`Base package → +10% per meaningful level → round to the nearest practical dice package`

The GM may depart from this guideline when a technique's actual effect changes substantially, such as gaining a much larger area, additional targets, persistent duration, piercing defenses or major battlefield manipulation.

### Damage dice and the dice roller

Damage may use d4, d6, d8, d10 or d12 and multiple dice may be rolled together.

If a damage package is too large for the player's dice application, it may be split into equivalent groups and summed.

## 5. Resource Philosophy

Chakra and Stamina are real numerical resources, not narrative labels.

The player must always know:
- current resource;
- maximum resource;
- cost of the declared action;
- resulting resource after resolution.

Recovery is an actual action and therefore competes with offensive, defensive and utility actions.

The 40% recovery rule is intentionally strong: recovering a large portion of a pool costs the character a full Action. This creates a meaningful combat choice between acting now and restoring resources.

## 6. Character Creation Boundary

This document does **not** define universal starting HP, Chakra or Stamina values.

Those values are calculated when a character is created from the shared character-creation framework and the character's chosen build.

Do not copy another character's resource totals.

The following remain character-creation inputs to be locked separately:
- starting HP calculation;
- starting Chakra calculation;
- starting Stamina calculation;
- level progression of those pools;
- ATK;
- DEF;
- CONTROL;
- Jutsu modifier;
- Taijutsu modifier;
- Genjutsu modifier;
- Social modifier;
- Affinity;
- Proficiency;
- starting/basic technique access.
