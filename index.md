---
theme: league
---

# Getting Funcy

#### How To Use Functions in JavaScript

_by Colin Jaffe_

###### (Sorry not sorry for the puns.)

---

## What Will I Learn Here?

- Why functions are neat-o.<!-- .element: class="fragment" -->
- How to define a function.<!-- .element: class="fragment" -->
- How to call a function.<!-- .element: class="fragment" -->

---

## What's A Real-World Analogue For Functions?

What a great question!

They're a lot like cooking recipes:

A set of instructions for accomplishing a task.

```markdown
1. Spread butter on one side of each piece of bread.
2. Put cheese on other side of one slice.
3. Put the other slice, butter-side up, on top.
4. Grill on pan until bread is browned on one side.
5. Flip sandwich and brown other side.
```

---

## Why Use Functions?

### They allow you to organize code.

<!-- .element: class="fragment" -->

Instead of clogging your app with:

<!-- .element: class="fragment" -->

```javascript
console.log("Hello:");
console.log(username);
console.log("Today is:");
console.log(todaysDate);
```

<!-- .element: class="fragment" -->

After putting that code in a function called `greetUser`, you could instead write:

<!-- .element: class="fragment" -->

```javascript
greetUser();
```

<!-- .element: class="fragment" -->

---

## How Do We Do Use Functions?

Define it using the `function` keyword and curly braces to wrap the code:

```javascript
function greetUser() {
  console.log("Hello:");
  console.log(username);
  console.log("Today is:");
  console.log(todaysDate);
}
```

And, later, call it using:

```javascript
greetUser();
```

The parentheses indicate that we want to "call" or "invoke" (run) the function.

---

## Now You Have A "Recipe Book" For Code

```javascript
function greetUser() {
  console.log("Hello:");
  console.log(username);
  console.log("Today is:");
  console.log(todaysDate);
}
```

```javascript
function logUserIn() {
  // More code here.
}
```

```javascript
function loadMovieList() {
  // Even more code here.
}
```

```javascript
function initializeGame() {
  // Probably just tons of code here.
}
```

Note: Cool stuff here.
