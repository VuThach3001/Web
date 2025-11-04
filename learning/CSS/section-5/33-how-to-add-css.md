# Introduction to CSS

## Topic: How to add CSS?

## Date: 16/01/2025 

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

There are 3 types of adding CSS to html file:

**1. Inline:**
  ``` 
    <html style = "background: blue"> 
    </html>
  ```
  - Attribute **style** can be in all tag (html, img, p...)
  - The first pat would be **property** and the second part is the **value**.
  - **Advantage**: Useful for adding CSS style to **just a single element** you want to test or only want it in one signle element on HTML page.
  - **Disadvantage**: Can not add these inline style to each and every single of the tags.

**2. Internal:**
  ``` 
    <html>
      <head>
        <style>
          html{
            background: red;
          }
        </style>
      </head>
    </html>
  ```
  - This is done through a special HTML tag call the **style element**.
  - **html{}**: Selector comes with a set of curly braces and CSS goes in between these two sets of curly braces.
  - **Advantage**: 
    - This can apply to anywhere within the same html document.
    - Useful for applying it only to one HTML document.
  - **Disadvantage**: Can not use for multi-page website.

**3. External:**
  ``` 
    <html>
      <head>
        <link
          rel="stylesheet"
          href="./styles.css"
        />
      </head>
    </html>
  ```
  - Use a .css file. Inside this CSS file is where we write our CSS rules.
  - Using the **link element (< link />)** to link the html file with css file. There are 2 common things in this element:
    - **Relationship (rel)**: refer to what is the role of this thing that we're linking to.
    - **Hyperlink reference (href)**: refer to where is it located.

    *Note: This external style CSS is what's used most commonly in web development.*

---

### Summary Section (Summary of Notes)