## Lists in HTML

_List is a collection of multiple items either in ordered or unordered manner. In HTML we have three types of lists as follows._

- **Ordered List:** A list which follows any order is known as order list. By default it follows numeric list. We can change the type of lists using type attribute inside opening `<ul>` tag. There are five types of ordered lists such as number, capital alphabets, small alphabets, small roman number and capital roman numbers.

```html
<ol type="1" reversed start="10">
  <li>India</li>
  <li>Russia</li>
  <li>Morocco</li>
  <li>America</li>
</ol>
```

- **Unordered list:** Unordered list is a collection of multiple items without any order. By default the type of unordered list is disc. We have total 4 types of unordered list such as disc, circle, square and none.

```html
<ul type="disc">
  <li>Oil</li>
  <li>Tomato</li>
  <li>Onion</li>
  <li>Brinjal</li>
  <li>Cheese</li>
  <li>Maggi</li>
</ul>
```

- **Description list:** This lists provide a descriptions to the list items. We can creat description list using `<dl>` tag and inside we can use `<dt>` tag which represents description term and `<dd>` which represents the description data or definition for the specified term.

```html
<dl>
  <dt>Chicken</dt>
  <dd>1 Kg</dd>
  <dt>Curd</dt>
  <dd>1 litre</dd>
  <dt>Rice</dt>
  <dd>1 Kg</dd>
</dl>
```
