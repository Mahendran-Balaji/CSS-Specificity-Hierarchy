# CSS Specificity Hierarchy

Every CSS selector has its place in the specificity hierarchy.

There are four categories which define the specificity level of a selector:

```html
Inline styles - Example: <h1 style="color: pink;">
IDs - Example: #navbar
Classes, pseudo-classes, attribute selectors - Example: .test, :hover, [href]
Elements and pseudo-elements - Example: h1, ::before
```

```html
<html>
<head>
  <style>
    #demo {color: blue;}
    .test {color: green;}
    p {color: red;}
  </style>
</head>
<body>

<p id="demo" class="test" style="color: pink;">Mahendran Balaji</p>

</body>
</html>

```
```
