# Grid

## Topic: Grid Item Placement

## Date: 16/05/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- How to layout items in the grid

---

### Notes Section (Main Notes)

- It's really important to define some of the terms that are used often in CSS:
  - **grid-container**: A container that containes all of the items.
  - **grid-items**: The items that are placed inside the grid.
  - **tracks**: when we create and size our grid, then we will have rows and columns which are known as **row tracks** and **column tracks**.
  - **grid-template-rows** and **grid-template-columns**: we usually create and size the mentioned tracks using these properties.
  - **grid-cell**: Within the intersection of the tracks, we create some small units. You can use multiple cells to create a grid item.
  - **grid-lines:** We have horizontal lines and we have vertical lines. 
    - We can only control the grid lines by using **gap** property to specify its height or width.
    - We can neither change the color nor put anything inside the lines.
  ```
  index.html:

  <div>
    <div class="item cowboy">a</div>
    <div class="item astronaut">b</div>
    <div class="item book">c</div>
  </div>

  ---
  style.css:

  .container{
    height: 100vh;
    display: grid;
    gap: 3rem;
    grid-template-columns: 1fr 1fr 1.5fr;
    grid-template-rows: 1fr 1fr;
  }
  ```

---
### Summary Section (Summary of Notes) 

