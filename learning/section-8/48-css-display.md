# CSS Properties

## Topic: CSS Display

## Date: 02/04/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

**Span Element**

```
<span>
    Text
</span>

```

- Usually will see the span element will be in the middle of another element.
- The unique thing about the span element that's really cool is that it's by default has a different value for displaying property
- 
There are three common types of display values

**1. Inline**

The span has the value set to something called "inline". 

It means that we will keep for the elements in the same line until we can no longer fit anymore onto the width of the web page.

***Important things***:
- Cant't actually set the size, width and height of these elements as they will default to the size of their content

```
h2 {
    display: inline;
}
<h2>Harry</h2>
<h2>Potter</h2>
```
The result would be:

```
    Harry 
    Potter
```
**2. Block**

The span has the value set to something called "block". 

Instead of keeping the text in the same line. It turns out to set the context to the next line

```
h2 {
    display: block;
}
<h2>Harry</h2>
<h2>Potter</h2>
```
The result would be:

```
    Harry Potter
```

**3. Inline - Block**

---

### Summary Section (Summary of Notes) 

