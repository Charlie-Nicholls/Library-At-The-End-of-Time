---
type: locale
locations:
 - "[[The Badlands]]"
displayLink: "[[Roaring Badlands Desert#Roaring Badlands Desert]]"
---

![[banner.jpg|banner]]
###### Roaring Badlands Desert
<span class="sub2">:FasCircleQuestion: Desert</span>

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
FROM "Compendium/NPCs" AND [[Roaring Badlands Desert]]
SORT file.name ASC
>
>> [!example]- LOCATIONS
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/Atlas/Material Plane/Toril/Faerûn/The Badlands/Eastwood" AND [[Roaring Badlands Desert]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[Roaring Badlands Desert]]
SORT file.ctime DESC