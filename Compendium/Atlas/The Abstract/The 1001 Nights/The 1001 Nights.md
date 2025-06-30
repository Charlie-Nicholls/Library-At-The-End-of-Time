---
type: locale
locations:
 - "[[The Library]]"
 - "[[The Realm of Fiction]]"
displayLink: "[[The 1001 Nights]]"
---

![[banner.jpg|banner]]
###### The 1001 Nights
<span class="sub2">:FasCircleQuestion: Prison</span>

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
FROM "Compendium/NPCs" AND [[#]] OR "Compendium/Party" AND [[#]] 
> 
>> [!example]- LOCATIONS
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/Atlas/The Abstract/The Library/The 1001 Nights" AND [[#]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[#]]
SORT file.ctime DESC