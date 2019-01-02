---
title: Split Your Styles into Smaller Chunks with Partials
---
## Split Your Styles into Smaller Chunks with Partials

You can use import with CSS or Sass to split your files into smaller, more maintainable portions. The difference between the two is that when import is used with normal CSS, it creates another HTTP request for every file you import. With Sass instead, the file is taken and combined into the one you are importing into, so you can serve a single CSS file to the browser.

## Hint 1:

remember, you don't need to add the extension of the file to import when you use @import.

## Solution:

```
// The main.scss file

@import 'variables'

```

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
