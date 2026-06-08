````markdown
# CSS Colors - Revision Notes

## What is Color in CSS?

CSS supports multiple ways to define colors:

1. Named Colors
2. Hexadecimal Colors
3. RGB Colors
4. HSL Colors
5. RGBA Colors
6. HSLA Colors
7. Hex Colors with Alpha

---

# Foreground vs Background

## Foreground Color

Controls text color.

```css
color: red;
````

Example:

```css
h1{
    color:red;
}
```

---

## Background Color

Controls background color.

```css
background-color: yellow;
```

Example:

```css
h1{
    background-color: yellow;
}
```

---

# Named Colors

Uses English color names.

Example:

```css
color: blue;
background-color: limegreen;
```

Examples:

* red
* blue
* black
* white
* green
* yellow
* orange

Pros:

* Easy to remember.

Cons:

* Limited color choices.

---

# Hexadecimal Colors

Format:

```css
#RRGGBB
```

Example:

```css
color: #FFFFFF;
background-color: #000000;
```

Common Colors:

| Color | Hex     |
| ----- | ------- |
| Black | #000000 |
| White | #FFFFFF |
| Red   | #FF0000 |
| Green | #00FF00 |
| Blue  | #0000FF |

Short Form:

```css
#FFFFFF → #FFF
#000000 → #000
#00FFFF → #0FF
```

---

# RGB Colors

Format:

```css
rgb(red, green, blue)
```

Range:

```text
0 - 255
```

Example:

```css
color: rgb(255,0,0);
```

Examples:

```css
rgb(255,0,0)
rgb(0,255,0)
rgb(0,0,255)
```

---

# Hex vs RGB

Both represent the same colors.

Example:

```css
#FF0000
```

is equivalent to

```css
rgb(255,0,0)
```

Total Possible Colors:

```text
256 × 256 × 256
=
16,777,216 Colors
```

---

# HSL Colors

Format:

```css
hsl(hue, saturation, lightness)
```

Example:

```css
hsl(120,60%,70%)
```

---

## Hue

Color wheel angle.

| Color     | Degree |
| --------- | ------ |
| Red       | 0      |
| Green     | 120    |
| Blue      | 240    |
| Red Again | 360    |

---

## Saturation

Controls color intensity.

```text
0% = Gray
100% = Pure Color
```

---

## Lightness

Controls brightness.

```text
0% = Black
50% = Normal
100% = White
```

---

# RGBA

RGB + Alpha

Format:

```css
rgba(red, green, blue, alpha)
```

Example:

```css
rgba(255,0,0,0.5)
```

Alpha Range:

```text
0 = Transparent
1 = Opaque
```

---

# HSLA

HSL + Alpha

Format:

```css
hsla(hue,saturation,lightness,alpha)
```

Example:

```css
hsla(120,100%,50%,0.5)
```

---

# Hex with Opacity

Format:

```css
#RRGGBBAA
```

Example:

```css
#FF000080
```

Opacity Range:

```text
00 = Transparent
FF = Opaque
```

---

# Transparent Keyword

Example:

```css
background-color: transparent;
```

Equivalent To:

```css
rgba(0,0,0,0)
```

---

# Memory Tricks

Named Color
= Color Name

Hex
= #RRGGBB

RGB
= rgb(R,G,B)

HSL
= hsl(H,S,L)

RGBA
= RGB + Transparency

HSLA
= HSL + Transparency

Transparent
= Invisible Color

---

# Exam Definitions

### color

Changes text color.

### background-color

Changes background color.

### Hex Color

Represents colors using hexadecimal values.

### RGB

Represents colors using Red, Green and Blue values.

### HSL

Represents colors using Hue, Saturation and Lightness.

### Alpha

Controls transparency.

### Transparent

A fully transparent color.

---

# Quick Revision Table

| Format      | Example              |
| ----------- | -------------------- |
| Named       | blue                 |
| Hex         | #FF0000              |
| RGB         | rgb(255,0,0)         |
| HSL         | hsl(0,100%,50%)      |
| RGBA        | rgba(255,0,0,0.5)    |
| HSLA        | hsla(0,100%,50%,0.5) |
| Transparent | transparent          |

```
```
