# Advanced CSS

## Topic: Media Queries

## Date: 24/04/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

**Media Queries**

**Format:**

```
@media (max-width: 600px){
    h1{
        font-size: 15px;
    }
}
```
**1. Max Width**
- *max-width*: this is called **breakpoint**. Means that at this particular width, anything that is less than or equal to 600px.
  Then you should use this styling in here e.g. change the h1 to have a smaller font size when it's on a mobile phone instead of
  full width desktop website.

    ```
    div{
        background-color: blue;
        height: 200px;
        width: 200px;
    }

    @media (max-width: 600px){
        div{
            height: 100px;
            width: 100px;
        }
    }
    ```
- We use this media query max-width in order to define any screen size that is 600px or below. Then we provide an override to the default styling.

**2. Min Width**
- Also there is a minimum width query:
    ```
        @media (min-width: 600px){
            h1{
                font-size: 15px;
            }
        }
    ```
  - So if there is anything that is from 600pox upwards, then we should have a different styling.

**3. Combine**
  - You can also combine different breakpoints to target something that is a specific size.
    ```
    @media (min-width: 600px) and (max-width:900){
        /* Styles for screens between 600px and 900px */
    }
    ```
 - You can also flip that around by changing the smaller size to a max-width:
  ```
    @media (max-width: 600ox) and (min-width: 900px){
        /* Styles for screens less than 600px and greater than 900px */
    }
  ```

**4. Device**
---

### Summary Section (Summary of Notes) 

