# Grid

## Topic: Grid Sizing

## Date: 10/05/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- How to Size Columns and Rows
- **Column**: Change **width**
- **Rows**: Change **height**
---

### Notes Section (Main Notes)

**1. Fixed Size**
```
index.html:

<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
</div>

style.css:

.grid-container{
  display: grid;
  grid-template-columns: 100px 200px;
  grid-template-rows: 400px 800px;
}
```
- We will have 100px high for the first row and 200px high for the second row.
- We will set the first column to be 400px and the second column show be twice as wide at 800px.
- Note for font size:
  - **1px**: 1/96th inch.
  - **1pt**: 1/72nd inch.
  - **1em**: 100% of parent.
  - **1rem**: 100% of root.

- Instead of using grid-template-columns and grid-template-rows, you can combine the two of these into 1 property:
```
grid-template: 100px 200px / 400px 800px; (rows / columns)
```
---

**2. Auto Size**
- Another way that we can define our grid-template-rows and columns is to use the "auto" keyword.
```
grid-template-rows: 100px auto;
grid-template-columns: 200px auto;
```
- This will lead to each row that is going to try and fit to 100% of the horizontal available space.

**Note**: It would not be the same when we do the same thing with the rows. It doesn't try to take up 100% of your screen's height. Instead, it tries to fit the content into the div.

---
**3. Fractional Size**
- Frequently you want in your layout is to define the different areas of your layout with ratios for sizes.
- This is where the fractional unit comes in with the "fr", and this unit basically defines the ratios.
```
grid-template-rows: 1fr 2fr;
grid-template-columns: 1fr 2fr;
```
- The first row is half the size of the second row
---
**4. MinMax Size**
- Sometimes you want to define how your Grid is responsive, especially on the horizontal
```
grid-template-rows: 200px 400px;
grid-template-columns: 200px minmax(400px, 800px);
```
- We can you the function called minmax so that we can define the minimum width and the maximum width we want our columns or rows to be
---
**5. Repeat Size**
```
grid-template-rows: repeat(2, 200px);
grid-template-columns: repeat(2, 100px);
```
- It means that you want to repeat the size 2 times.
---
- In case you have 4 items, but you have created 2x3 grid
```
grid-template-rows: repeat(2, 200px);
grid-template-columns: repeat(3, 100px);
```
- They will be fitted into our grid from the top left all the way to the bottom.
- If we don't have any items for number 5 and 6, then it's just not going to add them
---
- What happens if we don't define enough rows and columns 
```
index.html:

<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
</div>

style.css:

.grid-container{
  display: grid;
  grid-template-columns: 200px 200px;
  grid-template-rows: 200px 200px;
}
```
- Anything that gets added afterwards will get an automatic size based on its height and also any existing column sizes
---
- Let's say if we have some code that will create more divs in the future. You can actually use the grid-auto-rows and grid-auto-columns.
```
grid-auto-rows: 300px;
grid-auto-columns: 300px;
```
- In this case, when we create a new row that doesn't fit within our grid because our grid, then it will give each of them 300px in height. This will allow you to control your styling no matter how many items gets added to the grid.
---
### Summary Section (Summary of Notes) 

