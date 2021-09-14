# HTML snippets

## Links

[See in HTML](./snippets.html)

- [Link forwarding](#link-forwarding)
- [Editable content](#editable-content)
- [Input with spellchecker](#input-with-spellchecker)
- [Input for files](#input-for-files)
- [Input with autocomplete](#input-with-autocomplete)
- [Acronym on hover](#acronym-on-hover)
- [Wrapper](#wrapper)
- [base URL](#base-url)
- [Dropdown with categories](#dropdown-with-categories)
- [Fieldset](#fieldset)
- [Show/hide password](#showhide-password)
- [noscript](#noscript)

## Snippets

### Link forwarding

> forwards the link when the page loads

```html
<meta http-equiv="refresh" content="0.1; url = https://url.to.link/with/path" />
```

---

### Editable content

> the content of this tag is editable

```html
<p contenteditable="true">Try to edit the content</p>
```

---

### Input with spellchecker

> Your input will get spellchecked

```html
<input type="text" spellcheck="true" />
```

---

### Input for files

> Upload multiple files

```html
<input type="file" multiple />
```

---

### Input with autocomplete

> An input with autocomplete suggestions

```html
<input list="posts" name="post" id="post" />
<datalist id="posts">
  <option value="11111"></option>
  <option value="22222"></option>
  <option value="33333"></option>
  <option value="44444"></option>
  <option value="55555"></option>
</datalist>
```

---

### Acronym on hover

> You can display details on hover

```html
<p>
  Hover
  <abbr title="This text will be shown if you hover">here</abbr>
  to see magic
</p>
```

---

### Wrapper

> A simple wrapper without JS

```html
<details>
  <summary>click for deatils</summary>
  <p>This is a deatiled text</p>
</details>
```

---

### base URL

> A meta tag to make a bas URL on a site

```html
<head>
  <base href="https://github.com/" />
</head>
```

---

### Dropdown with categories

> A Dropdown with categories for input

```html
<select>
  <optgroup label="Android">
    <option value="Samsung">Samsung</option>
    <option value="Xiaomi">Xiaomi</option>
    <option value="Oneplus">Oneplus</option>
  </optgroup>
  <optgroup label="iOS">
    <option value="iPhone">iPhone</option>
  </optgroup>
</select>
```

---

### Fieldset

> A fieldset with a description

```html
<form action="">
  <fieldset>
    <legend>Login</legend>
    <label for="username">Username</label>
    <input type="text" name="username" id="username" />
    <label for="password">Passowrd</label>
    <input type="password" name="password" id="password" />
  </fieldset>
</form>
```

---

### show/hide password

> simple button to show/hide password

```html
<input type="password" id="pwinput" />
<button id="tgpwbutton">Toggle Password</button>
<script>
  const passwordinput = document.querySelector("#pwinput");
  const tgbutton = document.querySelector("#tgpwbutton");

  tgbutton.addEventListener("click", () => {
    if (passwordinput.type === "password") {
      passwordinput.type = "text";
    } else if (passwordinput.type === "text") {
      passwordinput.type = "password";
    }
  });
</script>
```

---

### noscript

> If the browser doesn't support JS or JS is disabled

```html
<noscript> Sorry, your browser does not support JavaScript! </noscript>
```

---
