## Design web pages with CSS

## What is CSS?
- Cascading Style Sheets
- lets style webpages
- based on "rules" applied to html elements
- each rule begins with a selector used to identify the html tag
- the selector is followed by curly braces
- declarations are made in the braces
- declarations consist of a property and value
- a colon follows the property and a semicolon follows the value

**Example**

``` css
h1 {
    color: blue;
    font-size: 10em;
}
```

## How to add CSS
- 3 ways to add css: external, internal, inline
- add the follwing to your html head to link an external css file:

``` html
<link rel="stylesheet" href="style.css">
```


## CSS Color Property
- color is inherited

**Example**

``` css
body {
    color: rgb(140, 85, 37)
}
```


## Links
- [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)
- [How To Add CSS](https://www.w3schools.com/css/css_howto.asp)
- [CSS Color Property](https://www.w3schools.com/cssref/pr_text_color.asp)
