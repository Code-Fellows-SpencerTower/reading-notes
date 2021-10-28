# HTML Links, JS Functions, and Intro to CSS Layout

## HTML & CSS

### Chapter 4: Links (pp.74-93)

- create links with the `<a>` element
- add `href` attribute to `<a>` to link page
- use relative links if linking within your own page (aka file pathway)
- can use `../` to indicate folder above file

```html
    <a href="address">Link Title</a>
```

Email link:

```html
    <a href="mailto:emailadress">Email Link</a>
```

Link in new window:

```html
    <a href="address" target="_blank">Link Title</a>
```

- use `href="#idname"` to link to part of the same page

### Chapter 15: Layout (pp.358-404)

- `float` left or right (have to define width for float content)
- `clear` - left, right, both, none - means sides of box wont touch any other element
- `position: static` - block level elements sit on top eachother
- `position: relative` - moves element relative to where it would be normally, specify relative location with `top` and `left`
- `position: absolute` - element doesnt affect orientation of other elements, can use `top`, `left`, `width` to specify location
- `position: fixed` - fixes the position relative to browser window
- `z-index` - allows element to sit on top of other content

## JS

### Chapter 3: Functions, Methods, and Objects (pp.86-99)

- can return an array from a function
- if a function returns an array, you can return a single value from the array by calling the function with the index number, e.g. `getValues(arguments)[0]`

[Article: 6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

