---
type: locale
locations:
 - "[[The Badlands]]"
displayLink: "[[Flintfall#Flintfall]]"
---

![[banner.jpg|banner]]
###### Flintfall
<span class="sub2">:RiBuilding4Fill: Town</span>

---

> [!boxed|no-t]
> Introduction for players
>^IntroText

### Description
Description of location

---

> [!column|flex 3]
>> [!hint]-  NPCs
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/NPCs" AND [[Flintfall]]
SORT file.name ASC
>
>> [!example]- LOCATIONS
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/Atlas/Material Plane/Toril/Faerûn/The Badlands/Flintfall" AND [[Flintfall]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[Flintfall]]
SORT file.ctime DESC