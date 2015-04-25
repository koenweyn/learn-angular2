---
layout: default
title: ES6 Classes
edit_link: https://github.com/driftyco/learn-angular2/edit/gh-pages/es6/classes/index.md
tweet: "Understanding let and var in ES6"
---

In ES6, we have a new way of specifying variables: `let1`

Before ES6, we only had `var` which would create a variable scoped to the nearest function.

This was problematic because variables would leak into the rest of the function, especially when used with for loops.

Take this ES5 example:

```javascript
for(var i in thing) {
}
```

After the loop, `i` is still available! 

## Let

With `let`, that is no longer an issue. Let creates a variable
that is only available in the nearest block. 

This is perfect for loops and closures:

```javascript
for(let i in thing) {
 // i is available
}

// i is NOT available
```

In general, use `let` whenever possible.
