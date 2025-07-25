# 🌐 CSS (Day-04) – Revision Notes

---

## 1. What is CSS?
**CSS (Cascading Style Sheets)** is a style sheet language used to describe the appearance and formatting of a document written in HTML. It controls the design aspects like colors, layouts, spacing, fonts, and responsiveness of web pages, making them visually attractive and user-friendly.

**Example:**
```css
p {
  color: blue;
  font-size: 16px;
}
```
---
## 2. Basic CSS Format
CSS is written using rules, which consist of:

Selector: Target HTML element(s).

Declaration Block: One or more property-value pairs enclosed in {}.

**Syntax:**
```css
selector {
  property: value;
}
/* Example: */

h1 {
  color: red;
}
```
##  3. Including CSS
CSS can be included in three ways:

Inline CSS – written inside an HTML tag using the style attribute.

Internal CSS – defined inside a <style> tag in the <head> section.

External CSS – saved in a separate .css file and linked via <link>.

Best Practice: Use external CSS for maintainability.

**Example**(External):
```css
<link rel="stylesheet" href="style.css">
```
## 4. Color Property
The color property in CSS sets the color of text content inside an element.

**Example:**
```css
h2 {
  color: green;
}
```

## 5. Background Color Property
This property sets the background color of an element.

**Example:**
```css
div {
  background-color: lightblue;
}
```

## 6. Color Systems (Name & RGB)
CSS supports various color formats:

Color Names: e.g., red, blue, black

RGB (Red, Green, Blue): e.g., rgb(255, 0, 0)

**Example:**
```css
p {
  color: rgb(0, 128, 0); /* Green */
}
```

## 7. Hex Codes
Hexadecimal color codes represent colors using 6-digit combinations of letters and numbers. Each pair (RR, GG, BB) represents red, green, and blue intensity (00 to FF).

**Example:**
```css
body {
  background-color: #ffcc00; /* Yellow */
}
```
## 8. Text Align Property
The text-align property is used to align text within an element.

Common Values:
left

right

center

justify

**Example:**
```css
p {
  text-align: center;
}
```

## 9. Font Weight & Text Decoration
Font Weight: Adjusts the boldness of the text.

Common values: normal, bold, lighter, 100–900

Text Decoration: Adds styles like underline, overline, or line-through.

**Example:**
```css
h3 {
  font-weight: bold;
  text-decoration: underline;
}
```

## 10. Line Height & Letter Spacing
Line Height: Sets the amount of space between lines of text.

Letter Spacing: Adjusts spacing between characters in the text.

**Example:**
```css
p {
  line-height: 1.8;
  letter-spacing: 2px;
}
```

## 11. Units in CSS (Pixel)
CSS allows different types of units.
Pixels (px) are an absolute unit commonly used for fixed sizing.

Other units include %, em, rem, vw, and vh.

**Example:**
```css
div {
  width: 300px;
  padding: 20px;
}
```

## 12. Font Family
The font-family property defines the typeface (font) used for text.

Tip: Always provide a fallback font and a generic font family like sans-serif.

**Example:**
```css
body {
  font-family: Arial, Helvetica, sans-serif;
}
```