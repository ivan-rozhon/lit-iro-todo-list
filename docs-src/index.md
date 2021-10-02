---
layout: page.11ty.cjs
title: <iro-todo-list> ⌲ Home
---

# &lt;iro-todo-list>

`<iro-todo-list>` is an awesome element. It's a great introduction to building web components with LitElement, with nice documentation site as well.

## As easy as HTML

<section class="columns">
  <div>

`<iro-todo-list>` is just an HTML element. You can it anywhere you can use HTML!

```html
<iro-todo-list></iro-todo-list>
```

  </div>
  <div>

<iro-todo-list></iro-todo-list>

  </div>
</section>

## Configure with attributes

<section class="columns">
  <div>

`<iro-todo-list>` can be configured with attributed in plain HTML.

```html
<iro-todo-list name="HTML"></iro-todo-list>
```

  </div>
  <div>

<iro-todo-list name="HTML"></iro-todo-list>

  </div>
</section>

## Declarative rendering

<section class="columns">
  <div>

`<iro-todo-list>` can be used with declarative rendering libraries like Angular, React, Vue, and lit-html

```js
import {html, render} from 'lit-html';

const name = 'lit-html';

render(
  html`
    <h2>This is a &lt;iro-todo-list&gt;</h2>
    <iro-todo-list .name=${name}></iro-todo-list>
  `,
  document.body
);
```

  </div>
  <div>

<h2>This is a &lt;iro-todo-list&gt;</h2>
<iro-todo-list name="lit-html"></iro-todo-list>

  </div>
</section>
