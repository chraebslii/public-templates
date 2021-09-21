# JS snippets

## Content

- [Snippets for beginners](#snippets-for-beginners)
  - [alert](#alert)
  - [combine](#combine)
  - [prompts](#prompts)
  - [confirms](#confirms)
  - [if, else if, else](#if-else-if-else)
  - [short form](#short-form)
  - [while loops](#while-loops)
  - [for loops](#for-loops)
  - [switch statements](#switch-statements)
  - [functions](#functions)
- [Snippets for advanced](#snippets-for-advanced)
  - [center a div horizontally](#center-a-div-horizontally)
  - [action on key press](#action-on-key-press)

## Snippets for beginners

### alert

> alert in window

```js
alert("Hello World!");
```

---

### combine

> combine variables with strings

```js
var name = "John";
var str = `Hello ${name}!`;
```

---

### prompts

> promts in window

```js
var age = prompt("How old are you?", 100); // 100 is an optional argument
alert(`You are ${age} years old!`);
```

---

### confirms

> get a confirmation in window

```js
var isBoss = confirm("Are you the boss?");
alert(isBoss); // true if OK is pressed
```

---

### if, else if, else

> the basics for if, else if and else

```js
var year = prompt("Which year is now?", "");
if (year == 2021) {
  alert("You guessed it right!"); // 2021
} else if (year == 2020 || year == 2022) {
  alert("Thats not right its 2021"); // 2020 or 2021
} else {
  alert("How can you be so wrong?"); // any expect 2020, 2021, 2022
}
```

---

### short form

> short form for prompts

```js
var year = prompt("Which year is now?", "");
year == "2021" ? alert("Right!") : alert("Wrong."); // 1.: if true, 2. if false
```

---

### while loops

> a basic while loop

```js
var x = 0;
while (x < 3) {
  alert(x); // 0, 1, 2
  x++;
}
```

---

### for loops

> a basic for loop

```js
for (var i = 0; i < 3; i++) {
  // shows 0, then 1, then 2
  alert(i);
}
```

---

### switch statements

> the basics for switch statements

```js
let a = 2 + 2;
switch (a) {
  case 3:
    alert("Too small");
    break;
  case 4:
    alert("Exactly!");
    break;
  case 5:
    alert("Too big");
    break;
  default:
    alert("I don't know such values");
}
```

---

### functions

> how to make a function

```js
function showMessage(name) {
  alert("Hello " + name + " !");
}
showMessage("john"); // executes the function with parameter
```

---

## Snippets for advanced

### center a div horizontally

> how to center a div horizontally

```js
function center_a_div_horizontally() {
  const parent_div = document.getElementById("div_from_center");
  const parent_hight = parent_div.offsetHeight;

  const center_div = document.getElementById("div_to_center");
  const center_hight = center_div.offsetHeight;

  center_div.style.marginTop = (parent_hight - center_hight) / 2 + "px";
}
center_a_div_horizontally();
```

---

### action on key press

> execute an action on 'esc' key

```js
document.addEventListener("keydown", function (event) {
  if (event.key === "Escape") {
    // execution
  }
});
```

---

### XXX

> XXX

```js

```

---
