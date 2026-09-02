# Naruto 5e — PvP Protocol v0.1

**Status:** PLAYTEST PROTOCOL

PvP resolves player-vs-player Naruto 5e combat using the shared rules without mixing either fighter's campaign state into the other.

## Source of truth

PvP uses the current shared mechanics in `mechanics/`.

Unresolved mechanics must not be silently converted into permanent rules. If one matters during a match, declare a temporary ruling before the roll and record it in the match log.

## Isolation

Each fighter enters PvP with a validated character snapshot. The match starts from that snapshot. Campaign injuries, spent resources, prepared effects, equipment, summons or other state are not imported unless explicitly included.

PvP results do not automatically alter campaign canon or character progression.

## Match setup

Record for both fighters:
- Name
- Level / tier
- HP
- Chakra
- Stamina
- ATK
- DEF
- CONTROL
- Affinities
- Known techniques and costs
- Relevant passives/reactions
- Battlefield
- Starting distance
- Agreed restrictions

Both fighters receive the same starting information.

## Initiative

Use an established initiative rule when one exists. If none exists, use a clearly declared provisional d20 contest and record it as provisional.

## Turn procedure

Every meaningful action follows:

**DECLARE → MECHANICS → ROLL → RESOLVE → CINEMATIC**

Before the roll, the adjudicator states the relevant action economy, Chakra cost, Stamina cost if applicable, complexity and DC/contest whenever those values are not already fixed by the technique.

## Contested actions

Use the technique and situation to determine the appropriate resolution. Examples include ATK vs DEF for direct attacks, CONTROL for relevant chakra manipulation, and Stamina for physical endurance/strain.

Do not force every action into one universal formula.

## Jutsu

Before resolving a jutsu, determine:
- action type;
- Chakra cost;
- range/target;
- effect;
- resolution type;
- DC or opposing value;
- relevant affinity/proficiency;
- concentration/duration if applicable;
- available counterplay.

If the fighter cannot pay the declared Chakra cost, the technique is normally unavailable unless an explicitly established Overload rule applies.

## Reactions and prepared effects

A Reaction is available only when the character/technique grants one and its trigger occurs.

Prepared effects remain available according to their established duration and conditions. Preparation and exploitation are separate actions/resources unless a specific technique explicitly combines them.

## Damage and defeat

Use the fighter's actual HP, Chakra and Stamina and the technique's established effects. Consequences may instead be conditions, positioning, resource loss or interruption when the rules support that outcome.

Default victory condition: the opponent is no longer capable of continuing the fight.

## Fair adjudication

The same rules apply to both fighters. The adjudicator must reveal the mechanical basis of contested rulings, must not use hidden future declarations to favor either side, and must keep campaign canon separate from the PvP result.

## Match log

Record:

`Round → Fighter → Declaration → Mechanics → Roll → Result → Resource change → State change → Narration`

A match log is a playtest artifact. It can reveal balance problems or missing rules but does not automatically change the core system.
