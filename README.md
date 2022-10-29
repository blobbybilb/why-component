# Why?Component

### no-compile HTML/JS library to make reuseable components

**Status: production-ready meme**

## Features:

- Reuseable external components done in a very basic way (with markdown support)
- Looks like HTML (inspired by and complements AlpineJS)
- components are just normal html/markdown files

## How-to

Add this to HTML:

```html
<script defer src="/why.js"></script>
```

This repo is an example, see `index.html`.

## known bugs

- rendering markdown that has whitespace at the start of the line
