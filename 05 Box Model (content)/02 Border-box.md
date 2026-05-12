# Border-Box Model

1. `box-sizing: border-box;` changes the default box model.

2. It keeps the element’s `width` and `height` fixed.

3. Padding and border are included inside the box dimensions.

4. The overall size of the element does not increase.

5. This makes layouts easier to manage and align.

6. Example:
```css
* {
  box-sizing: border-box;
}
```

7. A `200px` wide box stays exactly `200px` wide even after adding padding and border.