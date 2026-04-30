## CSS

_CSS stands for Cascading Style Sheets. It is used to add styling and positioning to our HTML elements. It was introduced in 1995 by Hakon Wium Lee._

_We can add CSS in 3 ways._

1. **Inline CSS:** This is a way to add CSS using style attribute inside opening tag of HTML elements. This CSS is having the highest priority.

```css
<h1 style="color:red;">Hii this is CSS</h1>
```

2. **Internal CSS:** This is also a way to add the CSS to our HTMl elements, here we need to use style tag inside head tag to add the CSS. It contains targeted elements along with properties.

```html
<style>
  pre {
    color: red;
  }
</style>
```

3. **External CSS:** This is the way to add the CSS and it provides separation of Concern. Here we need to create one file having extension as `.css` and we need to link it to HTML file using link tag.

```html
<link rel="stylesheet" href="./style.css" />
```
