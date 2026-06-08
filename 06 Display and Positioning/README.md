````markdown
# CSS Positioning and Layout - Quick Revision Notes

## Position Property

The `position` property specifies how an element is positioned on a webpage.

### Relative

```css
position: relative;
````

* Moves relative to its original position.
* Original space remains reserved.
* Uses `top`, `left`, `right`, and `bottom`.

**Memory:** Moves itself.

---

### Absolute

```css
position: absolute;
```

* Removed from normal document flow.
* Positioned relative to the nearest positioned parent.
* If no positioned parent exists, uses the viewport.

**Memory:** Follows parent.

---

### Fixed

```css
position: fixed;
```

* Removed from normal flow.
* Positioned relative to the browser window.
* Remains visible while scrolling.

**Memory:** Follows screen.

---

### Sticky

```css
position: sticky;
```

* Acts like relative initially.
* Becomes fixed when scrolling reaches a specified offset.
* Requires `top`, `left`, `right`, or `bottom`.

**Memory:** Sticks on scroll.

---

## Z-Index

```css
z-index: 10;
```

Controls the stacking order of overlapping elements.

* Higher value = appears in front.
* Lower value = appears behind.
* Works on positioned elements.

**Memory:** Controls layers.

---

## Display Property

Controls how elements appear in a document.

### Inline

```css
display: inline;
```

* Takes only required width.
* Appears on the same line.
* Width and height do not work.

Common elements:

```html
<a>
<span>
<em>
<strong>
```

**Memory:** Inside the line.

---

### Block

```css
display: block;
```

* Starts on a new line.
* Takes full available width.
* Width and height work.

Common elements:

```html
<div>
<p>
<h1>
<section>
```

**Memory:** New line.

---

### Inline-Block

```css
display: inline-block;
```

* Appears on the same line.
* Width and height work.
* Combines inline and block features.

**Memory:** Same line + size control.

---

## Float Property

```css
float: left;
```

```css
float: right;
```

* Moves elements left or right.
* Allows text/content to wrap around them.

Common uses:

* Image and text layouts
* Older navigation layouts

**Memory:** Float left/right.

---

## Clear Property

```css
clear: left;
clear: right;
clear: both;
```

Prevents elements from sitting next to floated elements.

### Values

| Value | Description         |
| ----- | ------------------- |
| left  | Clears left floats  |
| right | Clears right floats |
| both  | Clears both sides   |
| none  | Default             |

Example:

```css
.footer{
    clear: both;
}
```

**Memory:** Stops float effects.

---

# Quick Memory Table

| Property     | Memory Trick       |
| ------------ | ------------------ |
| static       | Normal position    |
| relative     | Moves itself       |
| absolute     | Follows parent     |
| fixed        | Follows screen     |
| sticky       | Sticks on scroll   |
| z-index      | Controls layers    |
| inline       | Same line          |
| block        | New line           |
| inline-block | Same line + size   |
| float        | Float left/right   |
| clear        | Stop float effects |

---

# One-Line Definitions

### Position

Specifies how an element is positioned on a webpage.

### Relative

Positions an element relative to its normal position.

### Absolute

Positions an element relative to its nearest positioned ancestor.

### Fixed

Positions an element relative to the viewport and keeps it visible while scrolling.

### Sticky

Acts as relative until a scroll threshold is reached, then behaves like fixed.

### Z-Index

Controls the stacking order of overlapping elements.

### Inline

Displays elements on the same line and uses only the required width.

### Block

Displays elements on a new line and occupies available width.

### Inline-Block

Displays elements inline while allowing width and height adjustments.

### Float

Moves elements to the left or right of their container.

### Clear

Specifies which sides of an element cannot be adjacent to floated elements.

```
```
