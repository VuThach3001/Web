# Introduction to CSS

## Topic: CSS Selector

## Date: 17/01/2025 

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

There are 3 types of CSS selector:

**1. Class Selector**: Used for grouping elements in HTML file to apply the same CSS rule to all of them no matter which tag.
  ```
  Heading.html:

  <h2 class="red-text">Red</h2>
  <h2>Green</h2>
  <h2>Blue</h2>
  <p class="red-text">Paragraph</p>

  Style.css:

  .red-text{
    color: red;
  }
  ```
**2. Element Selector**: Apply to all the element that have the particular **tag**.
  ```
  Heading.html:

  <h2>Red</h2>
  <h2>Green</h2>
  <h2>Blue</h2>

  Style.css:

  h2{
    color: red;
  }
  ```
**3. ID Selector**: Select all elements with a particular ID attribute. However, **ID is only applied once for each element in a single HTML file**, it can not be cross-used like **class selector**.
  ```
  Heading.html:

  <h2 id="main">Red</h2>
  <h2>Green</h2>
  <h2>Blue</h2>

  Style.css:

  #main{
    color: red;
  }
  ```
**4. Attribute Selector**: Used to select the elements that have particular attributes or particular attribute values .
  ```
  Heading.html:

  <h2 draggable="true">Red</h2>
  <h2 draggable="false">Green</h2>
  <h2>Blue</h2>

  Style.css:

  h2[draggable="true"]{
    color: red;
  }
  ```
**5. Universal Selector**: Simply select all.
  ```
  Heading.html:

  <h2 class="red-text">Red</h2>
  <h2>Green</h2>
  <h2>Blue</h2>
  <p class="red-text">Paragraph</p>

  Style.css:

  *{
    color: red;
  }
  ```


---

### Summary Section (Summary of Notes)