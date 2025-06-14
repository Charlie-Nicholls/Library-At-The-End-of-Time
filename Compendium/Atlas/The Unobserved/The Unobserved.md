---
type: plane
displayLink: "[[The Unobserved]]"
---
![[imgTheUnobserved.png|banner p+cct]]
###### The Unobserved
<span class="sub2">:FasCircleHalfStroke:  Plane of Existence</span>

---

> [!boxed|no-t]
> The realm of the could-have-beens and never-weres
>^IntroText

### Description
Description of plane

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
FROM "Compendium/Atlas/The Unobserved" AND [[#]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[#]]
SORT file.ctime DESC