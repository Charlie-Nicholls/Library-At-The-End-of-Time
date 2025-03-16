---
type: npc
locations:
 - "[[Wandering Museum]]"
displayLink: "[[Sekhemkare]]"
---
###### Sekhemkare
<span class="sub2">:FasMapLocationDot: [[Wandering Museum]] | :FasHeartPulse: Dead </span>
___

> [!infobox|no-t right]
> ![[portrait.jpg|350]]
>
> | Type | Stat |
> | ---- | ---- |
> | :FasBriefcase: Job |  Pharaoh |
> | :FasVenusMars: Gender | Male |
> | :FasUser: Race | Human |
> | :FasClock: Age |  |
>
>> [!info]- STORYLINES
>>```dataview
>>LIST WITHOUT ID displayLink
>>FROM "Compendium/Party/Quests" AND [[#]]
>
>>[!note]- HISTORY
>>```dataview
>>LIST WITHOUT ID displayLink
>>FROM "Session Notes" AND [[#]]
>
>^InfoBox

# Profile

> [!recite|clean no-t]
>	Introduction for players
>^IntroText

### Description
Description

### Motivations
- List of Motivations

### Magic Items / Abilities
- None

### Allies
- [[Characters]] or [[Organisations]]

### Enemies
- [[Characters]] or [[Organisations]]

### Secrets
- None

### Statblock
```statblock
name: Sekhemkare
source: 5e SRD
size: Medium
type: undead
subtype: ""
alignment: lawful evil
ac: 13
hp: 90
hit_dice: 9d8 + 17
speed: 20 ft.
stats:
  - 16
  - 8
  - 15
  - 6
  - 10
  - 12
saves:
  - wisdom: 2
damage_vulnerabilities: fire
damage_resistances: ""
damage_immunities: bludgeoning, piercing, and slashing from nonmagical weapons
condition_immunities: necrotic, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: the languages it knew in life
cr: "3"
bestiary: true
traits:
  - name: Tricksters Magic
    desc: Sekhemkare is immune to any attack or spell from The Trickster
actions:
  - name: Multiattack
    desc: The mummy can use its Dreadful Glare and makes one attack with its rotting fist.
    attack_bonus: 0
  - name: Rotting Fist
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6 + 3) bludgeoning damage plus 10 (3d6) necrotic damage. If the target is a creature, it must succeed on a DC 12 Constitution saving throw or be cursed with mummy rot. The cursed target can't regain hit points, and its hit point maximum decreases by 10 (3d6) for every 24 hours that elapse. If the curse reduces the target's hit point maximum to 0, the target dies, and its body turns to dust. The curse lasts until removed by the remove curse spell or other magic."
    attack_bonus: 5
    damage_dice: 2d6
    damage_bonus: 3
  - name: Dreadful Glare
    desc: The mummy targets one creature it can see within 60 ft. of it. If the target can see the mummy, it must succeed on a DC 11 Wisdom saving throw against this magic or become frightened until the end of the mummy's next turn. If the target fails the saving throw by 5 or more, it is also paralyzed for the same duration. A target that succeeds on the saving throw is immune to the Dreadful Glare of all mummies (but not mummy lords) for the next 24 hours.
    attack_bonus: 0

