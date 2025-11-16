# Cornell Notes

## Topic: [Insert Topic Here]  

## Date: [Insert Date Here]  

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

**1. Internal linking Javascript file**
- In the head section of an HTML document, you can link a JavaScript file using the `<script>` tag.
- The reason for placing the `<script>` tag in the head section is to ensure that the JavaScript code is loaded before the body content is rendered, allowing scripts to manipulate the DOM as needed.
- Direct coding example:
```js
<script>
    let js = "amazing";
    if (js === "amazing") alert("Javascript is FUN");
    40 + 8 + 23 - 10;
    console.log(40 + 8 + 23 - 10);
</script>
```
- Linking external JavaScript file example:
```html
<head>
    <script src="path/to/your/javascriptfile.js"></script>
</head>
```

**2. External linking Javascript file**

- You can also link a JavaScript file externally by placing the `<script>` tag just before the closing `</body>` tag.
- This approach is often preferred for performance reasons, as it allows the HTML content to load first, improving the user experience.
```html
<body>
    <script src="path/to/your/javascriptfile.js"></script>
</body>
```

<!-- ### Summary Section (Summary of Notes) -->

[Insert a brief summary of the key ideas and takeaways]
