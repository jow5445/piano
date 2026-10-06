# ![Piano](https://jow5445.github.io/piano/)

![Piano](https://user-cdn.hackclub-assets.com/01a0eaed-ce6e-7b01-b1a3-44cc5ccf40d0/Screenshot%20From%202026-09-29%2005-10-13.png)

A small piano I made using HTML, CSS, and JavaScript.

You can click the keys with your mouse, or use your keyboard to play different notes.

## How to play

The white keys use these keyboard keys:

```text
Z X C V B N M
```

The black keys use:

```text
S D G H J
```

You can also just click the piano keys directly.

## How it works

Each piano key has a `data-note` attribute that points to an audio file.

For example:

```html
<div data-note="c" class="key White"></div>
```

When a key is pressed, JavaScript finds the matching audio element and plays it.

I also added an `active` class so the key changes appearance while the note is playing.

## Built with

* HTML
* CSS
* JavaScript

No frameworks or libraries are used.

## Running it

Just open `index.html` in a browser and start playing.

## Note

This was mainly a small project for practicing JavaScript events, DOM elements, and working with audio in the browser.