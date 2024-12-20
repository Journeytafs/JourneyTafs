# Cheat Sheet

For Compatibility it is written with HTML for reference.

Headers:
|Element | Description | HTML Syntax | Markdown Syntax|
|--------|-------------|-------------|----------------|
|H1 | Largest heading | `<h1>Heading 1</h1>` | # Heading 1|
|H2 | Second largest heading |`<h2>Heading 2</h2>` | ## Heading 2|
|H3 | Third largest heading | `<h3>Heading 3</h3>` | ### Heading 3|
|H4 | Fourth largest heading | `<h4>Heading 4</h4>` | #### Heading 4|
|H5 | Fifth largest heading | `<h5>Heading 5</h5>` | ##### Heading 5|
|H6 | Sixth largest heading | `<h6>Heading 6</h6>` | ###### Heading 6|

Text Styles:
|Element | Description | Syntax|
|--------|-------------|-------|
|Italics | Makes text italic. | `*text* or _text_`|
|Bold | Makes text bold. | `**text** or __text__`|
|Emphasis| Makes text Italic and bold | `***text*** or ___text___`|
|Blockquotes | Indicates extended quotations. | `> Quoted text`|
|Underline | Underlines text. | `<ins>Underlined text</ins>`|
|Strike-through | Strikes through text. | `~~text~~`|
|Boxed | Creates a box around text. | `<table><tr><td>Text</td></tr></table>`|
|Superscript** | Creates superscript text. | `<sup>Superscript</sup>`|
|Subscript [^1] | Creates subscript text. | `<sub>Subscript</sub>`|
|Highlight | Highlights very important words | `<mark>very important words</mark>`|
|Footnotes | Declutters text with references | `[^1] or [^bignote] & [^0]:explaination `|

Syntax Hightlighting and Code blocks [^2]:

|Feature|Syntax|Output|
|-------|------|------|
Single Line Code | ` int z = 19; ` | int x = 19;|
Multiline Code | ` use triple backticks ` | ``` test ``` |
Syntax Highlighting with Language Specified | Add lanaguage after triple backticks | ``` use the list, js ```|

Tables:

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |

And table alignment:

| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| Data 1       |   Data 2       | Data 3        |
| Data 4       |     Data 5     | Data 6        |

Links:

|Link Type | Description | Syntax | Output|
|----------|-------------|--------|-------|
|Inline Link | Used to link users to another page, displayed as blue hyperlinked words. | `[Link Text](https://www.google.org/)` | Link Text|
|Reference Link | Used to link one information object to another, by providing some references to that new page. | `[Link Text] [reference text][reference text]: https://www.google.org/` | Link Text|
|Relative Link | Shows the relationship between the current page’s URL and the linked page’s URL. | `[A relative Link] (rl.md)` | A relative Link|
|Auto Link | Automatically converts URLs into clickable links. | `Visit https://www.google.org/` | Visit https://www.google.org/|

Images, Gifs and Emojis [^3]:






Footnotes:
--------
> ([^1]: Clarity.)
SuperScript & Subscript:
This is a ^superscript^
And this is a ~superscript~
>>Git Flavor tags, use html tags, Sup and Sub
`<sup>Super</sup> and <sub>Sub</sub>`
Example:
X<sup>4</sup>c
H<sub>2</sub>O

> ([^2]:Link List of codes)

> ([^3]:Link List of emojis)



Emoji 2 ways, using a shortcode like this:
:kissing:
Or copy paste the emoji itself.
😗