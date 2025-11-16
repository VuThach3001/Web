# Intermediate CSS

## Topic: The Cascade - Specificity and Inheritance

## Date: 06/02/2025 

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

There are 4 broad categories which we look at when we're determining the overall level of importance of a CSS rule.

**1. Position**

- Like it will follow the flow when compiling:
  
  ```
    li{
      color: red;
      color: blue;
    }
    li{
      color: green;
    }
  ```
- In any way of declaration for li, it will take **the last property for the showing up on screen** and will be green for the above example.

**2. Specificity**

- Just like the flow when compiling, it will follow the priority:
  
  **1: ID**
  
  ```css
    li{color: blue;}
  ```

  **2: Attribute**
  ```css
    .first-class {color: red;}
  ```
  
  **3: Class**
  ```css
    li[draggable]{color: purple;}
  ```

  **4: Element**
  ```
    #first-id{color: orange;}
  ```

- If we apply CSS rules in this order, then the highest prioritied will be the one that will be applied.

**3. Type**

- It will follow this hierarchy:

  **1. Incline**
  ```
    <h1 style = " ">Hello</h1>
  ```
  **2. Internal**
  ```
    <style> </style>
  ```
  **3. External**
  ```
    <link ref="stylesheet" href="./style.css">
  ```

**4. Importance**

- If you add an exclamation mark (!) and "important", it will come out this as a highest level.

  ```
    color: red;
    color: green !important;
  ```

***Note: The importance also follow from the lowest to highest with: position -> specificity -> type -> importance***

---

### Summary Section (Summary of Notes)

