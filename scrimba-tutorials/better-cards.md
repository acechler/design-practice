# Better Cards

This shows an example on how to design better cards.
The importance of how white-space plays a role in better ui.
```css
html, body{
    margin: 0;
    padding: 0;
    height: 100vh;
}

body{
    background: #eeeeee;
    display: grid;
    place-items: center;
    grid-template-columns: repeat(2, auto);
}

.card{
    background: white;
    padding: .2em;
    width: 60%;
}

h1, p { margin: 0;}
h1 { font-size: 1.4em;}
p  { font-size: .8em; }

/* Overwrite CSS */

.secondary { padding: 1.5em;}

.secondary h1{ margin-bottom: .5em;}

.secondary p { line-height: 1.5em;}
```


```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="card">
    <h1>My Title</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus iste, ex nemo, explicabo cupiditate rerum consectetur animi ea nulla quae provident! Voluptatum nostrum dolore odit at, dolores qui consectetur soluta.</p>
  </div>
  <div class="card secondary">
    <h1>My Title</h1>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cum architecto, veniam repellendus consectetur iste ratione sequi distinctio rerum, cumque, hic culpa. Labore hic consectetur est ullam excepturi quasi tenetur molestiae?</p>
  </div>
</body>
</html>

```
