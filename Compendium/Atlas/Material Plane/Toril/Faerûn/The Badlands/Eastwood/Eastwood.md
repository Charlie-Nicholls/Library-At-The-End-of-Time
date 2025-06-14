---
type: locale
locations:
 - "[[The Badlands]]"
displayLink: "[[Eastwood#Eastwood]]"
---

![[banner.jpg|banner]]
###### Eastwood
<span class="sub2">:FasCity: City</span>

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
FROM "Compendium/NPCs" AND [[Eastwood]]
SORT file.name ASC
> 
>> [!example]- LOCATIONS
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/Atlas/Material Plane/Toril/Faerûn/The Badlands/Eastwood" AND [[Eastwood]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[Eastwood]]
SORT file.ctime DESC