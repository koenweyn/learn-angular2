---
layout: default
title: Components
edit_link: https://github.com/driftyco/learn-angular2/edit/gh-pages/components/index.md
tweet: "How to use components in Angular 2"
---

In Angular 2, Components are the main way we build and specify elements and logic on the page.

In Angular 1, we achieved this through directives, controllers, and scope. In Angular 2, all those concepts
are combined into Components.

### A simple component

Let's start with a very simple component that lists out our name:

```javascript
import {Component, View} from 'angular2/angular2'

@Component({
  selector: 'my-component'
})
@View({
  inline: "<div>Hello my name is {{name}}</div>"
})
export class MyComponent {
  constructor() {
    this.name = 'Max'
  }
  sayMyName() {
    console.log('My name is', this.name)
  }
}
```

