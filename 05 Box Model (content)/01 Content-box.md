# Box Model & Content-Box in CSS

## 15-Point Summary

<img src="content modal.png">

1. The CSS **Box Model** defines how element size and spacing work on a webpage.

2. Every HTML element is treated like a rectangular box.

3. The main parts of the box model are:
   - Content
   - Padding
   - Border
   - Margin

4. `width` and `height` normally apply only to the **content area**.

5. `padding` adds space between the content and the border.

6. `border` surrounds the padding and content.

7. `margin` creates space outside the border.

8. By default, browsers use the `content-box` box model.

9. In `content-box`, padding and border are added to the specified width and height.

10. Example:
```css
width: 300px;
padding: 10px;
border: 1px solid black;
```

11. The actual width becomes `322px`.

12. Height also increases when padding and borders are added.

13. This makes element sizing difficult to manage accurately.

14. Large projects become harder to align because box dimensions keep increasing unexpectedly.

15. CSS uses the `box-sizing` property to control how dimensions are calculated.

## Default Box-Sizing

```css
box-sizing: content-box;
```
