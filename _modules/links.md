---
layout: module-doc
title: Links
description: "Sass module for links used in RightScale apps"
name: designkit-links
source: https://github.com/rightscale-design/designkit-links
npm: https://www.npmjs.com/package/designkit-links
version: 1.0.0
updated: 7/18/2017
css-link: https://raw.githubusercontent.com/rightscale-design/designkit-links/master/dist/designkit-links.css
example-1: https://jasonmelgoza.github.io/designkit-links/basic.html
install: "npm install designkit-links --save"
dependencies:
  - name: Colors
    url: /modules/colors/

slug: modules
weight: 4
---

## Install

```bash
{{ page.install }}
```

## Dependencies

<ul>
  {% for item in page.dependencies %}
    <li><a href="{{ item.url }}">{{ item.name }}</a></li>
  {% endfor %}
</ul>

## Examples

### Basic Usage

Basic link styles.

**HTML**

```html
<a href="#">This is a link</a>
```

**Example**

<iframe style="height: 100px;" src="{{ page.example-1 }}"></iframe>

## CSS

<div class="snippet">
  <pre id="css_contents" class="highlighter-rouge snippet-css"><code class="css"></code></pre>
</div>
