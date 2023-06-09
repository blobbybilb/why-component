# Why?Component

### no-compile HTML/JS library to make reuseable components

**Status: [production-ready meme](https://github.com/fireship-io/flamethrower#README)**

## Why?
I often want components, like in most frontend frameworks, in pure HTML/CSS/JS without the need to compile. This is a simplest way I could think of to implement this.


## Features:

- Reuseable external components done in a very basic way (with markdown support)
- Looks like HTML (inspired by and complements AlpineJS)
- components are just normal html/markdown files

## How-to

Add this to HTML:

```html
<script defer src="/why.js"></script>
```

This repo is an example, see `index.html`. To try it out, clone/download this repository and start a file server in the main folder.

## known bugs

- rendering markdown that has whitespace at the start of the line


## Limitations
Yes.
