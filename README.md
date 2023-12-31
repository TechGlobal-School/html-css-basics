# HTML and CSS Class Notes

- Current version of HTML is 5 and CSS is 3.

## What is HTML?

- Structure/skeleton of web page
- Used to display the content of web page

## How to create an html file?

- You can create an html file using .html extention. Example: `index.html, users.html`

## Content of HTML file

- First line of the page is `<!DOCTYPE html>` (This is version 5)
- This is telling Web Browser what is the type of the file is being rendered.

- After doctype goes `html` element. Everything in the page goes inside this element. Example: `<html> All contnet ...</html>`
- `html` is a tag. And you create a web element using tags. Example: `<html> All contnet ...</html>`.

## `<head>` element

- Invisible part of the web page goes here
- But it is needed to show important informations like page title, metadata, scripts, critical css etc.

### `<title>` element

- You can update your page title using this element. `<title>HTML CSS Tutorial</title>`
- Make sure its inside `head` element.
- That is called **nesting element**. Example: `<head><title>HTML CSS Tutorial</title></head>`

### `<meta>` element

- Metadata of the web page
- Example: charset, title, author, keywords and favicon etc.

## `<body>` element

- Everything that is visible to users

### Heading elements

- From 6 to 1. 6 being the smallest and 1 being the biggest
- Example: `<h1>Heading 1</h1>`, `<h6>Heading 1</h6>`

### Paragraph element `<p>`

- Used to create a simple paragraphs
- Example: `<p>Content</p>`

### Some other example elements

- `<strong>` or `<b>` - makes text bold
- `<i>` or `<em>` - makes text italic
- `<hr/>` - creates a horizontal line
- `<br/>` - break/pushes elements to new line

### Self-closing elements

- If element doesn't have any content, you can self-close it.
- Example elements: `<hr/>`, `<br/>`, `<img />`

### Link element `<a>`

- Used to navigate between or out of the web page.
- When `target="_blank"` attr added website will be launched in a new tab when this link clicked on HTML page

## Attributes

### ID

- Used for unique element

### CLASS

- Used for common/multiple elements

## STYLING

1. Inline styling: Apply styles right to the element
2. Internal styling: Apply styles inside the head element
3. External styling: Apply styles by creating `.css` files

Precedence: Inline > Internal > External

- **padding:** space between content and border
- **margin:** space between border and other elements
- To style ID use `#`
- To style CLASS use `.`
- To style normal element without attribute, use tag name. Ex: `footer { styles ...}`

## Lists

1. Ordered list `ol`
2. Unordered list `ul`
3. Both of them have `li` children elements

## Tables

- `table` - required parent element
- `thead`, `tbody` or `tfoot` - optional elements. Help organize your table code better.
- `tr` - table row
- `th` - table heading
- `td` - table data

## HTML FORMS

Used to collect data from users

- `form` element to create a form
- `input` element. It is a self closing element.

  - `type=text` -> collect text data from user.
  - `type=email` -> collect email data from user
  - `type=password` -> collect password data from user

- `button` we can use button element to submit form data
- `label` is an element label for input
