
---

## 📘 Day-01 HTML - Noted

### 1. **Lists in HTML**

HTML provides two main types of lists:

 **Ordered List (`<ol>`)**: Displays items in a numbered format.
 **Unordered List (`<ul>`)**: Displays items in a bullet-point format.
  Each item in the list is defined using the `<li>` (list item) tag. Lists help organize content in a readable and structured way.

---

### 2. **Attributes in HTML**

Attributes provide **additional information about an HTML element**. They are always specified in the start tag and usually come in **name/value pairs** like `name="value"`.
Example:

<a href="https://example.com">Visit</a>

Here, `href` is an attribute of the `<a>` (anchor) tag.

---

### 3. **Anchor Element**

The `<a>` tag (anchor element) is used to create **hyperlinks**, allowing users to navigate from one page to another. The `href` attribute specifies the destination URL.
Example:

```html
<a href="https://google.com">Go to Google</a>
```

---

### 4. **Image Element**

The `<img>` tag is used to **embed images** in a webpage. It is an **empty tag** (doesn’t have a closing tag) and uses attributes like:

 `src`: The image source (URL or file path)
 `alt`: Alternate text (displayed if image fails to load)
  Example:

<img src="logo.png" alt="Website Logo">


---

### 5. **More HTML Tags**

Covers additional HTML elements such as:

 `<br>` (line break)
 `<hr>` (horizontal rule)
 `<strong>`, `<em>` for emphasizing text
  These tags enhance text formatting and content layout on webpages.

---

### 6. **Comments in HTML**

HTML comments are used to **leave notes or explanations** within the code, which are not visible in the browser.
Syntax:


<!-- This is a comment -->

Comments help developers understand the code or temporarily disable parts without deleting them.

---

### 7. **Is HTML Case Sensitive?**

HTML is not case-sensitive, which means `<HTML>` and `<html>` are treated the same. However, it’s a good practice to use **lowercase tags and attributes** to follow modern web standards (HTML5).
