# JS Drag and Drop

A small vanilla-JavaScript demo of a **sortable list**: reorder the items by
dragging one row onto another and the two swap places. Built as a learning
exercise, with no frameworks and no build step.

## Features

- Reorderable list using the native HTML Drag and Drop API.
- Items start in a randomly shuffled order on each load.
- Drop-target highlighting while dragging (`.over` state).
- Styles authored in SCSS and compiled to CSS.

## Tech

- HTML, vanilla JavaScript (no dependencies)
- SCSS → CSS
- Font Awesome for the grip icons

## Run

No install or build required — just open the page:

```bash
open index.html
```

To edit the styles, recompile the SCSS after changing `style.scss`:

```bash
sass style.scss style.css
```

## Files

```
index.html    # markup and Font Awesome include
script.js     # list rendering, drag events, swap logic
style.scss    # source styles
style.css     # compiled output
```

## Credits

Based on the "Sortable List" project from
[Brad Traversy's vanillawebprojects](https://github.com/bradtraversy/vanillawebprojects/tree/master/sortable-list)
([video](https://www.youtube.com/watch?v=wv7pvH1O5Ho)).
