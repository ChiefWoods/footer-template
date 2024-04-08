# Footer Template

Custom CSS footer styling shared among most of my web projects.

The styling applies to the following footer:

Note: GitHub icon is required, and can be found in the `/icons` folder

```
<footer>
  <span class="made-by">Copyright @
    <script>document.write(new Date().getFullYear())</script> ChiefWoods
  </span>
  <a class="github-link" href="https://github.com/ChiefWoods/footer-template" target="_blank">
    <img src="./icons/github.svg" class="github-icon" alt="GitHub">
  </a>
</footer>
```

## How To Use

- Add a `<link>` tag in your HTML

```
<link rel="stylesheet" href="https://chiefwoods.github.io/footer-template/template.css" />
```

- Add an `@import` rule in your CSS

```
@import url("https://chiefwoods.github.io/footer-template/template.css")
```