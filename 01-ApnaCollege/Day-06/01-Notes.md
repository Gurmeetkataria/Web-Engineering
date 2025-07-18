# 🌐 CSS (Day-06) – Revision Notes

## 1. Universal Selector

**Definition:**  
The universal selector `*` targets **all HTML elements** on the page. It is often used for resetting margin, padding, or applying a global style.

**Example:**
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

## 2.Element Selector
Definition:
Selects elements based on their HTML tag name.

Example:

``css
h1 {
  font-size: 2em;
  color: navy;
}
```

## 3.ID Selector
Definition:
Selects a specific element using its unique id value. It starts with a hash (#) symbol.

Note: IDs should be unique within a page.

Example:
```css
#main-header {
  background-color: black;
  color: white;
}
```
# 4.Class Selector
Definition:
Targets one or multiple elements that share the same class. It begins with a period (.).

Example:
```css
.card {
  border: 1px solid #ccc;
  padding: 10px;
}
```
# 5.Descendant Selector
Definition:
Selects elements that are nested within another element, regardless of how deeply they are nested.

Example:
```css
div p {
  color: gray;
}
```
# 6.Sibling Combinator
Definition:
Selects an element that comes immediately after another element at the same level using the + symbol.

Example:
```css
h1 + p {
  font-style: italic;
}
```
# 7.Child Combinator
Definition:
Selects elements that are direct children of another element using the > symbol.

Example:
```css
ul > li {
  color: green;
}
```
# 8.Attribute Selector
Definition:
Targets elements based on the presence or value of an attribute.

Example:
```css
input[type="email"] {
  border: 2px solid skyblue;
}
```
# 9.Pseudo Class
Definition:
Used to define the special state of an element such as hover, focus, first-child, etc. It starts with a single colon (:).

Example:
```css
a:hover {
  text-decoration: underline;
  color: red;
}
```
# 10.Pseudo Element
Definition:
Used to style specific parts of an element, like the first line or first letter. It starts with double colons (::).

Example:
```css
p::first-letter {
  font-size: 2em;
  color: darkorange;
}
```
# 11.Cascading & Specificity
Definition:

Cascading: The concept where the last declared rule wins if multiple rules target the same element.

Specificity: Determines which CSS rule takes precedence when more than one rule applies.

Specificity Ranking (Low to High):

Element selector → div, p

Class, attribute, pseudo-class → .class, [type="text"], :hover

ID selector → #id

Inline styles → style="" in HTML

!important rule → Overrides all

Example:
/* This will override the .title rule because of higher specificity */
#main-title {
  color: navy;
}
# 12.!important in CSS
Definition:
Forces a CSS rule to be applied, overriding all other rules, regardless of specificity. Use only when absolutely necessary.

Example:
```css
p {
  font-size: 18px !important;
}
```
# 13.Inheritance
Definition:
Inheritance means that some properties (like text color, font family) are passed from parent elements to their children unless overridden.

Example:
```css
body {
  font-family: Verdana;
  color: #333;
}
/* All child elements will inherit these unless they have their own styles */
```