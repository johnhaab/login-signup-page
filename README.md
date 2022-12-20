![](/assets/screenshot.png)

### Overview

Simple modern login/signup page.

### Links

- Live Site URL: [Click me!](https://johnhaab.github.io/login-signup-page/)

### Built with

- HTML5 markup
- CSS custom properties

Code snippets, see below:

```html
<div class="options">
   <input type="checkbox" id="check">
   <label for="check"> Remember for 30 days</label>
   <a href="#"><p>Forgot password?</p></a>
</div>
```
```css
input[type="checkbox"] {
    transform: translate(0%, 10%);
    appearance: none;
    -webkit-appearance: none;
    height: 20px;
    width: 20px;
    background-color: white;
    border: 2px solid hsl(120, 4%, 10%, 60%);
    border-radius: 5px;
    cursor: pointer;
    justify-content: center;
    align-items: center;
    display: flex;
    transition: all 0.2 ease;
}

input[type="checkbox"]:before {
    display: inline-block;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
}

input[type="checkbox"]:after {
    font-family: "Font Awesome 5 Free";
    font-weight: 900; 
    content: "\f00c";
    font-size: 12px;
}

input[type="checkbox"]:hover {
    background-color: rgba(185, 126, 214, 0.7);
    transition: all 0.2 ease-out;
}

input[type="checkbox"]:checked {
    background-color: rgba(185, 126, 214, 0.7);
    transition: all 0.2 ease-out;
}

input[type="checkbox"]::after {
    display: block;
}
```

## Author

- Twitter - [@johnlhaab](https://www.twitter.com/johnlhaab)
