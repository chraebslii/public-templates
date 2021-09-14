# Emmet Cheatsheet

## What is Emmet?

>Emmet is a plugin for many popular text editors which greatly improves HTML & CSS workflow

## Links

- [HTML](#html)
  - [classes](#classes)
  - [IDs](#ids)
  - [value](#value)
  - [custom attributes](#custom-attributes)
  - [child](#child)
  - [siblings](#siblings)
  - [multiplication](#multiplication)
  - [auto numbering](#auto-numbering)
  - [grouping](#grouping)
  - [lorem ipsum](#lorem-ipsum)
- [CSS](#css)
  - [Value aliase](#value-aliase)
  - [Color aliases](#color-aliases)
  - [Unit aliases](#unit-aliases)
  - [combinations](#combinations)

---

## HTML

### classes

`.container`

```html
<div class="container"></div>
```

### IDs

`#container`

```html
<div id="container"></div>
```

### value

`a{click}`

```html
<a href="">click</a>
```

### custom attributes

`p[value="hello"]`

```html
<p value="hello"></p>
```

### child

`div>p`

```html
<div>
    <p></p>
</div>
```

### siblings

`div+p+a`

```html
<div></div>
<p></p>
<a href=""></a>
```

### multiplication

`ul>li*5`

```html
<ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul>
```

### auto numbering

`ul>li.item$*5`

```html
<ul>
    <li class="item1"></li>
    <li class="item2"></li>
    <li class="item3"></li>
    <li class="item4"></li>
    <li class="item5"></li>
</ul>
```

### grouping

`div+(header>div)+a+p`

```html
<div></div>
<header>
    <div></div>
</header>
<a href=""></a>
<p></p>
```

### lorem ipsum

`p*4>lorem`

```html
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint architecto, sed assumenda maxime aliquam nulla, velit sit necessitatibus enim voluptatum vero sequi! Voluptates blanditiis quisquam minima natus commodi voluptatibus quae!</p>
<p>Architecto a doloremque soluta sed nisi sunt vel eveniet eum eaque deleniti, repudiandae magni non quo qui amet, iure, ducimus ea dolores. Eaque accusamus atque recusandae dignissimos nisi expedita laborum.</p>
<p>Ipsum, amet non eum ratione alias iusto fuga eveniet cupiditate delectus adipisci laudantium dolor unde. Ratione cum esse error nesciunt numquam ipsa exercitationem quam quibusdam ex! Quae voluptatem voluptas omnis.</p>
<p>Suscipit similique quidem reprehenderit, possimus beatae cumque unde praesentium obcaecati excepturi dolorum ipsa adipisci esse ullam odit et! Vero possimus sed blanditiis ab temporibus quam iste impedit. Pariatur, quaerat unde.</p>
```

---

## CSS

### Value aliase

- `p -> %`
- `e -> em`
- `x -> ex`

### Color aliases

- `#1 -> #111111`
- `#e0 -> #e0e0e0`
- `#fc0 -> #ffcc00`

### Unit aliases

- `w100p -> width: 100%`
- `h100p -> height: 100%`
- `m2e -> margin: 2em`
- `p2e -> padding: 2em`
- `fw400 -> font-weight: 400`
- ` -> `
- ` -> `
- ` -> `
- ` -> `

### combinations

- `m10p30e5x -> margin: 10% 30em 5ex`
- `m2e+p!2e -> margin: 2em; padding: 2em !important;`
