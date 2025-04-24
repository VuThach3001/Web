# CSS Properties

## Topic: Combining CSS Selectors

## Date: 22/01/2025 

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

**1. Several ways to combine CSS selectors**

**Group Rule**

To apply the rules for both selectors
```
selector, selector {
  color: blueviolet;
}
```

**Child Rule**

To apply the rule selected from the parent pointing to the child selector.
```
selector (parent) > selector (child) {
  color: firebrick;
}
```

**Descendant**

To apply to a descendant of the left side selector
```
selector selector{
  color: blue;
}
```

**Chaining**

To apply where ALL selectors are true
```
selectorselector{
  color: seagreen;
}
```
*Note: The first item in the chain must be the element to avoid misunderstanding*

**Combining Combiners**
```
selector selectorselector{
  font-size: 0.5rem;
}
```
---

### Summary Section (Summary of Notes)

