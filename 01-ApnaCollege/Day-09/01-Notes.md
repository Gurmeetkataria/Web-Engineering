# CSS (Day-09) – Revision Notes

## 1.  What is Flexbox?

Flexbox is a CSS layout model that helps distribute space and align items efficiently in a container — even when their size is unknown or dynamic.  
It works in a **one-dimensional** flow: either in rows or columns.

```css
.container {
  display: flex;
}
```

### 2. Display Flex
To enable Flexbox behavior, use display: flex on the parent container.
All direct children become flex items.

**Example**
```css
.container {
  display: flex;
}
```

## 3. Flex Direction
Specifies the direction of flex items inside the container.

Value	Description
row	Left to right (default)
row-reverse	Right to left
column	Top to bottom
column-reverse	Bottom to top

**Example**
```css
.container {
  flex-direction: row;
}
```
## 4. Justify Content
Aligns items horizontally along the main axis.

Value	Purpose
flex-start	Align to start
center	Align to center
flex-end	Align to end
space-between	Equal spacing between
space-around	Equal spacing around each item
space-evenly	Equal spacing between and around

**Example:**
```css
.container {
  justify-content: space-between;
}
```

## 5. Flex Wrap
By default, items try to fit in one line.
flex-wrap allows them to wrap onto multiple lines.

Value	Description
nowrap	All items in one line
wrap	Wrap items to new row
wrap-reverse	Wrap in reverse order

 **Example**
```css
.container {
  flex-wrap: wrap;
}
```

## 6. Align Items
Aligns flex items vertically along the cross axis.

Value	Meaning
stretch	Stretch to fill (default)
flex-start	Align to top
center	Align to center
flex-end	Align to bottom
baseline	Align based on text baseline

**Example**
```css
.container {
  align-items: center;
}
```
## 7. Align Content
Aligns multiple rows of items vertically when there is space in the container.
Only works when items are wrapped using flex-wrap.

Value	Effect
stretch	Stretches rows (default)
center	Centers all rows
space-between	Equal space between rows
space-around	Equal space around each row
space-evenly	Equal spacing everywhere

**Example**
```css
.container {
  flex-wrap: wrap;
  align-content: space-evenly;
}
```

## 8. Align Self
Overrides align-items for individual flex items.

Value	Meaning
auto	Uses parent's setting
center	Center this item
flex-start	Align to top
flex-end	Align to bottom

**Example**
```css
.item {
  align-self: flex-end;
}
```

## 9. Flex Sizing
Defines how items grow, shrink, and take up space.

Properties
flex-grow: Can it grow?

flex-shrink: Can it shrink?

flex-basis: Initial/default size

 **Example**
```css
.item {
  flex-grow: 2;
  flex-shrink: 1;
  flex-basis: 100px;
}
```

10. ✍️ Flex Shorthand
A shortcut to define grow, shrink, and basis in one line.

Syntax
css
Copy
Edit
.item {
  flex: <grow> <shrink> <basis>;
}
