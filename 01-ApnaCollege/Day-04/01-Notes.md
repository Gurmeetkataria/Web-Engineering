# 🌐 HTML Day-04 – Notes

## 1.  Tables in HTML
Tables in HTML are used to organize data into rows and columns, making it easy to display tabular content such as schedules, reports, and data entries.

`<table>`, `<tr>`, `<th>`, `<td>`

Example:
<table>
  <tr><th>Name</th><th>Age</th></tr>
  <tr><td>Ali</td><td>20</td></tr>
</table>

## 2. Semantics in Tables
Semantic tags like `<thead>`, `<tbody>`, and `<tfoot>` give meaning and structure to table content, improving accessibility for screen readers and search engines.

Example:
<table>
  <thead><tr><th>Item</th></tr></thead>
  <tbody><tr><td>Pen</td></tr></tbody>
  <tfoot><tr><td>Total</td></tr></tfoot>
</table>

## 3. Colspan & Rowspan Attributes
These attributes allow a single table cell to span multiple rows or columns, which is useful for merging cells in headers or grouping data visually.

colspan: Merges columns.
rowspan: Merges rows.

Example:
<tr>
  <td colspan="2">Merged Column</td>
</tr>
<tr>
  <td rowspan="2">Merged Row</td><td>Data</td>
</tr>

## 4. Forms in HTML
Forms are interactive elements in HTML used to collect user input and send it to a server for processing (e.g., login, signup, feedback).

Tag: <form>

Example:
```<form>
  <input type="text" />
  <button type="submit">Submit</button>
</form>```

## 5. Input – Form Element
The <input> element is used to collect different types of data from the user, such as text, numbers, emails, and passwords.

Common types: text, email, password, number, date, file, etc.

Example:
<input type="email" placeholder="Enter your email" />

## 6. Placeholders & Labels
placeholder: Helps users understand what input is expected.

label: Connects to input fields for accessibility and improves form usability, especially for screen readers.

Example:
<label for="name">Name:</label>
<input type="text" id="name" placeholder="Enter your name" />

## 7. Button Element
Definition: The <button> element performs actions such as submitting forms or triggering JavaScript. Essential for interactivity and data submission.

Types: submit, reset, button

Example:
<button type="submit">Submit</button>

## 8. Name Attribute
Definition: The name attribute identifies form data and is used in data submission to the backend. It's crucial because form data is submitted as key-value pairs where name is the key.

Example:
<input type="text" name="username" />

## 9. Checkbox – Input Element
Definition: Checkboxes allow users to select multiple options independently. Ideal for forms involving categories, skills, or preferences.

Example:
<input type="checkbox" name="skill" value="HTML"> HTML

## 10. Radio – Input Element
Definition: Radio buttons are used when only one option is allowed. All related radio inputs must share the same name.

Example:
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female

## 11. Select – Input Element
Definition: The <select> element provides a dropdown list. It’s useful for selecting one item from a fixed set of choices (like country, course, etc.).

Example:
<select>
  <option value="html">HTML</option>
  <option value="css">CSS</option>
</select>

## 12. Range – Input Element
Definition: The <input type="range"> is used for numeric input via a slider. You can customize the range using min, max, and step.

Example:
<input type="range" min="1" max="100" step="5">

## 13. Text Area
Definition: The <textarea> element allows multi-line input, suitable for long-form content like comments, reviews, or messages.

Example:
<textarea rows="4" cols="30">Enter your feedback...</textarea>