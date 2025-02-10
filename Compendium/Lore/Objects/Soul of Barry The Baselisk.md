---
type: object
displayLink: "[[Soul of Barry The Baselisk#Soul of Barry The Baselisk]]"
aliases: Barry
---

###### Soul of Barry The Baselisk
<span class="sub2">:FasGhost: Soul</span>
___

> [!infobox|no-t right]
> ![[embed.jpg|350]]
>
> | Type | Stat |
> | ---- | ---- |
> | :FasMap: Location | N/A |
> | :FasUser: Owner | [[Clickity Clackity]] |
>>[!hint]- PEOPLE
>>```dataview
>>LIST WITHOUT ID displayLink
>FROM "Compendium/NPCs" AND [[Soul of Barry The Baselisk]] OR "Compendium/Party/Player Characters" AND [[Soul of Barry The Baselisk]]
>
>>[!note]- HISTORY
>>```dataview
>LIST WITHOUT ID displayLink
>FROM "Session Notes" AND [[Soul of Barry The Baselisk]]

> [!recite|clean no-t]
>	Introduction for players
>^IntroText

### Description
When taken through the [[The Book Wormhole]] whilst still alive, Barry's body was disintegrated and his soul reached out to [[Clickity Clackity]] as he was dying and latched on. This conferred the following abilities to [[Clickity Clackity]]:

### Abilities
- Barry's soul will possess any familiars summoned with the *Find Familiar* spell.
- As a familiar, Barry can use an action to use ***Petrifying Gaze*** once per summoning that is only exhausted when a targeted creature fails the save.

***Petrifying Gaze***. If a creature starts its turn within 30 feet of the basilisk and the two of them can see each other, the basilisk can force the creature to make a DC 12 Constitution saving throw if the basilisk isn't incapacitated. On a failed save, the creature magically begins to turn to stone and is restrained. At the end of each of its turns, the target repeats the save, ending the effect on itself on a success.

- You always have [[Baselisk Hatching]] available as a wildshape option, this does not count against your number of prepared wildshape options.

```statblock
name: Baselisk Hatchling
ac: 15
hp: 11
dice: 2d6
speed: 20
stats: [13,8,15,2,8,7]
senses: darkvision 60ft., passive perception 9
cr: 1/4
actions:
  - name: Petrifying Glare (Recharge 4-6).
    desc: "The basilisk whelp glares at a target within 60 feet that it can see. The target must succeed on a DC 12 Constitution saving throw or turn to stone, becoming petrified until the start of the basilisk hatchling’s next turn."
  - name: Bite. 
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6 + 1) piercing damage plus 3 (1d6) poison damage."
reactions:
  - name: Protective Gaze. 
    desc: "When a friendly creature that the basilisk whelp can see would take damage, the basilisk whelp can use its reaction to take the petrifying glare action, targeting that friendly creature, before the damage is dealt (the creature may choose to fail the saving throw)."
```