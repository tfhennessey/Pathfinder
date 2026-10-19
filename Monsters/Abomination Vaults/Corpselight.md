---
obsidianUIMode: preview
noteType: pf2eMonster
aliases:
  - Corpselight
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/level/2
  - pf2e/creature/rarity/rare
statblock: inline
name: Corpselight
level: 2
image: atlas-vtt/collections/Default/tokens/Monsters/corpselight_1791920119778_d3uqyb.webp
---
```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "AV1"
name: "Corpselight"
level: "Creature 2"
alignment: "CE"
size: "Medium"
trait_03: "Rare"
trait_04: "Undead"
modifier: 7
perception:
  - name: "Perception"
    desc: "Perception +7; __corpse sense (precise) 30 feet__, __darkvision__;"
languages: "Common, Necril; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +7 (1d20+7); __Intimidation__: +8 (1d20+8); __Stealth__: +8 (1d20+8); "
abilityMods: [3, 4, 1, 1, 1, 2]

abilities_top:
  - name: "Corpse Sense"
    desc: "  A corpselight can sense dead bodies within range. This is a precise sense that functions through solid barriers less than 5 feet thick."

abilities_bot:
  - name: "Sunlight Powerlessness"
    desc: "  A corpselight exposed to sunlight is [[rules/conditions.md#Stunned|stunned 2]] and [[rules/conditions.md#Clumsy|clumsy 2]], and cannot Claim a Corpse."
  - name: "Wisp Form"
    desc: "  When a corpselight is reduced to 0 Hit Points while merged with a corpse, it is instead reduced to 1 Hit Point as the corpse collapses to the ground and the corpselight emerges in its wisp form. While in wisp form, a corpselight is Tiny and can take no actions other than Claim Corpse or Fly. A corpselight that starts its turn in wisp form must attempt a DC 16 flat check at the end of its turn; if it fails, it loses 1 Hit Point. A corpselight reduced to 0 Hit Points while in wisp form is destroyed."
  - name: "Claim Corpse"
    desc: "⬻ ([[necromancy]]); __Prerequisites__ The corpselight is in wisp form and is adjacent to a Medium or Small corpse that hasn't been claimed by a corpselight in the past 24 hours; __Effect__ The corpselight merges with the corpse, causes the corpse to Stand, and regains 3d6 Hit Points."
  - name: "Death Light"
    desc: "⬽ ([[emotion]], [[fear]], [[mental]], [[necromancy]], [[occult]]); __Prerequisites__ The corpselight is in a corpse; __Effect__ The corpselight emits a sickly blue beam of light from its mouth and eyes in a 20-foot cone. All living creatures in this area must attempt a DC 18 Fortitude saving throw. If at least 1 creature fails its save, the corpselight regains 2d6 Hit Points, gaining any that exceed its maximum as temporary Hit Points that last for 1 minute. The corpselight can't use Death Light again for 1d4 rounds. __Critical Success__ The creature is unaffected. __Success__ The creature takes 1d6 negative damage. __Failure__ The creature takes 2d6 negative damage and is [[rules/conditions.md#Frightened|frightened 1]]. __Critical Failure__ The creature takes 4d6 negative damage and is frightened 3."

speed: 25 feet; fly 25 feet (wisp form only);

ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__: +5 (1d20+5); __Ref__: +10 (1d20+10); __Will__: +7 (1d20+7);"
hp: 40
health:
  - name: HP
    desc: "40; negative healing; __Immunities__ death effects, disease, fear, paralyzed, poison, precision, unconscious; __Weaknesses__ bludgeoning 5 (in skeletal corpses) or slashing 5 (in fleshy corpses); "

attacks:
  - name: Melee
    desc: "⬻ jaws +10; __Damage__ 1d8+6 (1d8+6) piercing"
  - name: Melee
    desc: "⬻ claw +10 ([[agile]]); __Damage__ 1d6+6 (1d6+6) slashing"

sourcebook: "_Abomination Vaults_ #1: Ruins of Gauntlight, page 82."
```

**Larger Corpselights** — a typical corpselight can animate only a Small or Medium corpse, but particularly powerful corpselights can inhabit larger bodies. Their basic abilities remain the same, but the damage they deal and the DC of their Death Light increase as appropriate for their increased level.
