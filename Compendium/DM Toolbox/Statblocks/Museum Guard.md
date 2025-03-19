---
type: statblock
locations:
  - "[[Wandering Museum]]"
displayLink: "[[Museum Guard]]"
---
###### Museum Guard
<span class="sub2">:LiLayoutList: Humanoid </span>
___

> [!recite|clean no-t]
>	
>^IntroText

### Description

### Statblock
> ```statblock
> name: Museum Guard
> size: Medium
> type: humanoid
> subtype: any race
> alignment: any alignment
> ac: 16
> hp: 17
> hit_dice: 3d8 + 3
> speed: 30 ft.
> stats:
>   - 13
>   - 12
>   - 12
>   - 10
>   - 14
>   - 10
> skillsaves:
>   - perception: 4
>   - insight: 4
> damage_vulnerabilities: ""
> damage_resistances: ""
> damage_immunities: ""
> condition_immunities: ""
> senses: passive Perception 14
> languages: any one language (usually Common)
> cr: 1/8
> traits:
>   - name: Alarm Level
>     desc: The museum guard gains a bonus to all Perception and Insight checks equal to the alarm level of the museum
> actions:
>   - name: Short Spear
>     desc: "Melee Weapon Attack: +3 to hit, reach 5 ft., Hit: 5 (1d8 + 1) piercing damage."
>     attack_bonus: 3
>     damage_dice: 1d8
>     damage_bonus: 1
>   - name: Heavy Crossbow
>     desc: "Ranged Weapon Attack: +3 to hit, range 100/400 ft., Hit: 6 (1d10 + 1) piercing damage."
>     attack_bonus: 3
>     damage_dice: 1d10
>     damage_bonus: 1
> source: Homebrew
> layout: Basic 5e Layout
> ```

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