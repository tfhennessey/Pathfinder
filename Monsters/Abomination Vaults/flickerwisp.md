---
obsidianUIMode: preview
noteType: pf2eMonster
aliases:
  - Flickerwisp
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/level/2
  - pf2e/creature/rarity/uncommon
statblock: inline
name: Flickerwisp
level: 2
image: atlas-vtt/collections/Default/tokens/Monsters/flickerwhips_1791920119755_1dzy33.webp
---
```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "AV1"
name: "Flickerwisp"
level: "Creature 2"
alignment: "CE"
size: "Small"
trait_03: "Uncommon"
trait_04: "Aberration"
trait_05: "Air"
modifier: 9
perception:
  - name: "Perception"
    desc: "Perception +9; __darkvision__;"
languages: "Aklo, Common; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +8 (1d20+8); __Deception__: +7 (1d20+7); __Intimidation__: +5 (1d20+5); __Stealth__: +8 (1d20+8); "
abilityMods: [-5, 4, 0, 0, 3, 1]

abilities_top:
  - name: "Glow"
    desc: " ([[aura]], [[light]]) 5 feet. A flickerwisp is itself naturally invisible, but glows with pale yellow light, casting bright light in the aura and making it visible."
  - name: "Innocuous"
    desc: "  A flickerwisp's appearance registers strangely in the minds of creatures who are [[rules/conditions.md#Confused|confused]]. A creature with the confused condition never targets a flickerwisp with attacks unless the creature has been damaged by the flickerwisp's shock ability within the last 24 hours."
  - name: "Magic Immunity"
    desc: "  A flickerwisp is immune to all spells except [[compendium/spells/faerie-fire|faerie fire]], [[compendium/spells/gust-of-wind|gust of wind]], [[compendium/spells/magic-missile|magic missile]], and [[compendium/spells/maze|maze]]."

abilities_bot:
  - name: "Consume Confusion"
    desc: "⬻ ([[concentrate]]); __Frequency__ once per round; __Requirement__ A creature within 15 feet of the flickerwisp is confused; __Effect__ The flickerwisp feeds on the creature's confusion, even as its flashing body and disjointed gyrations cause existing confusion effects to persist. It regains 1d4 Hit Points, and if the creature's confused condition has a limited duration, it lasts 1 additional round."
  - name: "Flicker"
    desc: "⬺ ([[emotion]], [[enchantment]], [[mental]], [[visual]]); The flickerwisp churns and flits in the air around an adjacent creature's head, and its length flashes and sparkles in a bewildering array of distracting pulsations. The creature must succeed at a DC 18 Will save or become [[rules/conditions.md#Confused|confused]] for 1 round (2 rounds on a critical failure). On a critical success, the creature is temporarily immune to Flicker for 24 hours."

speed: fly 25 feet;

ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__: +6 (1d20+6); __Ref__: +10 (1d20+10); __Will__: +7 (1d20+7);"
hp: 18
health:
  - name: HP
    desc: "18; __Immunities__ magic; "

attacks:
  - name: Melee
    desc: "⬻ shock +11 ([[magical]]); __Damage__ 1d8+2 (1d8+2) electricity"

sourcebook: "_Abomination Vaults_ #1: Ruins of Gauntlight, page 83."
```
