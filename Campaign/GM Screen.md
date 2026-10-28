---
obsidianUIMode: preview
---
# GM Screen

Quick reference for the table. Every action name links to its full rule.

## Your turn at a glance

Each round you get **3 actions** and **1 reaction**. Actions can be spent in any order; you can split movement. Unused actions are lost. Your reaction refreshes at the start of your turn, and you can usually use it on anyone's turn, including your own.

- **Free actions** (marked [F]) cost nothing but still need their trigger or permission.
- **Reactions** (marked [R]) cost your 1 reaction per round.
- **Activities** taking longer than 1 round can't normally be done in an encounter. Committing to a multi-action activity means you spend all of it, and losing it partway means losing all those actions.

## Core numbers

**Multiple attack penalty** — resets at the end of your turn; every check with the attack trait counts.

| Attack | Normal | Agile |
|---|---|---|
| First | none | none |
| Second | –5 | –4 |
| Third or later | –10 | –8 |

**Degrees of success**

| Result | Outcome |
|---|---|
| Beat DC by 10+ | Critical success |
| Meet or beat DC | Success |
| Miss DC by less than 10 | Failure |
| Miss DC by 10+ | Critical failure |
| Natural 20 | One degree better |
| Natural 1 | One degree worse |

Natural 20/1 shifts the degree *before* any other adjustment. Apply the nat 20/1 bump first, then anything else that changes degree.

**Cover and flanking**

| Situation | Effect |
|---|---|
| Lesser cover (usually a creature) | +1 AC; can't Hide |
| Standard cover | +2 AC, Reflex vs. area effects, Stealth; can Hide |
| Greater cover (via Take Cover) | +4 to the same |
| Flanking | Target is [[Rules/conditions#Flat-Footed\|flat-footed]] (–2 AC) to melee from flankers |

You flank when you and an ally are on opposite sides or corners of the foe, both able to act, both threatening it with melee. Reach weapons use their reach for this.

**DCs**

| Rank | Simple DC |
|---|---|
| Untrained | 10 |
| Trained | 15 |
| Expert | 20 |
| Master | 30 |
| Legendary | 40 |

| Difficulty | Adjustment |
|---|---|
| Incredibly easy | –10 |
| Very easy | –5 |
| Easy | –2 |
| Hard | +2 |
| Very hard | +5 |
| Incredibly hard | +10 |

See [[Rules/tables/dcs-by-level|DCs by Level]] for level-based DCs and [[Rules/tables/creature-identification-skills|Creature Identification Skills]] for which skill identifies which creature.

## Basic actions (available to every creature)

### Attacking and spells

| Action | Cost | What it does |
|---|---|---|
| [[Rules/actions/strike\|Strike]] | [>] | Attack roll vs. AC with a wielded weapon or unarmed attack |
| [[Rules/actions/cast-a-spell\|Cast a Spell]] | varies | Cost is in the spell's stat block |
| [[Rules/actions/sustain-a-spell\|Sustain a Spell]] | [>] | Keep a sustained spell going to the end of your next turn |
| [[Rules/actions/dismiss\|Dismiss]] | [>] | End one dismissible spell or item effect |
| [[Rules/actions/activate-an-item\|Activate an Item]] | varies | Cost is in the item's stat block |
| [[Rules/actions/ready\|Ready]] | [>>] | Pick an action + trigger; use it as a reaction before your next turn |
| [[Rules/actions/raise-a-shield\|Raise a Shield]] | [>] | Gain the shield's circumstance bonus to AC until your next turn |
| [[Rules/actions/escape\|Escape]] | [>] | Check vs. the DC of whatever has you grabbed, immobilized, or restrained |
| [[Rules/actions/aid\|Aid]] | [R] | Your skill/attack check vs. DC 20: crit +2 (+3 master, +4 legendary), success +1, crit fail –1. Needs a setup action on your turn |

### Movement

| Action | Cost | What it does |
|---|---|---|
| [[Rules/actions/stride\|Stride]] | [>] | Move up to your Speed |
| [[Rules/actions/step\|Step]] | [>] | Move 5 feet; does not trigger reactions |
| [[Rules/actions/leap\|Leap]] | [>] | 10 ft horizontal (Speed 15+), 15 ft (Speed 30+); vertically 3 ft up and 5 ft across |
| [[Rules/actions/crawl\|Crawl]] | [>] | Move 5 feet while staying prone |
| [[Rules/actions/stand\|Stand]] | [>] | Stop being prone |
| [[Rules/actions/drop-prone\|Drop Prone]] | [>] | Become prone |
| [[Rules/actions/climb\|Climb]] | [>] | Athletics; needs both hands free |
| [[Rules/actions/swim\|Swim]] | [>] | Athletics, untrained |
| [[Rules/actions/burrow\|Burrow]] | [>] | Move through loose earth at your burrow Speed |
| [[Rules/actions/fly\|Fly]] | [>] | Move at fly Speed; upward movement costs like difficult terrain |
| [[Rules/actions/mount\|Mount]] | [>] | Get on (or off) a mount |
| [[Rules/actions/take-cover\|Take Cover]] | [>] | Standard cover becomes greater cover |
| [[Rules/actions/grab-an-edge\|Grab an Edge]] | [R] | Reflex save when you fall past a handhold |

Diagonal movement: 5 ft, 10 ft, 5 ft, 10 ft. Difficult terrain doubles the cost.

### Perception, knowledge, and interaction

| Action | Cost | What it does |
|---|---|---|
| [[Rules/actions/interact\|Interact]] | [>] | Manipulate an object: draw, open a door, pick something up (manipulate trait) |
| [[Rules/actions/seek\|Seek]] | [>] | Secret Perception check; 30-ft cone or 15-ft burst for creatures, 10-ft square for objects and secret doors |
| [[Rules/actions/sense-motive\|Sense Motive]] | [>] | Secret Perception check against a creature's Deception DC |
| [[Rules/actions/recall-knowledge\|Recall Knowledge]] | [>] | Skill check to remember facts; simple DCs or level-based DCs |
| [[Rules/actions/point-out\|Point Out]] | [>] | Hidden creature becomes hidden (not undetected) to allies who can see and hear you |
| [[Rules/actions/avert-gaze\|Avert Gaze]] | [>] | +2 vs. visual abilities requiring you to look |
| [[Rules/actions/release\|Release]] | [F] | Let go of something you're holding |
| [[Rules/actions/delay\|Delay]] | [F] | Drop out of initiative, re-enter at the end of any creature's turn |

## Skill actions in combat

Costs are actions. "(T)" means trained only. Saves listed are the DC you roll against.

### Acrobatics (Dex)

| Action | Cost | Notes |
|---|---|---|
| [[Rules/actions/balance\|Balance]] | [>] | Narrow surface or uneven ground; you're flat-footed on uneven ground and may fall prone on a hit or failed save |
| [[Rules/actions/tumble-through\|Tumble Through]] | [>] | Stride up to Speed, Acrobatics vs. Reflex DC to pass through one enemy's space |
| [[Rules/actions/maneuver-in-flight\|Maneuver in Flight]] | [>] | (T) requires a fly Speed |
| [[Rules/actions/squeeze\|Squeeze]] | exploration | (T) through tight spaces |

### Athletics (Str)

| Action | Cost | Notes |
|---|---|---|
| [[Rules/actions/climb\|Climb]] | [>] | Both hands free |
| [[Rules/actions/force-open\|Force Open]] | [>] | Doors, containers, stuck things |
| [[Rules/actions/grapple\|Grapple]] | [>] | vs. **Fortitude DC**; one free hand, target no more than one size larger |
| [[Rules/actions/shove\|Shove]] | [>] | vs. **Fortitude DC**; pushes 5 ft (10 ft on crit) |
| [[Rules/actions/trip\|Trip]] | [>] | vs. **Reflex DC**; knocks prone |
| [[Rules/actions/disarm\|Disarm]] | [>] | (T) vs. **Reflex DC**; on a crit you knock the item free |
| [[Rules/actions/high-jump\|High Jump]] | [>>] | Athletics check, then Leap; 5 ft up, or 8 ft on a crit |
| [[Rules/actions/long-jump\|Long Jump]] | [>>] | Athletics check, then Leap; can exceed your normal leap distance |

All the maneuvers share: target can't be more than one size larger than you, and they have the attack trait (so they take MAP).

### Deception (Cha)

| Action | Cost | Notes |
|---|---|---|
| [[Rules/actions/create-a-diversion\|Create a Diversion]] | [>] | vs. each observer's Perception DC; success makes you hidden to them |
| [[Rules/actions/feint\|Feint]] | [>] | (T) vs. **Perception DC**; target flat-footed to your next attack (better on crit) |
| [[Rules/actions/lie\|Lie]] | 1 round | vs. Perception DC; targets get +4 if they know the subject well |

### Intimidation (Cha)

| Action | Cost | Notes |
|---|---|---|
| [[Rules/actions/demoralize\|Demoralize]] | [>] | vs. **Will DC**; frightened 1 (2 on crit); target immune 10 min after an attempt |
| [[Rules/actions/coerce\|Coerce]] | 1 minute+ | vs. Will DC; in combat, rarely useful — but it's how you make someone talk |

### Stealth (Dex)

| Action | Cost | Notes |
|---|---|---|
| [[Rules/actions/hide\|Hide]] | [>] | Secret vs. Perception DC; needs cover/concealment. You stop being hidden if you do anything but Hide, Sneak, or Step |
| [[Rules/actions/sneak\|Sneak]] | [>] | Move 5 ft (up to half Speed with feats); Stealth vs. Perception DC |
| [[Rules/actions/conceal-an-object\|Conceal an Object]] | [>] | Palm an item; sets the DC for others to find it |

### Thievery (Dex)

| Action | Cost | Notes |
|---|---|---|
| [[Rules/actions/disable-a-device\|Disable a Device]] | [>>] | (T) thieves' tools; complex devices need multiple successes |
| [[Rules/actions/pick-a-lock\|Pick a Lock]] | [>>] | (T) thieves' tools; multiple successes for better locks |
| [[Rules/actions/steal\|Steal]] | [>] | vs. Perception DC; needs a hand free |
| [[Rules/actions/palm-an-object\|Palm an Object]] | [>] | vs. Perception DC |

### Medicine (Wis) — needs [[compendium/equipment/items/healers-tools|healer's tools]]

| Action | Cost | Notes |
|---|---|---|
| [[Rules/actions/administer-first-aid\|Administer First Aid]] | [>>] | Stabilize (DC = 5 + recovery roll DC) or stop bleeding |
| [[Rules/actions/treat-poison\|Treat Poison]] | [>] | (T) vs. the poison's save DC; +2 to the victim's next save (+4 on a crit) |
| [[Rules/actions/treat-wounds\|Treat Wounds]] | 10 min | (T) DC 15: 2d8 HP (4d8 on crit), wounded removed. Expert DC 20 +10 HP, master DC 30 +30, legendary DC 40 +50. Once per hour per creature |
| [[Rules/actions/treat-disease\|Treat Disease]] | downtime | (T) as Treat Poison, for disease |

### Everything else

| Skill | Actions |
|---|---|
| Nature | [[Rules/actions/command-an-animal\|Command an Animal]] [>] |
| Performance | [[Rules/actions/perform\|Perform]] [>] |
| Arcana / Occultism / Religion / Society / Lore | [[Rules/actions/recall-knowledge\|Recall Knowledge]] [>], [[Rules/actions/decipher-writing\|Decipher Writing]], [[Rules/actions/identify-magic\|Identify Magic]], [[Rules/actions/learn-a-spell\|Learn a Spell]] |
| Crafting | [[Rules/actions/repair\|Repair]] (10 min), [[Rules/actions/identify-alchemy\|Identify Alchemy]] (10 min), [[Rules/actions/craft\|Craft]] (downtime) |
| Survival | [[Rules/actions/track\|Track]], [[Rules/actions/sense-direction\|Sense Direction]], [[Rules/actions/cover-tracks\|Cover Tracks]], [[Rules/actions/subsist\|Subsist]] |
| Diplomacy | [[Rules/actions/gather-information\|Gather Information]], [[Rules/actions/make-an-impression\|Make an Impression]], [[Rules/actions/request\|Request]] |

## Exploration activities

Declare one for the whole party member while travelling. Most cap you at half travel speed; the party moves at the slowest member's pace.

| Activity | Speed | Effect |
|---|---|---|
| [[Rules/actions/avoid-notice\|Avoid Notice]] | half | Stealth check; if a fight starts you roll Stealth for initiative and to stay unnoticed |
| [[Rules/actions/defend\|Defend]] | half | Shield raised when combat breaks out (before your first turn) |
| [[Rules/actions/detect-magic\|Detect Magic]] | half | Repeated detect magic; no chance to miss an aura at 300 ft/min, none before the party reaches it at 150 ft/min |
| [[Rules/actions/investigate\|Investigate]] | half | Secret Recall Knowledge checks for clues as you go |
| [[Rules/actions/repeat-a-spell\|Repeat a Spell]] | half | Keep a 2-action-or-less spell (usually a cantrip) running; can also sustain a spell or activation |
| [[Rules/actions/scout\|Scout]] | half | Whole party gets +1 circumstance to initiative |
| [[Rules/actions/search\|Search]] | half | Automatic secret Seek checks for hidden doors, hazards, items; 150 ft/min to check everything before you reach it |
| [[Rules/actions/follow-the-expert\|Follow the Expert]] | varies | Copy an expert+ ally's tactic; add your level to the check, +2/+3/+4 by their rank |
| [[Rules/actions/hustle\|Hustle]] | ×2 | Double travel speed for Con modifier × 10 minutes (minimum 10) |
| [[Rules/actions/track\|Track]] | half | Survival to follow tracks |

Skill-based exploration activities from Chapter 4: [[Rules/actions/borrow-an-arcane-spell|Borrow an Arcane Spell]], [[Rules/actions/coerce|Coerce]], [[Rules/actions/cover-tracks|Cover Tracks]], [[Rules/actions/decipher-writing|Decipher Writing]], [[Rules/actions/gather-information|Gather Information]], [[Rules/actions/identify-alchemy|Identify Alchemy]], [[Rules/actions/identify-magic|Identify Magic]], [[Rules/actions/impersonate|Impersonate]], [[Rules/actions/learn-a-spell|Learn a Spell]], [[Rules/actions/make-an-impression|Make an Impression]], [[Rules/actions/repair|Repair]], [[Rules/actions/sense-direction|Sense Direction]], [[Rules/actions/squeeze|Squeeze]], [[Rules/actions/track|Track]], [[Rules/actions/treat-wounds|Treat Wounds]].

Don't forget [[Rules/actions/refocus|Refocus]]: 10 minutes to regain 1 Focus Point, and it usually stacks with whatever else you're doing.

## Reference tables

- [[Rules/tables/travel-speed|Travel Speed]]
- [[Rules/tables/dcs-by-level|DCs by Level]]
- [[Rules/tables/simple-dcs|Simple DCs]]
- [[Rules/tables/dc-adjustments|DC Adjustments]]
- [[Rules/tables/size-and-reach|Size and Reach]]
- [[Rules/tables/creature-identification-skills|Creature Identification Skills]]
- [[Rules/conditions|Conditions]] — the full list, alphabetized

## This adventure

- [[Campaign/Adventures/Abomination Vaults/Gauntlight Ruins|Gauntlight Ruins]] — level 1, areas A1–A25
- [[Campaign/Adventures/Abomination Vaults/Servants' Quarters|Servants' Quarters]] — level 2, areas B1–B35
- [[Campaign/Adventures/Abomination Vaults/Library|Library]] — level 3, areas C1–C40
