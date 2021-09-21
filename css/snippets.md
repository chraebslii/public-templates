# CSS snippets

## Content

- [change cursor](change-cursor)
- [smooth scrolling](smooth-scrolling)
- [show on hover](show-on-hover)
- [center anything](center-anything)
- [insert before](insert-before)
- [custom user selection](custom-user-selection)

## snippets

### change cursor

> Change the Cursor on your website

```css
body {
  cursor: url(path/to/image), auto;
  cursor: auto;
  cursor: crosshair;
  cursor: default;
  cursor: e-resize;
  cursor: help;
  cursor: move;
  cursor: n-resize;
  cursor: ne-resize;
  cursor: nw-resize;
  cursor: pointer;
  cursor: progress;
  cursor: s-resize;
  cursor: se-resize;
  cursor: sw-resize;
  cursor: text;
  cursor: w-resize;
  cursor: wait;
}
```

---

### smooth scrolling

> enable smooth scrolling

```css
* {
  scroll-behavior: smooth;
}
```

---

### show on hover

> Show an element if you hover an other (here: if the div gets hovered, p will show)

```css
p {
  display: none;
  background-color: yellow;
  padding: 20px;
}

div:hover p {
  display: block;
}
```

---

### center anything

> Center any tag

```css
div {
  display: flex;
  align-items: center;
  justify-content: center;
}
```

---

### insert before

> insert content before an element

```css
p::before {
  content: url(path/to/content);
}
```

---

### custom user selection

> Change the color of the user selection

```css
p::selection {
  color: red;
}
```
