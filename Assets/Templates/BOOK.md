<%*
// ###########################################################
//                        Helper Functions
// ###########################################################

// Convert string to camelCase
function toCamelCase(str) {
  return str
    .replace(/(?:^\w|[A-Z]|\b\w|\s+|[-_])/g, (match, index) =>
      index === 0 ? match.toLowerCase() : match.toUpperCase()
    )
    .replace(/[\s-_]+/g, '');
}

// ###########################################################
//                        Main Code Section
// ###########################################################

// Call modal form & declare variables
const result = await MF.openForm('BOOK');
const name = result.Name.value;
const author = result.Author.value;
const type = "book"

if (result.status === 'ok') {

    // Rename file & open in new tab; Fire toast notification
    await tp.file.rename(name);
    await app.workspace.getLeaf(true).openFile(tp.file.find_tfile(name));
    new Notice().noticeEl.innerHTML = `<span style="color: green; font-weight: bold;">Finished!</span><br>New book <span style="text-decoration: underline;">${name}</span> added`;

} else {

    // Fire toast notification & exit templater
    new Notice().noticeEl.innerHTML = `<span style="color: red; font-weight: bold;">Cancelled:</span><br>Book has not been added`;
    return;
}
_%>

---
type: book
displayLink: "[[<% name %>]]"
---

###### <% name %>
<span class="sub2">By [[<% author %>#<% author %>]]</span>
<span class="sub2">:FasBook: Book</span>

---

> [!recite|clean no-t]
>	Introduction for players
>^IntroText


### Text

> [!recite|clean no-t]
> 	Text inside the book.
>^BookText

---

> [!column|flex 3]
>>[!hint]- QUESTS
>>```dataview
>>LIST WITHOUT ID displayLink
>FROM "Compendium/Party/Quests" AND [[#]]
>
>>[!note]- HISTORY
>>```dataview
>LIST WITHOUT ID displayLink
>FROM "Session Notes" AND [[#]]