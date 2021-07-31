# Box Model

The CSS Box Model is the foundation of layout on the web.

Each element is represented as a rectangular box, with the boxes content, padding, border, and margin built up around each other.

<https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model>

## Block Boxes and Inline Boxes

CSS operates with primarily two types of boxes:

- Block Box
- Inline Box

Block boxes will:

- Break onto a new line.
- Extend in the inline direction to fill the space available in its container. This typically means the box will become as wide as its container.
- The CSS "width" and "height" properties are respected.
- Padding, margin, and border will cause other elements to be pushed away from the box.

Inline boxes will:

- Not break onto a new line.
- The "width" and height" properties will *not* apply.
- Vertical padding, margins, and borders will apply but not cause other inline boxes to move away from the box.
- Horizontal padding, margins, and borders will apply and will cause other inline boxes to move away from the box.
