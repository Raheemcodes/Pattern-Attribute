## HTML INPUT PATTERN ATTRIBUTE

<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>

> Form validation with just HTML and CSS

### What is the `pattern attribute`?

> The `pattern` attribute is an attribute of the text, tel, email, url, password, and search input types. [Vist MDN for more detailed explanation](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/pattern)

### Examples :

1. Email Validation

```html
<div class="input-field">
  <input
    placeholder="E-Mail"
    pattern="^\S+@\S+\.com+$"
    type="email"
    class="input-control"
  />
  <span>Please, enter a valid E-Mail!</span>
</div>
```

#### Links :-

- [View at CodePen](https://codepen.io/raheemscorp/pen/poVZoOZ)
- [View at StackBlitz](https://stackblitz.com/edit/web-platform-1aoslh?file=index.html)
