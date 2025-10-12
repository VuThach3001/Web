# Bootstrap

## Topic: What is Bootstrap?

## Date: 12/10/2025

---

### Cue Column (Questions, Keywords, or Prompts)

- External Layout Systems

---

### Notes Section (Main Notes)

**1. Bootstrap**

- Bootstrap is a CSS framework created in 2010 by two Twitter developers Mark Otto and Jacob Thornton.
- The power of Bootstrap and the reason why it is so popular is it contained pre-made CSS files which you can simply include into your project in order to use their pre-built components and styling. 
- One of the biggest reasons why Bootstrap took off is because of their 12-column layout system built on top of Flexbox.

```html
index.html:
<ul class="">
  <li>
    <button class="">Home</button>
  </li>
</ul>
```
```css
bootstrap.css:
.nav{
  --bs-nav-link-padding-x: 1rem;
  --bs-nav-link-padding-y: 0.5rem;
  --bs-nav-link-font-weight: ;
  --bs-nav-link-color: var(--bs-link-color);
  --bs-nav-link-hover-color: var(--bs-link-hover-color);
  --bs-nav-link-disabled-color: var(--bs-link-secondary-color);
  display: flex;
  flex-wrap: wrap;
  padding-left: 0;
  margin-bottom: 0;
  list-style: none;
}
```

**2. CSS Frameworks**

- The two most popular CSS frameworks are Bootstrap and Foundation. But there are a lot more like MUI and Tailwind.

**Pros:**
- They're easy and fast to use and you get a ton of pre-built components
- Get really consistent styling across your website
- Have really good browser compatibility because they've tested all of the different browsers Safari, Chrome, Firefox, and Edge

**Cons**
- Class Bloat: where you have a lot of styling going into the actual HTML file and it looks a lot less clean
- Customization: in order to customize each and every component, it can be really time consuming. If you want to build a website where you want to have full control over every pixel and layout and everything to be the way you designed it, then external CSS frameworks is probably not the way to go.

**3. When to/When not to use Bootstrap**

**When to:**
- Build a mobile-first responsive website that you want to put online very quickly and access beautiful components designed by professional designers.

**When not to:**
- Build a very simple website, where you just need HTML and CSS and you can quickly throw
- Build a really complex custom design website and you want complete control over the design

**4. How to use Bootstrap?**

- Include the Bootstrap CSS and JS files in your project. You can either download them or use a CDN (Current Delivery Network).

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdm.jsdelivr.net/npm/bootstrap@...">
```

---
### Summary Section (Summary of Notes) 

