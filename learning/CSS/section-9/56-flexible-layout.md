# Flexbox

## Topic: Flexible Layout

## Date: 28/04/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

- One of the first thing to differentiate when we're talking about the different properties to set is whether this property is going to go onto the child, which is the flex item?
- So in this case, each of these items that are contained within the flexible container is a child or is the property going on to the parent?
- There is 1 property called **order** which sets the element's order with the highest order taken place from right to left.

**Flex-wrap** 
- Property: this is really useful when you run out of space on the horizontal once we run out of space, it's not going to go on to the next line.
- The default behavior of Flexbox and the flex-wrap property is normally set to nowrap. Then it's just going to continue pushing until you can't collapse any of these items anymore and things get push off the pages.
  ```
  flex-wrap: nowrap;
  ```
- However, if you want this to actually continue on to the next line instead of being invisible, then you could change this property flex-wrap to wrap instead and then move all the elements that don't have enough space to fit in its full minimum width onto the top line.
- *Note*: **Flex-wrap** is a property on the parent, so this is set onto the Flexbox container itself and it tells how all of the children should behave

**Justify-content**
- This is set on the parent container.
- It basically sets the distribution of our items along the main axis.
  ```
    justify-content: flex-start;
  ```
  - If the main axis is set from left to right, flex-start means that it will go from the start position is from left and oppositely.
  - If the main axis is set top to bottom, flex-start means that it will go from the start position is from the top and oppositely.
  ```
    justify-content: center;
  ```
  - It is saying that to center the items in CSS
  ```
    justify-content: space-between;
  ```
  - This is something that's used really commonly because when you're creating a website layout, you kind of want everything to use up the available space and create some gaps between each other to distribute.

**Align-items**
- It's a little different from **justify-items** even though some of the values might seem really similar.
- **Align-items** is only actually sets the distribution along the cross-axis.
- This is a property that's set on our container.
- For align-items to really work, we actually need to set the height of the container. In this case, we're setting it to 70vh (viewport height: the height of the window that you're viewing the page)
- **Flex-start** is going to make it all bunch up to the top and flex-end, which makes everything bunch up to the bottom and so on.

```
align-items: center;
height: 70vh;
```

**Align-self**
- You can reach into the actual item itself and set a property called "align-self". Saying that let's be an independent item and let's think for ourselves.
- If we set this property to start or end or whichever it is, the it's actually make this item separate from the groupthink and do its own thing

**Align-content**
- Similar to **align-items**, but it only works when you have the **flex-wrap set to wrap**.
- If we applied, align-content to center and we made our Flexbox wrap, then when the width of our window reduces, everything will bunch up together.
---

### Summary Section (Summary of Notes) 

