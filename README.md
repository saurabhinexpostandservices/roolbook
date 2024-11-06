[Click to see full checklist](https://autumn-snowshoe-4ac.notion.site/Front-end-developer-rules-for-ESS-123e51c77d3c80e18ef3df1c24bc75bd)

Here is a list of all the key semantic HTML elements:

### Document Structure Elements
1. **`<html>`**: Root element of an HTML document.
2. **`<head>`**: Contains meta-information about the document (title, links to stylesheets, scripts, etc.).
3. **`<title>`**: Defines the title of the document, displayed in the browser tab.
4. **`<body>`**: Contains the visible content of the document.

### Content Sectioning Elements
These tags help organize the page content into meaningful sections.

1. **`<header>`**: Represents a header section for a document or a section, typically containing introductory content or navigational links.
2. **`<nav>`**: Defines a set of navigational links.
3. **`<main>`**: Denotes the main content of the document. Only one `<main>` should be used per page.
4. **`<section>`**: Groups related content within a thematic section, often used with a heading.
5. **`<article>`**: Represents a self-contained piece of content that could stand alone, like a blog post or news article.
6. **`<aside>`**: Contains content tangentially related to the main content, like sidebars or advertisements.
7. **`<footer>`**: Represents the footer for a document or section, typically containing author info, copyright, or navigational links.

### Text Content Elements
These tags give semantic meaning to different types of text.

1. **`<h1>` to `<h6>`**: Defines headings, with `<h1>` as the highest (most important) and `<h6>` as the lowest.
2. **`<p>`**: Represents a paragraph.
3. **`<hr>`**: Represents a thematic break or horizontal line, often used to separate content.
4. **`<pre>`**: Displays preformatted text, preserving whitespace and line breaks.
5. **`<blockquote>`**: Indicates a quoted section, usually with a source attribute.
6. **`<ol>`**: Ordered list (numbered).
7. **`<ul>`**: Unordered list (bulleted).
8. **`<li>`**: List item, used inside `<ol>` and `<ul>`.
9. **`<dl>`**: Definition list.
10. **`<dt>`**: Definition term, used inside `<dl>`.
11. **`<dd>`**: Definition description, used inside `<dl>`.

### Inline Text Semantics
These tags define semantic meaning for specific inline text elements.

1. **`<a>`**: Anchor, used for hyperlinks.
2. **`<strong>`**: Indicates strong importance; usually bolded.
3. **`<em>`**: Denotes emphasized text, usually italicized.
4. **`<mark>`**: Highlights or marks text.
5. **`<small>`**: Indicates a side comment, disclaimer, or legal note (often rendered smaller).
6. **`<cite>`**: Denotes the title of a work, like a book or movie title.
7. **`<abbr>`**: Represents an abbreviation or acronym, with optional `title` for explanation.
8. **`<code>`**: Defines a piece of code.
9. **`<samp>`**: Denotes sample output from a program.
10. **`<kbd>`**: Represents user input, typically from a keyboard.
11. **`<var>`**: Represents a variable or placeholder text in mathematical expressions.
12. **`<sub>`**: Subscript text (e.g., in chemical formulas).
13. **`<sup>`**: Superscript text (e.g., exponents).
14. **`<b>`**: Bold text, without semantic emphasis.
15. **`<i>`**: Italicized text, without semantic emphasis.
16. **`<u>`**: Underlined text, for annotations.

### Media Elements
These tags provide semantic meaning for media content.

1. **`<figure>`**: Represents self-contained content, like images or charts.
2. **`<figcaption>`**: Caption or description for the `<figure>`.
3. **`<img>`**: Embeds an image.
4. **`<audio>`**: Embeds audio content.
5. **`<video>`**: Embeds video content.
6. **`<source>`**: Specifies multiple media resources for `<audio>` and `<video>`.
7. **`<track>`**: Provides text tracks for `<video>` and `<audio>`, like subtitles.

### Table Elements
These tags provide semantic structure for tabular data.

1. **`<table>`**: Creates a table.
2. **`<caption>`**: Provides a title or caption for the table.
3. **`<thead>`**: Groups the header content in a table.
4. **`<tbody>`**: Groups the body content in a table.
5. **`<tfoot>`**: Groups the footer content in a table.
6. **`<tr>`**: Table row.
7. **`<th>`**: Table header cell.
8. **`<td>`**: Table data cell.

### Forms and Input Elements
These tags help create forms with meaningful and accessible input fields.

1. **`<form>`**: Wraps form elements for user input.
2. **`<fieldset>`**: Groups related elements in a form.
3. **`<legend>`**: Caption for a `<fieldset>`.
4. **`<label>`**: Label for form elements, improving accessibility.
5. **`<input>`**: Generic input field for data.
6. **`<button>`**: Clickable button.
7. **`<select>`**: Dropdown list.
8. **`<option>`**: Option in a `<select>` list.
9. **`<textarea>`**: Multi-line text input field.
10. **`<output>`**: Represents the result of a calculation or user action.
11. **`<datalist>`**: Provides a list of predefined options for input.
12. **`<progress>`**: Represents progress of a task.
13. **`<meter>`**: Indicates a scalar measurement within a range (e.g., disk usage).

### Interactive Elements
These tags enhance interactivity and provide additional features for users.

1. **`<details>`**: Creates a collapsible area with optional hidden content.
2. **`<summary>`**: Caption for the `<details>` element.
3. **`<dialog>`**: Represents a dialog box or other interactive component.
4. **`<menu>`**: Represents a list of commands or options (typically for contextual menus).

---

These semantic tags help structure HTML documents in a way that is both accessible and meaningful, improving SEO, readability, and user experience.