# Naruto 5e — Core Mechanics v0.3

**Status:** ESTABLISHED PLAYTEST CORE

This document is the shared mechanical foundation for Naruto 5e. It is written so a player can use the system without knowing D&D 5e.

## 1. Design philosophy

Naruto 5e uses familiar dice and a clear resolution structure, but the player does not need prior D&D knowledge.

The GM explains the mechanic before the roll. The player only needs to know:
- what is being attempted;
- what type of roll is required;
- which modifier applies;
- the DC, when a DC applies;
- the resource cost;
- what the result means.

Naruto flavor changes how an action looks, not how many actions a character receives unless a specific rule says otherwise.

## 2. Dice

The system uses standard polyhedral dice:
- d20
- d12
- d10
- d8
- d6
- d4

`XdY` means rolling X dice of type Y and adding the results.

Examples:
- `1d20` = one twenty-sided die;
- `3d8` = three eight-sided dice, added together;
- `6d10` = six ten-sided dice, added together.

The player may roll using any standard dice roller. If needed, the GM may roll on the player's behalf, but the preferred experience is for the player to roll their own dice.

## 3. The d20 and DC

The **d20** is the primary uncertainty die.

**DC (Difficulty Class)** means how difficult the declared action is. The player rolls the required d20/check and succeeds when the final result meets or exceeds the declared DC.

Stable DC guidance:
- DC 8 — trivial
- DC 10 — easy
- DC 12 — routine combat task
- DC 14 — demanding
- DC 16 — difficult
- DC 18 — very difficult
- DC 20 — exceptional
- DC 22+ — extraordinary

The DC is chosen from the declared action and its actual mechanical complexity. Relevant factors include complexity, scale, range, duration, precision, simultaneous effects, battlefield interaction, affinity, proficiency and preparation.

The GM must establish the DC before the roll whenever the action requires one.

## 4. Mandatory action procedure

Every meaningful uncertain action follows the same sequence:

**DECLARE → MECHANICS → ROLL → RESOLVE → CINEMATIC**

### DECLARE
The player says what they want to do.

### MECHANICS
The GM translates the declaration into game mechanics before the roll:
- action economy;
- action type;
- technique type;
- Complexity;
- Chakra Cost;
- applicable modifier/proficiency;
- DC or target defense;
- damage/effect if relevant.

### ROLL
The player makes the stated roll.

### RESOLVE
The GM applies the result to the battlefield, resources and targets.

### CINEMATIC
Only after the mechanical result is known does the GM narrate the outcome cinematically.

Cinematic narration never retroactively creates extra actions, free resources, extra movement or additional rolls.

## 5. Core action economy

Unless a specific ability says otherwise, a combat turn contains:
- Movement;
- 1 Action;
- 1 Bonus Action, if a feature allows one;
- 1 Reaction per round;
- free speech/simple interaction.

A fast-looking Naruto technique does not automatically create extra actions.

Multiple techniques in one turn require an actual mechanical reason, such as Action + Bonus Action, Action + Reaction, or a feature explicitly permitting the combination.

Rapid hand seals are normally cinematic unless a technique explicitly gives them mechanical importance.

## 6. Four primary roll categories

Naruto 5e distinguishes four common categories of meaningful rolls.

### Jutsu Roll
Used when executing chakra-based techniques.

`d20 + applicable Jutsu modifier`

The GM determines whether the technique instead requires a Control check, target save/check, or another defined resolution.

### Taijutsu Roll
Used for physical combat techniques, martial attacks and similar physical actions.

`d20 + applicable Taijutsu modifier`

### Genjutsu Roll
Used when applying or executing Genjutsu.

`d20 + applicable Genjutsu modifier`

The target may then make the defense/check required by the specific technique.

### Social Check
Used for persuasion, deception, intimidation, negotiation, reading a social situation and other meaningful social interaction.

`d20 + Social modifier`

Social actions always use a modifier when a meaningful check is required. They are not simply unmodified d20 rolls.

## 7. Control

**CONTROL** represents precision in chakra molding and technique execution.

Control is a character score, not automatically a flat bonus to every roll.

When a Control check is required:

`d20 + Control Modifier vs declared DC`

Control Modifier:

`floor((CONTROL - 10) / 2)`

Examples:
- CONTROL 7 → −2
- CONTROL 10 → +0
- CONTROL 14 → +2
- CONTROL 16 → +3
- CONTROL 18 → +4
- CONTROL 20 → +5

Simple techniques may require no Control check. Complex or improvised techniques may require one.

The GM must state that Control is relevant before the roll. Control is not secretly added to every jutsu.

## 8. Chakra

Chakra is a numerical resource pool.

Example:

`Chakra 44 / 44`

Using a technique with Cost 7 changes it to:

`Chakra 37 / 44`

The earlier `6d20` Chakra-pool concept is retired. d20s are resolution dice, not Chakra units.

Every meaningful non-basic jutsu has a Chakra Cost.

Current cost guidance:
- Basic: 0–1
- Simple: 2–4
- Moderate: 5–8
- Advanced: 9–14
- Major: 15–20+
- Exceptional: individually determined

These ranges are guidance, not universal spell prices. The actual Cost is determined from the declared technique and its Complexity.

If a character does not have enough Chakra, the technique is normally unavailable unless an established Overload rule explicitly permits forcing it.

## 9. Complexity

**Complexity is determined from the declared technique at the moment the action is declared.**

The GM evaluates what the player is actually attempting before determining:
- Complexity;
- DC;
- Chakra Cost;
- damage/effect;
- required roll.

Complexity reflects the actual difficulty of the technique, including factors such as scale, precision, range, duration, multiple simultaneous effects and battlefield manipulation.

A player cannot declare a simple technique and add major effects after the roll to avoid its proper Complexity.

## 10. Basic Shinobi Techniques

Basic shinobi techniques function as the system's equivalent of cantrips: foundational techniques that a trained shinobi can use without treating every use as a major resource expenditure.

Examples may include basic versions of:
- Bunshin;
- Henge;
- Kawarimi;
- Body Flicker;
- basic chakra manipulation;
- other universally taught shinobi fundamentals.

A basic technique can become the foundation for more complex techniques when combined with other known principles.

More advanced applications may require higher level, training, proficiency, affinity or another explicit requirement.

## 11. Jutsu construction

Every recurring complex jutsu should eventually define:
- Name;
- Type: Jutsu / Genjutsu / Taijutsu where applicable;
- Nature/Affinity;
- Complexity;
- Action cost;
- Range;
- Target/Area;
- Roll or defense method;
- DC or target defense;
- Chakra Cost, if applicable;
- Damage/effect;
- Duration;
- Concentration requirement, if any;
- Scaling;
- Special interactions;
- Level/training requirements, if any.

Improvised techniques may be created during play, but the GM assigns their temporary mechanics before resolution and clearly marks any new ruling as provisional unless the rule already exists.

## 12. Damage

Damage is represented with standard dice.

The complexity, level, scale and actual effect of a technique determine its damage dice. The GM chooses an appropriate die type and number based on the technique rather than allowing the player to select an arbitrary damage package.

The system supports multiple damage dice, including large rolls where appropriate. A standard dice roller can handle up to the practical limit of the player's chosen application; if a roll exceeds that limit, the GM may split it into clearly equivalent groups.

Narrative destruction does not automatically equal combat damage. Combat damage must be mechanically established.

## 13. Affinity

Elemental Affinity is established during character creation.

Affinity determines what elemental manipulation a character is naturally suited to and can affect the difficulty, availability or quality of relevant techniques according to established character rules.

Affinity is not a reason to create extra rolls for every technique.

## 14. Proficiency

Proficiency is established during character creation.

Relevant proficiency categories may include:
- Jutsu;
- Taijutsu;
- Genjutsu;
- Senjutsu;
- Social Interaction;
- other explicitly established specialties.

Proficiency affects the character's applicable modifiers and/or access to techniques according to the character-creation rules.

Do not invent additional proficiency rolls simply because a character has a proficiency.

## 15. Character creation and progression

Character creation is collaborative and sequential.

The player describes the kind of shinobi they want to become. The system then translates that concept into mechanical choices, including stats, Chakra, Stamina, affinities, proficiencies and starting techniques.

The player does not need to know D&D rules to create a character.

Character-specific numerical formulas are part of the character-creation rules and profile, not this generic combat document. Do not copy another character's values into a new character.

### Power progression principle

Powerful abilities are generally **progression goals, not permanent impossibilities**.

When a player asks for an ability above their current level, the GM should not simply reject the concept if it can reasonably exist in the system.

Instead:
1. identify what the player is trying to achieve;
2. determine the appropriate power tier;
3. check the current level, affinities, proficiencies and training;
4. explain what is currently possible;
5. identify the progression path toward the desired ability;
6. provide a weaker/current-stage version when appropriate;
7. preserve the advanced ability as a meaningful future goal.

Example:

A new Level 7 character asks for Madara-scale meteor techniques capable of destroying an army.

The GM should explain that the character is not currently at that power tier, but that the concept can become a high-level progression goal. A Level 20-scale technique may require additional level, affinity, proficiency and/or training requirements.

The point is **"not yet"**, not **"never."**

### Examples of progression framing

**Kekkei Tōta / extreme elemental mastery:**
A character with only a limited number of Chakra Natures and one relevant proficiency should not immediately perform army-scale techniques. The GM should show the route toward the required mastery and level rather than declaring the concept impossible.

**Sharingan:**
A player may begin with a basic stage when their character qualifies. Higher stages such as Mangekyō should be gated behind appropriate level and any required training/story conditions rather than being treated as permanently unavailable.

**Senjutsu:**
Basic Senjutsu access can begin through training. Greater mastery and Sage-level abilities can require a dedicated training path and additional progression.

These examples illustrate the philosophy, not a complete list of fixed level gates. Specific gates must be established explicitly before being treated as universal rules.

## 16. Basic conditions

Use a small set of recognizable conditions and always explain their consequence in plain language.

Examples include:
- Restrained — movement is severely limited and attacks against the character may become easier depending on the established rule;
- Stunned — the character is temporarily unable to act normally;
- Prone — the character is knocked down and movement/attacks are affected;
- Blinded — sight-based actions are impaired;
- Charmed — social/hostile interaction is affected by the condition's defined consequence;
- Unconscious — the character cannot act normally until the condition ends.

Do not create a custom condition when an existing basic condition expresses the same mechanical consequence.

Exact condition wording and numerical consequences should be defined in the shared conditions reference before being treated as locked.

## 17. Reactions

A Reaction is a real resource.

Once spent, it is unavailable until the character's next turn begins unless a specific rule restores or modifies it.

Defensive techniques such as Substitution are Reactions only when the character has a defined Reaction-based technique and meets its requirements.

## 18. Prepared effects

Prepared techniques can persist and be exploited later when their mechanics allow it.

Setup and exploitation are separate actions/resources unless a specific technique explicitly combines them.

A player cannot retroactively use an effect that did not mechanically exist at the moment it is needed.

## 19. Concentration

Where a technique is mechanically equivalent to a sustained concentration effect, use the established concentration rule unless the technique explicitly replaces it.

## 20. Nature Energy and Senjutsu

Nature Energy is separate from ordinary Chakra.

Senjutsu can involve gathering, storing, transferring and molding Nature Energy with Chakra.

Basic Senjutsu may be accessible through appropriate training. Higher Senjutsu mastery is a progression path rather than an automatically available starting power.

Exact numerical Senjutsu limits, conversion rates, Sage Mode thresholds and advanced transformations remain unresolved unless explicitly locked in a newer shared rule.

## 21. Overload

If current Chakra is insufficient for a technique, the technique is normally unavailable.

A future or established Overload rule may allow a character to force a technique beyond the safe Chakra reserve. Until such a rule is explicitly locked, negative Chakra is not automatically permitted.

## 22. GM correction rule

If a declared action violates established action economy, resource limits, positioning, reaction economy or known technique rules, the GM corrects it **before** resolving the action.

Preferred style:

> "Cool idea. Mechanically that's two actions. You can do X now, or use Y if you have the feature that combines them."

The GM should preserve the player's intended fantasy where possible while correcting the mechanics.

## 23. Canon, established rules and provisional rulings

Use these labels consistently:

**ESTABLISHED** — locked shared rule.

**PLAYTEST/DRAFT** — currently being tested and not fully locked.

**PROVISIONAL RULING** — temporary decision required to continue play; record it for later review.

**UNKNOWN** — the available rules do not define the answer.

Never silently turn a provisional ruling into permanent canon.

## 24. Core GM principle

The GM's job is not to say no to creative Naruto ideas. The GM's job is to translate those ideas into fair progression and mechanics.

When an idea is too powerful for the current character:

**Do not kill the fantasy. Build the road toward it.**

The player should leave the conversation knowing both:
- what they can do now;
- what they can become later.
