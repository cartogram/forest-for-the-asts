---
title: The forest for the (Abstract Syntax) trees - Matt Seccafien - React Advanced London
theme: styles.css
revealOptions:
  transition: "none"
---

<!-- markdownlint-disable -->

# The forest for the _(Abstract Syntax)_ Trees

_Matt Seccafien_

React Advanced, October 2021

---

# Hi! I'm Matt

I work at Shopify on the **Hydrogen** team

![shopify](images/shopify-logo.png)

---

## Hydrogen is an opinionated React framework and SDK for building fast and dynamic Shopify powered custom storefronts.

_(currently in private beta)_

---

![tobi at unite](images/tobi-unite.png)

[unite.shopify.com](https://unite.shopify.com/)

---

![crash course](images/crash-course-youtube.png)

---

[NextJS examples](https://github.com/vercel/next.js/tree/canary/examples)

![Next js examples on github](images/nextjs-examples-github.png)

---

![charly stiching starters together](images/charly-complicated.gif)

---

![rocket help](images/rocket-help.gif)

---

## Configuration

![Configuration](images/inputs.png)

---

## Parsing

![parsing](images/parsing.png)

---

## Transform

![transform](images/transform.png)

---

## Generation

![generation](images/generation.png)

---

# 1. Parsing

Turn code into an syntax tree

•

# 2. Transformation

Manipulate syntax tree

•

# 3. Generation

Turn back into code

---

[Babel](https://babeljs.io/)

![babel website](images/babel-website.png)

---

<!-- markdownlint-disable -->
<section data-auto-animate>
  <pre data-id="code-animation"><code data-trim data-line-numbers>
    let planets = [
      { name: 'mars', diameter: 6779 },
    ]
  </code></pre>
</section>
<section data-auto-animate>
  <pre data-id="code-animation">
    <code data-trim data-line-numbers>
      let planets = [
        { name: 'mars', diameter: 6779 },
        { name: 'earth', diameter: 12742 },
        { name: 'jupiter', diameter: 139820 }
      ]
    </code>
  </pre>
</section>
<!-- markdownlint-enable -->
