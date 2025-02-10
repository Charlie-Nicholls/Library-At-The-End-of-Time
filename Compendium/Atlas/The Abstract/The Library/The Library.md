---
type: realm
locations:
 - "[[The Abstract]]"
displayLink: "[[The Library#The Library]]"
---

![[banner.jpg|banner]]
###### The Library
<span class="sub2">:RiGlobalLine: Realm (world)</span>

---

> [!recite|clean no-t]
>	Introduction for players
>^IntroText

### Description
The Library stretches on seemingly for infinity. It contains every story ever told, every book ever written, and all the knowledge ever recorded. Those on the material plane often describe it as 'The Library at The End of Time', but this is a misnomer. Inside The Library, the flow of time is non-linear, you might find you arrive at a destination before an independent observer sees you leave. Instead it follows the rule of narrative, you arrive when the story needs you to. Those who run the library maintain a constant connection to the material plane, allowing books to leave and enter The Library is essential for its continued function. As such, the religious sects associated with The Library will freely lend books of lesser importance to the public. Books which are considered dangerous for a given time or place require special dispensation to be lent out, and their return is more strictly enforced.

---

> [!column|flex 3]
>> [!hint]-  NPCs
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/NPCs" AND [[The Library]]
SORT file.name ASC
>
>> [!example]- LOCATIONS
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/Atlas/The Abstract/The Library" AND [[The Library]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[The Library]]
SORT file.ctime DESC