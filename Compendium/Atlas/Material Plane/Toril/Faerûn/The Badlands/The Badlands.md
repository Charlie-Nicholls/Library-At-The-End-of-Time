---
type: territory
locations:
 - "[[Faerûn]]"
displayLink: "[[The Badlands#The Badlands]]"
---

![[banner.jpg|banner]]
###### The Badlands
<span class="sub2">:FasMap: General Region</span>

---

> [!recite|clean no-t]
>	Introduction for players
>^IntroText

### Description
Description of Territory

---

> [!column|flex 3]
>> [!hint]-  NPCs
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/NPCs" AND [[The Badlands]]
SORT file.name ASC
> 
>> [!example]- LOCATIONS
>>```dataview
LIST WITHOUT ID displayLink + " (" + type + ")"
FROM "Compendium/Atlas/Material Plane/Toril/Faerûn/The Badlands" AND [[The Badlands]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[The Badlands]]
SORT file.ctime DESC