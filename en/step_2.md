## Heading and Background

Magazine-style websites often have lots of small items on a page. First, create a heading and background for your magazine.

--- task ---

Open the <a href="https://editor.raspberrypi.org/en/projects/magazine-starter" target="_blank">starter project</a>.

--- /task ---

--- task ---
Make up a name for your magazine and add it as a `<h1>` heading.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 7
line_highlights: 8
---
<body>
	<h1>My Magazine</h1>

</body>

--- /code ---

--- /task ---

--- task ---
In the sidebar, open the `style.css` file. Change the style of the heading. Here's an example, but you can choose your own style:


--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
---
h1 {
    text-align: center;
    color: white;
    background: black;
    padding: 5px;
}
--- /code ---

--- /task ---

--- task ---

Look at the CSS style for `body`. Change the colours of the background and the font to your own choices.


--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 8
line_highlights: 9-10
---
body {
  background: linear-gradient(to bottom right, red, white);
  font-family: Verdana;
  padding: 15px;
}

--- /code ---

--- /task ---


