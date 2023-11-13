# Business reference archirecture for [md-docs](https://github.com/biz-dev-ops/md-docs-cli)

HTML5 web component which renders a business reference architecture.

## Usage

- Add `business-reference-archirecture.js` to the webpage
- Add the `<business-reference-archirecture></business-reference-archirecture>` to the page

## Attributes

### model-json

An HTML escaped version of the business reference model.

### model

The business reference model, must be set via JavaScript.

## Examples

### HTML

```html
<business-reference-archirecture model-json="{ &quot;key &quot;: &quot;value &quot; }" />
```

### HTML and JavaScript

```html
<business-reference-archirecture id="business-reference-architecture" />

<script>
    document.getElementById('business-reference-architecture').model = {
    	...
    }
<script>
```
