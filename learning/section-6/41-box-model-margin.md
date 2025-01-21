# CSS Properties

## Topic: The CSS Box Model - Margin, Padding and Border

## Date: 22/01/2025 

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

**1. Height and Width**

- We have an element that has a height of 300px, we can change that height to allow our element
to take up more vertical spacing on the webpage. When this happens, it pushes the box of any other elements lower
on the web page, also for the width.
- We can either do this using pixels or percentages.

```
  width: 100%;
```

**2. Border**

- A border can also be set on each of the HTML elements.
```
  border: 10px solid black;
```
- **10x:** the thickness of the border
- **solid:** the style of the border. You can change to dashed-line,...
- **black:** the color of the border

  *Note: the properties of the border does not effect to the width and height of the box*
- You can also modify with more specific rules:
```
  border: 10px solid black;
    border-top: 0px;
    border-width: 0px 10px 20px 30px;
```
- **border-width**:
  - **0px**: the top of the box
  - **10px**: the right of the box
  - **20px**: the bottom of the box
  - **30px**: the left of the box
  
  *Note: You can also set 2 element for the border-with, which first element for the **top** and **bottom**, the second for the rest.*

**3. Padding**
- **Functionality:** Imagine the box is the paragraph covered by a border, padding will push the border out of the box by the desired pixels.

```
  padding: 20px;
```
**3. Margin**
- **Functionality:** Imagine the box is the paragraph covered by a border, padding will push the part that's outside of the border by the desired pixels.

```
  margin: 20px;
```
**4. Content Division Element**

- When we want to group different bits of content together so that we can style it. The way that we would create the artificial boxes to cover:
```
  <div>As many element as we want</div>
```
---

### Summary Section (Summary of Notes)

Useful links:

