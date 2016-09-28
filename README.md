# d2l-numeric-pager

A [Polymer](https://www.polymer-project.org/1.0/)-based web component for numeric-pager.

## Installation

`d2l-numeric-pager` can be installed from [Bower][bower-url]:
```shell
bower install d2l-numeric-pager
```

## Usage

Include the [webcomponents.js](http://webcomponents.org/polyfills/) "lite" polyfill (for browsers who don't natively support web components), then import the opener and content components as needed:

```html
<head>
	<script src="https://s.brightspace.com/lib/webcomponentsjs/0.7.21/webcomponents-lite.min.js"></script>
</head>
```

### Numeric Pager

A Numeric Pager can be defined using `d2l-numeric-pager`.

```html
<link rel="import" href="../d2l-numeric-pager/d2l-numeric-pager.html">

<d2l-numeric-pager page-count="10"></d2l-numeric-pager>
```

### Usage in Production

In production, it's recommended to use a build tool like [Vulcanize](https://github.com/Polymer/vulcanize) to combine all your web components into a single import file. [More from the Polymer Docs: Optimize for Production](https://www.polymer-project.org/1.0/tools/optimize-for-production.html)...

## Coding styles

See the [VUI Best Practices & Style Guide](https://github.com/Brightspace/valence-ui-docs/wiki/Best-Practices-&-Style-Guide) for information on VUI naming conventions, plus information about the [EditorConfig](http://editorconfig.org) rules used in this repo.


[bower-url]: http://bower.io/search/?q=d2l-table
