# [Halfmoon](https://www.gethalfmoon.com)

> Front-end framework with a built-in dark mode and full customizability using CSS variables; great for building dashboards and tools.

- **Built-in dark mode**—Halfmoon comes with a built-in, toggleable dark mode, which is one of its most important and defining features.
- **Fully customizable using CSS variables**—The framework is built entirely using CSS variables (also known as CSS custom properties). There are close to *1,500 CSS variables*, which means that almost everything can be customized by overriding a property, making it very easy to theme Halfmoon to fit your brand. [Learn more about customization](https://www.gethalfmoon.com/docs/customize/).
- **Great for building dashboards and tools**—The components have a very standard look and feel to them, making them suitable for dashboards and tools. Moreover, a lot of importance is placed on components such as forms, navbars, sidebars, dropdowns, toasts, shortcuts, etc. and there are also *tons of utilities* available.
- **Optional JS library**—Many of the components found in Halfmoon are built to work without JavaScript. However, the framework still comes with a powerful JavaScript library with no extra dependencies, such as jQuery.
- **Bootstrap like classes**—The class names should be instantly familiar to anyone who has used Bootstrap.
- **Cross-browser compatibility**—Fully supports almost all the browsers under the sun, including really old ones like Internet Explorer 11.

To learn more, go to [the documentation](https://www.gethalfmoon.com/docs/introduction/).

## Quickstart

The quickest way to get started with Halfmoon is by using the CDN to include the following files:

```html
<!-- Halfmoon CSS -->
<link href="https://cdn.jsdelivr.net/npm/halfmoon@1.1.1/css/halfmoon-variables.min.css" rel="stylesheet" />
<!--
  Or,
  Use the following (no variables, supports IE11):
  <link href="https://cdn.jsdelivr.net/npm/halfmoon@1.1.1/css/halfmoon.min.css" rel="stylesheet" />
-->

<!-- Halfmoon JS -->
<script src="https://cdn.jsdelivr.net/npm/halfmoon@1.1.1/js/halfmoon.min.js"></script>
```

**Pleast note**, the JS file should be placed at the end of the `<body>` tag. Otherwise, some things may not work as expected. For example, using the `onclick="..."` event to call one of Halfmoon's built-in methods will not work **unless** the JS file is placed at the end of the `<body>` tag.
