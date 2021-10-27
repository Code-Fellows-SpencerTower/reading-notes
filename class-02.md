# Basics of HTML, CSS, & JS

## HTML & CSS

### Chapter 2: Text

- structural markup: structural elements, e.g. elements for headings and paragraphs
- semantic markup: markup to convey additional meaning, e.g. `<strong>`, `<em>`, etc. 
- 6 levels of headings `<h1>` (main heading) through `<h6>`
- `<p>` are shown on a new line by default
- `<sup>` = superscript, used commonly for suffixes or math
- `<sub>` = subscript, used commonly for footnotes
- white space collapsing = browsers display 2+ sequential spaces as a single white space.
- `<br />` = linebreak
- `<hr />`= horizonal line linebreak, can be used to divide sections

#### Semantic Markup Tags

- `<strong>` = strong importance, text will show in bold
- `<em>` = emphasis, text will show in italics
- `<blockquote>` = used for long quotes, still requires the `<p>` tag for quote text
- `<q>` = used for short quotes, Internet Explorer does not put quotes around `<q>` tags
- `<abbr>` = used for abbreviations, uses a title attribute for the full term that is being abbreviated. Syntax: `<abbr title="full term">`abbreviation`</abbr>`
- `<cite>` = used to cite sources
- `<dfn>` = defining instance, used when a new term is defined
- `<address>` = used for contact info for author of the webpage
- `<ins>` = underlines content added to a doc
- `<del>` = crosses out content deleted from a doc
- `<s>` = crosses out content that is not relevant but should remain in the doc, e.g. a change in price for an item

### Chapter 10: Introducing CSS

- use `<link />` tag to link an external CSS sheet
- `<link />` takes the `href`, `type`, and `rel` attributes
- `href` = document location
- `type` should be set to `text/css` - optional
- `rel` should be set to `stylesheet`
- `<style>` is used to write CSS styling within the html document
- *types of CSS selectors - see page 238 in textbook*

## JS

### Chapter 2: Basic Javascript Instructions

- declare an unassigned variable if its value will be conditionally assigned (e.g. in an if/else statement)
- data types: Numbers, Strings, Boolean
- booleans `true` and `false` are lowercase
- escape character: `\` - use before quotes within a string if the quotes are part of the string
- variables can start with letters, $, or _, but not numbers
- cannot use - or . in a variable name
- arrays are declared with a *literal array*: `x = [values];` or with an *array constructor*: `var x = new Array(values);`
- array indexing starts at 0
- `.textcontent` = sets text of specified element along with all of its descendents

### Chapter 4: Decisions and Loops

- operands can include expressions enclosed in brackets
- expressions always evaluate to a single value
