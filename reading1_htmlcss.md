## HTML & Javascript Notes

### Chapter 1: Structure

- headings and subheadings separate the hierarchy of information found on the page
- attribute = extra info about the content in the element
- value = the info/setting of the attribute, in double quotes
- `<body>` is what is displayed in the browser
- `<head>` has information about the page

### Chapter 8: Extra Markup

- start with a doctype tag, html 5 starts with `<!DOCTYPE html>`
- comments in html: `<!-- comment -->`
- block level elements - start on a new line when rendered in the browser. e.g. `<h1>`, `<p>`, `<li>`, `<li>` elements
- inline elements - e.g. `<a>`, `<b>`, `<em>`, `<img>`
- `<div>` - groups together elements into a single block-level box
- makes it easier to contain sections of a page
- `<span>` - inline version of div. Used to contain inline elements. Often used to apply CSS to inline elements.
- `<iframe>` - 'inline frame', can see another page within the iframe window. Often used to show google maps
- requires the `src`, `height`, `width`, `scrolling` (only html 4 and xml), `frameborder` (only html 4 and xml), and `seamless` attributes
- `seamless` attribute - applied for iframes without scrollbars, does not require a value, not supported by older browsers
- `<meta>` located inside the `<head>` element, provides information about the page

### Chapter 17: HTML5 Layout

- `<article>` is used to separate sections on a page
- `<aside>` is used either inside or outside an `<article>`, 
- if inside an article, the aside contains info related to the article's content, but not central to the article's message
- if outside an article, the aside contains information related to the whole webpage
- `<section>` - used to group similar content together, can contain article elements
- `<hgroup>` - groups headers together to wrap them as heading and subheadings
- `<figure>` & `<figcaption>`- used to wrap things like images, videos, and code samples
- `<div>` - used to group elements, usually used when there is no specific grouping element to wrap content
- `<a>` can be used to wrap and link entire sections
- additional .js needs to be applied for html5 to be correctly rendered by older browsers

### Chapter 18: Process & Design

- important to keep in mind the motivations and goals of your target audience when designing a site
- card sorting- a technique used to design a site that breaks content into cards which are categorized by content and used to determine different sections of the site
- visual hierarchy - conveys content based on color, size, images, and styling