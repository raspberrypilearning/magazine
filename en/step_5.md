## Another page

Add another page to your magazine website.

--- task ---

Click **Add file** and call your new file `page2.html`:

![The code editor with an arrow pointing at 'add file' and a popup box with the name 'page2.html' filled in](images/page2.png)

--- /task ---

--- task ---

Select all of the code from `index.html`, copy it and then paste it into `page2.html`.

--- /task ---


--- task ---

In `page2.html`, change the `<h1>` title to the title for your new page.

--- code ---
---
language: html
filename: page2.html
line_numbers: true
line_number_start: 8
line_highlights: 8
---
<h1>Kitten care</h1>
--- /code ---

--- /task ---

--- task ---

Go back to `index.html`. Add a link to your second page:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 8
line_highlights: 11
---
<h1>My magazine</h1>
<div class="column1">
	Welcome to the kitten fan club
    <a href="page2.html">Page 2</a>
</div>
--- /code ---

--- /task ---

--- task ---

Test that you can click on your new link and move to page 2 of your magazine.

--- /task ---