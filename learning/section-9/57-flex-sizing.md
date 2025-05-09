# Flexbox

## Topic: Flex Sizing

## Date: 28/04/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- Shrinking
- Growing

---

### Notes Section (Main Notes)

- This will cover the content how to size the items in a Flexbox container shrinking and growing and how it should behave when it's in a responsive situation.
- The way that it works it out is basically a priority list. The first thing it looks at is whether if there is a minimum width and a maximum width that's set on the item. **If's not set**, it will look at the next thing: **basis set**, following would be the **width** and the **Content width**.
- The flow would be:
  ```
  Content width < Width < flex-basis < min-width < min-width/max-width
  ```
  **Max-width**: Looks at the longest possible line of the text.

  **Min-width**: Looks at the longest possible word of the text to determine the minimum width

  **Content width**: The length of the entire line when it's all on one line 
- The flexible part of the flexible box comes the ability to grow and shrink. We can easily to understand these properties by switching both of them off first by using 2 properties: **flex-basis** and **flex-grow**.
---
  ```
  flex-basis: 100px;
  flex-grow: 0;
  flex-shrink: 0;
  ```
- As a result, we try to increase and decrease the width of the window, the items don't actually change in their size at all.
---
  ```
  flex-basis: 100px;
  flex-grow: 1;
  flex-shrink: 0;
  ```
- When we adjust the width of our container, the width is reduced only to the flex-basis amount, which is 100px and doesn't go any further, if yes, the content will go off the screen. If there's more than 100px, it will continue to grow until it can fill up all of the space.
---
  ```
  flex-basis: 100px;
  flex-grow: 0;
  flex-shrink: 1;
  ```
- By default, it is going to set everything to the flex-basis and not going to grow to fill the space but to shrink beyond the flex-basis size until you reach that minimum width of the content
---
  ```
  flex-basis: 100px;
  flex-grow: 1;
  flex-shrink: 1;
  ```
- This going to try and take up as much width as possible and then when you shrink it, it's going to try and be as small as possible.
- In this case, the flex-basis is pretty much completely ignored because flex-grow and flex-shrink are both on.
  - Grow to the max width.
  - Shrink to the minimum width

- Now, the default for flex-basis is actually auto which is a little bit of a complex one because **it's going to look at the amount of content in each of the items so it's going to give more flex-basis to the items with more content**
- If you want everything to be equal width, them you simply switch it by giving it a 0.
  ```
  flex-basis: 0;
  flex-grow: 1;
  flex-shrink: 1;
  ```
- There's actually a shorthand way of writing this without having to write out flex-basis, flex-grow and flex-shrink by:
  ```
  flex: 1 1 1; (flex-grow | flex-shrink | flex-basis)
  ```
- Or if you want to enable/disable for the whole for 3 properties, just simply:
  ```
  flex: 1;
  ```
  ```
  flex: 0;
  ```

---

### Summary Section (Summary of Notes) 

