# Ex Web Components

A few extremely basic web component examples (using Custom elements, Shadow DOM, HTML templates and HTML imports).

```html
<!-- Ex Clock Component -->
<ex-clock hours="24" display="fill"></ex-clock>

<!-- Ex Hero Component -->
<ex-hero display="outline">
    <h1 slot="title">Lorem Ipsum</h1>
    <p slot="content">Vestibulum eleifend porttitor mollis.</p>
</ex-hero>

<!-- Ex Lifecycle Component -->
<ex-lifecycle></ex-lifecycle>
```