---
type: realm
locations:
 - "[[The Abstract]]"
displayLink: "[[The Realm of Fiction]]"
---

![[banner.jpg|banner]]

---

###### The Realm of Fiction
<span class="sub2">:RiGlobalLine: Realm (world)</span>

---

> [!boxed|no-t]
> Introduction for players
>^IntroText

### Description
Description of realm

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
FROM "Compendium/Atlas/The Abstract/The Realm of Fiction" AND [[#]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[#]]
SORT file.ctime DESC