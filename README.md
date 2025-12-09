# CSS Layout Switching Assignment

This project shows how a single HTML structure can display two different layouts by switching between two CSS stylesheets. The goal of this assignment is to use Flexbox and other CSS techniques to control layout without JavaScript.

## File Structure
- index.html — Shared HTML for both versions
- styleA.css — Vertical Layout (Version A)
- styleB.css — Horizontal Layout (Version B)
- README.md — Documentation

## Version A — Vertical Layout (styleA.css)
- Six boxes (A–F) aligned vertically
- Centered horizontally & evenly spaced vertically using Flexbox
- Box size: 100×100 px
- Alternating background colors
- 1px top border on each box
- Final box (F):
  - Background: #687291
  - 4px solid black border
  - Text centered both vertically & horizontally

## Version B — Horizontal Layout (styleB.css)
- Boxes A–E aligned horizontally in the top-left corner
- Boxes do not wrap on resize
- Box F fixed at the bottom-right corner of the window
- Box size: 100×150 px
- 10px dotted left border (#D0D0FF)
- 10px space between boxes
- Hover effect:
  - Background: yellow
  - Text: goldenrod
  - Cursor changes to pointer

## How to Switch Between Stylesheets
In index.html, comment/uncomment one of the following:

Version A:
<link rel="stylesheet" href="styleA.css">
<!-- <link rel="stylesheet" href="styleB.css"> -->

Version B:
<!-- <link rel="stylesheet" href="styleA.css"> -->
<link rel="stylesheet" href="styleB.css">

Refresh the browser to view the selected layout.

## Techniques Used
- HTML5
- CSS3
- Flexbox
- Positioning
- No JavaScript or external libraries


## Author
Sedef — Computer Engineering Student

