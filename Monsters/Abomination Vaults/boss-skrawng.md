---
obsidianUIMode: preview
noteType: pf2eMonster
aliases:
  - Boss Skrawng
  - Skrawng
tags:
  - pf2e/creature/type/fey
  - pf2e/creature/level/1
  - pf2e/creature/rarity/unique
statblock: inline
name: Boss Skrawng
level: 1
image: atlas-vtt/collections/Default/tokens/Monsters/BOSS_SKRAWNG_1791920119867_k0rjsg.webp
---
```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "AV1"
name: "Boss Skrawng"
level: "Creature 1"
alignment: "LE"
size: "Small"
trait_03: "Unique"
trait_04: "Fey"
trait_05: "Gremlin"
modifier: 7
perception:
  - name: "Perception"
    desc: "Perception +7; __darkvision__, __imprecise scent 30 feet__;"
languages: "Common, Undercommon; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +7 (1d20+7); __Diplomacy__: +4 (1d20+4), (Diplomacy: +10 (1d20+10) vs. arthropods); __Nature__: +5 (1d20+5); __Stealth__: +7 (1d20+7); __Thievery__: +7 (1d20+7); "
abilityMods: [1, 4, 1, 0, 2, 1]

abilities_top:
  - name: "Self-Loathing"
    desc: " ([[emotion]], [[mental]]);  A mitflit's self-loathing makes it easy to influence. It takes a –4 penalty to its Will DC against checks to [[Coerce]], [[Demoralize]], [[Make-an-Impression|Make an Impression]], and [[Request]]."
  - name: "Vermin Empathy"
    desc: "  Mitflits can use [[compendium/skills.md#Diplomacy|Diplomacy]] to [[Make-an-Impression|Make an Impression]] on and [[Request]] things of arthropods (insects, spiders, scorpions, crabs, and similar invertebrate animals). Most arthropods have a starting attitude of [[rules/conditions.md#Indifferent|indifferent]] to mitflits."
  - name: Items
    desc: "blowgun (10 darts, 2 with spear frog poison), mud and bug crown, trident;"
abilities_bot:
  - name: "Vengeful Anger"
    desc: " ([[emotion]], [[mental]]);  As long as it isn't [[rules/conditions.md#Frightened|frightened]], a mitflit gains a +2 status bonus to damage rolls against a creature that has previously damaged or tormented it."
  - name: "Spear Frog Poison"
    desc: " ([[poison]]); __Saving Throw__ DC 15 Fortitude; __Maximum Duration__ 6 rounds; __Stage 1__ 1d4 poison damage (1 round); __Stage 2__ 1d6 poison damage and [[rules/conditions.md#Enfeebled|enfeebled 1]] (1 round)"

speed: 20 feet; climb 20 feet;

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +4 (1d20+4); __Ref__: +9 (1d20+9); __Will__: +8 (1d20+8);"
hp: 24
health:
  - name: HP
    desc: "24; __Weaknesses__ cold iron 3; "

attacks:
  - name: Melee
    desc: "⬻ trident +6; __Damage__ 1d8+1 (1d8+1) piercing"
  - name: Ranged
    desc: "⬻ blowgun +9 ([[agile]], [[nonlethal]], [[range-increment|range increment 20 feet]]); __Damage__ 1 (1) piercing plus spear frog poison"
  - name: Ranged
    desc: "⬻ trident +9 ([[thrown|thrown 20 feet]]); __Damage__ 1d8+1 (1d8+1) piercing"

spellcasting:
  - name: "Primal Innate Spells"
    desc: "DC 17; __Cantrips (1st)__ [[prestidigitation]]; __1st__ [[bane]]; __2nd__ [[speak-with-animals|speak with animals]] at will; arthropods only;"
sourcebook: "_Abomination Vaults_ #1: Ruins of Gauntlight, page 12."
```

## At the table (A10)

Unique mitflit gang boss, leader of the Mudlickers. Not in a bestiary — the statblock above is transcribed from the adventure text, and the mitflit abilities are inherited unchanged ("as mitflit").

- He hangs back behind the throne and shoots from cover while the two mitflits and Bite Bite close to melee.
- The throne is scenery with **AC 10, Hardness 2, 3 HP**. At the end of each of his turns it shudders; it only collapses if a hero strikes it. If it does, he is [[Rules/conditions#Prone|prone]] and must burn at least 1 action per turn for 3 turns sputtering in Undercommon.
- He **begs for mercy at 5 HP or fewer** — his followers keep fighting to the death while he lives. That is the lever for the "what he knows" conversation on the fly.
- He speaks Common, unlike the rest of the Mudlickers, so he can be talked to. Bribe of 20 gp buys the crude maps.
