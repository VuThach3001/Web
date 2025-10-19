# Bootstrap

## Topic: Bootstrap Layout 

## Date: 12/10/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- Understanding the 12 column Bootstrap layout system

---

### Notes Section (Main Notes)

**1. 12-Column System**
- The 12-column system is made of 3 components:
  - Div: has a class of `container` and this is going to be the starting point
  - Inside the `container`, we need another `div` which is going to be of class `row`
  - Inside the `row`, we will have our items and they will be laid out using the column system
  
```html
<div class="container">
  <div class="row">
    <div class="col">Hello</div>
  </div>
</div>
```

**2. Containers and Rows**
- The layout begins with a 'container' to wrap the content, followed by 'row' divs, where columns are placed using the 'col' class to define their size.

**3. Column Sizing:**
- Columns can be sized using classes like 'col-2', 'col-4', etc., indicating how many of the 12 columns each section should occupy. 
- For example, 'col-2' takes up 2 columns, and 'col-4' takes up 4 

**4. Responsive Design**
- The system is designed to cater to multiple screen sizes. Containers can adjust based on screen real estate, ensuring optimal visibility and usability.


**5. Breakpoints:**
- Bootstrap allows multiple breakpoints within a single div, permitting flexibility based on screen size. You can mix column sizes within a row to create diverse layouts.

---
### Summary Section (Summary of Notes) 

