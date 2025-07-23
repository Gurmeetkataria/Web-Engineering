# 📘 CSS (Day-07) - Revision Notes

## 1. Box Model
The CSS Box Model describes the rectangular boxes that are generated for elements in the document tree.

**Includes:**
- Content
- Padding
- Border
- Margin

```css
div {
  width: 100px;
  padding: 10px;
  border: 5px solid black;
  margin: 20px;
}
```
## 2. Height & Width
Used to define the size of an element’s content area.

```css
.box {
  height: 200px;
  width: 300px;
}
```
## 3. Border
Adds a line around the content and padding of an element.

```css
.box {
  border: 2px solid red;
}
```
## 4. Border Radius
Rounds the corners of an element's border box.

```css
.box {
  border: 2px solid black;
  border-radius: 10px;
}
```
## 5. Padding Property
Defines the space between the content and the border.

```css
.box {
  padding: 15px;
}
```
## 6. Margin Property
Defines the space outside the border of an element.

```css
.box {
  margin: 20px;
}
```
## 7. Display Property
Specifies the display behavior of an element (e.g., block, inline, flex, grid, etc.).

```css
.box {
  display: block;
}
```
## 8. Block & Inline Elements (Conclusion)
**Block:** Starts on a new line, takes full width.

**Inline:** Stays in line, only takes as much width as needed.

```html
<p>This is a block element.</p>
<span>This is an inline element.</span>
```
## 9. Inline-Block
Displays an element as an inline-level block container. Allows setting width/height like block, but remains inline.

```css
.box {
  display: inline-block;
  width: 150px;
  height: 100px;
}
```
## 10. Relative Units (Percentage)
Percentage units are relative to the parent element’s size.

```css
.box {
  width: 50%; /* 50% of parent width */
}
```
## 11. Em & Rem in Units
em is relative to the font-size of the parent.

rem is relative to the font-size of the root (html).

```css
html {
  font-size: 16px;
}

.box {
  font-size: 2em;   /* 2 * parent font-size */
  padding: 1rem;    /* 16px padding */
}
```