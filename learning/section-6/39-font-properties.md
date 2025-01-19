# CSS Properties

## Topic: Font Properties

## Date: 19/01/2025 

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

**Font Properties**:

There are few common font properties:
  ```
  h1{
    color: blue;
    font-weight: bold;
    font-size: 20px;
    font-family: sans-serif;
  }
  ```
**1. Font Size**:
There are some ways to represent font-size:
- **1px** = 1/96th inch = 0.26mm.
- **1pt** = 1/72nd inch = 0.35mm.
- **1em**: 
  - 100% of parent which defines the width of the letter *m* is
  probably the widest letter in the English alphabet.
  - **Functionality**: It will refer 
  ***the font-size of the tag which enclose the working tag***
  ```
  <body> -> 20px -> parent tag
    <h1>Hello</h1> -> Working tag -> refer body tag's font-size -> 20px
  </body>
  ```
  - If we increase to **2em** or more. That means you will use 2 * 100%, 3 * 100%... font-size of the parent tag.
- **1rem**: 
  - 100% of root's font-size which means the **html** font's size.
  - **Functionality**: Just like **em unit** but now will refers to root's font-size (**html**)

**2. Font Weight**:
  ```
  h1{
    font-weight: bold;
  }
  ```
  - There are few options to choose:
    - **bold** or **normal bold** and we all know that means.
    - **lighter** or **bolder**: it will increase 100 or decrease 100 correspondingly.
    - **number**: we can use the number to describe the weight of font.

**3. Font Family**:
  ```
  h1{
    font-family: Helvetica, sans-serif;
  }
  ```
- **Helvetica**: this is called a ***Mac-specific typeface***. So
  in order for Windows user to use and in a general way. We will add
  a **backup generic font type** seperate with a comma to the **typeface**
- For the case of typeface which has more than 1 word, we need to put it in a quotation mark to tell CSS that we have spaces:
  ```
  h1{
    font-family: "Times New Roman", serif;
  }
  ```
- We can simply use the font from google with the below example:
  ```
    <head>
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=Arimo:ital,wght@0,400..700;1,400..700&family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
    </head>
  ```
---

### Summary Section (Summary of Notes)

Useful links:
1. [Font](fonts.google.com)