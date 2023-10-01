Typical HTML Skeleton:
```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>your page title goes here</title>
    <meta charset="utf-8">
  </head>
  <body>
  </body>
</html>
```
### Classes, IDs, and Names
Any element can use the `class` or `id` attribute, and a variety of elements can use the `name` attribute

`Class` identifies a set of page elements that you wish to style consistently 

Any number of elements may belong to the same class. List all the names separated by spaces in the class attribute (i.e. `class="executive management full-time"`

```HTML
<tr class="teaching-assistant">
      <td>Pete</td>
      <td>JS225</td>
    </tr>
```
```CSS
tr {
  background-color: lime;
  font-size: 200%;
}

.teaching-assistant {
  background-color: yellow;
}
```


The `id` attribute applies a unique identification string to a single element, such as a headline. No other `id`s on the page should have the same ID.

```HTML
<h1>This is a plain h1 heading</h1>
<h1 id="headline">This is my headline</h1>
```
```CSS
#headline {
  color: red;
  font-size: 48px;
}
```

The `name` attribute is used to assign a name to a form data element that the server can use to obtain the value 

Some similar tags are `<aside>`, `<section>`, `<blockquote>`, `article`, `<div> `. How you decide which to use is based on semantics

## CSS

There is inline, internal, and external CSS
 - Inline: adding a `style` attribute applies some CSS styling to the single element identified by the tag
 - Internal: listing all styles in the `style` attribute of 2 the `head` element










