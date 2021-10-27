# HTML Lists, CSS Boxes, JS Control Flow

## HTML & CSS

### Chapter 3: Lists

- `<ol>` = ordered list, each item numbered
- `<ul>` = unordered list, bullet points
- `<li>` = list item
- `<dl>` = definition list, contains `<dt>` (definition term) and `<dd>` (term's definition)
- `<dd>` may be used more than once if there are multiple definitions for the term
- `<dt>` may also be used more than once for a single definition

### Chapter 13: Boxes

- px, em, and % are popular to specify the dimensions 
of boxes
- One way to create a box:
- create a `<div>`
- put `<p>`  inside the div
- set height, width, background color for the div
- set the `<p>` height and width to a % of the div
- this will create a layered-looking box

- limit height and width with `min-height` and `max-height`
- `overflow: hidden` = hides content that wont fit the box
- `overflow: scroll` = adds a scrollbar to the side of the box if content is cut off

- boxes have 3 properties: border, margin, padding
- `margin` = space outside of the boxes border
- `padding` = space between boxes content and border

#### Change Inline/Block

- `inline` = block-level element becomes inline
- `block` = inline-level element becomes block-level

#### Hiding Boxes

- `visibility: hidden` = hides element
- `visibility: visible` = shows element

#### CSS3 

- *page 319-322 in textbook*
- `border-image` = applies image to boxes border, divides a background image into 9 peices to make the border image
- `border-radius` = rounds boxes borders

## JS

### Chapter 4: Decisions & Loops

- switch statements: 
``` Javascript
    switch (value) {
        case 'value1':
            action
        break;
        case 'value2':
        case 'value3':
            action
        break;
        default:
            action
        break;
    }
```
- **Truthy** = as if a value is true, can also be the number 1
- **Falsy** = as if a value is false, can also be the number 0
- short circuit values = logical operators work from left to right and stop (aka shrot circiut) when they find their result
