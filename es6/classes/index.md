---
layout: default
title: ES6 Classes
edit_link: https://github.com/driftyco/learn-angular2/edit/gh-pages/es6/classes/index.md
tweet: "How to write ES6 Classes"
---

ES6 Classes will feel very natural for those with experience writing Object-Oriented code in languages like Java and C#. Here's a simple example:

```javascript
class Beer {
}

class SpottedCow extends Beer {
  constructor() {
    this.deliciousness = 50;
    this.locations = 'Wisconsin';
    this.name = 'Spotted Cow';
  }
}

class MillerLite extends Beer {
  constructor() {
    this.deliciousness = 10;
    this.locations = 'anywhere';
    this.name = 'Miller Lite';
  }
}

let beer = new SpottedCow();

console.log('I am drinking a delicious', beer.name, 'that is available', beer.location);
```
