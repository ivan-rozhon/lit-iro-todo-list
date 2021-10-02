---
layout: page.11ty.cjs
title: <iro-todo> ⌲ Home
---

# &lt;iro-todo>

`<iro-todo>` is an awesome element. It's a great introduction to building web components with LitElement, with nice documentation site as well.

## As easy as HTML

<section class="columns">
  <div>

`<iro-todo>` is just an HTML element. You can it anywhere you can use HTML!

```html
<iro-todo></iro-todo>
```

  </div>
  <div>

<iro-todo></iro-todo>

  </div>
</section>

## Configure with attributes

<section class="columns">
  <div>

`<iro-todo>` can be configured with attributed in plain HTML.

```html
<iro-todo name="HTML"></iro-todo>
```

  </div>
  <div>

<iro-todo name="HTML"></iro-todo>

  </div>
</section>

## Declarative rendering

<section class="columns">
  <div>

`<iro-todo>` can be used with declarative rendering libraries like Angular, React, Vue, and lit-html

```js
import {html, render} from 'lit-html';

const name = 'lit-html';

render(
  html`
    <h2>This is a &lt;iro-todo&gt;</h2>
    <iro-todo .name=${name}></iro-todo>
  `,
  document.body
);
```

  </div>
  <div>

<h2>This is a &lt;iro-todo&gt;</h2>
<iro-todo name="lit-html"></iro-todo>

  </div>
</section>
