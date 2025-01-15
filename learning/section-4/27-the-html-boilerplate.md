# Multi-Page Websites

## Topic: The HTML Boilerplate

## Date: 14/01/2025 

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

- **The HTML Boilerplate**: There is a structure to the HTML files and it looks something like this:

  ``` 
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>My Website</title>
    </head>

    <body>
      <h1>Hello World!</h1>
    </body>
  </html>
  ```

- **``` <!DOCTYPE html> ```:** At the top of every HTML file, there should be a **Doctype declaration** which telling the browser which version of HTML the file was written in (the latest version HTML is HTML5 and the Doctype declaration looks like this with an *angle bracket (<>)*, an *exclamation mark (!)*, DOCTYPE in all caps and then html).
- **```<html lang="en"></html>:```** This is the root of the document. Everything else, other element, no matter if it's an h1 or an image or a link. they are all going to go inside the opening and closing tags of the html element.
  - **lang**: This attribute stands for the language of the text content in that element. This is very important for the users who can not see the website, because there are various screen readers and assistive technologies.

- **```<head></head>```**: This is an area where important information about our website is placed that is not going to be displayed to the user. It includes things that will help the website render in the browser correctly, but it doesn't include any sort of content like text or images or anything that the user will see.
- One of the things that should always have in the **Head Section** is the **meta tag** for the character set encoding of the web page (like *UTF-8* ...):

  ```
  <html lang="en">
    <meta charset="UTF-8"> 
    <title>My Website</title>
  </html>
  ```
- The **title** is usually what gets displayed up in the tab bar
- **```<body></body>```**: where we're going to be spending the majority of our time creating and writing the website. The text, title, image,...
- **Shortcut for VSCode - HTML file**: After creating a html file, you can simply type *exclamation mark (!)* and hit Enter on the first selection and then it will automatically insert all of the code for you. 
- **build your own element**


---

### Summary Section (Summary of Notes)