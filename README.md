# anu1
all concept of html
HTML (HyperText Markup Language)
HTML is used to structure content on the web.

🔹 1. Basic Structure
html
Copy
Edit
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>
🔹 2. Common HTML Tags
Headings: <h1> to <h6>

Paragraph: <p>

Line Break: <br>

Horizontal Rule: <hr>

Links: <a href="">

Images: <img src="" alt="">

Lists:

Ordered: <ol><li></li></ol>

Unordered: <ul><li></li></ul>

Tables:

<table>, <tr>, <th>, <td>

Forms:

<form>, <input>, <textarea>, <select>, <button>

Media:

<audio>, <video>, <iframe>

🔹 3. Attributes
href, src, alt, title, target, type, value, name, id, class, style, placeholder, readonly, disabled, checked, etc.

🔹 4. Semantic Elements
<header>, <footer>, <nav>, <main>, <section>, <article>, <aside>, <figure>, <figcaption>

🔹 5. Form Inputs
Types: text, password, email, radio, checkbox, submit, reset, date, file, color, range, hidden

🔹 6. Meta Tags
<meta charset="UTF-8">, viewport, keywords, description

🔹 7. HTML5 APIs
Geolocation API

Web Storage API (localStorage, sessionStorage)

Drag and Drop

Canvas API

🔵 CSS (Cascading Style Sheets)
CSS is used for styling HTML elements.

🔹 1. Ways to Apply CSS
Inline: <div style="color:red;">

Internal: <style>h1 { color: red; }</style>

External: <link rel="stylesheet" href="style.css">

🔹 2. Selectors
Basic: element, #id, .class

Group: h1, h2

Descendant: div p

Child: div > p

Adjacent Sibling: h1 + p

Attribute: input[type="text"]

🔹 3. Box Model
content, padding, border, margin

🔹 4. Display Property
block, inline, inline-block, none, flex, grid

🔹 5. Positioning
static, relative, absolute, fixed, sticky

top, right, bottom, left, z-index

🔹 6. Flexbox
display: flex

flex-direction, justify-content, align-items, flex-wrap, align-self

🔹 7. Grid
display: grid

grid-template-columns, grid-template-rows

gap, justify-items, align-items

🔹 8. Typography
font-family, font-size, font-style, font-weight, line-height, letter-spacing, text-align, text-decoration, text-transform

🔹 9. Colors & Backgrounds
color, background-color, background-image, background-size, background-repeat, opacity

🔹 10. Borders and Shadows
border, border-radius

box-shadow, text-shadow

🔹 11. Transitions and Animations
transition, transition-duration, transition-delay

@keyframes, animation-name, animation-duration, animation-iteration-count

🔹 12. Media Queries (Responsive Design)
css
Copy
Edit
@media (max-width: 768px) {
  body {
    background: lightblue;
  }
}
🔹 13. Pseudo-classes and Pseudo-elements
Pseudo-classes: :hover, :focus, :nth-child(), :first-child, :last-child

Pseudo-elements: ::before, ::after, ::first-letter, ::selection

🔹 14. CSS Variables
css
Copy
Edit
:root {
  --main-color: blue;
}
p {
  color: var(--main-color);
}
🔹 15. Z-Index & Stacking Context
Managing overlapping elements

🔹 16. Units
Absolute: px, pt, cm

Relative: %, em, rem, vw, vh

✅ Bonus: Best Practices
Use semantic HTML for SEO

Keep CSS in separate files

Use CSS Reset or Normalize

Use classes, not inline styles

Mobile-first approach in CSS


