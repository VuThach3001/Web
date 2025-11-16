# Introduction to HTML

## Topic: HTML Heading Elements 

## Date: 06/01/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- [Insert question or keyword]
- [Insert question or keyword]
- [Insert question or keyword]

---

### Notes Section (Main Notes)

- **Void element**: is an element where you are forbidden from putting any content inside the tag.
- **Horizontal Rule Element**: there will be a forward slash (/) just before the end of the tag.

    ```<hr />```

    |          Normal HTML Element            |             Horizontal Rule Element           | 
    |-----------------------------------------|-----------------------------------------------| 
    | < p >This is a paragraph.< /p >         |                     < hr />                   |

- **Example**:
  
    ```markdown
    <p>This is a paragraph.</p>
    <hr />
    <p>This is a paragraph.</p>
    ```
    **Result**:

    ![Horizontal Rule Element](E:/Project/Web/learning/section-2/image/15-1-1.png "Horizontal Rule Element")

- **Break Element**: there will be a forward slash (/) just before the end of the tag. We can't have the paragraph all run in one line, even if it's in the same paragraph.

    ```<br />```

---

### Summary Section (Summary of Notes)
|            Don't          |             Do           | 
|---------------------------|--------------------------| 
| < p >                     |  < p >Paragraph 1< /p >  |
| Paragraph 1< br  />       |  < p >Paragraph 2< /p >  |
| Paragraph 2< br  />       |                          |
| < /p >                    |                          |

**Horizontal Rule Element** and **Break Element** also can be shown like this:
    
    <hr /> -> <hr >
    <br /> -> <br >