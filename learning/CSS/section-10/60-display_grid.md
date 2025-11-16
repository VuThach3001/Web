# Grid

## Topic: Display: Grid

## Date: 09/05/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- A Two-Dimensional Layout system

---

### Notes Section (Main Notes)

- First we will look for the difference between Flexbox and Grid:

| Flexbox  | Grid     |
|----------|----------                                   |
| Align content along one dimensional line    | Lay out content a long a two dimensional grid     |

- You can also choose to combine 2 these displays to take the ultimate ability of them.
- You can sometimes have a Flexbox inside a grid and other times you might have a Grid inside a Flexbox.
```
index.html:

<div class="container">
  <p>...</p>
  <p>...</p>
  <p>...</p>
  <p>...</p>
</div>

style.css:

.container{
  display: grid;
  grid-template-columns: 1fr 2fr;
  grid-template-rows: 1fr 1fr'
  gap: 10px;
}

```
---

### Summary Section (Summary of Notes) 

