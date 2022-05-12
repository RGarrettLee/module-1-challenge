# Refactoring Codebase
## The Assignment

Given an existing `index.html` and `style.css` we are to refactor the code to incorporate semantic HTML elements and consolodate as much of the code as possible 

The project is live at [this link](https://rgarrettlee.github.io/module-1-challenge)

---

> ### What the code currently looks like

```html
<div class="header">
    <h1>Hori<span class="seo">seo</span>n</h1>
    <div>
        <ul>
            <li>
                <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li>
            <li>
                <a href="#online-reputation-management">Online Reputation Management</a>
            </li>
            <li>
                <a href="#social-media-marketing">Social Media Marketing</a>
            </li>
        </ul>
    </div>
</div>
```

The above code lacks and repeats the use of `<div>` throughout the code in place of tags such as `<section>` and `<header>`

> ### What the code needs to look like

```html
<header>
    <h1>Hori<span class="seo">seo</span>n</h1>
    <nav>
        <ul>
            <li>
                <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li>
            <li>
                <a href="#online-reputation-management">Online Reputation Management</a>
            </li>
            <li>
                <a href="#social-media-marketing">Social Media Marketing</a>
            </li>
        </ul>
    </nav>
</header>
```
This altered code is much more readable, semantic, and consistent with the rest of the codebase

---

## Mockup of the website

The website will look like this before and after the refactor

![website mockup](./assets/images/01-html-css-git-homework-demo.png)