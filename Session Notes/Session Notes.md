---
cssClasses: index
displayLink: "[[Session Notes]]"
alias: "Campaign Book"
---
###### <span class="head">Campaign Books</span> 
![[compendium.jpg|banner]]


 ### :FasBook: Book One - Authors & Editors
 
 ```dataviewjs
let pages = dv.pages('"Session Notes"').sort(p => p.chapter, "asc"); 
let chapters = [];
for (let i=0; i < pages.length; i++) {
	if (pages[i].chapter > 0) {
		chapters.push(`[[${pages[i].file.name}|Chapter ${pages[i].chapter} - ${pages[i].alias}]]`);
		}
	}
dv.list(chapters)
dv.list(pages[1])
```

