---
type: statblock
locations:
  - "[[Wandering Museum]]"
displayLink: "[[Sphinx Statue]]"
---
###### Sphinx Statues
<span class="sub2">:LiLayoutList: Construct </span>
___

> [!recite|clean no-t]
>	A large statue of a cat-like creature with feathered wings stands on a plinth; about the size of a lion cub wide eyes and arcane patterns in its fur. Five clear gems gleam in its forehead.
>^IntroText

### Description
[[The Trickster]] will immediately recognise these as Sphinxes of Wonder when they see them or have them described to them as they are creatures born in the abstract and common in the more abstract parts of [[The Library]]. [[Clickity Clackity]] will also have advantage to try and identify them having spent so much time in [[The Library]]. Recognition will inform the players these creatures are resistant to magical effects in their area.

### Statblock
```statblock
name: Sphinx Statue
size: Medium
type: construct
ac: 13
hp: 35
hit_dice: 7d8 + 7
speed: 20 ft., Fly 40 ft.
stats:
  - 6
  - 17
  - 13
  - 15
  - 12
  - 11
skillsaves:
  - arcana: 4
  - religion: 4
  - stealth: 5
damage_vulnerabilities: ""
damage_resistances: "Necrotic, Psychic, Radiant"
damage_immunities: ""
condition_immunities: ""
senses: darkvision 60 ft., passive Perception 11
languages: ""
cr: "1"
traits:
  - name: Magic Resistance
    desc: The sphinx has Advantage on saving throws against spells and other magic effects.
  - name: Dispel Invisibility
    desc: Any invisible creature that comes within 60 feet of the sphinx statue becomes visible. If the invisibility is cause by a spell, the spell ends. If the invisibility is caused by an item or other effect, the creatures remains visible as long as it is within 60 feet of the sphinx statue.
actions:
  - name: Rend
    desc: "Melee Attack Roll: +5, reach 5 ft. Hit: 5 (1d4 + 3) Slashing damage plus 7 (2d6) Radiant damage."
bonus_actions:
  - name: Burst of Ingenuity (2/Day).
    desc: "Trigger: The sphinx or another creature within 30 feet makes an ability check or saving throw. Response: The sphinx adds 2 to the roll"
modifier: 3
```

---

> [!column|flex 3]
>>[!info]- STORYLINES
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/Party/Quests" AND [[#]]
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[#]]
SORT file.ctime DESC