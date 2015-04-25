---
layout: default
title: Templates
edit_link: https://github.com/driftyco/learn-angular2/edit/gh-pages/templates/index.md
tweet: "All about Templates in Angular 2"
---

Templates are very similar to templates in Angular 1, though there are many small syntactical changes that make it more clear what is happening.

## A simple template

Let's start with a very simple template that shows our name and our favorite thing:

```html
{% raw %}
<div>
  Hello my name is {{name}} and I like {{thing}} quite a lot.
</div>
{% endraw %}
```

## Rendering

To render a string, we can use the standard double-curly

